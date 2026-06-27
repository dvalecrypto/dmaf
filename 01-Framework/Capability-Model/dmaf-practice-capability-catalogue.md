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

| Practice Domain | Initial Capability Count | Status |
|---|---:|---|
| Strategy & Business Value | 7 | Drafted |
| Discovery & Assessment | 8 | Drafted |
| Modernization Architecture | 8 | Drafted |
| Migration Factory | 8 | Drafted |
| Coexistence & Validation | Pending | Not Started |
| AI & Automation | Pending | Not Started |
| Executive Advisory | Pending | Not Started |
| Platform Operations, Adoption & Value Realization | Pending | Not Started |
| Modernization Intelligence Workbench | Pending | Not Started |

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

# 10. Practice Domain 1 — Strategy & Business Value

## 10.1 Domain Purpose

The Strategy & Business Value domain defines the business rationale for modernization.

It ensures that Databricks-led modernization is connected to executive priorities, measurable business outcomes, investment logic, strategic sequencing, risk reduction, and long-term platform value.

This domain is especially important before detailed discovery, architecture, or migration planning begins because it shapes why the modernization effort exists and what business value it must produce.

---

## 10.2 Capability Summary

| Capability ID    | Capability Name                         | Primary Lifecycle Stages   | Maturity Target      |
| ---------------- | --------------------------------------- | -------------------------- | -------------------- |
| DMAF-CAP-SBV-001 | Modernization Opportunity Qualification | Stage 0, Stage 1           | Level 3 — Managed    |
| DMAF-CAP-SBV-002 | Business Value Framing                  | Stage 0, Stage 1           | Level 3 — Managed    |
| DMAF-CAP-SBV-003 | Executive Sponsor Alignment             | Stage 0, Stage 1, Stage 10 | Level 3 — Managed    |
| DMAF-CAP-SBV-004 | Modernization Value Mapping             | Stage 1, Stage 3, Stage 9  | Level 3 — Managed    |
| DMAF-CAP-SBV-005 | Strategic Roadmap Framing               | Stage 1, Stage 3, Stage 4  | Level 3 — Managed    |
| DMAF-CAP-SBV-006 | Investment Case Development             | Stage 1, Stage 4           | Level 2 — Repeatable |
| DMAF-CAP-SBV-007 | Success Metric Definition               | Stage 1, Stage 9, Stage 10 | Level 3 — Managed    |

---

## 10.3 Capability — DMAF-CAP-SBV-001 — Modernization Opportunity Qualification

| Field                          | Description                                                                                                                                                                     |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-SBV-001                                                                                                                                                                |
| Capability Name                | Modernization Opportunity Qualification                                                                                                                                         |
| Practice Domain                | Strategy & Business Value                                                                                                                                                       |
| Business Objective             | Determine whether a modernization opportunity is real, strategically aligned, valuable, actionable, and appropriate for a Databricks-led advisory or delivery motion.           |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value                                                                               |
| Inputs                         | Initial client conversation notes, business drivers, known pain points, current-state technology signals, executive priorities, known constraints, modernization trigger events |
| Outputs                        | Opportunity qualification summary, modernization hypothesis, initial scope framing, preliminary value hypothesis, recommended next step                                         |
| Methods                        | Opportunity qualification method, modernization trigger assessment, initial value hypothesis framing, executive discovery conversation                                          |
| Assets                         | Opportunity qualification checklist, modernization hypothesis template, initial client discovery note template, executive conversation guide                                    |
| Owner                          | Account Executive / Engagement Lead                                                                                                                                             |
| KPIs                           | Qualified opportunity rate, opportunity-to-discovery conversion rate, clarity of business driver, executive sponsor identification rate                                         |
| Maturity Target                | Level 3 — Managed                                                                                                                                                               |
| Dependencies                   | Executive Advisory, Discovery & Assessment, Modernization Intelligence Workbench                                                                                                |
| Workbench Automation Potential | AI-assisted opportunity intake, modernization signal detection, initial hypothesis generation, opportunity scoring support                                                      |

### Notes

This capability ensures DMAF begins before formal discovery. It helps prevent premature solutioning by requiring the opportunity to be framed in terms of business drivers, modernization need, and strategic fit.

---

## 10.4 Capability — DMAF-CAP-SBV-002 — Business Value Framing

| Field                          | Description                                                                                                                                                               |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-SBV-002                                                                                                                                                          |
| Capability Name                | Business Value Framing                                                                                                                                                    |
| Practice Domain                | Strategy & Business Value                                                                                                                                                 |
| Business Objective             | Translate modernization drivers into clear business value themes that can be understood by executives and used to guide architecture, delivery, and investment decisions. |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value                                                                         |
| Inputs                         | Business objectives, pain points, current-state constraints, risk drivers, platform limitations, executive priorities, market or regulatory pressures                     |
| Outputs                        | Business value narrative, value driver map, modernization value themes, executive value summary                                                                           |
| Methods                        | Value driver mapping, business outcome framing, strategic theme development, modernization value narrative method                                                         |
| Assets                         | Value driver map template, business value framing worksheet, executive value narrative template                                                                           |
| Owner                          | Account Executive / Engagement Lead                                                                                                                                       |
| KPIs                           | Business value clarity, sponsor agreement on value drivers, ability to connect modernization scope to measurable outcomes                                                 |
| Maturity Target                | Level 3 — Managed                                                                                                                                                         |
| Dependencies                   | Executive Advisory, Modernization Architecture, Platform Operations, Adoption & Value Realization                                                                         |
| Workbench Automation Potential | AI-assisted value theme extraction, value narrative drafting, value driver mapping from discovery notes                                                                   |

### Notes

This capability supports the guiding principle **Business Value Before Technology**. It ensures modernization is not positioned as tool replacement, but as a business and operating model improvement.

---

## 10.5 Capability — DMAF-CAP-SBV-003 — Executive Sponsor Alignment

| Field                          | Description                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-SBV-003                                                                                                                                                   |
| Capability Name                | Executive Sponsor Alignment                                                                                                                                        |
| Practice Domain                | Strategy & Business Value                                                                                                                                          |
| Business Objective             | Ensure that modernization has visible executive ownership, aligned expectations, and a decision-making path before significant advisory or delivery work begins.   |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Stakeholder map, sponsor priorities, business objectives, funding context, risk concerns, decision timelines                                                       |
| Outputs                        | Sponsor alignment summary, stakeholder map, decision path, executive concerns log, alignment risks                                                                 |
| Methods                        | Stakeholder mapping, sponsor alignment workshop, executive concern analysis, decision path mapping                                                                 |
| Assets                         | Sponsor alignment checklist, stakeholder map template, executive alignment summary template                                                                        |
| Owner                          | Engagement Lead / Practice Lead                                                                                                                                    |
| KPIs                           | Sponsor clarity, decision-maker identification, stakeholder alignment score, unresolved executive concern count                                                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                                  |
| Dependencies                   | Executive Advisory, Business Value Framing, Strategic Roadmap Framing                                                                                              |
| Workbench Automation Potential | Stakeholder extraction from notes, sponsor concern summarization, alignment risk detection                                                                         |

### Notes

This capability is critical in enterprise modernization because technical readiness does not guarantee executive commitment. DMAF should surface sponsor alignment early.

---

## 10.6 Capability — DMAF-CAP-SBV-004 — Modernization Value Mapping

| Field                          | Description                                                                                                                            |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-SBV-004                                                                                                                       |
| Capability Name                | Modernization Value Mapping                                                                                                            |
| Practice Domain                | Strategy & Business Value                                                                                                              |
| Business Objective             | Map modernization activities to expected business, technical, operational, governance, cost, and AI-readiness outcomes.                |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture; Stage 9 — Platform Operations, Adoption & Value Realization |
| Inputs                         | Business value themes, current-state constraints, target-state architecture concepts, platform objectives, operating model goals       |
| Outputs                        | Modernization value map, outcome traceability model, value realization themes, benefits dependency map                                 |
| Methods                        | Value mapping, outcome dependency analysis, business-to-architecture traceability, benefit realization mapping                         |
| Assets                         | Modernization value map template, outcome traceability worksheet, value realization planning template                                  |
| Owner                          | Engagement Lead / Solution Architect                                                                                                   |
| KPIs                           | Percentage of modernization scope mapped to value drivers, value traceability completeness, stakeholder agreement on expected outcomes |
| Maturity Target                | Level 3 — Managed                                                                                                                      |
| Dependencies                   | Business Value Framing, Modernization Architecture, Platform Operations, Adoption & Value Realization                                  |
| Workbench Automation Potential | Automated value-to-scope mapping, outcome traceability suggestions, value gap detection                                                |

### Notes

This capability creates a bridge between executive value and technical modernization scope. It helps ensure architecture and migration decisions remain tied to measurable outcomes.

---

## 10.7 Capability — DMAF-CAP-SBV-005 — Strategic Roadmap Framing

| Field                          | Description                                                                                                                                             |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-SBV-005                                                                                                                                        |
| Capability Name                | Strategic Roadmap Framing                                                                                                                               |
| Practice Domain                | Strategy & Business Value                                                                                                                               |
| Business Objective             | Define a high-level modernization roadmap that sequences strategic outcomes, major workstreams, and decision points before detailed migration planning. |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning                                         |
| Inputs                         | Business objectives, value drivers, current-state constraints, target-state direction, risk factors, dependency themes                                  |
| Outputs                        | Strategic modernization roadmap, roadmap themes, executive sequencing view, investment and decision timeline                                            |
| Methods                        | Roadmap framing, theme-based sequencing, dependency-aware planning, executive roadmap storytelling                                                      |
| Assets                         | Strategic roadmap template, executive roadmap view, modernization sequencing worksheet                                                                  |
| Owner                          | Engagement Lead / Solution Architect                                                                                                                    |
| KPIs                           | Roadmap clarity, executive acceptance, alignment between roadmap and business value, decision point identification                                      |
| Maturity Target                | Level 3 — Managed                                                                                                                                       |
| Dependencies                   | Business Value Framing, Modernization Architecture, Migration Factory Planning                                                                          |
| Workbench Automation Potential | AI-assisted roadmap drafting, sequencing option generation, roadmap theme extraction from discovery inputs                                              |

### Notes

This capability is distinct from detailed migration wave planning. It frames the executive modernization journey before the Migration Factory creates execution-level waves and backlog.

---

## 10.8 Capability — DMAF-CAP-SBV-006 — Investment Case Development

| Field                          | Description                                                                                                                                                                  |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-SBV-006                                                                                                                                                             |
| Capability Name                | Investment Case Development                                                                                                                                                  |
| Practice Domain                | Strategy & Business Value                                                                                                                                                    |
| Business Objective             | Support funding and prioritization decisions by framing modernization investment in terms of value, risk reduction, cost drivers, delivery approach, and strategic outcomes. |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 4 — Migration Factory Planning                                                                                                    |
| Inputs                         | Value drivers, scope assumptions, migration complexity, cost drivers, risk factors, roadmap themes, platform benefits                                                        |
| Outputs                        | Investment case narrative, cost-benefit framing, funding rationale, executive decision support summary                                                                       |
| Methods                        | Investment framing, benefit-cost narrative development, risk-adjusted value discussion, modernization economics framing                                                      |
| Assets                         | Investment case template, cost driver worksheet, executive decision support template                                                                                         |
| Owner                          | Account Executive / Engagement Lead                                                                                                                                          |
| KPIs                           | Funding approval support, investment rationale clarity, decision-maker confidence, alignment to value drivers                                                                |
| Maturity Target                | Level 2 — Repeatable                                                                                                                                                         |
| Dependencies                   | Business Value Framing, Modernization Value Mapping, Migration Factory Planning, FinOps & Cost Optimization                                                                  |
| Workbench Automation Potential | Investment narrative drafting, cost driver extraction, value-risk trade-off summary generation                                                                               |

### Notes

This capability does not replace a formal financial business case process. It provides DMAF-aligned advisory framing to support investment decisions and proposal development.

---

## 10.9 Capability — DMAF-CAP-SBV-007 — Success Metric Definition

| Field                          | Description                                                                                                                                                       |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-SBV-007                                                                                                                                                  |
| Capability Name                | Success Metric Definition                                                                                                                                         |
| Practice Domain                | Strategy & Business Value                                                                                                                                         |
| Business Objective             | Define measurable indicators that determine whether modernization is producing business, platform, delivery, governance, cost, and adoption value.                |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Business objectives, value drivers, platform goals, delivery targets, governance expectations, adoption goals                                                     |
| Outputs                        | Success metric model, KPI list, value realization measures, platform outcome measures                                                                             |
| Methods                        | KPI definition, outcome measurement planning, value realization metric design, platform success measure framing                                                   |
| Assets                         | Success metric template, KPI library, value realization tracking template                                                                                         |
| Owner                          | Engagement Lead / Platform Lead                                                                                                                                   |
| KPIs                           | Metric coverage, stakeholder agreement on measures, ability to track post-migration outcomes, alignment between metrics and value drivers                         |
| Maturity Target                | Level 3 — Managed                                                                                                                                                 |
| Dependencies                   | Business Value Framing, Modernization Value Mapping, Platform Operations, Adoption & Value Realization                                                            |
| Workbench Automation Potential | KPI recommendation engine, value metric extraction, dashboard requirement generation                                                                              |

### Notes

This capability supports the DMAF principle that **Platform Value Is the Destination**. It ensures modernization success is not measured only by migration completion.

---

# 11. Strategy & Business Value Capability Map

| Capability ID    | Capability                              | Supports Business Value | Supports Delivery | Supports Governance | Supports Workbench |
| ---------------- | --------------------------------------- | ----------------------- | ----------------- | ------------------- | ------------------ |
| DMAF-CAP-SBV-001 | Modernization Opportunity Qualification | Yes                     | Yes               | Yes                 | Yes                |
| DMAF-CAP-SBV-002 | Business Value Framing                  | Yes                     | Yes               | Yes                 | Yes                |
| DMAF-CAP-SBV-003 | Executive Sponsor Alignment             | Yes                     | Yes               | Yes                 | Yes                |
| DMAF-CAP-SBV-004 | Modernization Value Mapping             | Yes                     | Yes               | Yes                 | Yes                |
| DMAF-CAP-SBV-005 | Strategic Roadmap Framing               | Yes                     | Yes               | Yes                 | Yes                |
| DMAF-CAP-SBV-006 | Investment Case Development             | Yes                     | Yes               | Yes                 | Yes                |
| DMAF-CAP-SBV-007 | Success Metric Definition               | Yes                     | Yes               | Yes                 | Yes                |

---

# 12. Strategy & Business Value Capability Governance

The Strategy & Business Value capabilities should be governed according to the following rules:

1. Do not begin modernization advisory work without identifying the business driver.
2. Do not position modernization only as technology replacement.
3. Do not create a roadmap without linking it to business value.
4. Do not proceed to detailed migration planning without understanding executive priorities.
5. Do not define success only as migration completion.
6. Do not create investment narratives that are disconnected from delivery complexity or risk.
7. Ensure business value, modernization scope, and platform value remain traceable.

---

# 13. Future Enhancements

Future versions of this domain section may include:

* opportunity qualification scoring model;
* value driver library;
* executive sponsor alignment checklist;
* modernization value map template;
* investment case template;
* KPI library;
* Workbench opportunity intake workflow;
* AI-assisted value narrative generator.

---

# 14. Practice Domain 2 — Discovery & Assessment

## 14.1 Domain Purpose

The Discovery & Assessment domain defines how DMAF gathers, normalizes, interprets, and scores current-state modernization evidence.

This domain creates the factual basis for modernization decisions. It helps ensure that strategy, architecture, migration planning, coexistence, validation, and executive recommendations are based on evidence rather than assumptions.

Discovery & Assessment is especially important because modernization programs often begin with incomplete, inconsistent, outdated, or fragmented information. DMAF must therefore provide repeatable capabilities for intake, interpretation, scoring, synthesis, and gap identification.

---

## 14.2 Capability Summary

| Capability ID    | Capability Name                           | Primary Lifecycle Stages  | Maturity Target   |
| ---------------- | ----------------------------------------- | ------------------------- | ----------------- |
| DMAF-CAP-DAS-001 | Discovery Intake & Evidence Management    | Stage 1, Stage 2          | Level 3 — Managed |
| DMAF-CAP-DAS-002 | Application & Workflow Inventory Analysis | Stage 2, Stage 4          | Level 3 — Managed |
| DMAF-CAP-DAS-003 | Data Source & Dependency Mapping          | Stage 2, Stage 3, Stage 4 | Level 3 — Managed |
| DMAF-CAP-DAS-004 | Current-State Architecture Assessment     | Stage 2, Stage 3          | Level 3 — Managed |
| DMAF-CAP-DAS-005 | Modernization Complexity Scoring          | Stage 2, Stage 4          | Level 3 — Managed |
| DMAF-CAP-DAS-006 | Migration Readiness Assessment            | Stage 2, Stage 4, Stage 5 | Level 3 — Managed |
| DMAF-CAP-DAS-007 | Risk & Constraint Identification          | Stage 2, Stage 3, Stage 4 | Level 3 — Managed |
| DMAF-CAP-DAS-008 | Discovery Findings Synthesis              | Stage 2, Stage 3, Stage 4 | Level 3 — Managed |

---

## 14.3 Capability — DMAF-CAP-DAS-001 — Discovery Intake & Evidence Management

| Field                          | Description                                                                                                                                                            |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-DAS-001                                                                                                                                                       |
| Capability Name                | Discovery Intake & Evidence Management                                                                                                                                 |
| Practice Domain                | Discovery & Assessment                                                                                                                                                 |
| Business Objective             | Establish a repeatable approach for collecting, organizing, validating, and managing discovery inputs so modernization decisions are based on reliable evidence.       |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 2 — Discovery & Assessment                                                                                                  |
| Inputs                         | Client documents, application inventories, workflow lists, architecture diagrams, interview notes, screenshots, data samples, runbooks, extracts, existing assessments |
| Outputs                        | Discovery evidence register, intake log, evidence quality notes, gap list, source document index                                                                       |
| Methods                        | Discovery intake method, evidence classification, document review, interview capture, evidence gap analysis                                                            |
| Assets                         | Discovery intake checklist, evidence register template, interview note template, discovery folder structure, evidence gap tracker                                      |
| Owner                          | Lead Business Analyst / Solution Architect                                                                                                                             |
| KPIs                           | Discovery input completeness, evidence traceability, unresolved evidence gaps, duplicate or conflicting input count                                                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                                      |
| Dependencies                   | Strategy & Business Value, Executive Advisory, Modernization Intelligence Workbench                                                                                    |
| Workbench Automation Potential | AI-assisted document intake, source classification, duplicate detection, evidence gap detection, discovery workspace creation                                          |

### Notes

This capability prevents discovery from becoming a loose document collection exercise. It establishes the evidence base required for assessment, architecture, and migration planning.

---

## 14.4 Capability — DMAF-CAP-DAS-002 — Application & Workflow Inventory Analysis

| Field                          | Description                                                                                                                                      |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-DAS-002                                                                                                                                 |
| Capability Name                | Application & Workflow Inventory Analysis                                                                                                        |
| Practice Domain                | Discovery & Assessment                                                                                                                           |
| Business Objective             | Analyze application, workflow, job, and pipeline inventories to understand modernization scope, complexity, ownership, and migration candidates. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 4 — Migration Factory Planning                                                                           |
| Inputs                         | Application inventory, workflow inventory, job schedules, ETL mappings, pipeline lists, ownership data, platform metadata                        |
| Outputs                        | Normalized inventory, application/workflow profile, scope summary, inventory quality assessment, candidate grouping                              |
| Methods                        | Inventory normalization, workflow classification, application profiling, scope segmentation, ownership analysis                                  |
| Assets                         | Application inventory template, workflow inventory workbook, inventory normalization guide, application profile template                         |
| Owner                          | Lead Business Analyst / Solution Architect                                                                                                       |
| KPIs                           | Inventory completeness, number of applications profiled, number of workflows classified, percentage of inventory with owners identified          |
| Maturity Target                | Level 3 — Managed                                                                                                                                |
| Dependencies                   | Discovery Intake & Evidence Management, Modernization Complexity Scoring, Migration Factory                                                      |
| Workbench Automation Potential | Inventory parsing, metadata extraction, workflow classification, duplicate application detection, inventory quality scoring                      |

### Notes

This capability is foundational for migration factory planning. Without an accurate inventory, wave planning, estimation, and dependency sequencing will be unreliable.

---

## 14.5 Capability — DMAF-CAP-DAS-003 — Data Source & Dependency Mapping

| Field                          | Description                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-DAS-003                                                                                                                                                   |
| Capability Name                | Data Source & Dependency Mapping                                                                                                                                   |
| Practice Domain                | Discovery & Assessment                                                                                                                                             |
| Business Objective             | Identify source systems, target systems, upstream dependencies, downstream consumers, data flows, and integration points that affect modernization scope and risk. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning                                                       |
| Inputs                         | System inventory, workflow inventory, data flow diagrams, ETL mappings, source extracts, target tables, downstream file lists, interface documentation             |
| Outputs                        | Dependency map, source-to-target relationship summary, upstream/downstream impact view, integration risk notes                                                     |
| Methods                        | Dependency mapping, source-to-target analysis, interface review, data lineage approximation, downstream impact analysis                                            |
| Assets                         | Dependency mapping template, source-to-target matrix, interface inventory template, dependency risk checklist                                                      |
| Owner                          | Solution Architect / Data Architect                                                                                                                                |
| KPIs                           | Dependency coverage, number of unresolved dependencies, downstream impact clarity, percentage of critical flows mapped                                             |
| Maturity Target                | Level 3 — Managed                                                                                                                                                  |
| Dependencies                   | Application & Workflow Inventory Analysis, Current-State Architecture Assessment, Coexistence & Validation                                                         |
| Workbench Automation Potential | Relationship extraction from inventories, dependency graph generation, missing dependency detection, downstream impact summarization                               |

### Notes

This capability is critical for avoiding modernization surprises. Dependency visibility directly affects architecture decisions, migration sequencing, validation design, and cutover risk.

---

## 14.6 Capability — DMAF-CAP-DAS-004 — Current-State Architecture Assessment

| Field                          | Description                                                                                                                                                                |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-DAS-004                                                                                                                                                           |
| Capability Name                | Current-State Architecture Assessment                                                                                                                                      |
| Practice Domain                | Discovery & Assessment                                                                                                                                                     |
| Business Objective             | Assess the current-state technology, data, integration, orchestration, governance, and operational architecture to inform Databricks target-state and transition planning. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture                                                                                                     |
| Inputs                         | Architecture diagrams, system inventories, infrastructure notes, platform documentation, security models, orchestration schedules, operational runbooks                    |
| Outputs                        | Current-state architecture summary, architecture risk notes, modernization constraints, transition considerations                                                          |
| Methods                        | Architecture review, platform capability assessment, architecture gap analysis, technical constraint assessment                                                            |
| Assets                         | Current-state architecture assessment template, platform capability checklist, architecture gap worksheet, modernization constraint log                                    |
| Owner                          | Solution Architect / Enterprise Architect                                                                                                                                  |
| KPIs                           | Architecture coverage, number of architectural constraints identified, completeness of platform capability assessment, target-state relevance                              |
| Maturity Target                | Level 3 — Managed                                                                                                                                                          |
| Dependencies                   | Data Source & Dependency Mapping, Modernization Architecture, Governance & Security                                                                                        |
| Workbench Automation Potential | Architecture note summarization, diagram interpretation support, platform capability extraction, architecture gap recommendation                                           |

### Notes

This capability creates the bridge between discovery and architecture. It ensures the target-state design accounts for the realities of the current environment.

---

## 14.7 Capability — DMAF-CAP-DAS-005 — Modernization Complexity Scoring

| Field                          | Description                                                                                                                                                         |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-DAS-005                                                                                                                                                    |
| Capability Name                | Modernization Complexity Scoring                                                                                                                                    |
| Practice Domain                | Discovery & Assessment                                                                                                                                              |
| Business Objective             | Score modernization candidates using consistent complexity factors so planning, sequencing, estimating, and risk decisions are evidence-based.                      |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 4 — Migration Factory Planning                                                                                              |
| Inputs                         | Application inventory, workflow inventory, dependency map, data volume indicators, transformation complexity, technology stack, business criticality, testing needs |
| Outputs                        | Complexity score, complexity tier, scoring rationale, candidate prioritization input, wave planning input                                                           |
| Methods                        | Complexity scoring model, weighted factor assessment, scoring workshop, complexity calibration                                                                      |
| Assets                         | Complexity scoring workbook, scoring rubric, complexity heatmap template, scoring calibration guide                                                                 |
| Owner                          | Lead Business Analyst / Migration Lead                                                                                                                              |
| KPIs                           | Percentage of candidates scored, scoring consistency, scoring confidence, number of high-complexity candidates identified                                           |
| Maturity Target                | Level 3 — Managed                                                                                                                                                   |
| Dependencies                   | Application & Workflow Inventory Analysis, Data Source & Dependency Mapping, Migration Factory                                                                      |
| Workbench Automation Potential | AI-assisted scoring suggestions, complexity factor extraction, heatmap generation, scoring anomaly detection                                                        |

### Notes

This capability supports industrialized delivery by creating a repeatable basis for migration wave planning. It should not be treated as a purely mechanical scoring exercise; expert review is required.

---

## 14.8 Capability — DMAF-CAP-DAS-006 — Migration Readiness Assessment

| Field                          | Description                                                                                                                                                                              |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-DAS-006                                                                                                                                                                         |
| Capability Name                | Migration Readiness Assessment                                                                                                                                                           |
| Practice Domain                | Discovery & Assessment                                                                                                                                                                   |
| Business Objective             | Determine whether applications, workflows, data sources, teams, environments, dependencies, and governance conditions are ready to proceed into pilot, planning, or migration execution. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 4 — Migration Factory Planning; Stage 5 — Reference Implementation / Pilot                                                                       |
| Inputs                         | Discovery findings, complexity scores, dependency map, architecture assessment, environment readiness, resource availability, validation needs                                           |
| Outputs                        | Readiness assessment, readiness gaps, recommended next steps, pilot candidate recommendations, readiness risk summary                                                                    |
| Methods                        | Readiness scoring, readiness review workshop, gap assessment, pilot candidate selection                                                                                                  |
| Assets                         | Migration readiness checklist, readiness scoring template, pilot selection criteria, readiness risk summary template                                                                     |
| Owner                          | Solution Architect / Migration Lead                                                                                                                                                      |
| KPIs                           | Readiness score, number of readiness gaps, pilot candidate confidence, remediation action closure rate                                                                                   |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                        |
| Dependencies                   | Modernization Complexity Scoring, Current-State Architecture Assessment, Migration Factory Planning                                                                                      |
| Workbench Automation Potential | Readiness scoring support, pilot candidate recommendation, readiness gap detection, remediation backlog generation                                                                       |

### Notes

This capability helps prevent premature migration execution. It ensures that planning reflects readiness, not just desire to move quickly.

---

## 14.9 Capability — DMAF-CAP-DAS-007 — Risk & Constraint Identification

| Field                          | Description                                                                                                                                                    |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-DAS-007                                                                                                                                               |
| Capability Name                | Risk & Constraint Identification                                                                                                                               |
| Practice Domain                | Discovery & Assessment                                                                                                                                         |
| Business Objective             | Identify risks, constraints, assumptions, gaps, and unknowns that may affect modernization scope, architecture, sequencing, validation, cost, or adoption.     |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning                                                   |
| Inputs                         | Discovery evidence, stakeholder interviews, architecture notes, inventory gaps, dependency map, business constraints, regulatory or operational considerations |
| Outputs                        | Risk and constraint register, assumptions log, issue list, unknowns list, mitigation themes                                                                    |
| Methods                        | Risk identification, constraint analysis, assumption capture, stakeholder concern analysis, impact assessment                                                  |
| Assets                         | Risk register template, constraint log, assumption tracker, discovery issue log, executive risk summary template                                               |
| Owner                          | Engagement Lead / Lead Business Analyst                                                                                                                        |
| KPIs                           | Number of risks identified, unresolved critical risks, number of assumptions requiring validation, mitigation ownership clarity                                |
| Maturity Target                | Level 3 — Managed                                                                                                                                              |
| Dependencies                   | Discovery Intake & Evidence Management, Current-State Architecture Assessment, Executive Advisory                                                              |
| Workbench Automation Potential | Risk extraction from notes, assumption detection, contradiction detection, risk categorization, mitigation suggestion drafting                                 |

### Notes

This capability should surface uncertainty early. DMAF should distinguish confirmed facts from assumptions, gaps, risks, and open questions.

---

## 14.10 Capability — DMAF-CAP-DAS-008 — Discovery Findings Synthesis

| Field                          | Description                                                                                                                                                                            |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-DAS-008                                                                                                                                                                       |
| Capability Name                | Discovery Findings Synthesis                                                                                                                                                           |
| Practice Domain                | Discovery & Assessment                                                                                                                                                                 |
| Business Objective             | Convert discovery evidence into clear findings, implications, recommendations, and next steps for architecture, migration planning, executive decision-making, and delivery readiness. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning                                                                           |
| Inputs                         | Evidence register, inventory analysis, dependency map, architecture assessment, complexity scoring, readiness assessment, risk register                                                |
| Outputs                        | Discovery findings report, executive findings summary, architecture implications, migration planning inputs, recommended next steps                                                    |
| Methods                        | Findings synthesis, evidence-to-recommendation mapping, executive summary development, gap and implication analysis                                                                    |
| Assets                         | Discovery findings template, executive findings deck, findings-to-recommendations matrix, discovery closeout checklist                                                                 |
| Owner                          | Engagement Lead / Solution Architect                                                                                                                                                   |
| KPIs                           | Findings clarity, stakeholder acceptance, recommendation traceability, number of unresolved evidence gaps at discovery close                                                           |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                      |
| Dependencies                   | All Discovery & Assessment capabilities, Executive Advisory, Modernization Architecture, Migration Factory                                                                             |
| Workbench Automation Potential | AI-assisted findings synthesis, recommendation drafting, evidence traceability mapping, executive summary generation                                                                   |

### Notes

This capability is the output bridge from discovery into decision-making. It ensures discovery does not end with raw facts, but with usable modernization intelligence.

---

# 15. Discovery & Assessment Capability Map

| Capability ID    | Capability                                | Supports Evidence Quality | Supports Architecture | Supports Migration Planning | Supports Workbench |
| ---------------- | ----------------------------------------- | ------------------------- | --------------------- | --------------------------- | ------------------ |
| DMAF-CAP-DAS-001 | Discovery Intake & Evidence Management    | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-002 | Application & Workflow Inventory Analysis | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-003 | Data Source & Dependency Mapping          | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-004 | Current-State Architecture Assessment     | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-005 | Modernization Complexity Scoring          | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-006 | Migration Readiness Assessment            | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-007 | Risk & Constraint Identification          | Yes                       | Yes                   | Yes                         | Yes                |
| DMAF-CAP-DAS-008 | Discovery Findings Synthesis              | Yes                       | Yes                   | Yes                         | Yes                |

---

# 16. Discovery & Assessment Capability Governance

The Discovery & Assessment capabilities should be governed according to the following rules:

1. Do not proceed to architecture or migration planning without sufficient discovery evidence.
2. Do not treat incomplete inventories as complete.
3. Do not hide assumptions inside recommendations.
4. Do not score complexity without documenting scoring rationale.
5. Do not treat dependency mapping as optional for complex modernization.
6. Do not present discovery findings without distinguishing facts, assumptions, risks, and gaps.
7. Ensure discovery outputs are traceable to source evidence.
8. Ensure discovery findings can be consumed by architecture, migration planning, validation, and executive advisory work.

---

# 17. Future Enhancements

Future versions of this domain section may include:

* discovery intake workflow;
* evidence register template;
* application inventory workbook;
* workflow inventory workbook;
* dependency mapping workbook;
* current-state architecture assessment template;
* complexity scoring workbook;
* readiness assessment checklist;
* discovery findings deck;
* Workbench discovery intake agent;
* AI-assisted evidence gap analyzer.

---

# 18. Practice Domain 3 — Modernization Architecture

## 18.1 Domain Purpose

The Modernization Architecture domain defines the target-state and transitional architecture models for Databricks-led modernization.

This domain connects discovery findings, business objectives, platform constraints, governance expectations, integration requirements, and migration strategy into a coherent architecture direction.

Modernization Architecture ensures that DMAF does not treat migration as a mechanical workload movement exercise. It defines the architectural foundation required for scalable, governed, validated, and value-oriented modernization.

---

## 18.2 Capability Summary

| Capability ID    | Capability Name                  | Primary Lifecycle Stages   | Maturity Target   |
| ---------------- | -------------------------------- | -------------------------- | ----------------- |
| DMAF-CAP-MAR-001 | Target-State Architecture Design | Stage 3, Stage 5           | Level 3 — Managed |
| DMAF-CAP-MAR-002 | Transitional Architecture Design | Stage 3, Stage 4, Stage 7  | Level 3 — Managed |
| DMAF-CAP-MAR-003 | Databricks Capability Mapping    | Stage 1, Stage 3, Stage 4  | Level 3 — Managed |
| DMAF-CAP-MAR-004 | Lakehouse Pattern Selection      | Stage 3, Stage 5, Stage 6  | Level 3 — Managed |
| DMAF-CAP-MAR-005 | Governance Architecture Design   | Stage 3, Stage 7, Stage 9  | Level 3 — Managed |
| DMAF-CAP-MAR-006 | Integration Architecture Design  | Stage 3, Stage 4, Stage 7  | Level 3 — Managed |
| DMAF-CAP-MAR-007 | Architecture Decision Management | Stage 3, Stage 4, Stage 5  | Level 3 — Managed |
| DMAF-CAP-MAR-008 | Reference Architecture Selection | Stage 3, Stage 5, Stage 10 | Level 3 — Managed |

---

## 18.3 Capability — DMAF-CAP-MAR-001 — Target-State Architecture Design

| Field                          | Description                                                                                                                                                                            |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MAR-001                                                                                                                                                                       |
| Capability Name                | Target-State Architecture Design                                                                                                                                                       |
| Practice Domain                | Modernization Architecture                                                                                                                                                             |
| Business Objective             | Define the future Databricks-centered architecture required to support business value, governed data delivery, scalable engineering, analytics, AI readiness, and platform operations. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 5 — Reference Implementation / Pilot                                                                                                       |
| Inputs                         | Business objectives, discovery findings, current-state architecture, application inventory, dependency map, governance requirements, platform constraints                              |
| Outputs                        | Target-state architecture, architecture principles, platform capability view, architecture roadmap, design assumptions                                                                 |
| Methods                        | Target-state architecture method, architecture capability mapping, platform pattern alignment, architecture review workshop                                                            |
| Assets                         | Target-state architecture template, Databricks architecture diagram template, architecture principles checklist, platform capability map                                               |
| Owner                          | Enterprise Architect / Solution Architect                                                                                                                                              |
| KPIs                           | Architecture approval, target-state clarity, stakeholder alignment, number of unresolved architecture decisions                                                                        |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                      |
| Dependencies                   | Discovery & Assessment, Strategy & Business Value, Governance & Security, Platform Operations, Adoption & Value Realization                                                            |
| Workbench Automation Potential | AI-assisted architecture draft generation, capability-to-architecture mapping, architecture gap detection, diagram generation support                                                  |

### Notes

This capability establishes the future-state direction for modernization. It should be tied to business value and platform outcomes, not simply to tool replacement.

---

## 18.4 Capability — DMAF-CAP-MAR-002 — Transitional Architecture Design

| Field                          | Description                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-MAR-002                                                                                                                                                   |
| Capability Name                | Transitional Architecture Design                                                                                                                                   |
| Practice Domain                | Modernization Architecture                                                                                                                                         |
| Business Objective             | Define how legacy and modern platforms will coexist during modernization while controlling risk, integration complexity, validation needs, and operational impact. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 7 — Coexistence & Validation                                                     |
| Inputs                         | Current-state architecture, target-state architecture, dependency map, migration roadmap, coexistence requirements, downstream impacts, cutover constraints        |
| Outputs                        | Transitional architecture, coexistence view, migration transition states, interim integration model, transition risk notes                                         |
| Methods                        | Transitional architecture planning, coexistence pattern assessment, transition-state mapping, dependency-aware architecture sequencing                             |
| Assets                         | Transitional architecture template, coexistence architecture pattern, transition-state diagram, interim integration checklist                                      |
| Owner                          | Solution Architect / Data Architect                                                                                                                                |
| KPIs                           | Transition-state clarity, coexistence risk reduction, unresolved transition dependencies, architecture readiness for migration planning                            |
| Maturity Target                | Level 3 — Managed                                                                                                                                                  |
| Dependencies                   | Target-State Architecture Design, Data Source & Dependency Mapping, Coexistence & Validation, Migration Factory                                                    |
| Workbench Automation Potential | Transition-state recommendation, coexistence pattern matching, dependency-to-transition mapping, transition risk detection                                         |

### Notes

This capability is essential when modernization cannot occur as a clean cutover. It makes coexistence intentional rather than accidental.

---

## 18.5 Capability — DMAF-CAP-MAR-003 — Databricks Capability Mapping

| Field                          | Description                                                                                                                                               |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MAR-003                                                                                                                                          |
| Capability Name                | Databricks Capability Mapping                                                                                                                             |
| Practice Domain                | Modernization Architecture                                                                                                                                |
| Business Objective             | Map modernization needs to relevant Databricks capabilities so that architecture decisions are aligned with platform strengths and business objectives.   |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning                                           |
| Inputs                         | Business value themes, current-state pain points, workload characteristics, governance needs, data engineering needs, analytics needs, AI-readiness goals |
| Outputs                        | Databricks capability map, platform fit summary, capability-to-use-case alignment, platform adoption implications                                         |
| Methods                        | Capability mapping, use-case alignment, platform fit assessment, capability gap analysis                                                                  |
| Assets                         | Databricks capability map template, platform fit assessment checklist, use-case alignment worksheet                                                       |
| Owner                          | Solution Architect / Databricks Practice Lead                                                                                                             |
| KPIs                           | Capability alignment clarity, number of mapped use cases, platform fit confidence, unresolved capability gaps                                             |
| Maturity Target                | Level 3 — Managed                                                                                                                                         |
| Dependencies                   | Strategy & Business Value, Target-State Architecture Design, Platform Operations, Adoption & Value Realization                                            |
| Workbench Automation Potential | Capability recommendation, use-case-to-platform mapping, capability gap detection, platform positioning summary generation                                |

### Notes

This capability reinforces the principle **Databricks by Design**. It ensures Databricks capabilities are positioned intentionally, not generically.

---

## 18.6 Capability — DMAF-CAP-MAR-004 — Lakehouse Pattern Selection

| Field                          | Description                                                                                                                                                     |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MAR-004                                                                                                                                                |
| Capability Name                | Lakehouse Pattern Selection                                                                                                                                     |
| Practice Domain                | Modernization Architecture                                                                                                                                      |
| Business Objective             | Select appropriate lakehouse architecture patterns for data ingestion, transformation, governance, serving, analytics, AI readiness, and operational use cases. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 5 — Reference Implementation / Pilot; Stage 6 — Migration Factory Execution                                         |
| Inputs                         | Workload inventory, data characteristics, latency requirements, governance requirements, transformation patterns, target-state architecture, platform standards |
| Outputs                        | Selected lakehouse patterns, architecture pattern rationale, implementation guidance, reusable reference pattern mapping                                        |
| Methods                        | Pattern selection method, workload-to-pattern mapping, data architecture review, architecture pattern fit assessment                                            |
| Assets                         | Lakehouse pattern catalogue, workload-to-pattern matrix, reference architecture diagrams, architecture pattern decision guide                                   |
| Owner                          | Data Architect / Solution Architect                                                                                                                             |
| KPIs                           | Pattern reuse rate, pattern fit confidence, number of workloads mapped to approved patterns, reduction in custom one-off designs                                |
| Maturity Target                | Level 3 — Managed                                                                                                                                               |
| Dependencies                   | Target-State Architecture Design, Reference Architecture Selection, Migration Factory, Governance & Security                                                    |
| Workbench Automation Potential | Pattern recommendation, workload-to-pattern mapping, reusable architecture diagram generation, pattern gap detection                                            |

### Notes

This capability supports standardization. It reduces the risk of every engagement creating a unique architecture for common modernization scenarios.

---

## 18.7 Capability — DMAF-CAP-MAR-005 — Governance Architecture Design

| Field                          | Description                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-MAR-005                                                                                                                                                   |
| Capability Name                | Governance Architecture Design                                                                                                                                     |
| Practice Domain                | Modernization Architecture                                                                                                                                         |
| Business Objective             | Define how governance, access control, security, lineage, policy enforcement, and data management expectations will be represented in the modernized architecture. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 7 — Coexistence & Validation; Stage 9 — Platform Operations, Adoption & Value Realization                              |
| Inputs                         | Enterprise governance requirements, security standards, data classification needs, access model, compliance expectations, current-state control model              |
| Outputs                        | Governance architecture view, access control model, policy alignment notes, data management considerations, governance implementation assumptions                  |
| Methods                        | Governance architecture assessment, access model design, policy mapping, control alignment review                                                                  |
| Assets                         | Governance architecture template, access control checklist, Unity Catalog readiness checklist, policy mapping worksheet                                            |
| Owner                          | Solution Architect / Governance Lead                                                                                                                               |
| KPIs                           | Governance requirement coverage, access model clarity, control alignment, unresolved governance gaps                                                               |
| Maturity Target                | Level 3 — Managed                                                                                                                                                  |
| Dependencies                   | Governance & Security, Risk & Compliance, Target-State Architecture Design, Platform Operations, Adoption & Value Realization                                      |
| Workbench Automation Potential | Governance gap detection, access model recommendation, policy-to-architecture mapping, governance checklist generation                                             |

### Notes

This capability ensures that governance is designed into modernization architecture rather than added after implementation.

---

## 18.8 Capability — DMAF-CAP-MAR-006 — Integration Architecture Design

| Field                          | Description                                                                                                                                                                   |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MAR-006                                                                                                                                                              |
| Capability Name                | Integration Architecture Design                                                                                                                                               |
| Practice Domain                | Modernization Architecture                                                                                                                                                    |
| Business Objective             | Define how modernized workloads will integrate with upstream systems, downstream consumers, orchestration tools, data platforms, reporting layers, and operational processes. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 7 — Coexistence & Validation                                                                |
| Inputs                         | Dependency map, source-to-target relationships, interface inventory, downstream file requirements, orchestration schedules, target-state architecture                         |
| Outputs                        | Integration architecture, interface model, upstream/downstream impact view, orchestration considerations, integration risks                                                   |
| Methods                        | Integration architecture review, interface mapping, orchestration pattern assessment, downstream impact analysis                                                              |
| Assets                         | Integration architecture template, interface inventory template, orchestration pattern guide, downstream impact checklist                                                     |
| Owner                          | Solution Architect / Integration Architect                                                                                                                                    |
| KPIs                           | Interface coverage, downstream impact clarity, integration risk visibility, unresolved integration dependencies                                                               |
| Maturity Target                | Level 3 — Managed                                                                                                                                                             |
| Dependencies                   | Data Source & Dependency Mapping, Transitional Architecture Design, Coexistence & Validation, Migration Factory                                                               |
| Workbench Automation Potential | Interface extraction, integration map generation, downstream impact summarization, orchestration pattern recommendation                                                       |

### Notes

This capability is important for enterprise modernization where data pipelines rarely operate in isolation. Integration design directly affects validation, cutover, and operations.

---

## 18.9 Capability — DMAF-CAP-MAR-007 — Architecture Decision Management

| Field                          | Description                                                                                                                                                      |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MAR-007                                                                                                                                                 |
| Capability Name                | Architecture Decision Management                                                                                                                                 |
| Practice Domain                | Modernization Architecture                                                                                                                                       |
| Business Objective             | Capture, govern, and communicate key architecture decisions so modernization teams understand design rationale, trade-offs, constraints, and downstream impacts. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 5 — Reference Implementation / Pilot                                           |
| Inputs                         | Architecture options, constraints, risks, decision points, stakeholder feedback, platform standards, pilot findings                                              |
| Outputs                        | Architecture decision records, decision log, open decision list, decision rationale, architecture trade-off summary                                              |
| Methods                        | Architecture decision record method, decision review, trade-off analysis, architecture governance review                                                         |
| Assets                         | Architecture decision record template, decision log, architecture trade-off worksheet, review checklist                                                          |
| Owner                          | Enterprise Architect / Solution Architect                                                                                                                        |
| KPIs                           | Decision traceability, open decision aging, decision approval rate, number of decisions with documented rationale                                                |
| Maturity Target                | Level 3 — Managed                                                                                                                                                |
| Dependencies                   | Target-State Architecture Design, Transitional Architecture Design, Governance & Security, Executive Advisory                                                    |
| Workbench Automation Potential | ADR drafting support, decision extraction from notes, open decision tracking, decision impact analysis                                                           |

### Notes

This capability supports traceability and governance. It helps prevent architecture choices from being lost in meeting notes or informal discussions.

---

## 18.10 Capability — DMAF-CAP-MAR-008 — Reference Architecture Selection

| Field                          | Description                                                                                                                                       |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MAR-008                                                                                                                                  |
| Capability Name                | Reference Architecture Selection                                                                                                                  |
| Practice Domain                | Modernization Architecture                                                                                                                        |
| Business Objective             | Select and adapt reusable Databricks-centered reference architectures to accelerate modernization design while preserving fit to client context.  |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 5 — Reference Implementation / Pilot; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Current-state architecture, target-state objectives, workload patterns, platform standards, industry requirements, reusable architecture library  |
| Outputs                        | Selected reference architecture, fit-gap notes, adaptation guidance, reusable pattern feedback                                                    |
| Methods                        | Reference architecture fit assessment, pattern selection, fit-gap analysis, architecture reuse review                                             |
| Assets                         | Reference architecture catalogue, architecture fit-gap worksheet, reference architecture selection checklist, reusable diagram library            |
| Owner                          | Solution Architect / Practice Lead                                                                                                                |
| KPIs                           | Reference architecture reuse rate, fit-gap clarity, reduction in custom architecture effort, reusable pattern improvement rate                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                 |
| Dependencies                   | Lakehouse Pattern Selection, Target-State Architecture Design, Knowledge Management, Reusable Accelerators                                        |
| Workbench Automation Potential | Reference architecture recommendation, pattern matching, fit-gap detection, diagram retrieval, architecture package generation                    |

### Notes

This capability keeps DMAF reusable and scalable. Reference architectures should accelerate design but should not replace client-specific architecture judgment.

---

# 19. Modernization Architecture Capability Map

| Capability ID    | Capability                       | Supports Target State | Supports Transition | Supports Governance | Supports Workbench |
| ---------------- | -------------------------------- | --------------------- | ------------------- | ------------------- | ------------------ |
| DMAF-CAP-MAR-001 | Target-State Architecture Design | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-002 | Transitional Architecture Design | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-003 | Databricks Capability Mapping    | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-004 | Lakehouse Pattern Selection      | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-005 | Governance Architecture Design   | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-006 | Integration Architecture Design  | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-007 | Architecture Decision Management | Yes                   | Yes                 | Yes                 | Yes                |
| DMAF-CAP-MAR-008 | Reference Architecture Selection | Yes                   | Yes                 | Yes                 | Yes                |

---

# 20. Modernization Architecture Capability Governance

The Modernization Architecture capabilities should be governed according to the following rules:

1. Do not define target-state architecture without reference to business value.
2. Do not define architecture without using discovery evidence.
3. Do not skip transitional architecture when coexistence or phased migration is required.
4. Do not treat governance and security as post-implementation concerns.
5. Do not create one-off architecture patterns when reusable reference architectures exist.
6. Do not make major architecture decisions without documenting rationale.
7. Do not proceed to migration planning without identifying major architecture dependencies.
8. Ensure architecture outputs are usable by Migration Factory, Coexistence & Validation, and Platform Operations.

---

# 21. Future Enhancements

Future versions of this domain section may include:

* target-state architecture template;
* transitional architecture template;
* Databricks capability map;
* lakehouse pattern catalogue;
* Unity Catalog governance architecture checklist;
* integration architecture checklist;
* architecture decision record template;
* reference architecture selection guide;
* architecture package generator concept;
* Workbench architecture recommendation agent.

---

# 22. Practice Domain 4 — Migration Factory

## 22.1 Domain Purpose

The Migration Factory domain defines how modernization is planned, sequenced, industrialized, executed, governed, and measured at scale.

This domain turns modernization strategy, discovery evidence, and architecture direction into a repeatable delivery model.

Migration Factory is central to DMAF because it moves modernization beyond one-off project execution. It provides the structure for wave planning, backlog management, delivery capacity, reusable migration patterns, execution governance, and delivery metrics.

---

## 22.2 Capability Summary

| Capability ID    | Capability Name                         | Primary Lifecycle Stages            | Maturity Target   |
| ---------------- | --------------------------------------- | ----------------------------------- | ----------------- |
| DMAF-CAP-MGF-001 | Migration Wave Planning                 | Stage 4, Stage 5, Stage 6           | Level 3 — Managed |
| DMAF-CAP-MGF-002 | Factory Backlog Management              | Stage 4, Stage 6                    | Level 3 — Managed |
| DMAF-CAP-MGF-003 | Migration Pattern Management            | Stage 4, Stage 5, Stage 6, Stage 10 | Level 3 — Managed |
| DMAF-CAP-MGF-004 | Delivery Capacity & Throughput Planning | Stage 4, Stage 6                    | Level 3 — Managed |
| DMAF-CAP-MGF-005 | Migration Estimation & Sizing           | Stage 2, Stage 4, Stage 6           | Level 3 — Managed |
| DMAF-CAP-MGF-006 | Dependency-Based Sequencing             | Stage 4, Stage 5, Stage 6           | Level 3 — Managed |
| DMAF-CAP-MGF-007 | Factory Execution Governance            | Stage 4, Stage 6, Stage 7           | Level 3 — Managed |
| DMAF-CAP-MGF-008 | Migration Metrics & Reporting           | Stage 4, Stage 6, Stage 10          | Level 3 — Managed |

---

## 22.3 Capability — DMAF-CAP-MGF-001 — Migration Wave Planning

| Field                          | Description                                                                                                                                                             |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-001                                                                                                                                                        |
| Capability Name                | Migration Wave Planning                                                                                                                                                 |
| Practice Domain                | Migration Factory                                                                                                                                                       |
| Business Objective             | Create a repeatable, risk-aware migration sequence that balances business value, technical complexity, dependency constraints, validation needs, and delivery capacity. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 5 — Reference Implementation / Pilot; Stage 6 — Migration Factory Execution                                                 |
| Inputs                         | Application inventory, workflow inventory, complexity scores, dependency map, business priorities, architecture decisions, resource capacity, validation requirements   |
| Outputs                        | Migration wave plan, wave sequencing rationale, wave backlog, roadmap view, pilot candidate recommendations                                                             |
| Methods                        | Complexity-based wave sequencing, dependency-aware planning, migration segmentation, wave planning workshop                                                             |
| Assets                         | Migration wave planning workbook, timeline simulator, wave planning template, executive migration roadmap                                                               |
| Owner                          | Migration Lead / Delivery Manager                                                                                                                                       |
| KPIs                           | Wave predictability, wave completion rate, schedule adherence, percentage of dependencies resolved before wave start                                                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                                       |
| Dependencies                   | Discovery & Assessment, Modernization Architecture, Coexistence & Validation, Executive Advisory                                                                        |
| Workbench Automation Potential | AI-assisted wave planning, scenario simulation, dependency-aware sequencing suggestions, wave risk detection                                                            |

### Notes

This capability is distinct from strategic roadmap framing. Strategic roadmap framing creates the executive journey. Migration Wave Planning creates the execution sequence.

---

## 22.4 Capability — DMAF-CAP-MGF-002 — Factory Backlog Management

| Field                          | Description                                                                                                                                     |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-002                                                                                                                                |
| Capability Name                | Factory Backlog Management                                                                                                                      |
| Practice Domain                | Migration Factory                                                                                                                               |
| Business Objective             | Maintain a governed backlog of modernization work items so migration execution can be planned, prioritized, tracked, and adjusted across waves. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution                                                                     |
| Inputs                         | Migration scope, application inventory, workflow inventory, wave plan, architecture decisions, defects, risks, dependencies, change requests    |
| Outputs                        | Factory backlog, prioritized work items, backlog status, blockers, change log, backlog health summary                                           |
| Methods                        | Backlog structuring, prioritization, delivery planning, blocker management, change control                                                      |
| Assets                         | Factory backlog template, backlog health dashboard, prioritization guide, delivery tracker                                                      |
| Owner                          | Delivery Manager / Migration Lead                                                                                                               |
| KPIs                           | Backlog readiness, blocked item count, backlog aging, work item completion rate, change request impact                                          |
| Maturity Target                | Level 3 — Managed                                                                                                                               |
| Dependencies                   | Migration Wave Planning, Migration Estimation & Sizing, Factory Execution Governance                                                            |
| Workbench Automation Potential | Backlog generation from inventory, backlog health analysis, blocker summarization, change impact detection                                      |

### Notes

This capability ensures migration work is managed as a factory backlog rather than as scattered tasks across documents, spreadsheets, and meeting notes.

---

## 22.5 Capability — DMAF-CAP-MGF-003 — Migration Pattern Management

| Field                          | Description                                                                                                                                                                              |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-003                                                                                                                                                                         |
| Capability Name                | Migration Pattern Management                                                                                                                                                             |
| Practice Domain                | Migration Factory                                                                                                                                                                        |
| Business Objective             | Identify, define, reuse, and improve repeatable migration patterns so modernization delivery becomes faster, more consistent, and less dependent on one-off decisions.                   |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 5 — Reference Implementation / Pilot; Stage 6 — Migration Factory Execution; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Current-state technologies, workload types, transformation patterns, architecture decisions, pilot findings, delivery lessons learned                                                    |
| Outputs                        | Migration pattern catalogue, pattern selection guidance, reusable implementation guidance, pattern improvement notes                                                                     |
| Methods                        | Pattern identification, pattern fit assessment, pilot pattern validation, lessons learned capture                                                                                        |
| Assets                         | Migration pattern catalogue, pattern selection matrix, pattern documentation template, lessons learned template                                                                          |
| Owner                          | Solution Architect / Migration Lead                                                                                                                                                      |
| KPIs                           | Pattern reuse rate, reduction in one-off delivery decisions, pattern quality feedback, number of validated patterns                                                                      |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                        |
| Dependencies                   | Modernization Architecture, Reference Implementation / Pilot, Knowledge Management, Reusable Accelerators                                                                                |
| Workbench Automation Potential | Pattern recommendation, pattern matching from workload metadata, pattern reuse tracking, pattern gap detection                                                                           |

### Notes

This capability helps DMAF industrialize delivery. Migration patterns should become reusable practice assets, not only informal project knowledge.

---

## 22.6 Capability — DMAF-CAP-MGF-004 — Delivery Capacity & Throughput Planning

| Field                          | Description                                                                                                                                                                                         |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-004                                                                                                                                                                                    |
| Capability Name                | Delivery Capacity & Throughput Planning                                                                                                                                                             |
| Practice Domain                | Migration Factory                                                                                                                                                                                   |
| Business Objective             | Estimate and manage how much modernization work the delivery team can realistically complete across waves, given resources, complexity, dependencies, validation needs, and governance constraints. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution                                                                                                                         |
| Inputs                         | Resource model, team roles, complexity scores, wave plan, backlog, delivery calendar, SME availability, environment constraints                                                                     |
| Outputs                        | Capacity plan, throughput assumptions, staffing model, delivery velocity expectations, capacity risks                                                                                               |
| Methods                        | Capacity planning, throughput estimation, velocity modeling, staffing analysis, constraint-based delivery planning                                                                                  |
| Assets                         | Capacity planning worksheet, velocity model, staffing plan template, throughput dashboard                                                                                                           |
| Owner                          | Delivery Manager / Migration Lead                                                                                                                                                                   |
| KPIs                           | Planned vs. actual throughput, resource utilization, capacity constraint count, delivery velocity trend                                                                                             |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                   |
| Dependencies                   | Migration Wave Planning, Factory Backlog Management, Migration Estimation & Sizing, Executive Advisory                                                                                              |
| Workbench Automation Potential | Throughput simulation, capacity risk detection, staffing scenario generation, velocity dashboarding                                                                                                 |

### Notes

This capability prevents migration plans from being built only around desired deadlines. It grounds execution in realistic team capacity and delivery constraints.

---

## 22.7 Capability — DMAF-CAP-MGF-005 — Migration Estimation & Sizing

| Field                          | Description                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-MGF-005                                                                                                                                                   |
| Capability Name                | Migration Estimation & Sizing                                                                                                                                      |
| Practice Domain                | Migration Factory                                                                                                                                                  |
| Business Objective             | Estimate modernization effort, sizing, and delivery complexity so scope, timelines, resource needs, and investment decisions are based on transparent assumptions. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution                                                      |
| Inputs                         | Application inventory, workflow inventory, complexity scoring, migration patterns, delivery history, architecture assumptions, validation requirements             |
| Outputs                        | Estimation model, sizing assumptions, effort estimate, estimate confidence level, estimation risk notes                                                            |
| Methods                        | Complexity-based estimation, pattern-based sizing, delivery calibration, estimation confidence assessment                                                          |
| Assets                         | Estimation workbook, sizing model, estimation assumption log, complexity-to-effort mapping guide                                                                   |
| Owner                          | Delivery Manager / Solution Architect                                                                                                                              |
| KPIs                           | Estimate accuracy, estimate confidence, variance between estimated and actual effort, assumption closure rate                                                      |
| Maturity Target                | Level 3 — Managed                                                                                                                                                  |
| Dependencies                   | Modernization Complexity Scoring, Migration Pattern Management, Delivery Capacity & Throughput Planning                                                            |
| Workbench Automation Potential | AI-assisted effort estimation, assumption extraction, estimate confidence scoring, actual-vs-estimate analysis                                                     |

### Notes

This capability should make assumptions visible. Estimates should not be presented as certainty when discovery evidence is incomplete.

---

## 22.8 Capability — DMAF-CAP-MGF-006 — Dependency-Based Sequencing

| Field                          | Description                                                                                                                                                          |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-006                                                                                                                                                     |
| Capability Name                | Dependency-Based Sequencing                                                                                                                                          |
| Practice Domain                | Migration Factory                                                                                                                                                    |
| Business Objective             | Sequence migration work based on upstream dependencies, downstream impacts, shared data structures, platform constraints, business priorities, and validation needs. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 5 — Reference Implementation / Pilot; Stage 6 — Migration Factory Execution                                              |
| Inputs                         | Dependency map, source-to-target matrix, interface inventory, architecture decisions, downstream consumer list, business criticality, validation constraints         |
| Outputs                        | Dependency-aware sequence, sequencing rationale, dependency blockers, sequencing risk summary                                                                        |
| Methods                        | Dependency analysis, sequencing workshop, blocker assessment, impact-based prioritization                                                                            |
| Assets                         | Dependency sequencing worksheet, dependency map, sequencing decision log, blocker tracker                                                                            |
| Owner                          | Migration Lead / Data Architect                                                                                                                                      |
| KPIs                           | Dependency blockers resolved before wave start, sequencing stability, downstream impact incidents, rework caused by missed dependencies                              |
| Maturity Target                | Level 3 — Managed                                                                                                                                                    |
| Dependencies                   | Data Source & Dependency Mapping, Integration Architecture Design, Coexistence & Validation                                                                          |
| Workbench Automation Potential | Dependency graph analysis, sequencing recommendation, blocker detection, downstream impact alerting                                                                  |

### Notes

This capability ensures migration is sequenced according to real technical and business dependencies, not only by application count or perceived simplicity.

---

## 22.9 Capability — DMAF-CAP-MGF-007 — Factory Execution Governance

| Field                          | Description                                                                                                                                                 |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-007                                                                                                                                            |
| Capability Name                | Factory Execution Governance                                                                                                                                |
| Practice Domain                | Migration Factory                                                                                                                                           |
| Business Objective             | Provide the governance routines, decision checkpoints, escalation paths, quality gates, and progress controls needed to manage migration factory execution. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution; Stage 7 — Coexistence & Validation                                             |
| Inputs                         | Factory plan, backlog, wave plan, risks, issues, defects, validation status, architecture decisions, delivery metrics                                       |
| Outputs                        | Governance cadence, status reports, issue and risk escalations, quality gate outcomes, decision log, delivery control summary                               |
| Methods                        | Factory governance cadence, quality gate review, risk and issue management, delivery checkpoint review, escalation management                               |
| Assets                         | Factory governance model, status report template, quality gate checklist, decision log, risk and issue tracker                                              |
| Owner                          | Delivery Manager / Engagement Lead                                                                                                                          |
| KPIs                           | Quality gate pass rate, unresolved blocker aging, decision turnaround time, escalation closure rate, delivery status accuracy                               |
| Maturity Target                | Level 3 — Managed                                                                                                                                           |
| Dependencies                   | Factory Backlog Management, Migration Metrics & Reporting, Coexistence & Validation, Executive Advisory                                                     |
| Workbench Automation Potential | Status summary generation, risk and issue trend analysis, quality gate tracking, escalation recommendation                                                  |

### Notes

This capability prevents the migration factory from becoming only a delivery engine. It ensures execution remains governed, transparent, and decision-ready.

---

## 22.10 Capability — DMAF-CAP-MGF-008 — Migration Metrics & Reporting

| Field                          | Description                                                                                                                                               |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-MGF-008                                                                                                                                          |
| Capability Name                | Migration Metrics & Reporting                                                                                                                             |
| Practice Domain                | Migration Factory                                                                                                                                         |
| Business Objective             | Measure and communicate migration factory progress, throughput, quality, risk, predictability, and readiness so stakeholders can make informed decisions. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution; Stage 10 — Continuous Optimization & Modernization Intelligence              |
| Inputs                         | Wave plan, backlog, status updates, defects, validation results, risks, issues, estimates, actual effort, delivery milestones                             |
| Outputs                        | Migration dashboard, executive status summary, factory KPI report, delivery trend analysis, lessons learned input                                         |
| Methods                        | KPI definition, delivery reporting, trend analysis, executive status reporting, performance review                                                        |
| Assets                         | Migration dashboard template, factory KPI library, executive status template, delivery metrics workbook                                                   |
| Owner                          | Delivery Manager / Practice Lead                                                                                                                          |
| KPIs                           | Migration velocity, wave completion rate, defect trend, estimate variance, quality gate pass rate, schedule adherence                                     |
| Maturity Target                | Level 3 — Managed                                                                                                                                         |
| Dependencies                   | Factory Backlog Management, Delivery Capacity & Throughput Planning, Factory Execution Governance, Knowledge Management                                   |
| Workbench Automation Potential | Dashboard generation, executive status drafting, KPI trend analysis, lessons learned extraction                                                           |

### Notes

This capability supports visibility and continuous improvement. Reporting should measure more than activity; it should show delivery health, risk, quality, and predictability.

---

# 23. Migration Factory Capability Map

| Capability ID    | Capability                              | Supports Planning | Supports Execution | Supports Governance | Supports Workbench |
| ---------------- | --------------------------------------- | ----------------- | ------------------ | ------------------- | ------------------ |
| DMAF-CAP-MGF-001 | Migration Wave Planning                 | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-002 | Factory Backlog Management              | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-003 | Migration Pattern Management            | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-004 | Delivery Capacity & Throughput Planning | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-005 | Migration Estimation & Sizing           | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-006 | Dependency-Based Sequencing             | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-007 | Factory Execution Governance            | Yes               | Yes                | Yes                 | Yes                |
| DMAF-CAP-MGF-008 | Migration Metrics & Reporting           | Yes               | Yes                | Yes                 | Yes                |

---

# 24. Migration Factory Capability Governance

The Migration Factory capabilities should be governed according to the following rules:

1. Do not start factory execution without a defined wave plan.
2. Do not build migration waves without considering dependencies.
3. Do not use complexity scoring without documenting assumptions.
4. Do not treat estimates as fixed when discovery confidence is low.
5. Do not run migration execution without backlog governance.
6. Do not scale migration without reusable migration patterns where practical.
7. Do not report only activity; report progress, quality, risk, and predictability.
8. Ensure factory lessons learned improve future patterns, estimates, assets, and Workbench intelligence.

---

# 25. Future Enhancements

Future versions of this domain section may include:

* migration factory planning workbook;
* wave planning scenario simulator;
* dependency-based sequencing model;
* migration estimation workbook;
* migration pattern catalogue;
* factory backlog dashboard;
* delivery capacity model;
* factory governance checklist;
* migration KPI dashboard;
* Workbench migration factory planner.

---

# 26. Status

This Practice Capability Catalogue is currently in **Draft v0.5.0** status.

The following practice domains have been drafted:

* Strategy & Business Value
* Discovery & Assessment
* Modernization Architecture
* Migration Factory

Remaining capability domains are pending.

