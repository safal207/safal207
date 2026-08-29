# Aleksei Safonov — Smart Contract QA & AI Agent Verification

## I pressure-test the moment software moves money or claims a real-world result.

**Independent smart-contract testing, AI-agent verification, agentic-payment security, and FinTech reliability engineering.**

> When a payout, escrow release, settlement, or agent action times out, retries, races, or recovers from stale state — can you prove whether **zero, one, or an unknown number of economic effects** occurred, and block retry when the answer is unknown?

I help Web3, DeFi, FinTech, and AI-agent teams turn one high-risk transition into **bounded adversarial tests, reproducible evidence, and regression coverage before production**.

I bring **7+ years of QA and FinTech reliability experience** across banking, brokerage, REST APIs, WebSockets, SQL, integrations, payment reconciliation, risk, regression strategy, and failure analysis.

**Latest public interoperability:** [T-Trace/OpenPoC](https://github.com/safal207/T-Trace) independently matched **18/18 Governex `-01` checks**; Governex now links the independent reports, and the draft author confirmed named RFC 7942 Implementation Status credit in the forthcoming revision.

```text
one critical workflow
        ↓
one economic promise
        ↓
bounded pressure test
        ↓
reproducible evidence and a clear ship / fix / stop decision
```

<!-- portable-evidence-pack:start -->
## 📦 New product — Portable Hydrated Lattice Evidence Pack

> **One ZIP. Exact inputs. Machine verdict. Human explanation. Independent replay.**

ContractGraph-QA now turns a financial or smart-contract state-machine assessment into a portable evidence package that another engineer can verify on a separate machine.

```text
contract structure
+ observed execution
+ reviewed authority / time bindings
→ PASS | FAIL | INCONCLUSIVE
→ deterministic evidence.zip
→ independent type-sensitive replay
```

The verifier checks canonical JSON and ZIP metadata, every entry hash and size, semantic replay, type drift, tampering, and an optional separately obtained SHA-256 for exact-byte integrity.

**Shipped and reviewed:** [product documentation](https://github.com/safal207/ContractGraph-QA/blob/main/docs/HYDRATED_LATTICE_EVIDENCE_PACK.md) · [merged implementation PR #97](https://github.com/safal207/ContractGraph-QA/pull/97) · [completed product scope #96](https://github.com/safal207/ContractGraph-QA/issues/96)

> Boundary: this is a reproducible proof package, not a security certificate, source-identity proof, or authorization to move money.
<!-- portable-evidence-pack:end -->

<!-- profile-offer:start -->
### 🟢 Open for paid, fixed-scope engagements

**Start with one question:**

> **What is the single transition your team cannot afford to get wrong?**

**[Email me that workflow](mailto:safal0645@gmail.com?subject=Fixed-scope%20verification%20request)** — a repository or contract link, the risky transition, and the desired deadline are enough for the first message.

I will respond with a **fit / no-fit assessment**, then propose the scope, authorization boundary, fixed quote, deliverables, and stop conditions before any execution.

Broad production access is not required. A repository, testnet, sandbox, test contract, or another explicitly authorized surface is enough.
<!-- profile-offer:end -->

---

<!-- recovery-kit:start -->
## ⚡ Free diagnostic — Ambiguous Payment Recovery Kit

> **Your provider said `accepted`. Can your workflow prove whether zero, one, or an unknown number of economic effects occurred before permitting a retry?**

### **[Run the live seven-question self-test →](https://ambiguous-payment-recovery-kit.lovable.app/?ref=github-profile&utm_source=github&utm_medium=profile&utm_campaign=ambiguous-payment-recovery)**

The kit maps the evidence boundary across:

```text
authorization
→ provider
→ external rail
→ recipient
→ customer ledger
```

| Verdict | What the evidence supports | Safe action |
|---|---|---|
| `VERIFIED` | One matching economic effect is independently observed | Finalize; do not retry |
| `SAFE_TO_RETRY` | Zero effects and a pre-effect rejection are proven | Permit a new attempt under policy |
| `UNVERIFIED` | The provider accepted, but the expected effect is absent | Do not claim success |
| `RECONCILE_REQUIRED` | An effect may have occurred or evidence disagrees | Block blind retry and reconcile |

**Public sandbox proof:**

```text
24 retry attempts
→ 1 durable reservation owner
→ 23 stale or duplicate attempts rejected
→ 1 external rail effect
→ 1 linked customer-ledger posting
→ receipt integrity: PASS
```

[Live recovery kit](https://ambiguous-payment-recovery-kit.lovable.app/?ref=github-profile&utm_source=github&utm_medium=profile&utm_campaign=ambiguous-payment-recovery) · [Executable proof and pilot lab](https://github.com/safal207/valta-pilot-lab) · [Request a fixed-scope review](mailto:safal0645@gmail.com?subject=Ambiguous%20payment%20recovery%20review)

> Boundary: this is reproducible evidence for the declared sandbox model, not a universal exactly-once guarantee, custody service, payment rail, or compliance certificate.
<!-- recovery-kit:end -->

---

## What I verify

| Search area | Practical question | Primary project |
|---|---|---|
| **Smart-contract QA and Solidity testing** | Can escrow, settlement, vesting, payout, or cancellation logic lose, duplicate, lock, or misallocate value? | [ContractGraph-QA](https://github.com/safal207/ContractGraph-QA) |
| **AI-agent verification and action receipts** | Does a valid-looking trace actually support the claimed real-world effect, or can evidence be stale, replayed, incomplete, or bypassed? | [T-Trace / OpenPoC](https://github.com/safal207/T-Trace) |
| **AI-agent authorization and payment security** | Should this exact action execute now, under this authority, scope, budget, recipient, and approval? | [ProofPath](https://github.com/safal207/ProofPath) |
| **AI-agent audit trails and causal lineage** | Why was this action allowed, and does its task, delegation, policy, or human-approval ancestry still exist? | [Causal-Memory-Layer](https://github.com/safal207/Causal-Memory-Layer) |
| **FinTech reliability and payment reconciliation** | Do provider state, external-rail effects, recipient state, customer ledger, and receipts converge to one justified recovery verdict? | [Live Recovery Kit](https://ambiguous-payment-recovery-kit.lovable.app/?ref=github-profile&utm_source=github&utm_medium=profile&utm_campaign=ambiguous-payment-recovery) · [Pilot Lab](https://github.com/safal207/valta-pilot-lab) |

---

<!-- partners:start -->
## Selected proof

This is **proof, not a logo wall**. I list completed work, independent interoperability, and merged contributions — not prospects, unanswered outreach, or implied endorsements.

| Evidence | Verified result |
|---|---|
| [Portable Hydrated Lattice Evidence Pack](https://github.com/safal207/ContractGraph-QA/blob/main/docs/HYDRATED_LATTICE_EVIDENCE_PACK.md) | **Exact inputs + machine verdict + human summary → deterministic ZIP → independent type-sensitive replay; merged after exact-head CI, Product, Portability, Finding report, and measurement-provenance validation** |
| [Cross-system payment recovery proof](https://github.com/safal207/valta-pilot-lab) | **24 concurrent retries → 1 durable owner → 23 rejected attempts → 1 external effect → 1 linked ledger posting → independently verifiable receipt** |
| [Valta Pilot Lab](https://github.com/safal207/valta-pilot-lab) | Completed and mutually signed-off Sprint 1 covering agent-payment policy enforcement, concurrent-spend behavior, and retry/idempotency exposure |
| [Governex Agent Action Receipts](https://github.com/governex/agent-action-receipts-vectors) | T-Trace/OpenPoC independently matched **18/18 pinned `-01` checks** — 16 receipt-log vectors plus 2 signed-head checks — without importing or executing the upstream verifier. Governex publicly links the reports, and the forthcoming `-01` RFC 7942 Implementation Status is confirmed to credit **Aleksei Safonov — Independent Researcher and Maintainer of T-Trace/OpenPoC**. |
| [AgenTrust trace-spec](https://github.com/agentrust-io/trace-spec) | Verification-outcome guidance was reviewed and merged in [PR #215](https://github.com/agentrust-io/trace-spec/pull/215) |

**Standards contribution:** technical feedback from the T-Trace/OpenPoC review informed the new repeated-`step_id`, signed-`seq` gap/reuse, and external signed-head assertion vectors. This is independent interoperability and threat-boundary work — not co-authorship, IETF adoption, or endorsement.

**Governex original `-00` evidence:**  
[13/13 report](https://github.com/safal207/T-Trace/blob/main/docs/governex-action-receipts-compatibility.md) · [Verifier source](https://github.com/safal207/T-Trace/blob/main/openpoc/action_receipt_compat.py) · [Pinned workflow](https://github.com/safal207/T-Trace/actions/workflows/governex-action-receipts.yml)

**Governex `-01` evidence:**  
[18/18 report](https://github.com/safal207/T-Trace/blob/main/docs/governex-action-receipts-v01-compatibility.md) · [Capture-side review](https://github.com/safal207/T-Trace/blob/main/docs/governex-action-receipts-v01-capture-review.md) · [Verifier source](https://github.com/safal207/T-Trace/blob/main/openpoc/action_receipt_compat_v01.py) · [Pinned workflow](https://github.com/safal207/T-Trace/actions/workflows/governex-action-receipts-v01.yml) · [PR #23](https://github.com/safal207/T-Trace/pull/23)

**Boundary:** these are different kinds of evidence. None implies blanket corporate partnership, adoption, formal standard status, or endorsement.
<!-- partners:end -->

---

<a id="paid-review"></a>
<!-- smart-contract-services:start -->
## 🛡️ First Risk Boundary Review

The first engagement is deliberately small: **one critical economic workflow**, a bounded set of adversarial cases, and evidence another engineer can reproduce.

The transformation is simple:

```text
“we think this path is safe”
              ↓
exact states, invariants, failures, and evidence
              ↓
a defensible engineering decision
```

### Best-fit workflows

- escrow creation, funding, release, dispute, refund, and auto-settlement;
- streaming-payment cancellation and exact end-time settlement;
- vesting, revocation, payouts, fees, revenue sharing, and value conservation;
- wallets, DeFi/FinTech contracts, and agentic-payment systems;
- contract ↔ API/backend ↔ ledger/audit consistency;
- Solidity/Foundry and other stacks agreed during scoping.

### Questions I pressure-test

| Risk area | The question |
|---|---|
| Value conservation | Can any path create, lose, strand, duplicate, or misallocate value? |
| Lifecycle safety | Does every value-holding state retain a valid path to settlement, refund, or recovery? |
| Timing boundaries | What happens exactly at cancellation, expiry, vesting, dispute, or end-time boundaries? |
| Retry and idempotency | Can an ambiguous response or repeated request commit twice? |
| Concurrency and ordering | Can two individually valid calls produce one invalid economic outcome? |
| Authorization | Can stale, revoked, reused, or mismatched authority still trigger an effect? |
| Cross-system consistency | Do contract state, API response, wallet, ledger, balances, and audit evidence converge? |
| Evidence integrity | Can a valid-looking trace omit, replay, mutate, or falsely claim the real-world effect? |

### What the client receives

1. A concise state-transition and risk map.
2. Reproducible tests and exact traces for confirmed issues.
3. Severity and business-impact analysis.
4. Minimal remediation guidance.
5. Regression, invariant, negative, boundary, or property-based coverage.
6. A short engineering report suitable for review and handoff.
7. An optional fix or pull request when separately agreed.

### Engagement boundary

- one critical workflow first, not an open-ended audit;
- scope, fee, authorization, delivery window, and stop conditions agreed before execution;
- repository, testnet, sandbox, or another explicitly authorized surface;
- no broad production access required;
- fully asynchronous, written collaboration is available;
- no testing without explicit authorization.

Recent scopes include escrow lifecycle safety, value conservation, dispute/release ordering, concurrent spending, duplicate/retry exposure, cancellation, and exact end-time settlement.

> Independent QA and adversarial verification reduce uncertainty within an agreed scope. They are not a guarantee of zero vulnerabilities or formal certification.

**[Request a fixed-scope review](mailto:safal0645@gmail.com?subject=Fixed-scope%20verification%20request)**
<!-- smart-contract-services:end -->

---

## Frequently asked questions

### What is smart-contract QA?

Smart-contract QA verifies whether allowed sequences of actors, calls, values, timestamps, retries, and concurrent transactions can violate a business or security invariant. It complements code review by testing reachable economic behavior and producing reproducible evidence.

### What is AI-agent verification?

AI-agent verification checks whether a specific action or claimed outcome is supported by current authority, exact intent, policy, causal lineage, action receipts, and independently inspectable evidence. Authentication alone does not prove that an action was appropriate or that its real-world effect occurred.

### What is agentic-payment verification?

Agentic-payment verification tests whether an AI-initiated payment remains bounded by recipient scope, asset rules, budgets, approvals, replay protection, idempotency, reconciliation, and auditable outcome evidence.

### Do you perform unrestricted production testing?

No. Testing stays inside an explicitly authorized repository, testnet, sandbox, test contract, API surface, or other agreed boundary. Public code or a public endpoint is not treated as authorization.

### What do you need for the first assessment?

A repository or contract link, chain and tooling, the highest-risk transition, current test status, and desired deadline. The first useful scope is usually one critical workflow rather than a broad open-ended audit.

---

## Other ways to enter the work

- **Need to diagnose an ambiguous payment retry?** Start with the [live seven-question Recovery Kit](https://ambiguous-payment-recovery-kit.lovable.app/?ref=github-profile&utm_source=github&utm_medium=profile&utm_campaign=ambiguous-payment-recovery).
- **Need a reproducible method for financial state transitions?** Start with [ContractGraph-QA](https://github.com/safal207/ContractGraph-QA).
- **Need independent action-receipt or evidence verification?** Start with [T-Trace / OpenPoC](https://github.com/safal207/T-Trace).
- **Need a pre-execution control layer for AI-agent actions?** Start with [ProofPath](https://github.com/safal207/ProofPath).
- **Need causal lineage and approval evidence for agent traces?** Start with [Causal-Memory-Layer](https://github.com/safal207/Causal-Memory-Layer).
- **Want the readable research and market-dialogue layer?** Open [RESONANCE](https://safal207.github.io/RESONANCE/).

<details>
<summary><strong>Flagship projects and research directions</strong></summary>

### [ContractGraph-QA](https://github.com/safal207/ContractGraph-QA)

Independent QA framework for stateful financial and contract workflows.

```text
actor → action → state transition → invariant → reproducible evidence
```

Use it to model economic promises, pressure-test failure paths, and deliver deterministic evidence ZIPs that another engineer can independently replay.

### [T-Trace / OpenPoC](https://github.com/safal207/T-Trace)

Open protocol and executable fixtures for acknowledged state transitions, action receipts, deterministic replay, and assurance boundaries.

```text
valid presented trace ≠ proof that every real-world effect was captured
```

**External validation:** independently matched Governex action-receipt suites at **13/13 (`-00`)** and **18/18 (`-01`)**; Governex publicly links the reports, and named T-Trace/OpenPoC credit is confirmed for the forthcoming RFC 7942 Implementation Status section.

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

</details>

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

## Follow and share the work

- [Ambiguous Payment Recovery Kit](https://ambiguous-payment-recovery-kit.lovable.app/?ref=github-profile&utm_source=github&utm_medium=profile&utm_campaign=ambiguous-payment-recovery) — live self-test, proof card, and machine-readable sandbox result.
- [RESONANCE](https://safal207.github.io/RESONANCE/) — evidence-first articles, verified reports, open problems, and market questions.
- [GitHub @safal207](https://github.com/safal207) — executable fixtures, tests, protocols, and public verification trails.
- [Brand, SEO & SMM kit](BRAND_SEO_SMM.md) — canonical bios, project one-liners, content pillars, and ready-to-use post formats.

## Contact

**Free recovery self-test:** [open the live kit](https://ambiguous-payment-recovery-kit.lovable.app/?ref=github-profile&utm_source=github&utm_medium=profile&utm_campaign=ambiguous-payment-recovery)  
**Paid review:** [send one high-risk workflow](mailto:safal0645@gmail.com?subject=Fixed-scope%20verification%20request)  
**Research, standards, grants, or collaboration:** [safal0645@gmail.com](mailto:safal0645@gmail.com)  
**Telegram:** [@Alexfox14](https://t.me/Alexfox14)  
**GitHub:** [@safal207](https://github.com/safal207)

```text
Build calmly. Pressure-test the boundary. Keep the evidence.
```
