---

asset_id: DMAF-FWK-001
title: DMAF Framework Core
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0
practice_domain:

* Governance
* Executive Advisory
* Modernization Architecture
  lifecycle_stage:
* Opportunity Qualification & Modernization Strategy
* Strategy & Business Value
  guiding_principles:
* Everything Is Traceable
* Knowledge Compounds
  last_updated: 2026-06-26

---

# DMAF Framework Core

## 1. Purpose

This folder contains the modular framework components of the Databricks Modernization Advisory Framework, referred to as DMAF.

The Framework Core translates the approved DMAF Foundation Architecture into focused reference files that can be used by practice leaders, engagement teams, architects, delivery leads, and future Workbench capabilities.

The Foundation Architecture remains the constitutional source of truth. The files in this folder provide more accessible, maintainable, and reusable views of the framework.

---

# 2. Source of Truth

The primary source of truth for DMAF Release 1.0 is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

All files in `01-Framework/` should align with the baselined Foundation Architecture unless a governed change is approved.

---

# 3. Framework Core Contents

The Framework Core is organized into the following areas:

| Folder                        | Purpose                                                                                                 |
| ----------------------------- | ------------------------------------------------------------------------------------------------------- |
| `Practice-Domains/`           | Defines the nine DMAF practice domains and how they organize modernization capability                   |
| `Lifecycle/`                  | Defines the DMAF modernization lifecycle from opportunity qualification through continuous optimization |
| `Cross-Cutting-Capabilities/` | Defines shared concerns that apply across all domains and lifecycle stages                              |
| `Meta-Model/`                 | Defines the five-layer DMAF structural model: Philosophy, Framework, Methods, Assets, Platform          |
| `Knowledge-Graph/`            | Defines how DMAF objects relate to each other for traceability and future Workbench automation          |
| `Taxonomy/`                   | Defines approved terms, naming conventions, and conceptual distinctions                                 |
| `Capability-Model/`           | Defines how practice capabilities are structured, owned, matured, measured, and governed                |

---

# 4. Framework Principles

The Framework Core should follow these rules:

1. Do not introduce conflicting terminology.
2. Do not duplicate the Foundation Architecture unnecessarily.
3. Do not create new concepts without identifying them as proposed or future-state.
4. Use the Foundation Architecture as the baseline reference.
5. Keep each file focused on one framework concept.
6. Maintain traceability to guiding principles, practice domains, lifecycle stages, and capabilities.
7. Write for both executive understanding and practitioner usability.

---

# 5. Sprint 2 Scope

Sprint 2 focuses on creating the first modular framework files.

The initial Sprint 2 target files are:

```text
01-Framework/README.md
01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
01-Framework/Practice-Domains/dmaf-practice-domain-model.md
01-Framework/Lifecycle/dmaf-lifecycle-model.md
01-Framework/Cross-Cutting-Capabilities/dmaf-cross-cutting-capabilities.md
01-Framework/Meta-Model/dmaf-meta-model.md
01-Framework/Knowledge-Graph/dmaf-knowledge-graph.md
```

The detailed capability catalogue is expected to be expanded in a later sprint.

---

# 6. Relationship to Other Repository Areas

The Framework Core connects to the rest of the DMAF repository as follows:

| Repository Area               | Relationship to Framework Core                                               |
| ----------------------------- | ---------------------------------------------------------------------------- |
| `00-Governance/`              | Provides approval, release, roadmap, and baseline control                    |
| `02-Playbook/`                | Applies the framework in practitioner guidance                               |
| `03-Assets/`                  | Stores reusable templates, workbooks, diagrams, and accelerators             |
| `04-Reference-Architectures/` | Applies the framework to Databricks-centered architecture patterns           |
| `05-Workbench/`               | Operationalizes framework concepts through software and AI-assisted services |
| `06-Research/`                | Provides market, platform, industry, and technology intelligence             |
| `07-Releases/`                | Stores release packages and snapshots                                        |

---

# 7. Governance

Framework Core files should use standard DMAF metadata.

Major changes to framework concepts should be handled through governance review and reflected in:

```text
00-Governance/Baseline-Register/
00-Governance/Release-Notes/
00-Governance/Roadmap/
```

---

# 8. Status

This Framework Core index is currently in **Draft v0.1.0** status.

It is the first artifact of Sprint 2.
