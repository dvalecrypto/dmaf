---

asset_id: DMAF-FWK-006
title: DMAF Meta Model
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0

practice_domain:
- Executive Advisory
- Modernization Architecture
- Modernization Intelligence Workbench

cross_cutting_capabilities:
  - Governance & Security
  - Knowledge Management
  - Reusable Accelerators
    
lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Strategy & Business Value
- Discovery & Assessment
- Modernization Architecture
- Continuous Optimization & Modernization Intelligence

guiding_principles:
- Business Value Before Technology
- Databricks by Design
- Modernization Is an Operating Model
- Executive Storytelling Matters
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Cross-Cutting-Capabilities/dmaf-cross-cutting-capabilities.md

last_updated: 2026-06-26

---

# DMAF Meta Model

## 1. Purpose

The purpose of this document is to define the meta model for the Databricks Modernization Advisory Framework, referred to as DMAF.

The DMAF Meta Model explains how the major layers of the framework relate to one another.

It prevents DMAF from becoming a loose collection of documents, templates, diagrams, workbooks, prompts, and ideas by defining the structural logic that connects:

* strategy;
* methodology;
* practice domains;
* lifecycle stages;
* methods;
* reusable assets;
* governance;
* automation;
* future Workbench capabilities.

The meta model gives DMAF a stable internal architecture.

---

## 2. Source of Truth

The source of truth for this model is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This document does not replace the Foundation Architecture.

It extracts and organizes the approved DMAF Meta Model so it can be used more easily by practice leaders, engagement teams, architects, delivery leads, asset owners, and future Workbench capabilities.

---

## 3. Meta Model Definition

A **meta model** defines how the major components of a framework relate to each other.

The DMAF Meta Model is organized into five layers:

1. Philosophy
2. Framework
3. Methods
4. Assets
5. Platform

Each layer has a distinct role.

Together, these layers explain how DMAF moves from strategic belief to repeatable execution and eventually to platform-enabled modernization intelligence.

---

## 4. Five-Layer DMAF Meta Model

The approved DMAF Meta Model is:

```text
Philosophy
    ↓
Framework
    ↓
Methods
    ↓
Assets
    ↓
Platform
```

This relationship means:

* Philosophy governs the Framework.
* Framework organizes Methods.
* Methods use and produce Assets.
* Assets are operationalized by the Platform.
* Platform usage generates learning that improves Assets, Methods, Framework, and Philosophy over time.

DMAF is therefore designed as a learning system, not a static document set.

---

# 5. Layer 1 — Philosophy

## 5.1 Definition

The Philosophy layer defines why DMAF exists and what beliefs govern it.

It anchors DMAF in business value, Databricks-first modernization, operating model maturity, validation, executive clarity, traceability, and reusable knowledge.

## 5.2 Purpose

The purpose of the Philosophy layer is to ensure that DMAF does not become a purely mechanical delivery model.

It provides the decision logic behind the framework.

## 5.3 Includes

The Philosophy layer includes:

* vision;
* charter;
* core belief;
* guiding principles;
* strategic positioning;
* definition of what DMAF is and is not.

## 5.4 Example Artifacts

Examples of Philosophy-layer artifacts include:

* DMAF Foundation Architecture;
* DMAF Charter;
* DMAF Guiding Principles;
* DMAF Strategic Positioning Statement;
* DMAF Core Belief;
* Release 1.0 approval statement.

## 5.5 Key Question

The Philosophy layer answers:

> Why does DMAF exist, and what principles guide it?

## 5.6 Governance Considerations

Changes to the Philosophy layer should be tightly governed.

Examples of changes requiring governance approval include:

* renaming DMAF;
* changing the core belief;
* adding or removing guiding principles;
* changing Databricks-first positioning;
* redefining what DMAF is or is not.

---

# 6. Layer 2 — Framework

## 6.1 Definition

The Framework layer defines how DMAF is organized.

It provides the structure that allows DMAF to be applied consistently across different modernization opportunities, clients, industries, source platforms, and delivery scenarios.

## 6.2 Purpose

The purpose of the Framework layer is to turn DMAF philosophy into an organized model that can be applied, governed, reused, and extended.

## 6.3 Includes

The Framework layer includes:

* practice domains;
* lifecycle stages;
* cross-cutting capabilities;
* capability model;
* maturity model;
* governance model;
* taxonomy;
* operating views.

## 6.4 Example Artifacts

Examples of Framework-layer artifacts include:

* DMAF Taxonomy and Glossary;
* Practice Domain Model;
* DMAF Lifecycle Model;
* Cross-Cutting Capabilities Model;
* DMAF Meta Model;
* DMAF Knowledge Graph;
* Capability Model;
* Governance Model;
* Maturity Model.

## 6.5 Key Question

The Framework layer answers:

> How is DMAF organized?

## 6.6 Governance Considerations

Changes to the Framework layer should be governed when they affect the structure of DMAF.

Examples include:

* adding a practice domain;
* renaming a lifecycle stage;
* changing the knowledge graph relationship chain;
* redefining cross-cutting capabilities;
* changing capability hierarchy;
* modifying asset status definitions.

---

# 7. Layer 3 — Methods

## 7.1 Definition

The Methods layer defines how DMAF work is performed.

Methods translate framework concepts into repeatable practitioner approaches.

## 7.2 Purpose

The purpose of the Methods layer is to make DMAF actionable.

Methods allow teams to apply the framework in actual modernization engagements.

## 7.3 Includes

The Methods layer includes:

* repeatable approaches;
* practitioner processes;
* workshops;
* assessments;
* scoring models;
* decision trees;
* analysis techniques;
* planning methods;
* validation methods;
* delivery patterns.

## 7.4 Example Methods

Examples of Methods-layer content include:

* opportunity qualification method;
* discovery and assessment method;
* application complexity scoring method;
* migration wave planning method;
* reference implementation method;
* coexistence strategy method;
* validation planning method;
* executive advisory method;
* platform adoption method;
* value realization method.

## 7.5 Key Question

The Methods layer answers:

> How is DMAF work performed?

## 7.6 Governance Considerations

Methods should be governed to ensure they remain repeatable, practical, and aligned to the framework.

Method changes should be reviewed when they:

* alter how a capability is performed;
* affect client-facing recommendations;
* change assessment or scoring logic;
* change migration sequencing logic;
* affect validation evidence;
* influence delivery governance.

---

# 8. Layer 4 — Assets

## 8.1 Definition

The Assets layer contains reusable work products that support DMAF execution.

Assets may be internal, client-facing, delivery-oriented, technical, advisory, or software-supporting.

## 8.2 Purpose

The purpose of the Assets layer is to make DMAF reusable and scalable.

Assets prevent teams from recreating the same materials across engagements.

## 8.3 Includes

The Assets layer includes:

* templates;
* workbooks;
* diagrams;
* executive decks;
* checklists;
* scripts;
* prompts;
* proposal language;
* playbook chapters;
* reference architectures;
* industry packs;
* research briefs;
* workshop materials;
* Workbench design documents.

## 8.4 Example Assets

Examples of Assets-layer content include:

* discovery questionnaire;
* application inventory template;
* migration complexity scoring workbook;
* migration planning workbook;
* validation checklist;
* coexistence decision tree;
* Databricks reference architecture diagram;
* executive advisory deck;
* proposal accelerator;
* banking modernization advisory pack;
* reusable Workbench prompt library.

## 8.5 Key Question

The Assets layer answers:

> What reusable materials does DMAF use to perform and scale the work?

## 8.6 Governance Considerations

Assets should be governed through metadata, versioning, review, status, and traceability.

Every major asset should identify:

* asset ID;
* title;
* owner;
* status;
* version;
* practice domain;
* capability;
* lifecycle stage;
* guiding principles;
* dependencies;
* last updated date.

Assets should not be added simply because they exist. They should improve a defined capability.

---

# 9. Layer 5 — Platform

## 9.1 Definition

The Platform layer defines how DMAF can be operationalized through software, automation, knowledge systems, and AI-assisted advisory capabilities.

The primary future platform expression of DMAF is the Modernization Intelligence Workbench.

## 9.2 Purpose

The purpose of the Platform layer is to scale DMAF beyond manual consulting effort.

The Platform layer enables DMAF to become searchable, reusable, automated, intelligent, and measurable.

## 9.3 Includes

The Platform layer includes:

* engagement workspaces;
* input ingestion;
* document interpretation;
* inventory analysis;
* knowledge graph indexing;
* recommendation generation;
* artifact generation;
* AI advisory agents;
* asset search and retrieval;
* dashboarding;
* practice intelligence.

## 9.4 Example Platform Services

Examples of Platform-layer capabilities include:

* engagement workspace creation;
* messy input ingestion;
* modernization context interpretation;
* application inventory analysis;
* complexity scoring assistance;
* recommendation generation;
* knowledge graph search;
* asset retrieval;
* proposal drafting;
* artifact packaging;
* modernization dashboarding.

## 9.5 Key Question

The Platform layer answers:

> How does DMAF scale beyond manual consulting effort?

## 9.6 Governance Considerations

Platform services should not introduce ungoverned methodology.

They should operationalize approved DMAF concepts.

Workbench and AI capabilities should trace back to:

* guiding principles;
* practice domains;
* capabilities;
* methods;
* assets;
* lifecycle stages;
* release versions.

The Workbench is not the source of truth. It operationalizes the governed framework and asset library.

---

# 10. Meta Model Traceability

The meta model provides a simple traceability path from belief to automation.

Example:

```text
Philosophy:
Industrialize Delivery

Framework:
Migration Factory practice domain

Method:
Complexity-based wave sequencing

Asset:
Migration Factory Planning Workbook

Platform:
AI-assisted wave planning scenario simulator
```

This traceability helps DMAF maintain quality and coherence as it grows.

---

# 11. Relationship to the Knowledge Graph

The Meta Model and Knowledge Graph are related but distinct.

| Concept         | Purpose                                                                                        |
| --------------- | ---------------------------------------------------------------------------------------------- |
| Meta Model      | Defines the high-level structural layers of DMAF.                                              |
| Knowledge Graph | Defines how specific DMAF objects relate to each other for traceability and future automation. |

The Meta Model explains DMAF as an architecture.

The Knowledge Graph explains DMAF as a set of connected objects.

Together, they support governance, reuse, asset management, and Workbench automation.

---

# 12. Relationship to the Playbook

The Meta Model is not the playbook.

The Playbook belongs primarily to the Methods and Assets layers.

The playbook should explain how practitioners apply DMAF in real engagements.

For example:

* the Foundation Architecture defines that Migration Factory is a practice domain;
* the Meta Model shows where Methods and Assets fit;
* the Playbook explains how to run migration wave planning;
* the Asset Library provides the workbook, template, or checklist used during the activity.

---

# 13. Relationship to Reference Architectures

The Meta Model helps distinguish methodology from architecture patterns.

Reference architectures belong primarily to the Assets layer and are governed by the Framework layer.

A Databricks reference architecture explains a reusable technical pattern.

DMAF as a framework explains how to assess, plan, govern, validate, and apply that pattern in a modernization context.

This distinction prevents DMAF from becoming either:

* too abstract to deliver; or
* too narrow and technical to serve as a practice framework.

---

# 14. Relationship to the Workbench

The Modernization Intelligence Workbench belongs to the Platform layer.

It should operationalize DMAF by helping practitioners:

* ingest engagement inputs;
* interpret modernization context;
* retrieve relevant assets;
* identify gaps and contradictions;
* suggest methods and accelerators;
* generate recommendations;
* produce consulting-grade outputs;
* update the knowledge base.

The Workbench should not replace practitioner judgment or framework governance.

---

# 15. Meta Model Governance Rules

The DMAF Meta Model should be governed according to the following rules:

1. Do not change the five-layer model without governance approval.
2. Do not confuse Methods with Assets.
3. Do not confuse Assets with Platform Services.
4. Do not treat the Workbench as the source of truth.
5. Do not create assets that cannot be mapped to the framework.
6. Do not create platform services that cannot be traced to methods, assets, or capabilities.
7. Ensure framework updates are reflected in the Knowledge Graph where applicable.
8. Ensure new concepts identify their layer in the meta model.
9. Ensure the meta model remains simple enough to guide usage.
10. Ensure future automation reinforces, rather than bypasses, governance.

---

# 16. Future Enhancements

Future versions of this document may include:

* visual meta model diagram;
* layer-to-repository mapping;
* layer-to-asset mapping;
* layer-to-Workbench-service mapping;
* meta model decision tree;
* framework extension rules;
* examples by modernization scenario;
* executive-friendly one-page view;
* contributor checklist for assigning new content to the correct layer.

These enhancements are expected to be developed in later sprints and releases.

---

# 17. Review Checklist

Before approving changes to this document, reviewers should ask:

1. Are all five approved layers represented?
2. Are layer definitions consistent with the Foundation Architecture?
3. Is the relationship between layers clear?
4. Are Methods clearly distinguished from Assets?
5. Are Assets clearly distinguished from Platform Services?
6. Is the Workbench positioned as an operational layer rather than the source of truth?
7. Does the document support future Knowledge Graph development?
8. Does the document support future Workbench automation?
9. Does the document avoid introducing unsupported new framework concepts?
10. Is terminology consistent with the DMAF Taxonomy and Glossary?

---

# 18. Status

This Meta Model document is currently in **Draft v0.1.0** status.

It is the fifth substantive framework artifact created in Sprint 2.
