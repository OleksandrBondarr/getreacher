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

| Class | Definition |
|---|---|
| **R** — Reachable | Path exists from current state. Warrant chain complete. External observations confirm. |
| **A** — Assumption-bounded | Path conditional on unverified premise. Warrant chain incomplete. |
| **U** — Unreachable | Path architecturally excluded under protocol constraints. No state transition exists. |

Per-state. Per-agent. Per-system.

-----

## Why this exists

ERC-8004's Validation Registry currently supports three trust mechanisms:

- TEE attestations
- zkML proofs
- Stake-secured re-execution

All verify execution fidelity — that the code ran without tampering.

None classify what the agent can actually reach: whether claimed Reachable paths are genuinely reachable, whether Assumption-bounded paths' premises hold, or whether Unreachable paths are truly architecturally excluded.

When autonomous agents transact real capital at machine speed across multi-chain environments, "the system says it worked" is a coordination artifact, not a verification claim.

The methodology layer is missing. Reacher fills it.

-----

## How it works

The Reacher methodology framework operates through five disciplined principles:

