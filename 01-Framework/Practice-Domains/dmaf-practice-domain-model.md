---

asset_id: DMAF-FWK-003
title: DMAF Practice Domain Model
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0

practice_domain:
- Executive Advisory
- Modernization Architecture

cross_cutting_capabilities:
  - Governance & Security
  - Knowledge Management
  - Reusable Accelerators
    
lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Strategy & Business Value
- Discovery & Assessment
- Modernization Architecture

guiding_principles:
- Business Value Before Technology
- Databricks by Design
- Modernization Is an Operating Model
- Industrialize Delivery
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

last_updated: 2026-06-26

---

# DMAF Practice Domain Model

## 1. Purpose

The purpose of this document is to define the approved practice domain model for the Databricks Modernization Advisory Framework, referred to as DMAF.

Practice domains organize the major areas of advisory, architecture, delivery, governance, and enablement capability required to plan and execute Databricks-led modernization.

This document provides a standalone reference for the nine approved DMAF practice domains and explains how they relate to capabilities, lifecycle stages, cross-cutting capabilities, methods, assets, and future Workbench services.

---

## 2. Source of Truth

The source of truth for this model is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This document does not replace the Foundation Architecture.

It extracts and organizes the approved practice domain model so it can be used more easily by practice leaders, engagement teams, architects, delivery leads, asset owners, and future Workbench capabilities.

---

## 3. Practice Domain Definition

A **practice domain** is a major area of advisory, architecture, delivery, or enablement capability required to plan and execute Databricks-led modernization.

A practice domain describes **what kind of capability** DMAF applies.

A lifecycle stage describes **when work occurs**.

A capability describes **what the practice must be able to do** inside a domain.

A method describes **how a capability is performed**.

An asset describes **what reusable material supports the method**.

---

## 4. Approved Practice Domains

DMAF contains nine approved practice domains:

1. Strategy & Business Value
2. Discovery & Assessment
3. Modernization Architecture
4. Migration Factory
5. Coexistence & Validation
6. AI & Automation
7. Executive Advisory
8. Platform Operations, Adoption & Value Realization
9. Modernization Intelligence Workbench

These domains form the primary organizing model for DMAF practice capability.

---

# 5. Domain 1 — Strategy & Business Value

## 5.1 Domain Definition

The Strategy & Business Value domain defines the business rationale for modernization.

It ensures that modernization is connected to executive priorities, measurable outcomes, funding logic, risk reduction, and long-term platform value.

## 5.2 Primary Objective

Establish a clear business reason for modernization before technology decisions are made.

## 5.3 Typical Concerns

* modernization drivers;
* business case development;
* executive alignment;
* value hypotheses;
* investment rationale;
* strategic sequencing;
* opportunity qualification;
* target outcomes;
* sponsorship model.

## 5.4 Typical Outputs

* modernization strategy brief;
* value driver map;
* business case framing;
* opportunity qualification summary;
* executive alignment narrative;
* modernization hypothesis;
* success metric model.

## 5.5 Common Capabilities

* modernization opportunity qualification;
* business value framing;
* executive sponsor alignment;
* modernization value mapping;
* strategic roadmap framing;
* investment case development.

## 5.6 Primary Lifecycle Alignment

* Stage 0 — Opportunity Qualification & Modernization Strategy
* Stage 1 — Strategy & Business Value
* Stage 10 — Continuous Optimization & Modernization Intelligence

---

# 6. Domain 2 — Discovery & Assessment

## 6.1 Domain Definition

The Discovery & Assessment domain defines how DMAF gathers, normalizes, interprets, and scores the current-state environment.

It creates the evidence base for modernization decisions.

## 6.2 Primary Objective

Understand the current-state environment well enough to make defensible modernization recommendations.

## 6.3 Typical Concerns

* application inventory;
* workflow inventory;
* data source inventory;
* dependency mapping;
* business process context;
* complexity scoring;
* migration readiness;
* technical debt analysis;
* stakeholder interviews;
* discovery evidence management.

## 6.4 Typical Outputs

* discovery findings;
* application inventory;
* complexity assessment;
* dependency map;
* current-state architecture summary;
* risk register;
* modernization readiness assessment;
* candidate migration segments.

## 6.5 Common Capabilities

* application inventory analysis;
* workflow inventory analysis;
* dependency mapping;
* complexity scoring;
* current-state assessment;
* modernization readiness assessment;
* discovery evidence management.

## 6.6 Primary Lifecycle Alignment

* Stage 1 — Strategy & Business Value
* Stage 2 — Discovery & Assessment
* Stage 3 — Modernization Architecture
* Stage 4 — Migration Factory Planning

---

# 7. Domain 3 — Modernization Architecture

## 7.1 Domain Definition

The Modernization Architecture domain defines the target-state and transitional architecture models for Databricks-led modernization.

It connects current-state assessment to future-state platform design.

## 7.2 Primary Objective

Define a coherent Databricks-centered architecture direction and transition path.

## 7.3 Typical Concerns

* Databricks target architecture;
* lakehouse design;
* Delta Lake patterns;
* Unity Catalog governance;
* orchestration patterns;
* integration architecture;
* security architecture;
* data product design;
* reference architectures;
* transitional architecture;
* architecture decision records.

## 7.4 Typical Outputs

* target-state architecture;
* transitional architecture;
* Databricks capability map;
* governance and security model;
* integration model;
* architecture decision records;
* reference architecture alignment;
* architecture roadmap.

## 7.5 Common Capabilities

* target-state architecture design;
* transitional architecture design;
* Databricks capability mapping;
* lakehouse pattern selection;
* governance architecture design;
* architecture decision management;
* reference architecture selection.

## 7.6 Primary Lifecycle Alignment

* Stage 2 — Discovery & Assessment
* Stage 3 — Modernization Architecture
* Stage 4 — Migration Factory Planning
* Stage 5 — Reference Implementation / Pilot

---

# 8. Domain 4 — Migration Factory

## 8.1 Domain Definition

The Migration Factory domain defines how modernization is planned, sequenced, industrialized, executed, and measured at scale.

It is the delivery centerpiece of DMAF.

## 8.2 Primary Objective

Turn modernization strategy and architecture into repeatable, scalable, measurable migration execution.

## 8.3 Typical Concerns

* migration wave planning;
* complexity-based sequencing;
* factory backlog management;
* migration patterns;
* repeatable conversion methods;
* delivery roles;
* productivity metrics;
* reusable accelerators;
* dependency management;
* throughput planning;
* delivery governance.

## 8.4 Typical Outputs

* migration factory plan;
* migration waves;
* factory backlog;
* migration roadmap;
* migration estimates;
* resource plan;
* delivery metrics;
* repeatable migration patterns.

## 8.5 Common Capabilities

* migration wave planning;
* factory backlog management;
* migration complexity scoring;
* migration pattern management;
* dependency sequencing;
* factory KPI tracking;
* migration throughput planning.

## 8.6 Primary Lifecycle Alignment

* Stage 4 — Migration Factory Planning
* Stage 5 — Reference Implementation / Pilot
* Stage 6 — Migration Factory Execution
* Stage 10 — Continuous Optimization & Modernization Intelligence

---

# 9. Domain 5 — Coexistence & Validation

## 9.1 Domain Definition

The Coexistence & Validation domain defines how legacy and modern platforms operate during transition and how modernization outcomes are proven.

It is central to client trust, risk control, and production readiness.

## 9.2 Primary Objective

Ensure that modernized workloads are accurate, reconciled, trusted, and ready for production.

## 9.3 Typical Concerns

* coexistence architecture;
* parallel run strategy;
* reconciliation design;
* validation approach;
* cutover readiness;
* downstream impact;
* control totals;
* exception handling;
* audit evidence;
* operational acceptance;
* production readiness.

## 9.4 Typical Outputs

* coexistence strategy;
* validation strategy;
* reconciliation results;
* parallel run evidence;
* exception reports;
* cutover readiness assessment;
* business acceptance evidence;
* production readiness sign-off.

## 9.5 Common Capabilities

* coexistence strategy design;
* validation planning;
* reconciliation design;
* parallel run planning;
* cutover readiness assessment;
* validation evidence management;
* exception handling model.

## 9.6 Primary Lifecycle Alignment

* Stage 3 — Modernization Architecture
* Stage 5 — Reference Implementation / Pilot
* Stage 7 — Coexistence & Validation
* Stage 8 — Production Cutover

---

# 10. Domain 6 — AI & Automation

## 10.1 Domain Definition

The AI & Automation domain defines how automation and AI-assisted techniques accelerate modernization while preserving human governance.

## 10.2 Primary Objective

Improve modernization speed, quality, consistency, and reuse through automation and AI-assisted advisory capabilities.

## 10.3 Typical Concerns

* code interpretation assistance;
* metadata extraction;
* mapping acceleration;
* documentation generation;
* test case generation;
* risk analysis;
* recommendation drafting;
* knowledge retrieval;
* Workbench agents;
* automation governance.

## 10.4 Typical Outputs

* reusable prompts;
* automation scripts;
* AI-assisted analysis outputs;
* metadata extraction tools;
* recommendation drafts;
* test case suggestions;
* Workbench agent specifications;
* automation governance guidance.

## 10.5 Common Capabilities

* AI-assisted discovery interpretation;
* metadata extraction automation;
* recommendation drafting;
* code interpretation support;
* document generation support;
* AI governance review;
* automation pattern management.

## 10.6 Primary Lifecycle Alignment

* Stage 2 — Discovery & Assessment
* Stage 4 — Migration Factory Planning
* Stage 6 — Migration Factory Execution
* Stage 10 — Continuous Optimization & Modernization Intelligence

---

# 11. Domain 7 — Executive Advisory

## 11.1 Domain Definition

The Executive Advisory domain defines how modernization is communicated, positioned, and governed with senior stakeholders.

## 11.2 Primary Objective

Make modernization understandable, fundable, governable, and actionable for executive decision-makers.

## 11.3 Typical Concerns

* executive narratives;
* board-level summaries;
* transformation roadmaps;
* investment cases;
* risk and trade-off framing;
* decision support;
* sponsor alignment;
* proposal messaging;
* advisory workshops;
* executive-ready visuals.

## 11.4 Typical Outputs

* executive briefing;
* decision support summary;
* transformation roadmap;
* advisory deck;
* proposal narrative;
* investment framing;
* risk and trade-off summary;
* executive workshop materials.

## 11.5 Common Capabilities

* executive narrative development;
* advisory workshop facilitation;
* decision framing;
* modernization roadmap storytelling;
* proposal positioning;
* executive visual design;
* transformation value communication.

## 11.6 Primary Lifecycle Alignment

* Stage 0 — Opportunity Qualification & Modernization Strategy
* Stage 1 — Strategy & Business Value
* Stage 3 — Modernization Architecture
* Stage 10 — Continuous Optimization & Modernization Intelligence

---

# 12. Domain 8 — Platform Operations, Adoption & Value Realization

## 12.1 Domain Definition

The Platform Operations, Adoption & Value Realization domain defines how the modernized Databricks platform is adopted, governed, operated, optimized, and measured after migration.

## 12.2 Primary Objective

Ensure modernization produces durable enterprise value beyond migration completion.

## 12.3 Typical Concerns

* operating model;
* platform ownership;
* support model;
* runbooks;
* adoption roadmap;
* enablement;
* FinOps;
* governance maturity;
* platform KPIs;
* value realization tracking;
* continuous optimization.

## 12.4 Typical Outputs

* platform operating model;
* support model;
* adoption roadmap;
* runbooks;
* enablement plan;
* FinOps model;
* platform KPI dashboard;
* value realization report;
* continuous improvement backlog.

## 12.5 Common Capabilities

* platform operating model design;
* adoption planning;
* value realization tracking;
* FinOps model design;
* governance maturity improvement;
* platform KPI management;
* continuous optimization planning.

## 12.6 Primary Lifecycle Alignment

* Stage 8 — Production Cutover
* Stage 9 — Platform Operations, Adoption & Value Realization
* Stage 10 — Continuous Optimization & Modernization Intelligence

---

# 13. Domain 9 — Modernization Intelligence Workbench

## 13.1 Domain Definition

The Modernization Intelligence Workbench domain defines the future software-enabled layer of DMAF.

The Workbench is intended to operationalize the framework by helping practitioners ingest messy engagement inputs, interpret modernization context, generate recommendations, manage reusable assets, and produce consulting-grade outputs.

## 13.2 Primary Objective

Scale DMAF through software-enabled advisory, knowledge management, automation, and AI-assisted modernization intelligence.

## 13.3 Typical Concerns

* engagement workspace structure;
* input normalization;
* document interpretation;
* inventory analysis;
* recommendation generation;
* artifact generation;
* knowledge graph indexing;
* asset retrieval;
* AI agents;
* modernization dashboards;
* proposal acceleration.

## 13.4 Typical Outputs

* Workbench blueprint;
* engagement workspace model;
* input interpretation model;
* knowledge graph service model;
* AI agent specifications;
* dashboard concepts;
* artifact generation workflows;
* platform service specifications.

## 13.5 Common Capabilities

* engagement workspace management;
* input ingestion and normalization;
* modernization context interpretation;
* asset retrieval;
* recommendation generation;
* knowledge graph indexing;
* AI agent orchestration;
* advisory output generation.

## 13.6 Primary Lifecycle Alignment

The Workbench supports all lifecycle stages as a horizontal platform layer.

It is especially relevant to:

* Stage 0 — Opportunity Qualification & Modernization Strategy
* Stage 2 — Discovery & Assessment
* Stage 4 — Migration Factory Planning
* Stage 10 — Continuous Optimization & Modernization Intelligence

---

# 14. Domain-to-Lifecycle Alignment

The following table summarizes the primary relationship between practice domains and lifecycle stages.

| Practice Domain                                   | Primary Lifecycle Stages            |
| ------------------------------------------------- | ----------------------------------- |
| Strategy & Business Value                         | Stage 0, Stage 1, Stage 10          |
| Discovery & Assessment                            | Stage 1, Stage 2, Stage 3, Stage 4  |
| Modernization Architecture                        | Stage 2, Stage 3, Stage 4, Stage 5  |
| Migration Factory                                 | Stage 4, Stage 5, Stage 6, Stage 10 |
| Coexistence & Validation                          | Stage 3, Stage 5, Stage 7, Stage 8  |
| AI & Automation                                   | Stage 2, Stage 4, Stage 6, Stage 10 |
| Executive Advisory                                | Stage 0, Stage 1, Stage 3, Stage 10 |
| Platform Operations, Adoption & Value Realization | Stage 8, Stage 9, Stage 10          |
| Modernization Intelligence Workbench              | All stages                          |

---

# 15. Domain Ownership Model

The initial ownership model for the practice domains is:

| Practice Domain                                   | Primary Owner                              |
| ------------------------------------------------- | ------------------------------------------ |
| Strategy & Business Value                         | Account Executive / Engagement Lead        |
| Discovery & Assessment                            | Lead Business Analyst / Solution Architect |
| Modernization Architecture                        | Enterprise Architect / Solution Architect  |
| Migration Factory                                 | Delivery Manager / Migration Lead          |
| Coexistence & Validation                          | Test Manager / Data Architect              |
| AI & Automation                                   | AI Enablement Lead                         |
| Executive Advisory                                | Engagement Lead / Practice Lead            |
| Platform Operations, Adoption & Value Realization | Platform Lead / Customer Success Lead      |
| Modernization Intelligence Workbench              | Practice Lead / Product Owner              |

Ownership means accountability for quality, consistency, maturity, and evolution of the domain.

It does not mean the owner performs all work in the domain.

---

# 16. Domain-to-Knowledge Graph Relationship

Each practice domain should be traceable through the DMAF Knowledge Graph.

The approved relationship chain is:

```text
Guiding Principles
        ↓
Practice Domains
        ↓
Capabilities
        ↓
Methods
        ↓
Assets
        ↓
Platform Services
```

Example:

```text
Guiding Principle:
Industrialize Delivery

Practice Domain:
Migration Factory

Capability:
Migration Wave Planning

Method:
Complexity-Based Wave Sequencing

Asset:
Migration Factory Planning Workbook

Platform Service:
AI-Assisted Wave Planning Scenario Simulator
```

This traceability supports quality control, reuse, governance, and future Workbench automation.

---

# 17. Domain Governance Rules

Practice domains should be governed according to the following rules:

1. Do not rename a practice domain without governance approval.
2. Do not add a new practice domain unless it represents a major new capability area.
3. Do not confuse practice domains with lifecycle stages.
4. Do not add capabilities without mapping them to a domain.
5. Do not add assets without mapping them to a domain and capability.
6. Ensure each domain has an accountable owner.
7. Ensure each domain can support methods, assets, KPIs, and maturity assessment.
8. Ensure new domain concepts align with the Foundation Architecture.

---

# 18. Future Enhancements

Future versions of the Practice Domain Model may include:

* detailed capability catalogue by domain;
* domain maturity model;
* domain KPI model;
* domain RACI model;
* domain-specific asset inventory;
* domain-specific Workbench services;
* domain-level practice health dashboard.

These enhancements are expected to be developed in future sprints and releases.

---

# 19. Review Checklist

Before approving changes to this document, reviewers should ask:

1. Are all nine approved practice domains represented?
2. Are the domain names consistent with the Foundation Architecture?
3. Are domains clearly distinguished from lifecycle stages?
4. Are domain objectives clear?
5. Are typical outputs reusable and practice-oriented?
6. Are common capabilities described without over-defining the future capability catalogue?
7. Is ownership clear?
8. Is the Workbench treated as a domain and horizontal enabler?
9. Is terminology consistent with the DMAF taxonomy?
10. Does the document support future capability catalogue development?

---

# 20. Status

This Practice Domain Model is currently in **Draft v0.1.0** status.

It is the second substantive framework artifact created in Sprint 2.
