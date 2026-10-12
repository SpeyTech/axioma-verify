# axioma-verify
## Axioma Framework — Verification Tooling — Replay, Chain Verification, Bit-Identity

**DVEC:** v1.3
**Determinism Class:** D1
**Layer:** Verification Tooling — Replay, Chain Verification, Bit-Identity
**License:** AGPL-3.0
**Part of:** [axilog.io](https://axilog.io) · SpeyTech

> *"Turing completeness is a vulnerability. Totality is a feature."*

### Overview

**Status: placeholder. No implementation exists at this revision.**

The repository contains directory scaffolding (`.gitkeep` files), the LICENSE and this README. There is no source code, header, build system, test or requirements document. The intended scope (replay, chain verification and bit-identity tooling) is not implemented here. At this revision:

- the only independent verifier in the estate is [fcc-verify](https://github.com/SpeyTech/fcc-verify), which checks FCC experiment frames and is not a general Axioma evidence verifier;
- `axioma-audit` provides `ax_verify_chain()`, which checks context flags only and does not recompute or compare hashes.

### Governing Documents

- [Axioma Framework v0.4](https://github.com/SpeyTech/axioma-spec/blob/main/docs/AXIOMA-FRAMEWORK-v0.4.md)
- DVEC-001: this README declares v1.3; the only DVEC text in axioma-spec is [DVEC-001 v1.4](https://github.com/SpeyTech/axioma-spec/blob/main/docs/DVEC-001-v1.4-Final.md)
- [DVM-SPEC-001](https://github.com/SpeyTech/certifiable)

### SRS Documents

None at this revision (`docs/requirements/` is empty).

### License

AGPL-3.0 — see LICENSE

---

Copyright © 2026 Spey Systems LTD. All rights reserved.
Patent GB2521625.0
