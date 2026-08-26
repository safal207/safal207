# Aleksei Safonov

## Independent Smart-Contract & AI-Agent Verification Engineer

I help Web3, FinTech, and AI-agent teams answer one expensive question **before production**:

> Can this workflow lose, duplicate, lock, or falsely report value when timeouts, retries, concurrency, stale state, or partial failure occur?

I bring **12+ years of QA and FinTech reliability experience** across banking, brokerage, APIs, WebSockets, SQL, integrations, risk, regression strategy, and failure analysis.

My work turns critical state transitions into **bounded tests, reproducible evidence, and regression coverage**.

```text
one workflow → one economic risk → one bounded sprint → reproducible evidence
```

### 🟢 Open for fixed-scope paid engagements

**Email preferred:** [safal0645@gmail.com](mailto:safal0645@gmail.com)  
**Telegram:** [@Alexfox14](https://t.me/Alexfox14)

To request a review, send:

1. repository or contract link;
2. chain, language, and tooling;
3. highest-risk workflow;
4. current test status;
5. desired deadline.

I will return a proposed **scope, authorization boundary, fixed quote, and deliverables** before execution.

---

## Choose the right path

| You need | Best starting point | Outcome |
|---|---|---|
| A smart-contract or payment-flow review | [ContractGraph-QA](https://github.com/safal207/ContractGraph-QA) | Reproducible failure traces, invariant coverage, and an engineering-ready report |
| Independent action-receipt or evidence verification | [T-Trace / OpenPoC](https://github.com/safal207/T-Trace) | Cross-implementation checks and explicit assurance boundaries |
| A pre-execution control layer for AI-agent actions | [ProofPath](https://github.com/safal207/ProofPath) | Intent, scope, authority, reversibility, and evidence checks before execution |
| Research, editorial, or market dialogue | [RESONANCE](https://safal207.github.io/RESONANCE/) | Evidence-first technical stories and open product questions |

---

## Smart-contract and financial workflow QA

I accept paid, fixed-scope engagements for:

- escrow and dispute/release workflows;
- streaming payments and exact end-time settlement;
- vesting, revocation, and final settlement;
- payouts, revenue sharing, fees, and reconciliation;
- wallets, DeFi/FinTech contracts, and agentic payments;
- Solidity/Foundry and other stacks agreed during scoping.

### Questions I pressure-test

| Risk area | The question |
|---|---|
| Value conservation | Can any path create, lose, strand, or misallocate value? |
| Lifecycle safety | Does every value-holding state retain a valid path to settlement, refund, or recovery? |
| Timing boundaries | What happens exactly at cancellation, expiry, vesting, or end-time boundaries? |
| Retry and idempotency | Can an ambiguous response or repeated request commit twice? |
| Concurrency | Can two individually valid calls produce one invalid economic outcome? |
| Authorization | Can stale, revoked, or mismatched authority still trigger an effect? |
| Cross-system consistency | Do contract state, API response, ledger, balances, and audit evidence converge? |

### What the client receives

- a bounded state-transition and risk map;
- reproducible tests and exact traces for confirmed issues;
- severity and business-impact analysis;
- minimal remediation guidance;
- regression, invariant, negative, boundary, or property-based coverage;
- a concise engineering report;
- an optional fix or pull request when separately agreed.

### Engagement boundary

- one critical workflow first, not an open-ended audit;
- repository, testnet, sandbox, or another explicitly authorized surface;
- no broad production access required;
- async written collaboration is available;
- no testing without explicit authorization.

Recent scopes include escrow lifecycle safety, value conservation, dispute/release ordering, concurrent spending, duplicate/retry exposure, cancellation, and exact end-time settlement.

> Independent QA and adversarial verification reduce uncertainty within an agreed scope. They are not a guarantee of zero vulnerabilities or formal certification.

---

## Selected verified work and collaborations

I list **completed work, independent interoperability, and merged contributions** here. I do not present prospects, unanswered outreach, or informal conversations as partnerships.

| Organization / project | Verified result |
|---|---|
| [Valta](https://www.valta.co/) · [Valta Pilot Lab](https://github.com/safal207/valta-pilot-lab) | Completed and mutually signed-off Sprint 1 covering agent-payment policy enforcement, concurrent-spend behavior, and retry/idempotency exposure |
| [Governex Agent Action Receipts](https://github.com/governex/agent-action-receipts-vectors) | T-Trace/OpenPoC independently matched **13/13** public conformance vectors without importing the reference verifier; accepted for inclusion in the planned `-01` Implementation Status |
| [AgenTrust trace-spec](https://github.com/agentrust-io/trace-spec) | Verification-outcome guidance was reviewed and merged in [PR #215](https://github.com/agentrust-io/trace-spec/pull/215) |

**Governex compatibility evidence:**  
[Report](https://github.com/safal207/T-Trace/blob/main/docs/governex-action-receipts-compatibility.md) · [Verifier source](https://github.com/safal207/T-Trace/blob/main/openpoc/action_receipt_compat.py) · [Pinned interoperability workflow](https://github.com/safal207/T-Trace/actions/workflows/governex-action-receipts.yml)

---

## Flagship projects

### [ContractGraph-QA](https://github.com/safal207/ContractGraph-QA)

Independent QA framework for stateful financial and contract workflows.

```text
actor → action → state transition → invariant → reproducible evidence
```

Use it to model economic promises, pressure-test failure paths, and produce evidence that engineering teams can replay.

### [T-Trace / OpenPoC](https://github.com/safal207/T-Trace)

Open protocol and executable fixtures for acknowledged state transitions, action receipts, deterministic replay, and assurance boundaries.

```text
valid presented trace ≠ proof that every real-world effect was captured
```

### [ProofPath](https://github.com/safal207/ProofPath)

Pre-execution gateway for high-risk AI-agent and API actions.

```text
valid credential ≠ valid action ≠ valid scope ≠ valid approval
```

Best reviewer entry point: [Reviewer First Screen](https://github.com/safal207/ProofPath/blob/main/docs/REVIEWER_FIRST_SCREEN.md)

### [Causal-Memory-Layer](https://github.com/safal207/Causal-Memory-Layer)

Causal audit layer for AI-agent action traces, parent authority, approval lineage, and reviewer evidence.

### [RESONANCE](https://safal207.github.io/RESONANCE/)

Evidence-first journal connecting technical artifacts to readable stories, open questions, and product signals.

```text
research signal → evidence → readable story → market question → product signal
```

### [Kairos Gate for X-Cell](https://github.com/safal207/Kairos-Gate-for-X-Cell)

Frontier research on evidence and governance boundaries for agentic biology. Computational and documentary only; it does not authorize experiments, treatment, or clinical decisions.

---

## How I work

- **Evidence over confidence.** A convincing claim is not a substitute for a reproducible result.
- **Root cause over symptom.** I separate product defects, contract gaps, deployment failures, and evidence limitations.
- **Exact scope before execution.** Risk, authorization, deliverables, and stop conditions are agreed first.
- **RED → fix → GREEN.** A result is not closed until the failure is reproduced and the remediation is verified.
- **Written, inspectable collaboration.** Decisions and evidence remain reviewable after the conversation ends.

---

## Background

I am a senior QA engineer, AI-product builder, and independent researcher focused on high-stakes systems where correctness depends on more than a successful HTTP response or a passing happy-path test.

My FinTech background includes banking, brokerage, API and integration testing, SQL, WebSockets, risk and reporting systems, regression prioritization, and quality-process design.

My current thesis is simple:

> AI models may propose possibilities. Evidence determines what is supported. Authorized humans determine what may proceed.

---

## Contact

**Paid review or collaboration:** [safal0645@gmail.com](mailto:safal0645@gmail.com)  
**Telegram:** [@Alexfox14](https://t.me/Alexfox14)  
**GitHub:** [@safal207](https://github.com/safal207)

When contacting me about a review, include the repository, highest-risk transition, test environment, and deadline. A narrow, concrete workflow gets the fastest useful answer.
