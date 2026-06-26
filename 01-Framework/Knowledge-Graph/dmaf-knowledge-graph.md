---

asset_id: DMAF-FWK-007
title: DMAF Knowledge Graph
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0

practice_domain:
- Modernization Intelligence Workbench
- Executive Advisory
- Modernization Architecture

cross_cutting_capabilities:
  - Governance & Security
  - Knowledge Management
  - Reusable Accelerators
    
lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Continuous Optimization & Modernization Intelligence

guiding_principles:
- Everything Is Traceable
- Knowledge Compounds
- AI Accelerates, People Govern
- Executive Storytelling Matters

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Cross-Cutting-Capabilities/dmaf-cross-cutting-capabilities.md
- 01-Framework/Meta-Model/dmaf-meta-model.md

last_updated: 2026-06-26

---

# DMAF Knowledge Graph

## 1. Purpose

The purpose of this document is to define the Knowledge Graph model for the Databricks Modernization Advisory Framework, referred to as DMAF.

The DMAF Knowledge Graph defines how framework objects relate to each other so that DMAF remains traceable, governable, reusable, and eventually machine-readable.

The Knowledge Graph helps answer questions such as:

* Which guiding principle governs this asset?
* Which practice domain owns this capability?
* Which lifecycle stage uses this method?
* Which reusable assets support this activity?
* Which Workbench services could automate or assist this work?
* Which assets are missing for a given modernization scenario?
* Which framework concepts should be updated when a method or asset changes?

The Knowledge Graph is both a governance model and a future platform architecture concept.

---

## 2. Source of Truth

The source of truth for this model is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This document does not replace the Foundation Architecture.

It extracts and organizes the approved DMAF Knowledge Graph so it can be used more easily by practice leaders, asset owners, architects, delivery leads, governance reviewers, and future Workbench capabilities.

---

## 3. Knowledge Graph Definition

A **knowledge graph** is a connected model of concepts, objects, and relationships.

In DMAF, the Knowledge Graph defines how framework objects connect across principles, domains, capabilities, methods, assets, and platform services.

The purpose is to make DMAF:

* traceable;
* searchable;
* governable;
* reusable;
* explainable;
* automation-ready;
* suitable for future AI-assisted advisory workflows.

The Knowledge Graph prevents DMAF from becoming a collection of disconnected documents.

---

## 4. Approved Knowledge Graph Object Types

DMAF contains six approved Knowledge Graph object types:

1. Guiding Principles
2. Practice Domains
3. Capabilities
4. Methods
5. Assets
6. Platform Services

Each object type has a specific role in the framework.

---

# 5. Object Type 1 — Guiding Principles

## 5.1 Definition

Guiding Principles define the decision rules that govern DMAF.

They influence how practice domains are interpreted, how capabilities are designed, how methods are applied, how assets are evaluated, and how Platform Services should behave.

## 5.2 Purpose

Guiding Principles ensure that DMAF decisions remain aligned to the core beliefs of the framework.

They provide the “why” behind DMAF choices.

## 5.3 Examples

Examples of DMAF Guiding Principles include:

* Business Value Before Technology;
* Databricks by Design;
* Modernization Is an Operating Model;
* Industrialize Delivery;
* Coexistence Is Intentional;
* Trust Is Earned Through Validation;
* AI Accelerates, People Govern;
* Executive Storytelling Matters;
* Knowledge Compounds;
* Platform Value Is the Destination;
* Everything Is Traceable.

## 5.4 Key Question

Guiding Principles answer:

> What rules govern DMAF decisions?

## 5.5 Relationship to Other Objects

Guiding Principles govern Practice Domains.

They also provide review criteria for Capabilities, Methods, Assets, and Platform Services.

---

# 6. Object Type 2 — Practice Domains

## 6.1 Definition

Practice Domains define the major areas of DMAF advisory, architecture, delivery, governance, and enablement capability.

## 6.2 Purpose

Practice Domains organize the major capability areas required to plan and execute Databricks-led modernization.

## 6.3 Examples

Examples of DMAF Practice Domains include:

* Strategy & Business Value;
* Discovery & Assessment;
* Modernization Architecture;
* Migration Factory;
* Coexistence & Validation;
* AI & Automation;
* Executive Advisory;
* Platform Operations, Adoption & Value Realization;
* Modernization Intelligence Workbench.

## 6.4 Key Question

Practice Domains answer:

> What major areas of practice capability does DMAF require?

## 6.5 Relationship to Other Objects

Practice Domains are governed by Guiding Principles.

Practice Domains contain Capabilities.

A Practice Domain may support multiple lifecycle stages.

---

# 7. Object Type 3 — Capabilities

## 7.1 Definition

Capabilities define what DMAF must be able to do within each practice domain.

A capability is more specific than a practice domain and more stable than an individual asset, template, or deliverable.

## 7.2 Purpose

Capabilities provide the organizing unit for practice maturity, methods, assets, KPIs, ownership, and future Workbench automation.

## 7.3 Examples

Examples of capabilities may include:

* modernization opportunity qualification;
* application inventory analysis;
* migration complexity scoring;
* target-state architecture design;
* migration wave planning;
* coexistence strategy design;
* validation planning;
* executive narrative development;
* platform operating model design;
* Workbench recommendation generation.

## 7.4 Key Question

Capabilities answer:

> What does this practice domain need to be able to perform?

## 7.5 Relationship to Other Objects

Capabilities belong to Practice Domains.

Capabilities are executed through Methods.

Capabilities are supported by Assets.

Capabilities may eventually be automated or assisted by Platform Services.

---

# 8. Object Type 4 — Methods

## 8.1 Definition

Methods define how capabilities are performed.

A method may include a repeatable approach, practitioner process, workshop, assessment model, scoring approach, decision tree, or delivery pattern.

## 8.2 Purpose

Methods translate DMAF capabilities into repeatable practitioner action.

They make the framework executable.

## 8.3 Examples

Examples of methods include:

* Opportunity Qualification Method;
* Discovery and Assessment Method;
* Application Complexity Scoring Method;
* Migration Wave Planning Method;
* Coexistence Strategy Method;
* Validation Planning Method;
* Executive Readiness Review Method;
* Platform Adoption Method;
* Value Realization Method.

## 8.4 Key Question

Methods answer:

> How is the capability executed?

## 8.5 Relationship to Other Objects

Methods execute Capabilities.

Methods use and produce Assets.

Methods may be supported by Platform Services.

---

# 9. Object Type 5 — Assets

## 9.1 Definition

Assets are reusable work products used to perform, explain, accelerate, govern, or scale DMAF work.

Assets may be internal, client-facing, delivery-oriented, technical, advisory, or software-supporting.

## 9.2 Purpose

Assets make DMAF reusable.

They allow practitioners to apply the framework consistently across engagements without recreating work from scratch.

## 9.3 Examples

Examples of DMAF Assets include:

* templates;
* workbooks;
* diagrams;
* playbook chapters;
* executive decks;
* assessment forms;
* reference architectures;
* proposal language;
* checklists;
* scripts;
* prompts;
* industry packs;
* release notes;
* baseline registers.

## 9.4 Key Question

Assets answer:

> What reusable materials support the method?

## 9.5 Relationship to Other Objects

Assets support Methods.

Assets should trace to Capabilities, Practice Domains, Guiding Principles, Lifecycle Stages, and Release versions.

Assets may be indexed, retrieved, generated, or improved by Platform Services.

---

# 10. Object Type 6 — Platform Services

## 10.1 Definition

Platform Services are software-enabled or AI-assisted capabilities that operationalize DMAF through the Modernization Intelligence Workbench or related tooling.

## 10.2 Purpose

Platform Services scale DMAF beyond manual consulting effort.

They help practitioners apply the framework, interpret inputs, retrieve assets, identify gaps, generate recommendations, and produce advisory outputs.

## 10.3 Examples

Examples of Platform Services include:

* engagement workspace creation;
* input ingestion;
* messy document interpretation;
* application inventory interpretation;
* complexity scoring assistance;
* recommendation generation;
* architecture diagram generation;
* artifact retrieval;
* knowledge graph search;
* proposal drafting;
* modernization dashboarding;
* asset reuse tracking.

## 10.4 Key Question

Platform Services answer:

> What can be automated, assisted, or scaled through software?

## 10.5 Relationship to Other Objects

Platform Services operationalize Assets, Methods, and Capabilities.

They must remain governed by DMAF principles and should not bypass human review.

---

# 11. Approved Relationship Chain

The approved DMAF Knowledge Graph relationship chain is:

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

This relationship chain means:

* Guiding Principles govern Practice Domains.
* Practice Domains contain Capabilities.
* Capabilities are executed through Methods.
* Methods use and produce Assets.
* Assets are operationalized through Platform Services.

This chain supports the DMAF principle that **Everything Is Traceable**.

---

# 12. Relationship Types

The Knowledge Graph may use the following relationship types.

| Relationship    | Meaning                                                                                        |
| --------------- | ---------------------------------------------------------------------------------------------- |
| governs         | A Guiding Principle governs a Practice Domain, Capability, Method, Asset, or Platform Service. |
| contains        | A Practice Domain contains one or more Capabilities.                                           |
| executes        | A Method executes or performs a Capability.                                                    |
| supports        | An Asset supports a Method or Capability.                                                      |
| produces        | A Method may produce an Asset or Deliverable.                                                  |
| operationalizes | A Platform Service operationalizes an Asset, Method, or Capability.                            |
| aligns_to       | An object aligns to a Lifecycle Stage, Practice Domain, Release, or Guiding Principle.         |
| depends_on      | An object depends on another object.                                                           |
| improves        | A new or revised object improves an existing Capability, Method, Asset, or Platform Service.   |
| replaces        | A newer object replaces an older object.                                                       |
| deprecates      | An object makes another object no longer recommended for use.                                  |

These relationship types may evolve as the Workbench matures.

---

# 13. Example Knowledge Graph Trace — Migration Factory

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

This trace shows how a practical asset connects back to framework principles and forward to possible Workbench automation.

---

# 14. Example Knowledge Graph Trace — Coexistence & Validation

```text
Guiding Principle:
Trust Is Earned Through Validation

Practice Domain:
Coexistence & Validation

Capability:
Validation Strategy Design

Method:
Reconciliation and Parallel Run Planning

Asset:
Coexistence and Validation Checklist

Platform Service:
AI-Assisted Validation Gap Analyzer
```

This trace shows how validation-related assets should remain connected to trust, evidence, and governance.

---

# 15. Example Knowledge Graph Trace — Executive Advisory

```text
Guiding Principle:
Executive Storytelling Matters

Practice Domain:
Executive Advisory

Capability:
Executive Narrative Development

Method:
Modernization Value Story Framing

Asset:
Executive Advisory Deck Template

Platform Service:
AI-Assisted Executive Summary Generator
```

This trace shows how executive-facing outputs can be governed and connected to reusable advisory methods.

---

# 16. Example Knowledge Graph Trace — Workbench

```text
Guiding Principle:
Knowledge Compounds

Practice Domain:
Modernization Intelligence Workbench

Capability:
Engagement Knowledge Capture

Method:
Input Normalization and Asset Mapping

Asset:
Engagement Workspace Template

Platform Service:
Workbench Knowledge Graph Indexing
```

This trace shows how the Workbench should capture and reuse modernization knowledge rather than operate as a disconnected tool.

---

# 17. Traceability Standard

Every major DMAF artifact should be traceable to at least:

* one Guiding Principle;
* one Practice Domain;
* one Capability;
* one Lifecycle Stage;
* one Method or Asset type;
* one Release version.

Where applicable, each artifact should also identify:

* owner;
* status;
* version;
* maturity level;
* dependencies;
* related assets;
* intended audience;
* automation potential;
* last updated date.

This traceability standard should be reflected in asset metadata.

---

# 18. Minimum Metadata for Knowledge Graph Readiness

A DMAF asset is considered minimally ready for future Knowledge Graph indexing when it includes:

```yaml
asset_id: DMAF-XXX-000
title: Asset Title
status: Draft
version: 0.1.0
owner: Owner Role
release: Release-1.0
practice_domain:
  - Practice Domain
capability:
  - Capability Name
lifecycle_stage:
  - Lifecycle Stage
guiding_principles:
  - Guiding Principle
dependencies:
  - Related Asset
last_updated: YYYY-MM-DD
```

Additional metadata may be added as the Workbench matures.

---

# 19. Knowledge Graph Use Cases

The DMAF Knowledge Graph may support the following use cases.

## 19.1 Asset Discovery

Find all assets related to a practice domain, lifecycle stage, method, or capability.

Example:

> Show all assets related to Migration Factory Planning.

## 19.2 Gap Analysis

Identify missing assets, methods, or capabilities for a modernization engagement.

Example:

> This engagement includes coexistence risk, but no validation checklist has been selected.

## 19.3 Recommendation Support

Suggest methods or assets based on engagement inputs.

Example:

> The inventory indicates high dependency complexity. Recommend dependency mapping and wave planning assets.

## 19.4 Proposal Acceleration

Generate proposal language based on relevant practice domains, lifecycle stages, and reusable assets.

Example:

> Create proposal language for an Informatica-to-Databricks migration with Oracle coexistence constraints.

## 19.5 Workbench Automation

Support Workbench services that retrieve, interpret, map, and generate modernization content.

Example:

> Map uploaded discovery notes to DMAF lifecycle stages and recommend missing artifacts.

## 19.6 Practice Intelligence

Track which assets are reused, which capabilities are most mature, and which areas need improvement.

Example:

> Show which Migration Factory assets are used most often across engagements.

---

# 20. Knowledge Graph and the Modernization Intelligence Workbench

The DMAF Knowledge Graph will eventually support the Modernization Intelligence Workbench.

Future Workbench capabilities may include:

* finding all assets related to a practice domain;
* identifying which lifecycle stage an asset supports;
* recommending missing artifacts for an engagement;
* generating proposal content from reusable patterns;
* comparing client inputs against DMAF capability models;
* surfacing contradictions or gaps in discovery evidence;
* mapping messy engagement notes to framework concepts;
* tracking which assets are reused across engagements;
* identifying which capabilities require improvement;
* generating modernization dashboards.

The Workbench should use the Knowledge Graph to make DMAF more usable, searchable, traceable, and intelligent.

The Workbench should not replace DMAF governance.

---

# 21. Knowledge Graph and Governance

The Knowledge Graph supports DMAF governance by making relationships visible.

It helps reviewers answer:

* Does this asset align to an approved practice domain?
* Does this asset support a defined capability?
* Does this method have supporting assets?
* Does this Platform Service automate an approved method?
* Does this recommendation trace to a guiding principle?
* Does this new asset duplicate an existing asset?
* Does this change affect related methods, assets, or Workbench services?

The Knowledge Graph makes governance more practical because dependencies are easier to identify.

---

# 22. Knowledge Graph and Asset Review

Before approving a major DMAF asset, reviewers should confirm:

1. The asset has metadata.
2. The asset maps to at least one practice domain.
3. The asset maps to at least one lifecycle stage.
4. The asset supports at least one capability or method.
5. The asset aligns to at least one guiding principle.
6. The asset has a release version.
7. The asset has an owner.
8. The asset has clear status.
9. The asset does not duplicate another asset.
10. The asset has potential reuse value.

This review supports the DMAF principle that Everything Is Traceable.

---

# 23. Knowledge Graph and Capability Development

As DMAF matures, each capability should become a Knowledge Graph node.

A capability node should eventually connect to:

* its practice domain;
* related lifecycle stages;
* methods that execute it;
* assets that support it;
* KPIs that measure it;
* maturity level;
* owner;
* dependencies;
* Workbench automation potential.

This will allow DMAF to identify capability maturity gaps and prioritize future investment.

---

# 24. Knowledge Graph and Release Management

The Knowledge Graph should support release management by identifying:

* which assets belong to a release;
* which framework objects changed in a release;
* which downstream assets may be affected by a change;
* which deprecated assets should no longer be used;
* which future release items are linked to current gaps.

Release notes and baseline registers should eventually be connected to the Knowledge Graph.

---

# 25. Governance Rules

The DMAF Knowledge Graph should be governed according to the following rules:

1. Do not change the approved relationship chain without governance approval.
2. Do not create major assets without traceability metadata.
3. Do not create Platform Services that bypass approved methods or assets.
4. Do not treat AI-generated outputs as approved without human review.
5. Do not create duplicate assets when an existing asset can be improved.
6. Do not add new object types without updating the taxonomy and baseline register.
7. Do not confuse Practice Domains with Lifecycle Stages.
8. Do not confuse Assets with Platform Services.
9. Ensure Knowledge Graph relationships remain simple enough to be used.
10. Ensure future Workbench automation reinforces the framework rather than replacing it.

---

# 26. Future Enhancements

Future versions of this document may include:

* visual Knowledge Graph diagram;
* formal node schema;
* formal relationship schema;
* YAML metadata schema;
* JSON representation of graph objects;
* graph database implementation concept;
* Workbench indexing architecture;
* asset dependency map;
* capability-to-asset matrix;
* lifecycle-to-asset matrix;
* knowledge graph dashboard concept;
* AI agent mapping to graph objects;
* governance workflow for graph updates.

These enhancements are expected to be developed in later sprints and releases.

---

# 27. Review Checklist

Before approving changes to this document, reviewers should ask:

1. Are all six approved object types represented?
2. Is the relationship chain consistent with the Foundation Architecture?
3. Are object definitions clear?
4. Are relationship types practical?
5. Are examples traceable and realistic?
6. Does the document support future Workbench automation?
7. Does the document support asset governance?
8. Does the document avoid over-engineering the graph too early?
9. Is terminology consistent with the DMAF Taxonomy and Glossary?
10. Does the document reinforce the principle that Everything Is Traceable?

---

# 28. Status

This Knowledge Graph document is currently in **Draft v0.1.0** status.

It is the sixth substantive framework artifact created in Sprint 2.
