# Reacher

**Reachable failure paths for autonomous on-chain agents.**

R/A/U state validation. ERC-8004 attestations. Verification, not coordination.

→ [getreacher.xyz](https://getreacher.xyz)

---

## Naming and Prior Work

This project's repository handle is `OleksandrBondarr` with a doubled r. My legal surname is **Bondar**. The doubled-r appears in this handle and the repo URL only because the username `Bondar` was already taken on GitHub when I registered. Canonical Reacher publications use *Bondar*; the doubled-r persists only in immutable handle-level identifiers.

This matters because **Roman Bondar** is co-author of [arXiv:2601.08333](https://arxiv.org/abs/2601.08333), [arXiv:2601.15059](https://arxiv.org/abs/2601.15059), [arXiv:2603.03119](https://arxiv.org/abs/2603.03119), and sole author of [draft-bondar-wca-00](https://datatracker.ietf.org/doc/draft-bondar-wca/) — foundational works that this project's methodology directly builds on. Roman Bondar and I are not related, to my knowledge; *Bondar* is a common Ukrainian surname (cooper / barrel-maker).

Reacher's theoretical foundations are not original to this project. The following primitives originate in the Romanchuk–Bondar / Bondar work and are cited throughout the Mirror Report:

- **Semantic laundering** — Romanchuk & Bondar, arXiv:2601.08333
- **Warrant erosion principle** — Romanchuk & Bondar, arXiv:2601.08333
- **Theorem of Inevitable Self-Licensing** — Romanchuk & Bondar, arXiv:2601.08333
- **Channel-to-content trust conflation** — Bondar, draft-bondar-wca-00 §2
- **Non-interference (NI-1/2/3)** — Bondar, draft-bondar-wca-00 §9.1
- **Responsibility vacuum** — Romanchuk & Bondar, arXiv:2601.15059
- **4-modality speech-act admissibility** — Romanchuk, draft-romanchuk-normative-admissibility-00

What Reacher contributes that is original to this project: R/A/U state classification operating on system states (not statements); on-chain attestation binding via ERC-8004; multi-agent Epistemic Evolution Engine methodology; applied implementation in the DeFAI domain (Olas/Pearl ecosystem).

I disclosed this situation to Oleg Romanchuk and Roman Bondar by direct email on **9 May 2026**, before the Mirror Report's public release on 14 May 2026.

---

## What Reacher does

Smart contract audits ask: *did the agent execute correctly?*
Reacher asks: *which failure paths can the agent actually reach?*

Different question. Different methodology. Different artifact.

Reacher provides independent epistemic validation for autonomous on-chain agents through R/A/U state classification, with results published as Mirror reports and anchored as signed attestations on the ERC-8004 Validation Registry.

---

## R/A/U Classification

| Class | Definition |
|---|---|
| **R** — Reachable | Path exists from current state. Warrant chain complete. External observations confirm. |
| **A** — Assumption-bounded | Path conditional on unverified premise. Warrant chain incomplete. |
| **U** — Unreachable | Path architecturally excluded under protocol constraints. No state transition exists. |

Per-state. Per-agent. Per-system.

---

## Why this exists

ERC-8004's Validation Registry currently supports three trust mechanisms:

- TEE attestations
- zkML proofs
- Stake-secured re-execution

All verify execution fidelity — that the code ran without tampering.

None classify what the agent can actually reach: whether claimed Reachable paths are genuinely reachable, whether Assumption-bounded paths' premises hold, or whether Unreachable paths are truly architecturally excluded.

When autonomous agents transact real capital at machine speed across multi-chain environments, "the system says it worked" is a coordination artifact, not a verification claim.

The methodology layer is missing. Reacher fills it.

---

## How it works

The Reacher methodology framework operates through five disciplined principles:

1. **Reachability over execution.** Auditors verify code ran. Reacher classifies which states the system can transit to. Reachability is not correctness — and correctness without reachability bounds is silent on the failure modes that matter most.

2. **States, not statements.** Where speech-act admissibility frameworks classify what an agent can *say* admissibly, R/A/U classifies what an agent can *cause* the system to *reach*. The two layers are orthogonal and complementary.

3. **Verification, not coordination.** Format-level checks in which all participants agree the system works produce *coordination* contracts that license themselves. Independent external classification — anchored on-chain — produces a *verification* contract. ERC-8004 attestation is the substrate; methodology is the differentiator.

4. **Open methodology.** All hypothesis cards, R/A/U classifications, and warrant chains are published with the Mirror Report. Closed-box scoring without methodology disclosure is itself a self-licensing failure mode.

5. **Per-deployment, not per-vendor.** Each Reacher report targets a specific deployment (a specific agent class, on a specific protocol, on a specific chain). Vendor-level aggregate scores collapse the dimensions that operational risk lives in.

---

## Report #001 — May 14, 2026

**Target:** DeFAI trader agents, Olas/Pearl Modius/Optimus class operating on Base, Optimism, and Mode.

**Output:** Mirror report (8 hypothesis cards, R/A/U-classified findings, executive score matrix, mitigation list) plus signed on-chain attestation anchored on the ERC-8004 Validation Registry.

**Methodology:** Epistemic Evolution Engine — multi-agent process (ScientistNode → CounterfactualNode → AdversarialCritic) with explicit UNRECOVERABLE flagging and warrant-chain mapping per finding.

---

## Reach

- Twitter: [@getreacher](https://twitter.com/getreacher)
- Farcaster: [@getreacher](https://warpcast.com/getreacher)
- ENS: [reacherxyz.eth](https://app.ens.domains/reacherxyz.eth)
- Site: [getreacher.xyz](https://getreacher.xyz)

---

*Reacher v.001 · OPERATIONAL · 2026*
