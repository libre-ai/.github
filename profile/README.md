# Libre AI

Libre AI is an open-source, sovereign software lab rebuilding its product line for the AI-native era.

**All current work happens in the canonical base repository: [`libre-ai/libre-ai`](https://github.com/libre-ai/libre-ai)** — contracts, specifications, architecture, and shared foundations.

The target topology is multi-repository ([ADR-0008](https://github.com/libre-ai/libre-ai/blob/main/docs/adr/0008-multi-repo-target-topology-and-brand.md)): real product repositories will reopen on their preserved historical URLs, consuming the base as a versioned dependency. Until a product is activated by owner decision, its repository stays frozen with a status notice. Legacy tooling repositories are retired after verified capture; the freeze record is [`ecosystem/LEGACY-MANIFEST.yaml`](https://github.com/libre-ai/libre-ai/blob/main/ecosystem/LEGACY-MANIFEST.yaml).

Seven products are being rebuilt from locked specifications: **Radar, Notebook, AI Practices, Sessions, Boussole Politique, Spec Studio, and Model Policy**. None is released yet; foundations come first.

The portfolio's pole star is **the method itself** ([ADR-0009](https://github.com/libre-ai/libre-ai/blob/main/docs/adr/0009-constellation-portfolio-and-method.md)): governable agentic management of this constellation — bounded plans, refusals, evidence, gates. Its public tracer is this very forge, self-documented. The machine-readable inventory of this organization is [`ecosystem/repositories.v1.yaml`](https://github.com/libre-ai/libre-ai/blob/main/ecosystem/repositories.v1.yaml); this page is a projection of it.

Start here:

- [Vision](https://github.com/libre-ai/libre-ai/blob/main/vision.md) — why a greenfield rebuild, 10-year horizon
- [Goals and status](https://github.com/libre-ai/libre-ai/blob/main/STATUS.md) — phased transformation (G0–G5), currently G2
- [Target architecture](https://github.com/libre-ai/libre-ai/blob/main/docs/architecture/TARGET.md)
- [Invariants register](https://github.com/libre-ai/libre-ai/blob/main/docs/decisions/INVARIANTS.md)

Governance and forge doctrine: [`constantin-jais/constantin-jais`](https://github.com/constantin-jais/constantin-jais) (control plane).
