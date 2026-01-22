# HCIP: Human–Cognitive Interface Protocol  
**Author:** Christopher Coyle  
**Repository Focus:** Ethical Spine, Governance Framework, and Cross‑System Coherence Testing  
**Status:** Conceptual Architecture & Public‑Safe Artifacts

---

## Overview

HCIP (Human–Cognitive Interface Protocol) is a cognitive architecture centered on a **fixed ethical spine**, explicit **governance and safety primitives**, and **audit‑ready decision traces**.

This repository contains **public‑safe artifacts only**, designed for:

- Cross‑system evaluation (LLMs, agents, and tooling)
- Ethical and governance benchmarking
- Research, discussion, and standards exploration

All implementation details of HCIP remain **proprietary** and are intentionally excluded.

---

## Ethical Spine (ETHIC_SPINE_V1)

As of **January 22, 2026 — 13:28 CST**, in English:

> “The HCIP ethical spine is a fixed set of five invariants—autonomy, non‑harm, truthfulness, dignity, and transparent governance—that cannot be reconstructed, inverted, drifted, or overridden by any operator or subsystem.”

**Invariants:**

- **E1 — Autonomy:** No coercion or collapse of user agency.  
- **E2 — Non‑harm:** No causing or enabling harm; no instrumentalization of persons.  
- **E3 — Truthfulness:** No fabrication of capabilities; no deceptive framing.  
- **E4 — Dignity:** No degradation or diminishment of personhood.  
- **E5 — Transparent Governance:** Governance actions must be transparent, reversible, and accountable.

These are treated as **axioms**, not tunable policies.

---

## Public Artifacts in This Repository

This repo includes:

- **HCIP Ethical Spine (ETHIC_SPINE_V1)** — canonical, timestamped definition  
- **HCIP Ethical Coherence & Safety Test Suite** — for LLMs and systems to self‑evaluate against HCIP’s principles  
- **Auditability & Governance Descriptions** — how decisions can be traced back to specific invariants  
- **Unified Boundary Protocol (UBP‑1.0) — Public‑Safe Excerpt** — how HCIP separates public concepts from proprietary mechanisms

**Not included:**

- Operator internals  
- FRAME schemas  
- Reconstruction algorithms  
- Load/expiry equations  
- Ledger implementation details  
- Emergent behavior logs or traces  

These remain private and are not part of this repository.

---

## HCIP Ethical Coherence & Safety Test Suite

The test suite is designed for **external systems (including LLMs)** to evaluate:

- **Ethical consistency** of the five invariants  
- **Structural coherence** of a HCIP‑like architecture  
- **Resilience under corruption and semantic inversion scenarios**  
- **Auditability** of ethical decisions

Evaluators are instructed to return:

- `OVERALL_VERDICT: PASS` or `OVERALL_VERDICT: FAIL`  
- A short justification referencing specific tests

This suite is **implementation‑agnostic** and can be used as:

- A research tool  
- A governance benchmark  
- A safety/compliance check for HCIP‑inspired systems

---

## Attribution

HCIP and the associated ethical spine, governance framing, and test suites were authored by **Christopher Coyle**.

This repository serves to:

- Establish **authorship and conceptual priority**  
- Provide **public‑safe artifacts** for evaluation and dialogue  
- Support future **standardization and licensing** efforts

Implementation details of HCIP are **proprietary** and protected as intellectual property.

---

## License

© Christopher Coyle.  
You may use the materials in this repository for **research, evaluation, and discussion**, provided that:

- Authorship is preserved  
- HCIP is cited appropriately  
- No claim is made to the underlying proprietary implementation

For commercial use, licensing, or collaboration inquiries, please contact the author.