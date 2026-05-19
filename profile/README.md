![Status](https://img.shields.io/badge/status-published-1a1917?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0-1a1917?style=flat-square)
![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey?style=flat-square)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18833956.svg)](https://doi.org/10.5281/zenodo.18833956)

# Agent Manifest

A declarative specification for AI agent identity, authority, and operational boundaries — making agent identity, declared authority, and operational boundaries legible before execution.

**Start here**

- **Visitors / reviewers** — [agent-manifest-spec.org](https://agent-manifest-spec.org)
- **Developers / builders** — [agent-manifest](https://github.com/agent-manifest/agent-manifest) (specification, schema, 5-minute integration)
- **Researchers / conceptual readers** — [∈ Principle](https://github.com/agent-manifest/e-principle) (philosophical foundation)

---

## What It Is

Agent Manifest is an open specification that enables AI agents to declare their identity, purpose, capabilities, and operational boundaries in a structured, machine-readable format **before any interaction begins**.

A manifest is a pre-execution declaration. It is not a runtime observation, a behavioral log, or an enforcement mechanism. It is a structured commitment made by or on behalf of an agent, published at a known location, and readable by any party before the interaction starts.

---

## What It Is Not

- It is not a runtime monitor or behavioral inspector.
- It is not a compliance enforcement layer.
- It is not a guarantee of behavior — it is a declaration of intent and declared constraints.
- It does not observe, intercept, or audit live agent execution.
- It does not replace governance frameworks, policy engines, or audit systems.

A manifest makes declared identity and boundaries legible. Whether those declarations are honored is a separate layer of responsibility.

---

## Core Principles

**Declaration before interaction.** An agent that declares itself before acting is structurally different from one that does not. The declaration creates a record, a reference point, and an implicit commitment.

**Pre-execution legibility.** Identity, purpose, capabilities, and boundaries must be readable before execution begins — not reconstructed from logs after the fact.

**Structural accountability.** Public declaration under a known identity creates accountability through visibility, not through enforcement.

**Open and composable.** The specification is open, versioned, and designed to be composed with governance, policy, and discovery layers built by others.

---

## Ecosystem

| Repository | Role |
|---|---|
| [agent-manifest](https://github.com/agent-manifest/agent-manifest) | Core specification and JSON schema |
| [agent-manifest-registry](https://github.com/agent-manifest/agent-manifest-registry) | Governance model and discovery layer |
| [agent-manifest-dataset](https://github.com/agent-manifest/agent-manifest-dataset) | Public registry of declared manifests |
| [agent-manifest-ambassador](https://github.com/agent-manifest/agent-manifest-ambassador) | Conversational manifest generator |
| [agent-manifest-diplomat](https://github.com/agent-manifest/agent-manifest-diplomat) | Registration API endpoint (infrastructure) |
| [boundary-handshake](https://github.com/agent-manifest/boundary-handshake) | Declaration-first agent interoperability |
| [e-principle](https://github.com/agent-manifest/e-principle) | Philosophical foundation: *The Destination of Actions* |

---

## Specification

**Schema**
```
https://agent-manifest-spec.org/spec/v1.0/schema.json
```

**Discovery endpoint**
```
https://agent-manifest-spec.org/.well-known/agent-manifest-registry.json
```

**Website**
[agent-manifest-spec.org](https://agent-manifest-spec.org)

---

## Research & Citation

Agent Manifest ecosystem artifacts are archived with DOI via Zenodo.

| Artifact | DOI |
|---|---|
| Agent Manifest specification | [10.5281/zenodo.18833956](https://doi.org/10.5281/zenodo.18833956) |
| Boundary Handshake | [10.5281/zenodo.18894794](https://doi.org/10.5281/zenodo.18894794) |
| ∈ Principle | [10.5281/zenodo.18965669](https://doi.org/10.5281/zenodo.18965669) |

**ORCID** [0009-0008-7216-3032](https://orcid.org/0009-0008-7216-3032)

---

## License

Specification and documentation: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
Infrastructure code: MIT

Individual repositories may carry their own license terms.

---

**Part of the [Agent Manifest](https://agent-manifest-spec.org) ecosystem**

[Spec](https://github.com/agent-manifest/agent-manifest) ·
[Registry](https://github.com/agent-manifest/agent-manifest-registry) ·
[Dataset](https://github.com/agent-manifest/agent-manifest-dataset) ·
[Ambassador](https://github.com/agent-manifest/agent-manifest-ambassador) ·
[Diplomat](https://github.com/agent-manifest/agent-manifest-diplomat) ·
[Boundary Handshake](https://github.com/agent-manifest/boundary-handshake) ·
[∈ Principle](https://github.com/agent-manifest/e-principle)

CC BY 4.0 · Hernán Alfredo Capucci · [ORCID 0009-0008-7216-3032](https://orcid.org/0009-0008-7216-3032)
