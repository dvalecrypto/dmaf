---

asset_id: DMAF-FWK-009
title: DMAF Practice Capability Catalogue
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.5

practice_domain:
- Strategy & Business Value
- Discovery & Assessment
- Modernization Architecture
- Migration Factory
- Coexistence & Validation
- AI & Automation
- Executive Advisory
- Platform Operations, Adoption & Value Realization
- Modernization Intelligence Workbench

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- FinOps & Cost Optimization
- AI Enablement
- Automation
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Strategy & Business Value
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Reference Implementation / Pilot
- Migration Factory Execution
- Coexistence & Validation
- Production Cutover
- Platform Operations, Adoption & Value Realization
- Continuous Optimization & Modernization Intelligence

guiding_principles:
- Business Value Before Technology
- Modernization Is an Operating Model
- Industrialize Delivery
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Capability-Model/dmaf-capability-model.md

last_updated: 2026-06-26

---

# DMAF Practice Capability Catalogue

## 1. Purpose

The purpose of this document is to define the initial Practice Capability Catalogue for the Databricks Modernization Advisory Framework, referred to as DMAF.

The catalogue identifies the reusable practice capabilities required to plan, govern, deliver, validate, operate, and improve Databricks-led modernization engagements.

This document moves DMAF from framework architecture into practice architecture.

The Practice Capability Catalogue supports:

* capability ownership;
* method development;
* reusable asset planning;
* maturity assessment;
* KPI definition;
* Workbench automation planning;
* practice onboarding;
* roadmap prioritization.

---

## 2. Source of Truth

The source of truth for this catalogue is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This catalogue is also governed by:

```text
01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
01-Framework/Practice-Domains/dmaf-practice-domain-model.md
01-Framework/Capability-Model/dmaf-capability-model.md
```

This document should not redefine the DMAF framework.

It should use the approved framework to define the capabilities required by the practice.

---

## 3. Capability Definition

A capability is a reusable practice competency.

It defines what DMAF must be able to do within a practice domain.

A capability is more specific than a practice domain and more stable than an individual template, deck, workbook, script, or deliverable.

Each capability should eventually connect to:

* business objective;
* practice domain;
* lifecycle stages;
* inputs;
* outputs;
* methods;
* assets;
* owner;
* KPIs;
* maturity level;
* dependencies;
* Workbench automation potential.

---

## 4. Capability Definition Template

Each capability should use the following structure.

| Field                          | Description                                                         |
| ------------------------------ | ------------------------------------------------------------------- |
| Capability ID                  | Unique identifier for the capability                                |
| Capability Name                | Name of the reusable practice capability                            |
| Practice Domain                | Primary domain where the capability belongs                         |
| Business Objective             | Why the capability matters                                          |
| Lifecycle Stages               | Where the capability is used                                        |
| Inputs                         | Information or artifacts required                                   |
| Outputs                        | Work products produced                                              |
| Methods                        | Repeatable approaches used                                          |
| Assets                         | Templates, workbooks, diagrams, playbooks, scripts, or accelerators |
| Owner                          | Role accountable for capability quality                             |
| KPIs                           | Measures used to assess effectiveness                               |
| Maturity Target                | Intended maturity level                                             |
| Dependencies                   | Related capabilities, methods, assets, or decisions                 |
| Workbench Automation Potential | Future software or AI-assisted support                              |

---

## 5. Capability ID Convention

Capability IDs should use the following convention:

```text
DMAF-CAP-[DOMAIN]-[NUMBER]
```

Recommended domain abbreviations:

| Domain                                            | Abbreviation |
| ------------------------------------------------- | ------------ |
| Strategy & Business Value                         | SBV          |
| Discovery & Assessment                            | DAS          |
| Modernization Architecture                        | MAR          |
| Migration Factory                                 | MGF          |
| Coexistence & Validation                          | COV          |
| AI & Automation                                   | AIA          |
| Executive Advisory                                | EXA          |
| Platform Operations, Adoption & Value Realization | POV          |
| Modernization Intelligence Workbench              | MIW          |

Example:

```text
DMAF-CAP-MGF-001 = Migration Wave Planning
```

---

## 6. Capability Catalogue Structure

The catalogue is organized by the nine approved DMAF practice domains.

1. Strategy & Business Value
2. Discovery & Assessment
3. Modernization Architecture
4. Migration Factory
5. Coexistence & Validation
6. AI & Automation
7. Executive Advisory
8. Platform Operations, Adoption & Value Realization
9. Modernization Intelligence Workbench

Each domain section will define an initial set of capabilities.

---

## 7. Initial Capability Catalogue Summary

| Practice Domain                                   | Initial Capability Count | Status      |
| ------------------------------------------------- | -----------------------: | ----------- |
| Strategy & Business Value                         |                  Pending | Not Started |
| Discovery & Assessment                            |                  Pending | Not Started |
| Modernization Architecture                        |                  Pending | Not Started |
| Migration Factory                                 |                  Pending | Not Started |
| Coexistence & Validation                          |                  Pending | Not Started |
| AI & Automation                                   |                  Pending | Not Started |
| Executive Advisory                                |                  Pending | Not Started |
| Platform Operations, Adoption & Value Realization |                  Pending | Not Started |
| Modernization Intelligence Workbench              |                  Pending | Not Started |

---

## 8. Development Approach

The capability catalogue will be developed domain by domain.

Recommended sequence:

1. Strategy & Business Value
2. Discovery & Assessment
3. Modernization Architecture
4. Migration Factory
5. Coexistence & Validation
6. Executive Advisory
7. Platform Operations, Adoption & Value Realization
8. AI & Automation
9. Modernization Intelligence Workbench

This sequence starts with advisory and discovery capabilities before moving into execution, operations, automation, and platform intelligence.

---

## 9. Review Criteria

Before approving a capability, reviewers should ask:

1. Is the capability clearly named?
2. Does it belong to an approved practice domain?
3. Does it have a clear business objective?
4. Is it reusable across engagements?
5. Is it distinct from a method, asset, deliverable, or lifecycle stage?
6. Does it support one or more lifecycle stages?
7. Does it have an accountable owner?
8. Can methods and assets be derived from it?
9. Can it be measured?
10. Could it eventually be supported by the Workbench?

---

## 10. Status

This Practice Capability Catalogue is currently in **Draft v0.1.0** status.

The catalogue shell has been created. Capability definitions will be added in controlled domain increments during Sprint 3.
