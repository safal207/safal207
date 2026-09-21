# CrewAI #5802 — External validation of action identity and authoritative readback

**Date:** 21 September 2026  
**Status:** bounded external comparison completed  
**Primary thread:** https://github.com/crewAIInc/crewAI/issues/5802

## Why this matters

The question was deliberately narrower than “does retry work?” or “is execution exactly once?”

The boundary under test was:

> Can a logical action identity be committed before dispatch, independently bound to the intended payload, compared against authoritative external readback, and classified without silently upgrading missing, duplicated, mismatched, or unavailable evidence into success?

This distinction matters because a locally successful call, a passing test, or a retained request record is not by itself proof that the intended external effect occurred exactly once.

## Pinned reference fixture

mstevens843 published a pinned Crashpoint action-readback fixture at:

- publication commit: `bb9cd47c4b0b02527aab7b369d17b32829cc4e20`
- report: https://github.com/mstevens843/crashpoint/blob/bb9cd47c4b0b02527aab7b369d17b32829cc4e20/results/13-action-readback.md
- evidence bundle: https://github.com/mstevens843/crashpoint/tree/bb9cd47c4b0b02527aab7b369d17b32829cc4e20/evidence/action_readback/action_readback_self_reviewed_v2

The fixture mints and durably records a fresh logical action ID and canonical payload before worker dispatch, then compares that admission record against an out-of-process ledger observed by a fresh process.

It contains six predeclared cases, three trials each:

| Fixture outcome | Trials |
|---|---:|
| `ONE_EFFECT_MATCHING` | 6 |
| `NO_EFFECT` | 3 |
| `MULTIPLE_EFFECTS_MATCHING` | 3 |
| `ONE_EFFECT_MISMATCHED` | 3 |
| `INDETERMINATE` | 3 |

The upstream report states that all 18 trials matched the frozen prediction and documents the fixture's same-host, non-provider, non-distributed limits.

## Independent SafeAgent Control comparison

azender1 later reported a bounded SafeAgent Control comparison against that exact pinned bundle:

https://github.com/crewAIInc/crewAI/issues/5802#issuecomment-5764332870

The upstream offline verifier reportedly returned:

- 18 trials;
- valid manifest receipt;
- zero verification problems.

A narrow external-evidence adapter was used without modifying the frozen v12 reconciliation core.

Reported mapping:

| Pinned external evidence | SafeAgent Control classification | Count |
|---|---|---:|
| `ONE_EFFECT_MATCHING` | `CONFIRMED` | 6 |
| `NO_EFFECT` | `MISSING_EXTERNALLY` | 3 |
| `MULTIPLE_EFFECTS_MATCHING` | `CONTRADICTION` | 3 |
| `ONE_EFFECT_MISMATCHED` | `CONTRADICTION` | 3 |
| `INDETERMINATE` | `UNCERTAIN` | 3 |

The comparison explicitly preserved the difference between a trial matching its frozen prediction and an action being `CONFIRMED`.

For the reported `CONFIRMED` classification, the comparison required:

1. a committed pre-dispatch logical action ID;
2. complete external readback;
3. exactly one external effect;
4. a payload digest matching the admitted payload.

The adapter/fail-closed tests and full SafeAgent Control suite were reported as `162 passed, 2 skipped`.

## What this supports

Within the published fixture boundary, this is external evidence that the reconciliation mapping does not collapse materially different states into one green outcome:

- one matching effect can become `CONFIRMED` only when the admission and external evidence conditions are present;
- duplicate matching effects remain visible as `CONTRADICTION`;
- one effect with the wrong payload remains `CONTRADICTION`;
- unavailable readback remains `UNCERTAIN`;
- a verified zero-effect terminal readback is kept separate as `MISSING_EXTERNALLY`.

This is the result I wanted from the comparison: preserve the epistemic boundary between **test expectation**, **observed external effect**, and **justified reconciliation claim**.

## What this does not support

This result is intentionally not presented as proof of:

- universal or distributed exactly-once execution;
- real payment-provider behavior;
- host or power-loss durability;
- distributed fencing;
- permission to replay merely because a bounded readback produced `MISSING_EXTERNALLY`;
- SafeAgent claim / TTL / sweep lifecycle correctness in this fixture;
- statistical reliability rates from 18 deterministic trials.

The Crashpoint side is pinned to an immutable publication commit and public evidence bundle.

At the time of this record, the SafeAgent Control comparison is publicly documented in the CrewAI issue comment, but I have not found a separately pinned public SafeAgent commit or raw adapter/result artifact containing this exact comparison. I therefore treat the issue comment as external comparison evidence, not as an independently replayable SafeAgent artifact.

## My role

I did not author either external implementation.

My contribution was to define and keep narrowing the verification boundary in the public thread: pre-dispatch logical-action identity, independent payload binding, authoritative external readback, visible duplicates/mismatches, and fail-closed treatment of unavailable evidence.

After the Crashpoint fixture was published, I explicitly requested the raw mapping/result rather than further expanding the fixture. The subsequent SafeAgent Control comparison tested that boundary.

Closure comment:

https://github.com/crewAIInc/crewAI/issues/5802#issuecomment-5766532553

## Portfolio claim

A precise statement for reuse:

> In CrewAI #5802, a verification boundary I helped define was implemented as a pinned 18-trial Crashpoint fixture and then mapped by an independent SafeAgent Control contributor. The comparison preserved `CONFIRMED`, `MISSING_EXTERNALLY`, `CONTRADICTION`, and `UNCERTAIN` as distinct evidence states rather than treating a passing fixture trial as proof of successful execution. The result is bounded to the published same-host fixture and is not an exactly-once or provider-level guarantee.
