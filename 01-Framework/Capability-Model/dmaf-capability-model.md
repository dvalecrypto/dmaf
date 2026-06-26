---

asset_id: DMAF-FWK-008
title: DMAF Capability Model
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0

practice_domain:
- Governance
- Executive Advisory
- Modernization Architecture
- Migration Factory
- Coexistence & Validation
- AI & Automation
- Platform Operations, Adoption & Value Realization
- Modernization Intelligence Workbench

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
- AI Accelerates, People Govern
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Knowledge-Graph/dmaf-knowledge-graph.md

last_updated: 2026-06-26

---

# DMAF Capability Model

## 1. Purpose

The purpose of this document is to define the capability model for the Databricks Modernization Advisory Framework, referred to as DMAF.

The DMAF Capability Model defines what the practice must be able to do in order to deliver Databricks-led modernization consistently.

It provides the structure for organizing:

* reusable practice capabilities;
* methods;
* assets;
* maturity levels;
* ownership;
* KPIs;
* dependencies;
* future Workbench automation potential.

The capability model helps DMAF move from a framework into an operational practice architecture.

---

## 2. Source of Truth

The source of truth for this model is:

```text id="d15w20"
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This document does not replace the Foundation Architecture.

It extracts and organizes the approved DMAF Capability Model so it can be used more easily by practice leaders, capability owners, engagement teams, architects, delivery leads, asset owners, and future Workbench capabilities.

---

## 3. Capability Definition

A **capability** is a reusable practice competency.

It defines what DMAF must be able to do within a practice domain.

A capability is:

* more specific than a practice domain;
* more stable than an individual asset;
* reusable across engagements;
* governable;
* measurable;
* improvable over time;
* potentially automatable through the Workbench.

A capability should not be confused with a method, asset, deliverable, or lifecycle stage.

---

## 4. Capability Hierarchy

The approved DMAF capability hierarchy is:

```text id="oy2w1t"
DMAF
├── Guiding Principles
├── Practice Domains
│   ├── Capabilities
│   │   ├── Methods
│   │   ├── Assets
│   │   ├── Platform Services
│   │   └── KPIs
│   └── Maturity Model
└── Governance
```

This hierarchy ensures that capabilities are not created in isolation.

Each capability should connect to:

* one or more guiding principles;
* one practice domain;
* one or more lifecycle stages;
* one or more methods;
* one or more reusable assets;
* one or more measurable outcomes;
* future Platform Services where applicable.

---

## 5. Capability vs. Related Concepts

| Concept          | Meaning                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------- |
| Practice Domain  | A major area of practice capability, such as Migration Factory or Coexistence & Validation. |
| Capability       | A specific reusable competency within a practice domain.                                    |
| Method           | How a capability is performed.                                                              |
| Asset            | A reusable work product that supports a method or capability.                               |
| Deliverable      | A client-specific output produced for a specific engagement.                                |
| Lifecycle Stage  | When work occurs in the modernization journey.                                              |
| Platform Service | A software-enabled or AI-assisted capability that operationalizes DMAF.                     |
| KPI              | A measure used to assess capability effectiveness or maturity.                              |

Example:

```text id="ijmsvp"
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

KPI:
Wave predictability
```

---

## 6. Capability Definition Standard

Each DMAF capability should be defined using a common structure.

| Field              | Description                                                |
| ------------------ | ---------------------------------------------------------- |
| Capability Name    | Name of the reusable practice capability                   |
| Practice Domain    | Domain where the capability primarily belongs              |
| Business Objective | Why the capability matters                                 |
| Inputs             | Information or artifacts required                          |
| Outputs            | Work products produced                                     |
| Methods            | Repeatable approaches used                                 |
| Assets             | Templates, diagrams, workbooks, playbooks, or accelerators |
| Platform Services  | Future software or AI-assisted support                     |
| Owner              | Role accountable for capability quality                    |
| KPIs               | Measures used to assess effectiveness                      |
| Maturity           | Current maturity level                                     |
| Dependencies       | Related capabilities, assets, methods, or decisions        |

This standard ensures that DMAF capabilities are defined consistently and can be governed as reusable practice assets.

---

## 7. Example Capability — Migration Wave Planning

| Field              | Description                                                                                                                                          |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability Name    | Migration Wave Planning                                                                                                                              |
| Practice Domain    | Migration Factory                                                                                                                                    |
| Business Objective | Create a repeatable, risk-based migration sequence that balances business value, technical complexity, dependency constraints, and delivery capacity |
| Inputs             | Application inventory, dependency map, complexity assessment, business priorities, resource availability                                             |
| Outputs            | Migration waves, factory backlog, migration roadmap, executive roadmap view                                                                          |
| Methods            | Complexity scoring, dependency analysis, risk assessment, wave sequencing workshop                                                                   |
| Assets             | Migration Planning Workbook, Timeline Simulator, Wave Planning Template, Executive Roadmap                                                           |
| Platform Services  | AI-assisted wave optimizer, dependency visualizer, scenario simulator                                                                                |
| Owner              | Migration Lead / Delivery Manager                                                                                                                    |
| KPIs               | Wave predictability, schedule adherence, migration velocity, risk reduction                                                                          |
| Maturity           | Level 3 — Managed                                                                                                                                    |
| Dependencies       | Discovery & Assessment, Modernization Architecture, Coexistence & Validation                                                                         |

This example demonstrates how a capability connects practice intent, methods, assets, ownership, metrics, and automation potential.

---

## 8. Capability Maturity Model

DMAF uses a five-level capability maturity model.

| Level   | Name        | Description                                                                              |
| ------- | ----------- | ---------------------------------------------------------------------------------------- |
| Level 1 | Initial     | Capability is ad hoc, inconsistent, and dependent on individual practitioners            |
| Level 2 | Repeatable  | Basic templates or repeatable activities exist, but governance and metrics are limited   |
| Level 3 | Managed     | Capability is standardized, documented, governed, and measured                           |
| Level 4 | Optimized   | Capability uses reusable assets, automation, feedback loops, and continuous improvement  |
| Level 5 | Intelligent | Capability is AI-assisted, knowledge-driven, continuously learning, and highly automated |

The maturity model helps DMAF assess both internal practice readiness and client modernization maturity.

A capability does not need to begin at Level 5. The goal is to make capability maturity visible, intentional, and improvable.

---

## 9. Capability Ownership Model

Each DMAF practice domain should have an accountable owner or role.

The initial ownership model is:

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

Ownership does not mean one role performs all work in the domain.

It means that role is accountable for the quality, consistency, maturity, and evolution of the capability area.

---

## 10. Capability Lifecycle

DMAF capabilities should evolve through a governed lifecycle:

```text id="xnmc5s"
Defined
   ↓
Implemented
   ↓
Measured
   ↓
Improved
   ↓
Automated
```

---

### 10.1 Defined

The capability is named, described, mapped to a practice domain, and connected to business value.

A defined capability should have:

* a clear name;
* a practice domain;
* a business objective;
* initial inputs and outputs;
* initial ownership;
* known dependencies.

---

### 10.2 Implemented

The capability is supported by methods, templates, and reusable assets.

An implemented capability should have:

* one or more methods;
* one or more reusable assets;
* practitioner guidance;
* examples;
* review expectations.

---

### 10.3 Measured

The capability has KPIs, usage evidence, quality feedback, and delivery outcomes.

A measured capability should have:

* KPIs;
* usage tracking;
* quality review;
* delivery feedback;
* improvement backlog.

---

### 10.4 Improved

The capability is refined based on engagement learning, delivery results, stakeholder feedback, platform changes, and research.

An improved capability should show evidence of:

* asset refinement;
* lessons learned;
* updated methods;
* improved guidance;
* stronger quality controls.

---

### 10.5 Automated

The capability is partially or fully supported by scripts, templates, prompts, agents, dashboards, or Workbench services.

An automated capability may include:

* reusable scripts;
* AI-assisted workflows;
* automated analysis;
* dashboarding;
* Workbench services;
* knowledge graph integration.

Automation should not bypass governance or human review.

---

## 11. Initial Capability Catalogue Structure

The detailed capability catalogue will be expanded in a future sprint.

For Sprint 2, DMAF defines the initial structure for capability development by practice domain.

---

### 11.1 Strategy & Business Value Capabilities

Potential capabilities include:

* modernization opportunity qualification;
* business value framing;
* executive sponsor alignment;
* modernization value mapping;
* strategic roadmap framing;
* investment case development;
* success metric definition.

---

### 11.2 Discovery & Assessment Capabilities

Potential capabilities include:

* application inventory analysis;
* workflow inventory analysis;
* dependency mapping;
* current-state architecture assessment;
* migration complexity scoring;
* modernization readiness assessment;
* discovery evidence management;
* risk and constraint identification.

---

### 11.3 Modernization Architecture Capabilities

Potential capabilities include:

* target-state architecture design;
* transitional architecture design;
* Databricks capability mapping;
* lakehouse pattern selection;
* governance architecture design;
* integration architecture design;
* architecture decision management;
* reference architecture selection.

---

### 11.4 Migration Factory Capabilities

Potential capabilities include:

* migration wave planning;
* factory backlog management;
* migration complexity scoring;
* migration pattern management;
* dependency sequencing;
* delivery capacity planning;
* factory KPI tracking;
* migration throughput planning.

---

### 11.5 Coexistence & Validation Capabilities

Potential capabilities include:

* coexistence strategy design;
* parallel run planning;
* reconciliation design;
* validation strategy design;
* cutover readiness assessment;
* validation evidence management;
* exception handling model;
* production readiness assessment.

---

### 11.6 AI & Automation Capabilities

Potential capabilities include:

* AI-assisted discovery interpretation;
* metadata extraction automation;
* code interpretation support;
* recommendation drafting;
* test case generation support;
* automation pattern management;
* AI governance review.

---

### 11.7 Executive Advisory Capabilities

Potential capabilities include:

* executive narrative development;
* advisory workshop facilitation;
* decision framing;
* modernization roadmap storytelling;
* proposal positioning;
* executive visual design;
* transformation value communication.

---

### 11.8 Platform Operations, Adoption & Value Realization Capabilities

Potential capabilities include:

* platform operating model design;
* adoption planning;
* support model transition;
* runbook development;
* value realization tracking;
* FinOps model design;
* governance maturity improvement;
* platform KPI management;
* continuous optimization planning.

---

### 11.9 Modernization Intelligence Workbench Capabilities

Potential capabilities include:

* engagement workspace management;
* input ingestion and normalization;
* modernization context interpretation;
* asset retrieval;
* recommendation generation;
* knowledge graph indexing;
* AI agent orchestration;
* advisory output generation;
* practice intelligence dashboarding.

---

## 12. Capability-to-Knowledge Graph Relationship

Capabilities are central nodes in the DMAF Knowledge Graph.

The approved relationship chain is:

```text id="sg52t3"
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

A capability should connect:

* upward to a practice domain;
* backward to guiding principles;
* sideways to lifecycle stages and dependencies;
* downward to methods, assets, KPIs, and platform services.

This relationship ensures that DMAF can trace practical assets back to framework intent.

---

## 13. Capability Governance Rules

DMAF capabilities should be governed according to the following rules:

1. Do not create a capability without assigning it to a practice domain.
2. Do not create a capability without a clear business objective.
3. Do not confuse capabilities with methods, assets, or deliverables.
4. Do not create assets that do not improve at least one capability.
5. Do not create Platform Services that cannot be traced to a capability, method, or asset.
6. Do not mark a capability as mature without evidence.
7. Do not automate a capability before the underlying method and asset model are sufficiently understood.
8. Do not add duplicate capabilities when an existing capability can be refined.
9. Do not change capability ownership without governance review.
10. Do not expand the capability catalogue without updating related taxonomy and Knowledge Graph references.

---

## 14. Capability Review Criteria

Before approving a new or updated DMAF capability, reviewers should ask:

1. What practice domain owns this capability?
2. What business objective does it support?
3. What lifecycle stages use it?
4. What inputs does it require?
5. What outputs does it produce?
6. What methods execute it?
7. What assets support it?
8. What KPIs measure it?
9. What maturity level is realistic?
10. What future Platform Services could support it?
11. What dependencies does it have?
12. Does it align with DMAF guiding principles?
13. Does it avoid duplicating another capability?

---

## 15. Capability Maturity Assessment Questions

Capability maturity may be assessed using questions such as:

| Maturity Area | Assessment Question                                                                                       |
| ------------- | --------------------------------------------------------------------------------------------------------- |
| Definition    | Is the capability clearly named and described?                                                            |
| Ownership     | Is there an accountable owner?                                                                            |
| Method        | Is there a repeatable method?                                                                             |
| Assets        | Are reusable assets available?                                                                            |
| Measurement   | Are KPIs defined?                                                                                         |
| Governance    | Is the capability reviewed and governed?                                                                  |
| Reuse         | Is the capability reused across engagements?                                                              |
| Automation    | Is any part of the capability automated or AI-assisted?                                                   |
| Improvement   | Is feedback used to improve the capability?                                                               |
| Traceability  | Is the capability mapped to principles, domains, lifecycle stages, methods, assets, and release versions? |

---

## 16. Relationship to Future Sprint 3

Sprint 2 defines the capability model.

Sprint 3 should expand this into a detailed **Practice Capability Catalogue**.

The Practice Capability Catalogue should include:

* full list of capabilities by practice domain;
* capability definitions;
* owners;
* inputs;
* outputs;
* methods;
* assets;
* KPIs;
* maturity targets;
* dependencies;
* Workbench automation potential.

Sprint 3 should not redefine the capability model unless a governed change is approved.

It should use this document as the structure for detailed capability development.

---

## 17. Future Enhancements

Future versions of this document may include:

* full capability catalogue;
* capability heatmap;
* capability maturity assessment workbook;
* capability-to-asset matrix;
* capability-to-lifecycle matrix;
* capability RACI model;
* capability KPI library;
* Workbench automation mapping;
* capability dependency map;
* capability health dashboard.

These enhancements are expected to be developed in later sprints and releases.

---

## 18. Review Checklist

Before approving changes to this document, reviewers should ask:

1. Is the capability definition clear?
2. Is the capability hierarchy consistent with the Knowledge Graph?
3. Are Platform Services used consistently instead of Workbench Services?
4. Is the capability definition standard complete?
5. Is the maturity model practical?
6. Is the ownership model aligned with the Practice Domain Model?
7. Are capabilities distinguished from methods, assets, deliverables, and lifecycle stages?
8. Does the document support Sprint 3 capability catalogue development?
9. Does the document avoid over-defining the full capability catalogue prematurely?
10. Is terminology consistent with the DMAF Taxonomy and Glossary?

---

## 19. Status

This Capability Model document is currently in **Draft v0.1.0** status.

It is the seventh substantive framework artifact created in Sprint 2.
