# Aleksey Safonov

Independent AI Safety Researcher · Senior QA Engineer · FinTech reliability background

I build verifiable trust infrastructure for AI agents, fintech actions, memory systems, and public-good protocols.

```text
High-risk AI-agent actions should be reviewable, replayable, and evidence-backed before execution.
```

My work focuses on the infrastructure layer between an AI-agent proposal and a real-world effect: tool calls, code changes, infrastructure actions, financial workflows, governance actions, public-good protocols, and other high-impact operations.

## Creator & Editor — RESONANCE

> ### 🌐 [RESONANCE — Journal of Intelligence, Technology & Human Progress](https://safal207.github.io/RESONANCE/)
>
> I am the **creator and editor of RESONANCE**, an independent, evidence-first global journal about AI agents, trust infrastructure, science, technology, startups, and human progress.
>
> RESONANCE is the readable public layer above my research repositories: GitHub keeps the code, fixtures, benchmarks, PRs, and verification trail; the journal turns that evidence into clear stories, testable ideas, and open questions that engineers, researchers, founders, and product teams can actually engage with.
>
> **Why RESONANCE is different:**
>
> - **Evidence-first:** important claims link back to inspectable source material, code, PRs, fixtures, benchmarks, or authoritative references.
> - **Readable research:** dense technical threads become clear narratives — problem → mechanism → evidence → verification → implication → action.
> - **Multilingual:** key publication paths are available in **English, Russian, and Simplified Chinese**.
> - **Market dialogue, not vanity metrics:** selected articles end with a concrete open question designed to surface real workflows, missing guarantees, and product needs.
> - **Research-to-product loop:** `PUBLISH → ASK → LISTEN → DIAGNOSE → PILOT → PROVE → BUILD`.
> - **Inspectable publication quality:** SEO, internal-link, and Lighthouse experience contracts run in CI before publication.
>
> **Recent research:** [Memory Can Be True and Still Be Unsafe](https://safal207.github.io/RESONANCE/memory-can-be-true-and-still-be-unsafe.html) — why historical truth should not automatically retain current authority to drive an AI-agent action.
>
> **Open the journal → [RESONANCE](https://safal207.github.io/RESONANCE/)**  
> **Source repository → [safal207/RESONANCE](https://github.com/safal207/RESONANCE)**

<!-- partners:start -->
## Partners & verified collaborations

I distinguish completed collaboration, independent interoperability, merged open-source contribution, and pilot-stage conversations. Every status below is evidence-backed; none is a blanket endorsement or implied corporate alliance.

### Active collaborators

| Organization / project | Relationship | Verified status |
|---|---|---|
| [Valta](https://www.valta.co/) · [pilot lab](https://github.com/safal207/valta-pilot-lab) | Product verification and pilot collaboration | Completed and mutually signed-off Sprint 1 on agent-payment policy enforcement, concurrent-spend behavior, and retry/idempotency exposure; fixed-scope buyer pilots are being developed. |
| [Governex Agent Action Receipts](https://github.com/governex/agent-action-receipts-vectors) · [T-Trace/OpenPoC report](https://github.com/safal207/T-Trace/blob/main/docs/governex-action-receipts-compatibility.md) | Independent interoperability collaboration | T-Trace/OpenPoC independently matched all 13 public conformance vectors without importing the reference verifier; the planned `-01` Implementation Status will name the implementation. |
| [AgenTrust trace-spec](https://github.com/agentrust-io/trace-spec) | Open-source standards collaboration | Verification-outcome guidance was reviewed and merged in [PR #215](https://github.com/agentrust-io/trace-spec/pull/215); active work continues around action receipts and verification depth. |

### Fixed-scope pilot conversations

| Organization | Current state | Proposed pilot |
|---|---|---|
| [Passes](https://passes.com/) | Routed internally for product/payments review | Creator payment → earning → payout → reconciliation; timeout/retry pressure test; fixed scope `$500`. |
| [PaySureFy](https://paysurefy.com/) | Context qualified; fixed-scope offer sent for product/engineering review | Funded escrow → release/dispute → final settlement; boundary, retry, and exact-settlement tests; fixed scope `$750`. |

**Relationship boundary:** `active collaborator` means a completed working engagement, independent interoperability result, or merged open-source contribution. `Pilot conversation` does not mean customer, partner, adoption, endorsement, or signed engagement.
<!-- partners:end -->

<!-- smart-contract-services:start -->
## 🛡️ Smart-contract QA — accepting paid engagements

I accept **fixed-scope paid engagements** for independent smart-contract QA, adversarial testing, and financial state-machine verification.

**Best fit:** escrow, streaming payments, vesting, payouts and revenue sharing, wallets, DeFi/FinTech contracts, and agentic-payment systems. Solidity/Foundry is supported; other contract stacks can be agreed per scope.

### What I test

- lifecycle and state transitions: create → fund → execute → cancel/dispute → settle;
- value conservation, fees, balances, rounding, and exact end-time/cancellation boundaries;
- authorization, access control, replay/idempotency, retries, and concurrent calls;
- stuck funds, dead-end states, duplicate settlement or payout, stale state, and partial failure;
- contract ↔ API/backend ↔ ledger/audit consistency;
- regression, invariant, negative, boundary, and property-based tests.

### What the client receives

- a bounded test scope and risk model;
- reproducible failing tests and exact traces for confirmed issues;
- severity, business impact, and minimal remediation guidance;
- regression/invariant coverage and a concise engineering report;
- an optional fix or pull request when separately agreed.

### Engagement model

- start with one critical workflow instead of an open-ended audit;
- fixed scope, fee, authorization boundary, and deliverables agreed before execution;
- repository, testnet, sandbox, or another explicitly authorized test surface;
- no broad production access required;
- async written collaboration is available.

Recent verification scopes include escrow lifecycle safety, cancellation and exact end-time settlement, value conservation, dispute/release boundaries, concurrent execution, and duplicate/retry exposure.

**Request a review:** send the repository or contract link, chain and tooling, highest-risk workflow, current test status, and desired deadline to **safal0645@gmail.com** or Telegram **[@Alexfox14](https://t.me/Alexfox14)**.

**Evidence tooling:** [ContractGraph-QA](https://github.com/safal207/ContractGraph-QA)

> Independent QA and adversarial review reduce uncertainty within an agreed scope. They are not a guarantee of zero vulnerabilities, formal certification, or permission to test systems without authorization.
<!-- smart-contract-services:end -->


## Current external conversations

> **NVIDIA — Open Secure AI Alliance inquiry submitted (29 July 2026).** I submitted the official alliance form as an independent open-source maintainer and sent follow-up updates to the NVIDIA Connect and NVIDIA Inception program teams about the open-source agent-assurance portfolio.
>
> **Status:** awaiting guidance on the appropriate contributor or ecosystem pathway.
>
> This is a factual status update only. It does **not** imply membership, acceptance, affiliation, partnership, endorsement, or adoption by NVIDIA or the alliance.

## External review / falsification trail

My post-sandbox agent-governance work is being shared for adversarial review. The goal is to collect counterexamples, reproducible failure traces, and evidence-backed review state — not logos or implied endorsements.

| External target | Current evidence state | What it means |
|---|---|---|
| OpenAI | **ROUTED** | Support case #12892239 was explicitly passed to an appropriate internal team for review. |
| Anthropic Safeguards | **ACKNOWLEDGED** | Intake was acknowledged; technical review is not confirmed. |
| Meta | **SENT** | Post-sandbox governance one-pager, benchmark context, and external review trail were sent to the public Muse Spark Safety & Preparedness correspondence contact. |
| Hugging Face Security | **ACKNOWLEDGED** | Security report #41899 was received via automated acknowledgement. |
| OpenSSF AI/ML Security WG | **SENT** | Adversarial review request sent. |
| OWASP agentic-security / AI-testing contacts | **SENT** | Causal Transition Guard / Agent Trust Runtime material sent for review. |
| Invariant Labs | **SENT** | Multi-agent trust-runtime technical review requested. |
| AVERI-related third-party verification outreach | **SENT** | Open-source evidence-layer material sent for independent-review consideration. |

**Important:** `SENT`, `ACKNOWLEDGED`, and `ROUTED` are review-process states. They do **not** mean endorsement, independent reproduction, adoption, or validation.

The review trail is itself machine-verifiable:

```text
external response
      ↓
Review Event Envelope
      ↓
evidence-backed state transition
      ↓
External Validation Graph / EEW
      ↓
Git + CI
      ↓
ProofPath / CML
```

**Evidence source:** [LiminalOSAI — post-sandbox governance review trail](https://github.com/safal207/LiminalOSAI/pull/174)

## About me

> **Aleksey Safonov (Alex Lim, [@safal207](https://github.com/safal207)) — founder and evidence-systems builder**
>
> QA engineer, AI-product builder, and entrepreneur focused on turning uncertain, high-stakes ideas into testable protocols, traceable artifacts, and bounded decisions.
>
> **Mission:** build trustworthy infrastructure where AI models may propose possibilities, but evidence contracts and authorized humans determine what is supported and what may proceed.
>
> **Working principles:** root causes over symptoms · evidence over confidence · power under control · one verifiable artifact at a time.
>
> **Current frontier:** [Kairos Gate for X-Cell](https://github.com/safal207/Kairos-Gate-for-X-Cell), an evidence and governance layer for agentic biology that separates scientific support from permission to act.
>
> **Role boundary:** I do not present myself as a biologist or clinician and do not authorize experiments or treatment. My contribution is QA, product thinking, causal and evidence architecture, reproducibility, traceability, and governance.
>
> **Personal archetype:** the Silver Surfer — great power restrained by principle, balance, and responsibility.

## Bio / Agentic Biology

> ### 🧬 [Kairos Gate for X-Cell](https://github.com/safal207/Kairos-Gate-for-X-Cell)
>
> **Evidence and governance infrastructure for agentic biology.**
>
> Kairos Gate checks experimental units, provenance, independent replication, temporal identity, competing causal explanations, model compatibility, and claim boundaries before a scientific conclusion is allowed to move forward.
>
> ```text
> models may propose possibilities
>                 ↓
> evidence contracts determine what is supported
>                 ↓
> authorized humans determine what may proceed
> ```
>
> The project is computational and documentary only. It does not authorize wet-lab work, treatment, or clinical decisions.
>
> **Open the bio direction → [Kairos Gate for X-Cell](https://github.com/safal207/Kairos-Gate-for-X-Cell)**

## External bio ecosystem map

Kairos Gate is being designed to audit, compare, or interoperate with public open-source biology projects. These are **technical and scientific ecosystem relationships**, not claims of affiliation, endorsement, integration, or formal partnership.

| External repository | Ecosystem role | Kairos relationship |
|---|---|---|
| [DeplanckeLab/Live-seq](https://github.com/DeplanckeLab/Live-seq) | longitudinal single-cell transcriptomics and linked later phenotype | current reference case for source provenance, experimental-unit semantics, temporal identity, and replication-gap auditing |
| [NVIDIA/BioNeMo](https://github.com/NVIDIA/BioNeMo) | central open developer platform and index for AI-driven life-science tooling | target ecosystem for evidence passports, model governance, and reproducible compatibility reports |
| [NVIDIA-BioNeMo/bionemo-framework](https://github.com/NVIDIA-BioNeMo/bionemo-framework) | training and adaptation framework for biomolecular models | planned compatibility gate covering modality, species, context, timing, license, compute, training overlap, and domain shift |
| [ArcInstitute/evo2](https://github.com/ArcInstitute/evo2) | DNA foundation model for genome modeling and design | model-compatibility candidate; generated outputs must not substitute for independent biological evidence |
| [ArcInstitute/state](https://github.com/ArcInstitute/state) | cellular perturbation-response prediction | evaluation candidate for separating predictive performance from causal, experimental, or therapeutic support |
| [ArcInstitute/cell-eval](https://github.com/ArcInstitute/cell-eval) | perturbation-prediction evaluation metrics | candidate benchmark layer for machine-readable model evidence and reproducible score provenance |
| [ArcInstitute/SRAgent](https://github.com/ArcInstitute/SRAgent) | LLM agents for SRA and bioinformatics-database discovery | comparison and integration candidate for provenance-aware dataset search, rejection reasons, and evidence retention |
| [bowang-lab/scGPT](https://github.com/bowang-lab/scGPT) | single-cell foundation model | compatibility candidate requiring explicit species, modality, training-overlap, context, and domain-shift checks |

```text
public model or dataset
          ↓
exact-version provenance
          ↓
Kairos evidence contracts
          ↓
supported, limited, unresolved, or blocked claim
```

A repository appearing in this map means it is a relevant public evidence, model, benchmark, or agent surface. It does **not** mean its maintainers have reviewed, approved, adopted, or partnered with Kairos Gate.

## Core thesis

Modern AI systems do not only answer questions. They increasingly call tools, write code, modify infrastructure, move data, trigger workflows, and make decisions with real-world consequences.

My research and engineering work asks:

- What evidence should exist before an AI agent performs a high-risk action?
- How can action traces be made replayable, tamper-checkable, and useful for human reviewers?
- How can deterministic control layers complement probabilistic model evaluations?
- How can financial, governance, and infrastructure actions become more accountable before execution?
- What should a practical trust layer look like for multi-agent and human-in-the-loop systems?

## Active projects

### [RESONANCE](https://safal207.github.io/RESONANCE/)

Independent evidence-first journal and market-dialogue layer for AI, trust infrastructure, science, technology, startups, and human progress.

```text
research signal -> evidence -> readable story -> open question -> real workflow -> product signal
```

RESONANCE makes the technical work easier to inspect and easier to discuss outside a repository. It connects public research artifacts to a multilingual editorial layer and a structured `PUBLISH → ASK → LISTEN → BUILD` loop.

### [Kairos Gate for X-Cell](https://github.com/safal207/Kairos-Gate-for-X-Cell)

Evidence and governance layer for agentic biology.

```text
scientific proposal -> evidence audit -> bounded claim -> authorized human decision
```

Kairos Gate separates biological evidence, model output, and permission to act. It is the main bio-direction project for experimental-unit auditing, provenance, replication, temporal validity, causal-hypothesis ranking, and partner-laboratory evidence handoff.

### [Causal-Memory-Layer](https://github.com/safal207/Causal-Memory-Layer)

Causal audit layer for AI-agent action traces.

```text
agent action -> parent cause -> audit rule -> finding -> reviewer evidence
```

CML focuses on causal lineage: whether an agent action has a valid parent, approval path, and reviewable trace. It is designed as a lightweight accountability primitive for agent frameworks, memory systems, and high-risk tool-use workflows.

### [ProofPath](https://github.com/safal207/ProofPath)

Pre-execution gateway for high-risk AI-agent/API actions.

```text
valid credential != valid action != valid scope != valid reversibility != valid approval
```

ProofPath protects the meaning of an action before execution: intent, scope, causal parent, reversibility, approval, and audit trail.

Best entry point for reviewers:  
[Reviewer First Screen](https://github.com/safal207/ProofPath/blob/main/docs/REVIEWER_FIRST_SCREEN.md)

### [LiminalDB](https://github.com/safal207/LiminalDB)

Local-first and federated event-memory database for inspectable, replayable systems.

LiminalDB explores event envelopes, local replay, validation paths, and future federated replication for memory and protocol infrastructure.

### [fediverse-portability-test-kit](https://github.com/safal207/fediverse-portability-test-kit)

Public-good test kit for Fediverse portability, export/import checks, media integrity, visibility safety, and reviewer-friendly compatibility reports.

### [pythiaLabs](https://github.com/safal207/pythiaLabs)

Research and portfolio space for pre-execution evidence gates and AI-agent oversight prototypes.

Best entry point for grant, fellowship, and AI safety reviewers:  
[Reviewer Start Here](https://github.com/safal207/pythiaLabs/blob/main/REVIEWER_START_HERE.md)

### [LiminalQAengineer](https://github.com/safal207/LiminalQAengineer)

Causality-aware QA/CI reliability substrate for reproducible failure analysis and quality decision packets.

Best entry point for reliability and open-source infrastructure reviewers:  
[Reviewer First Screen](https://github.com/safal207/LiminalQAengineer/blob/main/docs/REVIEWER_FIRST_SCREEN.md)

## Liminal Stack

The broader project family is becoming a layered stack:

```text
CML                         -> causal accountability for agent traces
ProofPath                   -> action authorization and payment/API guard
LiminalDB                   -> replayable event-memory substrate
L-THREAD / LTP              -> secure trace and replay protocol
Liminal Presence Interface  -> presence, identity, and interaction layer
L-EDGE                      -> edge/runtime direction
Fediverse portability kit   -> public-good validation and portability testing
```

This is the long-term direction:

```text
verifiable trust infrastructure for AI agents, fintech actions, memory systems, and public-good protocols
```

## Project map

### Active focus

| Project | Role | Why it matters |
|---|---|---|
| [RESONANCE](https://safal207.github.io/RESONANCE/) | evidence-first journal + market-dialogue layer | turns research artifacts into readable multilingual narratives, open questions, and product signals |
| [Kairos Gate for X-Cell](https://github.com/safal207/Kairos-Gate-for-X-Cell) | agentic-biology evidence and governance layer | main bio direction; separates scientific support from permission to act |
| [Causal-Memory-Layer](https://github.com/safal207/Causal-Memory-Layer) | AI-agent causal audit | strongest AI safety / agent observability artifact |
| [ProofPath](https://github.com/safal207/ProofPath) | pre-execution action guard | strongest fintech / API / AI-agent authorization artifact |
| [LiminalDB](https://github.com/safal207/LiminalDB) | replayable event-memory DB | grant/public-good infrastructure path |
| [fediverse-portability-test-kit](https://github.com/safal207/fediverse-portability-test-kit) | portability validation kit | public-good / Fediverse grant path |
| [LiminalQAengineer](https://github.com/safal207/LiminalQAengineer) | QA reliability substrate | bridge between QA experience and AI infrastructure |

### Incubating

These projects are related to the long-term platform direction, but should remain secondary until the active focus is clearer:

- [L-THREAD-Liminal-Thread-Secure-Protocol-LTP-](https://github.com/safal207/L-THREAD-Liminal-Thread-Secure-Protocol-LTP-)
- [Liminal-Presence-Interface-LPI](https://github.com/safal207/Liminal-Presence-Interface-LPI)
- [L-EDGE-Liminal-Edge-OS](https://github.com/safal207/L-EDGE-Liminal-Edge-OS)
- [DMP-decision-memory-protocol](https://github.com/safal207/DMP-decision-memory-protocol)
- [Living-Relational-Identity-LRI](https://github.com/safal207/Living-Relational-Identity-LRI)
- [LRE-Core](https://github.com/safal207/LRE-Core)
- [Access-Orientation-Protocol](https://github.com/safal207/Access-Orientation-Protocol)
- [Scale-Descent-Protocol-SDP](https://github.com/safal207/Scale-Descent-Protocol-SDP)

### QA, career, and fintech bridge

These projects connect my background in QA, fintech, reliability, and product systems:

- [CareerOS](https://github.com/safal207/CareerOS)
- [qa-fintech-api-python-course](https://github.com/safal207/qa-fintech-api-python-course)
- [finanalytics-core](https://github.com/safal207/finanalytics-core)
- [TachTachAI](https://github.com/safal207/TachTachAI)
- [nexus-sales](https://github.com/safal207/nexus-sales)
- [nexus-ecosystem](https://github.com/safal207/nexus-ecosystem)

### Archive / idea bank

Some repositories are intentionally kept as prototypes, sketches, or idea bank material. They may contain useful concepts, but they are not the current execution focus.

Examples include older experiments around Liminal, Noosphere, education, Web3, DAO, voice, self-creation, and personal protocol ideas.

## Status and scope

These projects are experimental open-source research prototypes, not production safety infrastructure yet.

They do not claim full AI alignment, complete agent safety, certified security, regulatory compliance, or universal prevention of unsafe actions.

The current contribution is narrower and more testable:

```text
make high-risk AI-agent actions reviewable, replayable, and evidence-backed before execution
```

## Background

I have 12+ years of software QA and FinTech reliability experience, including brokerage, banking, API, WebSocket, SQL, risk, reporting, test strategy, regression prioritization, and quality process design.

This background shapes my AI safety work: I treat agent oversight as an engineering reliability problem, not only as a model-behavior problem.

## Reviewer paths

For reviewers, grantmakers, and collaborators:

- [RESONANCE — evidence-first journal](https://safal207.github.io/RESONANCE/)
- [RESONANCE source repository](https://github.com/safal207/RESONANCE)
- [Kairos Gate for X-Cell — bio direction](https://github.com/safal207/Kairos-Gate-for-X-Cell)
- [Causal-Memory-Layer](https://github.com/safal207/Causal-Memory-Layer)
- [ProofPath reviewer first screen](https://github.com/safal207/ProofPath/blob/main/docs/REVIEWER_FIRST_SCREEN.md)
- [PythiaLabs reviewer start](https://github.com/safal207/pythiaLabs/blob/main/REVIEWER_START_HERE.md)
- [PythiaLabs portfolio map](https://github.com/safal207/pythiaLabs/blob/main/AI_SAFETY_PORTFOLIO.md)
- [LiminalQAengineer reviewer first screen](https://github.com/safal207/LiminalQAengineer/blob/main/docs/REVIEWER_FIRST_SCREEN.md)
- [LiminalDB](https://github.com/safal207/LiminalDB)
- [Fediverse portability test kit](https://github.com/safal207/fediverse-portability-test-kit)

## Contact

Email: safal0645@gmail.com  
Telegram: @Alexfox14  
GitHub: https://github.com/safal207

---

## Short version

```text
I build deterministic oversight layers that gate, audit, and explain high-risk AI-agent actions before execution — and publish the evidence and open questions through RESONANCE.
```
