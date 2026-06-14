# Aleksey Safonov

Independent AI Safety Researcher · Senior QA Engineer · FinTech reliability background

I build verifiable trust infrastructure for AI agents, fintech actions, memory systems, and public-good protocols.

```text
High-risk AI-agent actions should be reviewable, replayable, and evidence-backed before execution.
```

My work focuses on the infrastructure layer between an AI-agent proposal and a real-world effect: tool calls, code changes, infrastructure actions, financial workflows, governance actions, public-good protocols, and other high-impact operations.

## Core thesis

Modern AI systems do not only answer questions. They increasingly call tools, write code, modify infrastructure, move data, trigger workflows, and make decisions with real-world consequences.

My research and engineering work asks:

- What evidence should exist before an AI agent performs a high-risk action?
- How can action traces be made replayable, tamper-checkable, and useful for human reviewers?
- How can deterministic control layers complement probabilistic model evaluations?
- How can financial, governance, and infrastructure actions become more accountable before execution?
- What should a practical trust layer look like for multi-agent and human-in-the-loop systems?

## Active projects

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
I build deterministic oversight layers that gate, audit, and explain high-risk AI-agent actions before execution.
```