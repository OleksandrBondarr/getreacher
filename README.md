# Reacher

**Reachable failure paths for autonomous on-chain agents.**

R/A/U state validation. ERC-8004 attestations. Verification, not coordination.

→ [getreacher.xyz](https://getreacher.xyz)

-----

## What Reacher does

Smart contract audits ask: *did the agent execute correctly?*
Reacher asks: *which failure paths can the agent actually reach?*

Different question. Different methodology. Different artifact.

Reacher provides independent epistemic validation for autonomous on-chain agents through R/A/U state classification, with results published as Mirror reports and anchored as signed attestations on the ERC-8004 Validation Registry.

-----

## R/A/U Classification

|Class                     |Definition                                                                            |
|--------------------------|--------------------------------------------------------------------------------------|
|**R** — Reachable         |Path exists from current state. Warrant chain complete. External observations confirm.|
|**A** — Assumption-bounded|Path conditional on unverified premise. Warrant chain incomplete.                     |
|**U** — Unreachable       |Path architecturally excluded under protocol constraints. No state transition exists. |

Per-state. Per-agent. Per-system.

-----

## Why this exists

ERC-8004’s Validation Registry currently supports three trust mechanisms:

- TEE attestations
- zkML proofs
- Stake-secured re-execution

All verify execution fidelity — that the code ran without tampering.

None classify what the agent can actually reach: whether claimed Reachable paths are genuinely reachable, whether Assumption-bounded paths’ premises hold, or whether Unreachable paths are truly architecturally excluded.

When autonomous agents transact real capital at machine speed across multi-chain environments, “the system says it worked” is a coordination artifact, not a verification claim.

The methodology layer is missing. Reacher fills it.

-----

## How it works

```
1. System Selection
   Identify target agent system. Define R/A/U boundaries.

2. Hypothesis Cards
   For each candidate failure path:
     • Truth-maker identified
     • Warrant chain mapped
     • R/A/U classification assigned

3. Independent Verification
   External observation. No self-licensing.
   Same epistemic class isolated.

4. Validation Report
   Public Mirror publication.
   Executive summary + per-card analysis.

5. On-chain Attestation
   Signed via ERC-8004 Validation Registry.
   Persistent, verifiable, system-level.
```

-----

## Status

**v.001** — First validation report drops on Mirror **May 14, 2026**.

- Target system: DeFAI trader agents (Olas/Modius class)
- 8 hypothesis cards (SYS-01 through SYS-08)
- Mirror publication + signed on-chain attestation

-----

## Research foundation

Reacher operationalizes architectural epistemology research developed by Romanchuk & Bondar (2026) within the specific domain of autonomous on-chain agents.

- Their framework formalizes agent statement evaluation. Reacher classifies agent state paths.
- Their domain is general LLM agents. Reacher’s domain is on-chain DeFAI / ERC-8004.
- Their output is normative algorithm specification. Reacher’s output is signed on-chain attestations.

### References

- Romanchuk, O. & Bondar, R. (2026). “Semantic Laundering in AI Agent Architectures: Why Tool Boundaries Do Not Confer Epistemic Warrant.” [arXiv:2601.08333](https://arxiv.org/abs/2601.08333)
- Romanchuk, O. & Bondar, R. (2026). “The Responsibility Vacuum: Organizational Failure in Scaled Agent Systems.” [arXiv:2601.15059](https://arxiv.org/abs/2601.15059)
- Romanchuk, O. (2026). “Normative Admissibility Framework for Agent Speech Acts.” IETF [draft-romanchuk-normative-admissibility-00](https://datatracker.ietf.org/doc/draft-romanchuk-normative-admissibility/)

-----

## Identity

|Channel  |Handle / Address                                        |
|---------|--------------------------------------------------------|
|Web      |[getreacher.xyz](https://getreacher.xyz)                |
|Twitter  |[@getreacher](https://twitter.com/getreacher)           |
|Farcaster|[@getreacher](https://warpcast.com/getreacher)          |
|ENS      |[reacherxyz.eth](https://app.ens.domains/reacherxyz.eth)|

-----

## Methodology

Reacher uses the **Epistemic Evolution Engine (EE)** — a methodology for systematic hypothesis validation through R/A/U state classification, developed by [Renova.lab](https://renova.lab).

-----

## Note on naming

The author’s surname (Bondarr) is unrelated to Roman Bondar of Romanchuk & Bondar (2026). Both works are independent.

-----

## License

This repository contains the public landing page for Reacher. All Reacher methodology, validation reports, and associated artifacts are © Renova.lab 2026.

-----

*Operating from autonomous.*
