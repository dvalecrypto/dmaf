---

asset_id: DMAF-GOV-TRACE-001
title: DMAF Traceability and Integration Review
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.5

practice_domain:
- Executive Advisory
- Modernization Intelligence Workbench

cross_cutting_capabilities:
- Governance & Security
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Continuous Optimization & Modernization Intelligence

guiding_principles:
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/README.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Cross-Cutting-Capabilities/dmaf-cross-cutting-capabilities.md
- 01-Framework/Meta-Model/dmaf-meta-model.md
- 01-Framework/Knowledge-Graph/dmaf-knowledge-graph.md
- 01-Framework/Capability-Model/dmaf-capability-model.md
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md

last_updated: 2026-06-26

---

# DMAF Traceability and Integration Review

## 1. Purpose

The purpose of this document is to define a formal traceability and integration checkpoint for the Databricks Modernization Advisory Framework, referred to as DMAF.

This review confirms that the Foundation Architecture, Framework Core, and Practice Capability Catalogue connect to each other before DMAF moves into methods, assets, templates, workbooks, diagrams, playbooks, and Workbench specifications.

This checkpoint exists to prevent DMAF from becoming a large collection of disconnected content.

---

## 2. Why This Review Happens Now

This review occurs after:

* Sprint 1 — Foundation Architecture
* Sprint 2 — Framework Core
* Sprint 3 — Practice Capability Catalogue

This is the right point to validate integration because DMAF now has:

* approved guiding principles;
* approved practice domains;
* approved lifecycle stages;
* approved cross-cutting capabilities;
* approved meta model;
* approved knowledge graph model;
* approved capability model;
* initial capability catalogue across all nine practice domains.

Before Sprint 4 begins, DMAF needs to confirm that the next layer of work can be traced back to the framework.

---

## 3. Integration Principle

DMAF should follow this integration chain:

```text
Foundation Architecture
        ↓
Framework Core
        ↓
Practice Capability Catalogue
        ↓
Methods
        ↓
Assets
        ↓
Workbench Services
```

Every future method, asset, template, workbook, diagram, prompt, or Workbench service should be traceable to this chain.

---

## 4. Review Scope

This review covers the following areas:

| Area                               | Review Question                                                                   |
| ---------------------------------- | --------------------------------------------------------------------------------- |
| Foundation Alignment               | Do Sprint 2 and Sprint 3 artifacts align to the Foundation Architecture?          |
| Taxonomy Consistency               | Are approved terms used consistently?                                             |
| Practice Domain Coverage           | Are all nine approved practice domains represented?                               |
| Lifecycle Coverage                 | Are all lifecycle stages supported by capabilities?                               |
| Capability Structure               | Are capabilities consistently defined?                                            |
| Cross-Cutting Capability Treatment | Are cross-cutting concerns separated from practice domains?                       |
| Knowledge Graph Alignment          | Do capabilities support future mapping to methods, assets, and platform services? |
| Metadata Quality                   | Do artifacts use consistent front matter and approved taxonomy values?            |
| Repository Fit                     | Are files stored in the correct repository locations?                             |
| Sprint 4 Readiness                 | Can methods and assets now be mapped from capabilities?                           |

---

## 5. Traceability Review Results

| Review Area                         | Result               | Notes                                                                                                                                                                   |
| ----------------------------------- | -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Foundation Architecture alignment   | Pass                 | Sprint 2 and Sprint 3 were derived from the Foundation Architecture.                                                                                                    |
| Framework Core completeness         | Pass                 | Sprint 2 created modular framework files for taxonomy, domains, lifecycle, cross-cutting capabilities, meta model, knowledge graph, and capability model.               |
| Capability Catalogue completeness   | Pass                 | Sprint 3 drafted capabilities across all nine approved practice domains.                                                                                                |
| Practice domain count               | Pass                 | Nine approved practice domains are represented.                                                                                                                         |
| Capability count                    | Pass                 | Initial catalogue contains 71 capabilities.                                                                                                                             |
| Taxonomy consistency                | Pass with monitoring | Governance was corrected so it is not treated as a practice domain.                                                                                                     |
| Cross-cutting capability separation | Pass                 | Governance & Security, Risk & Compliance, FinOps, AI Enablement, Automation, Knowledge Management, and Reusable Accelerators are treated as cross-cutting capabilities. |
| Knowledge Graph readiness           | Pass                 | Capabilities are ready to be mapped to methods, assets, KPIs, and future Platform Services.                                                                             |
| Metadata quality                    | Pass with monitoring | YAML front matter should continue to be validated before new artifact content is released.                                                                              |
| Sprint 4 readiness                  | Pass                 | DMAF is ready to move into Methods and Asset Mapping.                                                                                                                   |

---

## 6. Capability Coverage Summary

| Practice Domain                                   | Capability Count | Status      |
| ------------------------------------------------- | ---------------: | ----------- |
| Strategy & Business Value                         |                7 | Drafted     |
| Discovery & Assessment                            |                8 | Drafted     |
| Modernization Architecture                        |                8 | Drafted     |
| Migration Factory                                 |                8 | Drafted     |
| Coexistence & Validation                          |                8 | Drafted     |
| AI & Automation                                   |                8 | Drafted     |
| Executive Advisory                                |                8 | Drafted     |
| Platform Operations, Adoption & Value Realization |                8 | Drafted     |
| Modernization Intelligence Workbench              |                8 | Drafted     |
| **Total**                                         |           **71** | **Drafted** |

---

## 7. Key Integration Observations

DMAF now has a coherent framework structure.

The strongest integration points are:

1. The Foundation Architecture defines the constitutional model.
2. The Framework Core modularizes the model into reusable reference files.
3. The Capability Catalogue turns the framework into a practice architecture.
4. The Knowledge Graph provides the traceability model for future assets.
5. The Workbench domain provides the future software-enabled operating layer.

The main risk going forward is not missing content.

The main risk is uncontrolled expansion.

Sprint 4 should therefore avoid creating random templates. It should map methods and assets directly to approved capabilities.

---

## 8. Sprint 4 Entry Criteria

Sprint 4 may begin when the following conditions are true:

| Entry Criterion                            | Status   |
| ------------------------------------------ | -------- |
| Sprint 3 capability catalogue drafted      | Complete |
| All nine practice domains represented      | Complete |
| Capability ID convention established       | Complete |
| Capability-to-domain mapping established   | Complete |
| Lifecycle mapping included in capabilities | Complete |
| Workbench automation potential included    | Complete |
| Taxonomy cleanup completed                 | Complete |
| Traceability review created                | Complete |

Sprint 4 is approved to begin after this review is committed.

---

## 9. Sprint 4 Control Rule

Sprint 4 should follow this rule:

```text
No method or asset should be created unless it maps to an approved capability.
```

Each future method or asset should identify:

* related practice domain;
* related capability;
* related lifecycle stage;
* related guiding principle;
* related cross-cutting capability where applicable;
* intended audience;
* reusable asset type;
* owner;
* status;
* version.

---

## 10. Recommended Sprint 4 Focus

The recommended next sprint is:

```text
Sprint 4 — Methods and Asset Mapping
```

Recommended Sprint 4 outputs:

* capability-to-method matrix;
* capability-to-asset matrix;
* priority asset backlog;
* method definition standard;
* asset metadata standard;
* first reusable method definitions;
* first reusable asset build list.

Sprint 4 should not attempt to fully build every method or asset.

Its purpose should be to create the map that tells DMAF which methods and assets matter first.

---

## 11. Future Integration Gates

DMAF should use integration gates at the following points:

| Gate                                 | Timing                     | Purpose                                                                      |
| ------------------------------------ | -------------------------- | ---------------------------------------------------------------------------- |
| Gate 1 — Framework Traceability      | After Sprint 3             | Confirm Foundation, Framework Core, and Capability Catalogue align.          |
| Gate 2 — Method and Asset Coverage   | After Sprint 4             | Confirm methods and assets map to approved capabilities.                     |
| Gate 3 — Release 1.5 Baseline Review | Before Release 1.5 closure | Confirm Practice Architecture is ready to baseline.                          |
| Gate 4 — Consulting Asset Readiness  | Before Release 2.0         | Confirm client-facing assets are reusable, governed, and traceable.          |
| Gate 5 — Workbench Readiness         | Before Workbench build     | Confirm software services map to approved capabilities, methods, and assets. |

---

## 12. Status

This Traceability and Integration Review is currently in **Draft v0.1.0** status.

It confirms that DMAF is ready to proceed from capability architecture into Sprint 4 Methods and Asset Mapping.
