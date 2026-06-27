---

asset_id: DMAF-FWK-009
title: DMAF Practice Capability Catalogue
status: Draft
version: 0.9.0
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
| Coexistence & Validation | 8 | Drafted |
| AI & Automation | 8 | Drafted |
| Executive Advisory | 8 | Drafted |
| Platform Operations, Adoption & Value Realization | 8 | Drafted |
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

# 26. Practice Domain 5 — Coexistence & Validation

## 26.1 Domain Purpose

The Coexistence & Validation domain defines how legacy and modernized platforms operate during transition and how modernization outcomes are proven.

This domain is central to trust. It ensures that modernized workloads are accurate, complete, reconciled, explainable, supportable, and ready for production use.

Coexistence & Validation is especially important in enterprise modernization because migration rarely happens as a single clean replacement. Legacy and modern platforms may need to operate together while workloads are migrated, validated, compared, reconciled, and accepted.

---

## 26.2 Capability Summary

| Capability ID    | Capability Name                       | Primary Lifecycle Stages  | Maturity Target   |
| ---------------- | ------------------------------------- | ------------------------- | ----------------- |
| DMAF-CAP-COV-001 | Coexistence Strategy Design           | Stage 3, Stage 4, Stage 7 | Level 3 — Managed |
| DMAF-CAP-COV-002 | Parallel Run Planning                 | Stage 5, Stage 7, Stage 8 | Level 3 — Managed |
| DMAF-CAP-COV-003 | Reconciliation Design                 | Stage 5, Stage 7, Stage 8 | Level 3 — Managed |
| DMAF-CAP-COV-004 | Validation Strategy Design            | Stage 4, Stage 5, Stage 7 | Level 3 — Managed |
| DMAF-CAP-COV-005 | Exception Handling & Resolution Model | Stage 7, Stage 8          | Level 3 — Managed |
| DMAF-CAP-COV-006 | Cutover Readiness Assessment          | Stage 7, Stage 8          | Level 3 — Managed |
| DMAF-CAP-COV-007 | Validation Evidence Management        | Stage 5, Stage 7, Stage 8 | Level 3 — Managed |
| DMAF-CAP-COV-008 | Production Readiness Support          | Stage 8, Stage 9          | Level 3 — Managed |

---

## 26.3 Capability — DMAF-CAP-COV-001 — Coexistence Strategy Design

| Field                          | Description                                                                                                                                                                                |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-COV-001                                                                                                                                                                           |
| Capability Name                | Coexistence Strategy Design                                                                                                                                                                |
| Practice Domain                | Coexistence & Validation                                                                                                                                                                   |
| Business Objective             | Define how legacy and modernized platforms will operate together during transition while managing risk, data consistency, downstream impact, validation needs, and operational complexity. |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 7 — Coexistence & Validation                                                                             |
| Inputs                         | Current-state architecture, transitional architecture, dependency map, downstream consumer list, migration waves, validation requirements, cutover constraints                             |
| Outputs                        | Coexistence strategy, coexistence architecture view, transition-state model, coexistence risks, operational considerations                                                                 |
| Methods                        | Coexistence pattern assessment, transition-state mapping, downstream impact analysis, coexistence risk review                                                                              |
| Assets                         | Coexistence strategy template, coexistence decision tree, transition-state diagram, coexistence risk checklist                                                                             |
| Owner                          | Solution Architect / Data Architect                                                                                                                                                        |
| KPIs                           | Coexistence risk visibility, transition-state clarity, downstream impact coverage, unresolved coexistence dependencies                                                                     |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                          |
| Dependencies                   | Transitional Architecture Design, Integration Architecture Design, Migration Wave Planning, Risk & Compliance                                                                              |
| Workbench Automation Potential | Coexistence pattern recommendation, transition-state mapping, dependency-to-coexistence risk detection, coexistence summary drafting                                                       |

### Notes

This capability supports the DMAF principle **Coexistence Is Intentional**. Coexistence should be designed explicitly rather than discovered during testing or cutover.

---

## 26.4 Capability — DMAF-CAP-COV-002 — Parallel Run Planning

| Field                          | Description                                                                                                                                                  |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-COV-002                                                                                                                                             |
| Capability Name                | Parallel Run Planning                                                                                                                                        |
| Practice Domain                | Coexistence & Validation                                                                                                                                     |
| Business Objective             | Define when, how, and under what constraints legacy and modernized workloads will run in parallel to compare outputs and build stakeholder confidence.       |
| Lifecycle Stages               | Stage 5 — Reference Implementation / Pilot; Stage 7 — Coexistence & Validation; Stage 8 — Production Cutover                                                 |
| Inputs                         | Coexistence strategy, migration wave plan, validation requirements, source and target outputs, test environments, data availability, operational constraints |
| Outputs                        | Parallel run plan, comparison approach, test window schedule, parallel run constraints, acceptance criteria                                                  |
| Methods                        | Parallel run planning, output comparison design, test window planning, acceptance criteria definition                                                        |
| Assets                         | Parallel run planning template, output comparison checklist, test window planner, parallel run acceptance criteria template                                  |
| Owner                          | Test Manager / Data Architect                                                                                                                                |
| KPIs                           | Parallel run coverage, comparison success rate, number of unresolved differences, stakeholder confidence level                                               |
| Maturity Target                | Level 3 — Managed                                                                                                                                            |
| Dependencies                   | Coexistence Strategy Design, Reconciliation Design, Validation Strategy Design, Migration Factory                                                            |
| Workbench Automation Potential | Parallel run schedule generation, output comparison summary, unresolved difference tracking, acceptance evidence packaging                                   |

### Notes

Parallel run may not always be possible due to environment, data, platform, or cost constraints. When parallel run is limited, those constraints must be documented and alternative validation approaches must be defined.

---

## 26.5 Capability — DMAF-CAP-COV-003 — Reconciliation Design

| Field                          | Description                                                                                                                                                                                       |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-COV-003                                                                                                                                                                                  |
| Capability Name                | Reconciliation Design                                                                                                                                                                             |
| Practice Domain                | Coexistence & Validation                                                                                                                                                                          |
| Business Objective             | Define how legacy and modernized outputs will be compared, reconciled, explained, and accepted using appropriate control totals, record counts, hashes, business rules, and exception thresholds. |
| Lifecycle Stages               | Stage 5 — Reference Implementation / Pilot; Stage 7 — Coexistence & Validation; Stage 8 — Production Cutover                                                                                      |
| Inputs                         | Source outputs, target outputs, business rules, control totals, data quality expectations, transformation logic, downstream acceptance criteria                                                   |
| Outputs                        | Reconciliation approach, control framework, comparison rules, exception thresholds, reconciliation evidence                                                                                       |
| Methods                        | Reconciliation rule design, control total comparison, record count comparison, hash total comparison, business rule validation                                                                    |
| Assets                         | Reconciliation design template, control totals checklist, exception threshold worksheet, validation comparison matrix                                                                             |
| Owner                          | Data Architect / Test Manager                                                                                                                                                                     |
| KPIs                           | Reconciliation pass rate, unresolved exception count, exception aging, control coverage, acceptance threshold clarity                                                                             |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                 |
| Dependencies                   | Validation Strategy Design, Parallel Run Planning, Data Source & Dependency Mapping, Business Rule Analysis                                                                                       |
| Workbench Automation Potential | Reconciliation rule suggestion, control comparison automation, exception clustering, discrepancy summary generation                                                                               |

### Notes

Reconciliation should be designed before validation execution begins. It should define what must match, what differences are acceptable, how differences are explained, and who can approve exceptions.

---

## 26.6 Capability — DMAF-CAP-COV-004 — Validation Strategy Design

| Field                          | Description                                                                                                                                                 |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-COV-004                                                                                                                                            |
| Capability Name                | Validation Strategy Design                                                                                                                                  |
| Practice Domain                | Coexistence & Validation                                                                                                                                    |
| Business Objective             | Define the overall validation approach required to prove that modernized workloads are accurate, complete, reliable, supportable, and fit for business use. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 5 — Reference Implementation / Pilot; Stage 7 — Coexistence & Validation                                        |
| Inputs                         | Migration scope, target-state architecture, coexistence strategy, reconciliation needs, business rules, test strategy, risk profile, acceptance criteria    |
| Outputs                        | Validation strategy, validation scope, validation levels, acceptance criteria, validation roles, evidence requirements                                      |
| Methods                        | Validation planning, risk-based test design, acceptance criteria definition, evidence planning                                                              |
| Assets                         | Validation strategy template, validation planning checklist, acceptance criteria template, evidence requirement checklist                                   |
| Owner                          | Test Manager / Data Architect                                                                                                                               |
| KPIs                           | Validation coverage, acceptance criteria completeness, evidence completeness, defect leakage, stakeholder acceptance                                        |
| Maturity Target                | Level 3 — Managed                                                                                                                                           |
| Dependencies                   | Migration Factory Planning, Coexistence Strategy Design, Reconciliation Design, Risk & Compliance                                                           |
| Workbench Automation Potential | Validation strategy drafting, test coverage gap detection, acceptance criteria recommendation, evidence checklist generation                                |

### Notes

This capability supports the DMAF principle **Trust Is Earned Through Validation**. Validation should be treated as a design concern, not merely a test execution activity.

---

## 26.7 Capability — DMAF-CAP-COV-005 — Exception Handling & Resolution Model

| Field                          | Description                                                                                                                                                                      |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-COV-005                                                                                                                                                                 |
| Capability Name                | Exception Handling & Resolution Model                                                                                                                                            |
| Practice Domain                | Coexistence & Validation                                                                                                                                                         |
| Business Objective             | Define how validation exceptions, reconciliation differences, data quality issues, defects, and accepted variances will be triaged, explained, resolved, escalated, or approved. |
| Lifecycle Stages               | Stage 7 — Coexistence & Validation; Stage 8 — Production Cutover                                                                                                                 |
| Inputs                         | Reconciliation results, validation defects, exception reports, business rules, data quality findings, acceptance thresholds, stakeholder decisions                               |
| Outputs                        | Exception handling model, triage process, exception log, resolution status, approved variance list, escalation path                                                              |
| Methods                        | Exception triage, root cause analysis, variance classification, issue escalation, approval workflow                                                                              |
| Assets                         | Exception log template, triage decision tree, approved variance register, escalation checklist                                                                                   |
| Owner                          | Test Manager / Data Architect                                                                                                                                                    |
| KPIs                           | Exception closure rate, exception aging, approved variance count, unresolved critical exception count, escalation turnaround time                                                |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                |
| Dependencies                   | Reconciliation Design, Validation Strategy Design, Factory Execution Governance, Executive Advisory                                                                              |
| Workbench Automation Potential | Exception classification, root cause suggestion, variance clustering, executive exception summary generation                                                                     |

### Notes

Not all differences indicate failure. This capability ensures exceptions are classified, explained, and governed rather than treated as undifferentiated defects.

---

## 26.8 Capability — DMAF-CAP-COV-006 — Cutover Readiness Assessment

| Field                          | Description                                                                                                                                                                                                |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-COV-006                                                                                                                                                                                           |
| Capability Name                | Cutover Readiness Assessment                                                                                                                                                                               |
| Practice Domain                | Coexistence & Validation                                                                                                                                                                                   |
| Business Objective             | Determine whether modernized workloads are ready to transition into production based on validation evidence, operational readiness, unresolved risks, stakeholder acceptance, and rollback considerations. |
| Lifecycle Stages               | Stage 7 — Coexistence & Validation; Stage 8 — Production Cutover                                                                                                                                           |
| Inputs                         | Validation evidence, reconciliation results, exception log, operational readiness checklist, support model, rollback plan, deployment plan, stakeholder approvals                                          |
| Outputs                        | Cutover readiness assessment, go/no-go recommendation, readiness gaps, cutover risks, approval record                                                                                                      |
| Methods                        | Readiness review, go/no-go assessment, risk-based cutover review, stakeholder sign-off review                                                                                                              |
| Assets                         | Cutover readiness checklist, go/no-go decision template, cutover risk summary, stakeholder approval template                                                                                               |
| Owner                          | Delivery Manager / Test Manager                                                                                                                                                                            |
| KPIs                           | Readiness gate pass rate, unresolved critical risks, open severity defects, approval completeness, rollback readiness                                                                                      |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                          |
| Dependencies                   | Validation Evidence Management, Exception Handling & Resolution Model, Production Readiness Support, Executive Advisory                                                                                    |
| Workbench Automation Potential | Cutover readiness scoring, go/no-go summary generation, open risk detection, approval checklist tracking                                                                                                   |

### Notes

Cutover readiness should be evidence-based. It should not be driven only by schedule pressure.

---

## 26.9 Capability — DMAF-CAP-COV-007 — Validation Evidence Management

| Field                          | Description                                                                                                                                           |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-COV-007                                                                                                                                      |
| Capability Name                | Validation Evidence Management                                                                                                                        |
| Practice Domain                | Coexistence & Validation                                                                                                                              |
| Business Objective             | Capture, organize, retain, and communicate the evidence required to prove that validation activities were performed and that outcomes are acceptable. |
| Lifecycle Stages               | Stage 5 — Reference Implementation / Pilot; Stage 7 — Coexistence & Validation; Stage 8 — Production Cutover                                          |
| Inputs                         | Test results, reconciliation reports, exception logs, approvals, screenshots, comparison outputs, control totals, business sign-offs                  |
| Outputs                        | Validation evidence repository, evidence index, validation summary, approval evidence, audit support package                                          |
| Methods                        | Evidence capture, evidence indexing, validation traceability, approval documentation                                                                  |
| Assets                         | Validation evidence register, evidence folder structure, validation summary template, sign-off evidence checklist                                     |
| Owner                          | Test Manager / Lead Business Analyst                                                                                                                  |
| KPIs                           | Evidence completeness, evidence traceability, missing approval count, audit readiness, validation package quality                                     |
| Maturity Target                | Level 3 — Managed                                                                                                                                     |
| Dependencies                   | Validation Strategy Design, Reconciliation Design, Cutover Readiness Assessment, Knowledge Management                                                 |
| Workbench Automation Potential | Evidence indexing, validation package generation, missing evidence detection, audit-ready summary drafting                                            |

### Notes

Validation evidence is what turns testing activity into trust. This capability ensures acceptance can be supported after the fact.

---

## 26.10 Capability — DMAF-CAP-COV-008 — Production Readiness Support

| Field                          | Description                                                                                                                                                                        |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-COV-008                                                                                                                                                                   |
| Capability Name                | Production Readiness Support                                                                                                                                                       |
| Practice Domain                | Coexistence & Validation                                                                                                                                                           |
| Business Objective             | Support the transition from validated workload to production operation by ensuring support, monitoring, incident response, runbooks, ownership, and operational handoff are ready. |
| Lifecycle Stages               | Stage 8 — Production Cutover; Stage 9 — Platform Operations, Adoption & Value Realization                                                                                          |
| Inputs                         | Cutover readiness assessment, operational runbooks, support model, monitoring requirements, incident response plan, ownership model, platform operations requirements              |
| Outputs                        | Production readiness checklist, operational handoff package, support readiness notes, runbook gaps, post-cutover validation needs                                                  |
| Methods                        | Production readiness review, operational handoff planning, support model review, post-cutover verification planning                                                                |
| Assets                         | Production readiness checklist, operational handoff template, runbook checklist, post-cutover validation template                                                                  |
| Owner                          | Delivery Manager / Platform Lead                                                                                                                                                   |
| KPIs                           | Production readiness completion, support ownership clarity, runbook completeness, post-cutover incident count, handoff acceptance                                                  |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                  |
| Dependencies                   | Cutover Readiness Assessment, Platform Operations, Adoption & Value Realization, Governance & Security                                                                             |
| Workbench Automation Potential | Production readiness checklist generation, handoff package drafting, runbook gap detection, post-cutover issue summary                                                             |

### Notes

This capability connects Coexistence & Validation to Platform Operations. Modernization is not complete until the workload can be operated reliably.

---

# 27. Coexistence & Validation Capability Map

| Capability ID    | Capability                            | Supports Trust | Supports Cutover | Supports Governance | Supports Workbench |
| ---------------- | ------------------------------------- | -------------- | ---------------- | ------------------- | ------------------ |
| DMAF-CAP-COV-001 | Coexistence Strategy Design           | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-002 | Parallel Run Planning                 | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-003 | Reconciliation Design                 | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-004 | Validation Strategy Design            | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-005 | Exception Handling & Resolution Model | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-006 | Cutover Readiness Assessment          | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-007 | Validation Evidence Management        | Yes            | Yes              | Yes                 | Yes                |
| DMAF-CAP-COV-008 | Production Readiness Support          | Yes            | Yes              | Yes                 | Yes                |

---

# 28. Coexistence & Validation Capability Governance

The Coexistence & Validation capabilities should be governed according to the following rules:

1. Do not treat coexistence as an informal transition state.
2. Do not proceed to validation without defined acceptance criteria.
3. Do not rely on parallel run assumptions without confirming environment and data feasibility.
4. Do not treat reconciliation exceptions as defects until they are triaged.
5. Do not approve cutover without validation evidence.
6. Do not mark validation complete without documenting unresolved exceptions and accepted variances.
7. Do not transition to production without operational handoff readiness.
8. Ensure validation evidence can support executive, business, technical, and audit review.

---

# 29. Future Enhancements

Future versions of this domain section may include:

* coexistence strategy template;
* coexistence decision tree;
* parallel run planning template;
* reconciliation design workbook;
* validation strategy template;
* exception handling model;
* cutover readiness checklist;
* validation evidence register;
* production readiness checklist;
* Workbench validation gap analyzer.

---

# 30. Practice Domain 6 — AI & Automation

## 30.1 Domain Purpose

The AI & Automation domain defines how automation and AI-assisted techniques accelerate modernization while preserving human governance, traceability, and accountability.

This domain ensures that DMAF uses AI and automation deliberately rather than opportunistically. It supports faster discovery, better interpretation of complex inputs, reusable prompt patterns, automated metadata extraction, recommendation drafting, testing support, artifact generation, and future Workbench services.

AI & Automation must remain governed by the DMAF principle:

```text id="uxk3zj"
AI Accelerates, People Govern
```

AI-generated outputs should support practitioner judgment. They should not replace architecture accountability, delivery governance, client validation, or executive decision-making.

---

## 30.2 Capability Summary

| Capability ID    | Capability Name                          | Primary Lifecycle Stages                     | Maturity Target   |
| ---------------- | ---------------------------------------- | -------------------------------------------- | ----------------- |
| DMAF-CAP-AIA-001 | AI-Assisted Discovery Interpretation     | Stage 2, Stage 3, Stage 4                    | Level 3 — Managed |
| DMAF-CAP-AIA-002 | Metadata Extraction Automation           | Stage 2, Stage 4, Stage 6                    | Level 3 — Managed |
| DMAF-CAP-AIA-003 | Code & Logic Interpretation Support      | Stage 2, Stage 5, Stage 6                    | Level 3 — Managed |
| DMAF-CAP-AIA-004 | Recommendation Drafting & Review Support | Stage 0, Stage 2, Stage 3, Stage 4           | Level 3 — Managed |
| DMAF-CAP-AIA-005 | Test Case & Validation Support           | Stage 5, Stage 6, Stage 7                    | Level 3 — Managed |
| DMAF-CAP-AIA-006 | Automated Artifact Generation            | Stage 0, Stage 2, Stage 3, Stage 4, Stage 10 | Level 3 — Managed |
| DMAF-CAP-AIA-007 | Automation Pattern Management            | Stage 4, Stage 6, Stage 10                   | Level 3 — Managed |
| DMAF-CAP-AIA-008 | AI Governance & Human Review Model       | All stages                                   | Level 3 — Managed |

---

## 30.3 Capability — DMAF-CAP-AIA-001 — AI-Assisted Discovery Interpretation

| Field                          | Description                                                                                                                                                                              |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-001                                                                                                                                                                         |
| Capability Name                | AI-Assisted Discovery Interpretation                                                                                                                                                     |
| Practice Domain                | AI & Automation                                                                                                                                                                          |
| Business Objective             | Use AI to help interpret discovery inputs, identify themes, extract modernization signals, summarize current-state evidence, and surface gaps or contradictions for practitioner review. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning                                                                             |
| Inputs                         | Discovery notes, inventories, diagrams, screenshots, application lists, workflow lists, interview notes, architecture documents, technical extracts                                      |
| Outputs                        | Discovery summaries, extracted themes, evidence gaps, contradiction notes, modernization signals, preliminary findings                                                                   |
| Methods                        | AI-assisted document review, evidence interpretation, theme extraction, contradiction detection, practitioner validation review                                                          |
| Assets                         | Discovery interpretation prompt library, evidence review checklist, AI-assisted discovery summary template, contradiction log                                                            |
| Owner                          | AI Enablement Lead / Lead Business Analyst                                                                                                                                               |
| KPIs                           | Discovery interpretation cycle time, number of gaps detected, reviewer acceptance rate, number of AI outputs requiring correction                                                        |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                        |
| Dependencies                   | Discovery Intake & Evidence Management, Discovery Findings Synthesis, Knowledge Management                                                                                               |
| Workbench Automation Potential | Discovery input interpretation agent, evidence gap analyzer, contradiction detector, discovery summary generator                                                                         |

### Notes

This capability helps practitioners make sense of messy engagement inputs. AI should identify possible patterns, but findings must be reviewed and confirmed by accountable practitioners.

---

## 30.4 Capability — DMAF-CAP-AIA-002 — Metadata Extraction Automation

| Field                          | Description                                                                                                                                                                      |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-002                                                                                                                                                                 |
| Capability Name                | Metadata Extraction Automation                                                                                                                                                   |
| Practice Domain                | AI & Automation                                                                                                                                                                  |
| Business Objective             | Automate extraction of useful metadata from source files, inventories, platform exports, workflow lists, scripts, and technical documents to accelerate assessment and planning. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution                                                                    |
| Inputs                         | Source system exports, ETL metadata, workflow files, job schedules, table lists, file inventories, code repositories, configuration files                                        |
| Outputs                        | Extracted metadata, normalized inventory fields, source-to-target candidates, lineage hints, platform object lists                                                               |
| Methods                        | Metadata parsing, automated extraction, normalization, field mapping, extraction quality review                                                                                  |
| Assets                         | Metadata extraction script, metadata mapping template, extraction quality checklist, normalized inventory model                                                                  |
| Owner                          | AI Enablement Lead / Solution Architect                                                                                                                                          |
| KPIs                           | Extraction accuracy, metadata coverage, manual effort reduction, unresolved parsing errors, reviewer correction rate                                                             |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                |
| Dependencies                   | Application & Workflow Inventory Analysis, Data Source & Dependency Mapping, Automation                                                                                          |
| Workbench Automation Potential | Metadata ingestion service, inventory auto-parser, lineage hint generator, extraction quality dashboard                                                                          |

### Notes

This capability is especially important for large migration programs where manual inventory creation is slow, inconsistent, and error-prone.

---

## 30.5 Capability — DMAF-CAP-AIA-003 — Code & Logic Interpretation Support

| Field                          | Description                                                                                                                                                                                                       |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-003                                                                                                                                                                                                  |
| Capability Name                | Code & Logic Interpretation Support                                                                                                                                                                               |
| Practice Domain                | AI & Automation                                                                                                                                                                                                   |
| Business Objective             | Use AI-assisted techniques to help interpret legacy code, ETL logic, transformation rules, scheduling logic, SQL, scripts, and business rules so modernization teams can understand and validate migration scope. |
| Lifecycle Stages               | Stage 2 — Discovery & Assessment; Stage 5 — Reference Implementation / Pilot; Stage 6 — Migration Factory Execution                                                                                               |
| Inputs                         | SQL scripts, ETL mappings, workflow definitions, code snippets, scheduling rules, transformation logic, business rule documentation                                                                               |
| Outputs                        | Logic summaries, transformation descriptions, business rule candidates, complexity indicators, conversion notes, review questions                                                                                 |
| Methods                        | Code interpretation, transformation logic summarization, business rule extraction, SME review, complexity annotation                                                                                              |
| Assets                         | Code interpretation prompt library, transformation summary template, business rule extraction worksheet, SME review checklist                                                                                     |
| Owner                          | Solution Architect / AI Enablement Lead                                                                                                                                                                           |
| KPIs                           | Logic interpretation accuracy, SME correction rate, number of business rules extracted, reduction in manual code review time                                                                                      |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                                 |
| Dependencies                   | Modernization Complexity Scoring, Migration Pattern Management, Validation Strategy Design                                                                                                                        |
| Workbench Automation Potential | Code interpretation agent, transformation rule summarizer, business rule extractor, complexity annotation support                                                                                                 |

### Notes

This capability supports understanding; it should not be treated as automatic code conversion. AI interpretation must be reviewed by technical SMEs and validated against actual system behavior.

---

## 30.6 Capability — DMAF-CAP-AIA-004 — Recommendation Drafting & Review Support

| Field                          | Description                                                                                                                                                                |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-004                                                                                                                                                           |
| Capability Name                | Recommendation Drafting & Review Support                                                                                                                                   |
| Practice Domain                | AI & Automation                                                                                                                                                            |
| Business Objective             | Use AI to draft modernization recommendations, options, implications, risks, and next steps based on governed DMAF methods and reviewed evidence.                          |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning |
| Inputs                         | Discovery findings, business value themes, architecture notes, capability mappings, risks, constraints, complexity scores, roadmap themes                                  |
| Outputs                        | Draft recommendations, option summaries, implication notes, risk-based recommendations, next-step recommendations                                                          |
| Methods                        | Recommendation drafting, evidence-to-recommendation mapping, option framing, human review, recommendation traceability review                                              |
| Assets                         | Recommendation prompt library, recommendation review checklist, evidence-to-recommendation matrix, executive recommendation template                                       |
| Owner                          | Engagement Lead / Solution Architect                                                                                                                                       |
| KPIs                           | Recommendation traceability, reviewer acceptance rate, number of unsupported claims removed, recommendation cycle time                                                     |
| Maturity Target                | Level 3 — Managed                                                                                                                                                          |
| Dependencies                   | Discovery Findings Synthesis, Target-State Architecture Design, Strategic Roadmap Framing, Executive Advisory                                                              |
| Workbench Automation Potential | Recommendation generator, evidence traceability mapper, option comparison generator, unsupported-claim detector                                                            |

### Notes

This capability helps accelerate consulting output, but recommendations must remain traceable to evidence, framework principles, and practitioner judgment.

---

## 30.7 Capability — DMAF-CAP-AIA-005 — Test Case & Validation Support

| Field                          | Description                                                                                                                                                      |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-005                                                                                                                                                 |
| Capability Name                | Test Case & Validation Support                                                                                                                                   |
| Practice Domain                | AI & Automation                                                                                                                                                  |
| Business Objective             | Use automation and AI-assisted techniques to help generate validation ideas, test cases, reconciliation checks, exception categories, and evidence requirements. |
| Lifecycle Stages               | Stage 5 — Reference Implementation / Pilot; Stage 6 — Migration Factory Execution; Stage 7 — Coexistence & Validation                                            |
| Inputs                         | Business rules, transformation logic, validation strategy, reconciliation approach, source-target mappings, acceptance criteria, risk profile                    |
| Outputs                        | Draft test cases, validation scenarios, reconciliation check suggestions, evidence requirements, exception categories                                            |
| Methods                        | Test scenario generation, validation rule extraction, reconciliation check design, reviewer validation                                                           |
| Assets                         | Test case generation prompt library, validation scenario template, reconciliation checklist, evidence requirement checklist                                      |
| Owner                          | Test Manager / Data Architect                                                                                                                                    |
| KPIs                           | Test coverage improvement, reviewer acceptance rate, number of validation gaps detected, defect leakage reduction                                                |
| Maturity Target                | Level 3 — Managed                                                                                                                                                |
| Dependencies                   | Validation Strategy Design, Reconciliation Design, Code & Logic Interpretation Support, Exception Handling & Resolution Model                                    |
| Workbench Automation Potential | Test case generator, validation coverage analyzer, reconciliation check recommender, evidence gap detector                                                       |

### Notes

AI-generated test cases are suggestions. They must be reviewed against business rules, data behavior, acceptance criteria, and risk.

---

## 30.8 Capability — DMAF-CAP-AIA-006 — Automated Artifact Generation

| Field                          | Description                                                                                                                                                                                                                                 |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-006                                                                                                                                                                                                                            |
| Capability Name                | Automated Artifact Generation                                                                                                                                                                                                               |
| Practice Domain                | AI & Automation                                                                                                                                                                                                                             |
| Business Objective             | Generate first-draft DMAF artifacts such as summaries, templates, diagrams, assessments, recommendations, checklists, and executive-ready content from structured or semi-structured inputs.                                                |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Approved DMAF templates, discovery evidence, architecture notes, inventories, roadmap themes, risk registers, value drivers, capability metadata                                                                                            |
| Outputs                        | Draft artifacts, executive summaries, discovery reports, architecture summaries, roadmap views, checklists, recommendation drafts                                                                                                           |
| Methods                        | Template-driven generation, prompt-based drafting, artifact review workflow, metadata-driven output creation                                                                                                                                |
| Assets                         | Artifact generation prompt library, artifact review checklist, template catalogue, output quality checklist                                                                                                                                 |
| Owner                          | Practice Lead / AI Enablement Lead                                                                                                                                                                                                          |
| KPIs                           | Artifact drafting cycle time, reviewer acceptance rate, reuse rate, number of generated artifacts requiring major rework                                                                                                                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                                                           |
| Dependencies                   | Knowledge Management, Reusable Accelerators, Executive Advisory, Modernization Intelligence Workbench                                                                                                                                       |
| Workbench Automation Potential | Artifact generator, deck outline generator, diagram draft generator, executive summary generator, asset packaging service                                                                                                                   |

### Notes

This capability should accelerate production of reusable and client-facing artifacts. It must not bypass review, sanitization, quality control, or governance.

---

## 30.9 Capability — DMAF-CAP-AIA-007 — Automation Pattern Management

| Field                          | Description                                                                                                                                                                                    |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-007                                                                                                                                                                               |
| Capability Name                | Automation Pattern Management                                                                                                                                                                  |
| Practice Domain                | AI & Automation                                                                                                                                                                                |
| Business Objective             | Identify, govern, reuse, and improve automation patterns that reduce manual effort and improve consistency across discovery, planning, migration, validation, reporting, and asset management. |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution; Stage 10 — Continuous Optimization & Modernization Intelligence                                                   |
| Inputs                         | Repeated manual tasks, delivery pain points, reusable scripts, prompt patterns, workflow candidates, lessons learned, Workbench backlog items                                                  |
| Outputs                        | Automation pattern catalogue, automation candidates, reusable scripts, workflow designs, improvement backlog                                                                                   |
| Methods                        | Automation opportunity identification, pattern documentation, reuse review, automation governance, improvement prioritization                                                                  |
| Assets                         | Automation pattern catalogue, automation opportunity template, script inventory, workflow design template                                                                                      |
| Owner                          | AI Enablement Lead / Practice Lead                                                                                                                                                             |
| KPIs                           | Automation reuse rate, manual effort reduction, number of governed automation patterns, automation defect or exception rate                                                                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                              |
| Dependencies                   | Migration Pattern Management, Knowledge Management, Reusable Accelerators, Modernization Intelligence Workbench                                                                                |
| Workbench Automation Potential | Automation pattern recommender, script catalogue, workflow automation service, reuse tracking dashboard                                                                                        |

### Notes

Automation patterns should be treated as governed assets. Scripts, prompts, and workflows should be reusable, explainable, and maintained.

---

## 30.10 Capability — DMAF-CAP-AIA-008 — AI Governance & Human Review Model

| Field                          | Description                                                                                                                                              |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-AIA-008                                                                                                                                         |
| Capability Name                | AI Governance & Human Review Model                                                                                                                       |
| Practice Domain                | AI & Automation                                                                                                                                          |
| Business Objective             | Define how AI-assisted outputs are reviewed, governed, approved, corrected, rejected, or escalated so DMAF maintains trust, quality, and accountability. |
| Lifecycle Stages               | All stages                                                                                                                                               |
| Inputs                         | AI-generated outputs, prompts, source evidence, review criteria, quality standards, approval rules, risk considerations                                  |
| Outputs                        | AI review model, approval criteria, review log, exception handling rules, governance checklist, prompt usage guidance                                    |
| Methods                        | Human-in-the-loop review, AI output validation, prompt review, evidence checking, quality gate review                                                    |
| Assets                         | AI governance checklist, human review checklist, AI output review log, prompt quality standard, AI usage policy template                                 |
| Owner                          | Practice Lead / AI Enablement Lead                                                                                                                       |
| KPIs                           | AI output acceptance rate, number of unsupported AI claims detected, review completion rate, prompt reuse quality, AI-related quality issues             |
| Maturity Target                | Level 3 — Managed                                                                                                                                        |
| Dependencies                   | Risk & Compliance, Governance & Security, Knowledge Management, Executive Advisory                                                                       |
| Workbench Automation Potential | AI review workflow, unsupported-claim detector, citation and evidence checker, prompt governance dashboard                                               |

### Notes

This capability governs the use of AI across DMAF. It is required because AI-assisted modernization outputs can accelerate work but also introduce risk if unsupported, unreviewed, or disconnected from evidence.

---

# 31. AI & Automation Capability Map

| Capability ID    | Capability                               | Supports Acceleration | Supports Governance | Supports Quality | Supports Workbench |
| ---------------- | ---------------------------------------- | --------------------- | ------------------- | ---------------- | ------------------ |
| DMAF-CAP-AIA-001 | AI-Assisted Discovery Interpretation     | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-002 | Metadata Extraction Automation           | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-003 | Code & Logic Interpretation Support      | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-004 | Recommendation Drafting & Review Support | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-005 | Test Case & Validation Support           | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-006 | Automated Artifact Generation            | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-007 | Automation Pattern Management            | Yes                   | Yes                 | Yes              | Yes                |
| DMAF-CAP-AIA-008 | AI Governance & Human Review Model       | Yes                   | Yes                 | Yes              | Yes                |

---

# 32. AI & Automation Capability Governance

The AI & Automation capabilities should be governed according to the following rules:

1. Do not treat AI-generated outputs as approved without human review.
2. Do not use AI to create recommendations that cannot be traced to evidence.
3. Do not treat code interpretation as automatic code conversion.
4. Do not use automation patterns that are not documented, reviewable, or reusable.
5. Do not allow AI-generated artifacts to bypass quality gates.
6. Do not use AI outputs in executive-facing materials without practitioner validation.
7. Do not automate a capability before the underlying method is understood.
8. Ensure prompts, scripts, agents, and generated artifacts remain aligned to DMAF taxonomy, governance, and traceability standards.

---

# 33. Future Enhancements

Future versions of this domain section may include:

* AI-assisted discovery prompt library;
* metadata extraction script catalogue;
* code interpretation prompt library;
* recommendation drafting prompt library;
* test case generation pattern;
* artifact generation workflow;
* AI governance checklist;
* prompt quality standard;
* Workbench AI agent catalogue;
* human review workflow.

---

# 34. Practice Domain 7 — Executive Advisory

## 34.1 Domain Purpose

The Executive Advisory domain defines how modernization is communicated, positioned, governed, and made decision-ready for senior stakeholders.

This domain ensures that Databricks-led modernization can be understood by executives who may not be involved in technical implementation details but are accountable for investment decisions, risk acceptance, operating model change, business value, and transformation outcomes.

Executive Advisory is critical because modernization programs often fail when the technical approach is sound but the executive story is unclear.

---

## 34.2 Capability Summary

| Capability ID    | Capability Name                         | Primary Lifecycle Stages                    | Maturity Target   |
| ---------------- | --------------------------------------- | ------------------------------------------- | ----------------- |
| DMAF-CAP-EXA-001 | Executive Narrative Development         | Stage 0, Stage 1, Stage 3                   | Level 3 — Managed |
| DMAF-CAP-EXA-002 | Advisory Workshop Facilitation          | Stage 0, Stage 1, Stage 2, Stage 3          | Level 3 — Managed |
| DMAF-CAP-EXA-003 | Decision Framing & Options Analysis     | Stage 1, Stage 3, Stage 4, Stage 7          | Level 3 — Managed |
| DMAF-CAP-EXA-004 | Modernization Roadmap Storytelling      | Stage 1, Stage 3, Stage 4, Stage 10         | Level 3 — Managed |
| DMAF-CAP-EXA-005 | Proposal Positioning & Pursuit Support  | Stage 0, Stage 1                            | Level 3 — Managed |
| DMAF-CAP-EXA-006 | Executive Visual Design                 | Stage 0, Stage 1, Stage 3, Stage 4          | Level 3 — Managed |
| DMAF-CAP-EXA-007 | Transformation Value Communication      | Stage 1, Stage 9, Stage 10                  | Level 3 — Managed |
| DMAF-CAP-EXA-008 | Executive Governance & Steering Support | Stage 4, Stage 6, Stage 7, Stage 8, Stage 9 | Level 3 — Managed |

---

## 34.3 Capability — DMAF-CAP-EXA-001 — Executive Narrative Development

| Field                          | Description                                                                                                                                                                                          |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-001                                                                                                                                                                                     |
| Capability Name                | Executive Narrative Development                                                                                                                                                                      |
| Practice Domain                | Executive Advisory                                                                                                                                                                                   |
| Business Objective             | Create a clear executive-level modernization story that explains why modernization is needed, why Databricks is relevant, what value is expected, what risks exist, and what decisions are required. |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture                                                              |
| Inputs                         | Business drivers, modernization hypothesis, value themes, current-state pain points, architecture direction, risks, constraints, sponsor priorities                                                  |
| Outputs                        | Executive narrative, modernization storyline, advisory summary, transformation positioning message                                                                                                   |
| Methods                        | Executive story framing, value narrative development, issue-to-outcome mapping, modernization message structuring                                                                                    |
| Assets                         | Executive narrative template, modernization story arc template, advisory summary template, value message library                                                                                     |
| Owner                          | Engagement Lead / Practice Lead                                                                                                                                                                      |
| KPIs                           | Executive clarity, sponsor alignment, narrative reuse rate, stakeholder acceptance of modernization rationale                                                                                        |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                    |
| Dependencies                   | Business Value Framing, Modernization Value Mapping, Target-State Architecture Design                                                                                                                |
| Workbench Automation Potential | Executive narrative generator, value theme extractor, modernization storyline drafter, message consistency checker                                                                                   |

### Notes

This capability supports the DMAF principle **Executive Storytelling Matters**. It helps make complex modernization programs understandable and decision-ready.

---

## 34.4 Capability — DMAF-CAP-EXA-002 — Advisory Workshop Facilitation

| Field                          | Description                                                                                                                                                               |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-002                                                                                                                                                          |
| Capability Name                | Advisory Workshop Facilitation                                                                                                                                            |
| Practice Domain                | Executive Advisory                                                                                                                                                        |
| Business Objective             | Facilitate structured advisory sessions that align stakeholders, clarify modernization objectives, surface risks, confirm priorities, and guide decision-making.          |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value; Stage 2 — Discovery & Assessment; Stage 3 — Modernization Architecture |
| Inputs                         | Workshop objectives, stakeholder list, discovery questions, value themes, architecture topics, decision points, risks, constraints                                        |
| Outputs                        | Workshop agenda, facilitated discussion notes, decisions, open questions, alignment summary, recommended next steps                                                       |
| Methods                        | Advisory workshop design, stakeholder facilitation, decision capture, issue framing, alignment review                                                                     |
| Assets                         | Advisory workshop agenda template, facilitation guide, decision capture template, workshop summary template                                                               |
| Owner                          | Engagement Lead / Practice Lead                                                                                                                                           |
| KPIs                           | Workshop objective completion, decision capture quality, stakeholder participation, open question closure rate                                                            |
| Maturity Target                | Level 3 — Managed                                                                                                                                                         |
| Dependencies                   | Executive Sponsor Alignment, Discovery Intake & Evidence Management, Decision Framing & Options Analysis                                                                  |
| Workbench Automation Potential | Workshop agenda generator, stakeholder question generator, decision summary drafting, action item extraction                                                              |

### Notes

This capability helps convert discussion into structured modernization evidence, decisions, and next steps.

---

## 34.5 Capability — DMAF-CAP-EXA-003 — Decision Framing & Options Analysis

| Field                          | Description                                                                                                                                         |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-003                                                                                                                                    |
| Capability Name                | Decision Framing & Options Analysis                                                                                                                 |
| Practice Domain                | Executive Advisory                                                                                                                                  |
| Business Objective             | Present modernization options, trade-offs, risks, benefits, constraints, and recommendations in a form that supports executive decision-making.     |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 7 — Coexistence & Validation |
| Inputs                         | Discovery findings, architecture options, migration scenarios, coexistence constraints, risks, investment considerations, stakeholder concerns      |
| Outputs                        | Decision brief, options analysis, trade-off summary, recommendation, decision log                                                                   |
| Methods                        | Options analysis, decision tree framing, risk-benefit analysis, trade-off facilitation, recommendation review                                       |
| Assets                         | Decision brief template, options analysis matrix, trade-off summary template, executive decision log                                                |
| Owner                          | Engagement Lead / Solution Architect                                                                                                                |
| KPIs                           | Decision turnaround time, decision traceability, number of unresolved decision points, recommendation acceptance rate                               |
| Maturity Target                | Level 3 — Managed                                                                                                                                   |
| Dependencies                   | Architecture Decision Management, Risk & Constraint Identification, Investment Case Development                                                     |
| Workbench Automation Potential | Options comparison generator, trade-off summarizer, decision brief drafter, unresolved decision detector                                            |

### Notes

This capability ensures executives are not asked to approve vague recommendations. Decisions should include context, options, implications, and risks.

---

## 34.6 Capability — DMAF-CAP-EXA-004 — Modernization Roadmap Storytelling

| Field                          | Description                                                                                                                                                                      |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-004                                                                                                                                                                 |
| Capability Name                | Modernization Roadmap Storytelling                                                                                                                                               |
| Practice Domain                | Executive Advisory                                                                                                                                                               |
| Business Objective             | Communicate the modernization journey as a clear sequence of outcomes, phases, decisions, risks, and value realization milestones.                                               |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Strategic roadmap, migration wave plan, architecture roadmap, value map, dependencies, milestones, delivery constraints                                                          |
| Outputs                        | Executive roadmap view, transformation journey story, milestone narrative, roadmap briefing                                                                                      |
| Methods                        | Roadmap storytelling, milestone framing, phase narrative development, business outcome sequencing                                                                                |
| Assets                         | Executive roadmap template, modernization journey diagram, milestone narrative template, roadmap briefing deck                                                                   |
| Owner                          | Engagement Lead / Solution Architect                                                                                                                                             |
| KPIs                           | Roadmap clarity, stakeholder acceptance, decision point visibility, alignment between roadmap and value drivers                                                                  |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                |
| Dependencies                   | Strategic Roadmap Framing, Migration Wave Planning, Modernization Value Mapping                                                                                                  |
| Workbench Automation Potential | Roadmap narrative generator, milestone summarizer, roadmap-to-value mapper, executive journey visual generator                                                                   |

### Notes

This capability translates delivery sequence into executive meaning. It should explain not only what happens when, but why the sequence matters.

---

## 34.7 Capability — DMAF-CAP-EXA-005 — Proposal Positioning & Pursuit Support

| Field                          | Description                                                                                                                                                                |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-005                                                                                                                                                           |
| Capability Name                | Proposal Positioning & Pursuit Support                                                                                                                                     |
| Practice Domain                | Executive Advisory                                                                                                                                                         |
| Business Objective             | Position DMAF capabilities, Databricks modernization value, delivery approach, and advisory differentiators in pursuit and proposal materials.                             |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value                                                                          |
| Inputs                         | Opportunity qualification notes, business drivers, current-state pain points, client priorities, relevant DMAF capabilities, reference architectures, delivery assumptions |
| Outputs                        | Proposal narrative, pursuit strategy, scope positioning, value proposition, differentiator messaging                                                                       |
| Methods                        | Pursuit positioning, proposal narrative development, value proposition framing, scope shaping, objection handling                                                          |
| Assets                         | Proposal accelerator, pursuit qualification checklist, positioning statement library, modernization proposal outline                                                       |
| Owner                          | Account Executive / Engagement Lead                                                                                                                                        |
| KPIs                           | Proposal quality, pursuit conversion support, narrative reuse rate, alignment to client business drivers                                                                   |
| Maturity Target                | Level 3 — Managed                                                                                                                                                          |
| Dependencies                   | Modernization Opportunity Qualification, Business Value Framing, Executive Narrative Development                                                                           |
| Workbench Automation Potential | Proposal outline generator, pursuit messaging assistant, value proposition drafter, differentiator mapper                                                                  |

### Notes

This capability turns DMAF into reusable go-to-market intellectual property. It supports sales and advisory motions without reducing DMAF to a generic proposal template.

---

## 34.8 Capability — DMAF-CAP-EXA-006 — Executive Visual Design

| Field                          | Description                                                                                                                                                                   |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-006                                                                                                                                                              |
| Capability Name                | Executive Visual Design                                                                                                                                                       |
| Practice Domain                | Executive Advisory                                                                                                                                                            |
| Business Objective             | Create simple, high-impact visuals that help executives understand modernization strategy, architecture, roadmap, risk, value, and decisions.                                 |
| Lifecycle Stages               | Stage 0 — Opportunity Qualification & Modernization Strategy; Stage 1 — Strategy & Business Value; Stage 3 — Modernization Architecture; Stage 4 — Migration Factory Planning |
| Inputs                         | Executive narrative, roadmap, architecture direction, capability model, value map, risks, decision points                                                                     |
| Outputs                        | Executive diagrams, one-page visuals, roadmap visuals, before/after views, decision visuals, presentation graphics                                                            |
| Methods                        | Executive visual storytelling, abstraction, before/after framing, roadmap visualization, decision visualization                                                               |
| Assets                         | Executive one-page template, before/after modernization diagram, roadmap visual template, decision visual template                                                            |
| Owner                          | Engagement Lead / Practice Lead                                                                                                                                               |
| KPIs                           | Visual clarity, reuse rate, executive comprehension, reduction in explanation time                                                                                            |
| Maturity Target                | Level 3 — Managed                                                                                                                                                             |
| Dependencies                   | Executive Narrative Development, Modernization Roadmap Storytelling, Target-State Architecture Design                                                                         |
| Workbench Automation Potential | Executive visual generator, diagram draft assistant, visual consistency checker, one-page artifact generator                                                                  |

### Notes

This capability is important because senior stakeholders often understand modernization faster through visuals than through long technical documents.

---

## 34.9 Capability — DMAF-CAP-EXA-007 — Transformation Value Communication

| Field                          | Description                                                                                                                                                             |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-007                                                                                                                                                        |
| Capability Name                | Transformation Value Communication                                                                                                                                      |
| Practice Domain                | Executive Advisory                                                                                                                                                      |
| Business Objective             | Communicate modernization value throughout the journey so stakeholders understand progress, outcomes, risks reduced, capabilities enabled, and platform value realized. |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence       |
| Inputs                         | Value drivers, success metrics, migration progress, adoption metrics, platform KPIs, business outcomes, lessons learned                                                 |
| Outputs                        | Value realization narrative, transformation progress summary, executive value update, outcome communication                                                             |
| Methods                        | Value communication, outcome storytelling, KPI interpretation, executive progress reporting                                                                             |
| Assets                         | Value realization summary template, executive value update, outcome communication template, KPI interpretation guide                                                    |
| Owner                          | Engagement Lead / Platform Lead                                                                                                                                         |
| KPIs                           | Value realization visibility, executive confidence, metric-to-value traceability, stakeholder understanding of outcomes                                                 |
| Maturity Target                | Level 3 — Managed                                                                                                                                                       |
| Dependencies                   | Success Metric Definition, Modernization Value Mapping, Platform Operations, Adoption & Value Realization                                                               |
| Workbench Automation Potential | Value update generator, KPI-to-narrative converter, outcome summary drafter, benefit realization dashboarding                                                           |

### Notes

This capability ensures modernization value remains visible after the initial strategy and proposal stages. It links delivery progress to business and platform outcomes.

---

## 34.10 Capability — DMAF-CAP-EXA-008 — Executive Governance & Steering Support

| Field                          | Description                                                                                                                                                                                                |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-EXA-008                                                                                                                                                                                           |
| Capability Name                | Executive Governance & Steering Support                                                                                                                                                                    |
| Practice Domain                | Executive Advisory                                                                                                                                                                                         |
| Business Objective             | Support executive steering, governance, escalation, and decision-making during modernization delivery, validation, cutover, and adoption.                                                                  |
| Lifecycle Stages               | Stage 4 — Migration Factory Planning; Stage 6 — Migration Factory Execution; Stage 7 — Coexistence & Validation; Stage 8 — Production Cutover; Stage 9 — Platform Operations, Adoption & Value Realization |
| Inputs                         | Delivery status, risks, issues, decisions, validation status, cutover readiness, value metrics, adoption status                                                                                            |
| Outputs                        | Steering committee briefing, executive status summary, escalation summary, decision log, risk and issue narrative                                                                                          |
| Methods                        | Executive steering support, status synthesis, escalation framing, decision facilitation, governance cadence management                                                                                     |
| Assets                         | Steering committee deck template, executive status report, escalation summary template, decision log template                                                                                              |
| Owner                          | Engagement Lead / Delivery Manager                                                                                                                                                                         |
| KPIs                           | Executive decision turnaround, escalation closure rate, steering cadence adherence, status clarity, unresolved executive risks                                                                             |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                          |
| Dependencies                   | Factory Execution Governance, Migration Metrics & Reporting, Cutover Readiness Assessment                                                                                                                  |
| Workbench Automation Potential | Executive status generator, risk and issue summarizer, decision log extraction, steering deck generator                                                                                                    |

### Notes

This capability ensures executives remain engaged with the decisions and risks that matter most without being overwhelmed by delivery detail.

---

# 35. Executive Advisory Capability Map

| Capability ID    | Capability                              | Supports Executive Clarity | Supports Decisions | Supports Value | Supports Workbench |
| ---------------- | --------------------------------------- | -------------------------- | ------------------ | -------------- | ------------------ |
| DMAF-CAP-EXA-001 | Executive Narrative Development         | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-002 | Advisory Workshop Facilitation          | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-003 | Decision Framing & Options Analysis     | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-004 | Modernization Roadmap Storytelling      | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-005 | Proposal Positioning & Pursuit Support  | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-006 | Executive Visual Design                 | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-007 | Transformation Value Communication      | Yes                        | Yes                | Yes            | Yes                |
| DMAF-CAP-EXA-008 | Executive Governance & Steering Support | Yes                        | Yes                | Yes            | Yes                |

---

# 36. Executive Advisory Capability Governance

The Executive Advisory capabilities should be governed according to the following rules:

1. Do not create executive narratives that are disconnected from evidence.
2. Do not reduce modernization to technical implementation language.
3. Do not present decisions without options, implications, and risks.
4. Do not create roadmap visuals that imply certainty where assumptions remain open.
5. Do not use proposal language that conflicts with approved DMAF terminology.
6. Do not present value realization claims without supporting metrics or rationale.
7. Do not overwhelm executive stakeholders with delivery detail that obscures decisions.
8. Ensure executive-facing outputs are clear, traceable, and aligned to business value.

---

# 37. Future Enhancements

Future versions of this domain section may include:

* executive narrative template;
* advisory workshop facilitation guide;
* decision brief template;
* roadmap storytelling deck;
* proposal accelerator;
* executive one-page visual library;
* value realization communication template;
* steering committee deck template;
* Workbench executive summary generator.

---

# 38. Practice Domain 8 — Platform Operations, Adoption & Value Realization

## 38.1 Domain Purpose

The Platform Operations, Adoption & Value Realization domain defines how the modernized Databricks platform is operated, adopted, governed, optimized, and measured after migration.

This domain ensures that modernization does not end at technical cutover. A migration is only successful when the modernized platform becomes a trusted, supportable, adopted, cost-aware, and value-producing operating environment.

This domain connects production transition, operating model, enablement, FinOps, governance maturity, platform KPIs, value realization, and continuous optimization.

---

## 38.2 Capability Summary

| Capability ID    | Capability Name                            | Primary Lifecycle Stages            | Maturity Target   |
| ---------------- | ------------------------------------------ | ----------------------------------- | ----------------- |
| DMAF-CAP-POV-001 | Platform Operating Model Design            | Stage 8, Stage 9                    | Level 3 — Managed |
| DMAF-CAP-POV-002 | Adoption & Enablement Planning             | Stage 8, Stage 9, Stage 10          | Level 3 — Managed |
| DMAF-CAP-POV-003 | Support Model Transition                   | Stage 8, Stage 9                    | Level 3 — Managed |
| DMAF-CAP-POV-004 | Runbook & Operational Readiness Management | Stage 8, Stage 9                    | Level 3 — Managed |
| DMAF-CAP-POV-005 | FinOps & Consumption Management            | Stage 3, Stage 6, Stage 9, Stage 10 | Level 3 — Managed |
| DMAF-CAP-POV-006 | Platform KPI & Value Realization Tracking  | Stage 1, Stage 9, Stage 10          | Level 3 — Managed |
| DMAF-CAP-POV-007 | Governance Maturity Improvement            | Stage 3, Stage 9, Stage 10          | Level 3 — Managed |
| DMAF-CAP-POV-008 | Continuous Optimization Management         | Stage 9, Stage 10                   | Level 3 — Managed |

---

## 38.3 Capability — DMAF-CAP-POV-001 — Platform Operating Model Design

| Field                          | Description                                                                                                                                                   |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-001                                                                                                                                              |
| Capability Name                | Platform Operating Model Design                                                                                                                               |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                             |
| Business Objective             | Define how the modernized Databricks platform will be owned, governed, supported, funded, operated, improved, and adopted after migration.                    |
| Lifecycle Stages               | Stage 8 — Production Cutover; Stage 9 — Platform Operations, Adoption & Value Realization                                                                     |
| Inputs                         | Target-state architecture, production readiness plan, support requirements, governance requirements, ownership model, platform team structure, adoption goals |
| Outputs                        | Platform operating model, role model, governance cadence, ownership map, operating principles, platform management responsibilities                           |
| Methods                        | Operating model design, role and responsibility mapping, governance cadence design, platform ownership review                                                 |
| Assets                         | Platform operating model template, RACI template, governance cadence template, ownership model worksheet                                                      |
| Owner                          | Platform Lead / Customer Success Lead                                                                                                                         |
| KPIs                           | Ownership clarity, operating model approval, governance cadence adoption, unresolved role ambiguity count                                                     |
| Maturity Target                | Level 3 — Managed                                                                                                                                             |
| Dependencies                   | Target-State Architecture Design, Production Readiness Support, Governance & Security, Executive Advisory                                                     |
| Workbench Automation Potential | Operating model draft generator, RACI assistant, governance cadence recommender, ownership gap detector                                                       |

### Notes

This capability prevents modernization from ending with a technical deployment but no clear operating model. It defines how the platform will live after migration.

---

## 38.4 Capability — DMAF-CAP-POV-002 — Adoption & Enablement Planning

| Field                          | Description                                                                                                                                                |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-002                                                                                                                                           |
| Capability Name                | Adoption & Enablement Planning                                                                                                                             |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                          |
| Business Objective             | Plan how users, engineers, analysts, platform teams, governance stakeholders, and business teams will adopt and effectively use the modernized platform.   |
| Lifecycle Stages               | Stage 8 — Production Cutover; Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Stakeholder groups, platform capabilities, target operating model, training needs, adoption barriers, role expectations, onboarding requirements           |
| Outputs                        | Adoption plan, enablement roadmap, training themes, onboarding approach, stakeholder adoption risks                                                        |
| Methods                        | Adoption planning, stakeholder segmentation, enablement needs assessment, onboarding journey design                                                        |
| Assets                         | Adoption plan template, enablement roadmap template, stakeholder adoption matrix, onboarding checklist                                                     |
| Owner                          | Platform Lead / Customer Success Lead                                                                                                                      |
| KPIs                           | Adoption rate, enablement completion, active platform user growth, stakeholder satisfaction, onboarding cycle time                                         |
| Maturity Target                | Level 3 — Managed                                                                                                                                          |
| Dependencies                   | Platform Operating Model Design, Executive Advisory, Knowledge Management, Reusable Accelerators                                                           |
| Workbench Automation Potential | Enablement plan generator, stakeholder adoption tracker, onboarding checklist generation, adoption risk summarization                                      |

### Notes

This capability treats adoption as planned work, not an assumption. The modernized platform only creates value when teams know how to use it effectively.

---

## 38.5 Capability — DMAF-CAP-POV-003 — Support Model Transition

| Field                          | Description                                                                                                                                                            |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-003                                                                                                                                                       |
| Capability Name                | Support Model Transition                                                                                                                                               |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                                      |
| Business Objective             | Define how support responsibilities, incident handling, escalation paths, service expectations, and ownership move from project delivery into steady-state operations. |
| Lifecycle Stages               | Stage 8 — Production Cutover; Stage 9 — Platform Operations, Adoption & Value Realization                                                                              |
| Inputs                         | Production readiness assessment, support requirements, operating model, incident response expectations, team roles, service levels, known risks                        |
| Outputs                        | Support model, escalation path, incident response model, handoff plan, service responsibility map                                                                      |
| Methods                        | Support transition planning, incident model design, escalation path mapping, operational handoff review                                                                |
| Assets                         | Support model template, escalation matrix, handoff checklist, incident response template                                                                               |
| Owner                          | Platform Lead / Delivery Manager                                                                                                                                       |
| KPIs                           | Support ownership clarity, incident response readiness, handoff completion, post-cutover issue response time                                                           |
| Maturity Target                | Level 3 — Managed                                                                                                                                                      |
| Dependencies                   | Production Readiness Support, Cutover Readiness Assessment, Platform Operating Model Design                                                                            |
| Workbench Automation Potential | Support model drafter, escalation matrix generator, handoff gap detector, post-cutover issue summarizer                                                                |

### Notes

This capability ensures project teams do not leave operations teams with unclear responsibilities after go-live.

---

## 38.6 Capability — DMAF-CAP-POV-004 — Runbook & Operational Readiness Management

| Field                          | Description                                                                                                                                                               |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-004                                                                                                                                                          |
| Capability Name                | Runbook & Operational Readiness Management                                                                                                                                |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                                         |
| Business Objective             | Ensure that operational procedures, monitoring expectations, maintenance routines, job schedules, restart procedures, and support instructions are documented and usable. |
| Lifecycle Stages               | Stage 8 — Production Cutover; Stage 9 — Platform Operations, Adoption & Value Realization                                                                                 |
| Inputs                         | Production workloads, job schedules, platform architecture, monitoring requirements, incident scenarios, support model, operational constraints                           |
| Outputs                        | Runbooks, operational checklist, monitoring requirements, restart procedures, known issue guidance, operational readiness status                                          |
| Methods                        | Runbook development, operational readiness review, monitoring requirement review, support scenario walkthrough                                                            |
| Assets                         | Runbook template, operational readiness checklist, monitoring requirement template, support scenario checklist                                                            |
| Owner                          | Platform Lead / Operations Lead                                                                                                                                           |
| KPIs                           | Runbook completeness, operational readiness score, monitoring coverage, number of undocumented support scenarios                                                          |
| Maturity Target                | Level 3 — Managed                                                                                                                                                         |
| Dependencies                   | Production Readiness Support, Support Model Transition, Governance & Security                                                                                             |
| Workbench Automation Potential | Runbook draft generation, operational checklist generation, monitoring gap detection, support scenario summarization                                                      |

### Notes

This capability ensures platform operations can be performed repeatedly and reliably after delivery teams transition out.

---

## 38.7 Capability — DMAF-CAP-POV-005 — FinOps & Consumption Management

| Field                          | Description                                                                                                                                                                                               |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-005                                                                                                                                                                                          |
| Capability Name                | FinOps & Consumption Management                                                                                                                                                                           |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                                                                         |
| Business Objective             | Establish cost visibility, consumption awareness, optimization practices, and financial accountability for Databricks platform usage.                                                                     |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 6 — Migration Factory Execution; Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Workload characteristics, compute usage, job schedules, architecture design, environment strategy, consumption data, cost allocation needs                                                                |
| Outputs                        | FinOps operating view, cost driver model, consumption dashboard concept, optimization backlog, showback or chargeback considerations                                                                      |
| Methods                        | Cost driver analysis, consumption review, workload optimization review, FinOps cadence design                                                                                                             |
| Assets                         | FinOps checklist, cost driver worksheet, consumption dashboard template, optimization backlog template                                                                                                    |
| Owner                          | Platform Lead / FinOps Lead                                                                                                                                                                               |
| KPIs                           | Cost visibility, consumption trend, optimization savings, cost allocation coverage, number of unmanaged cost drivers                                                                                      |
| Maturity Target                | Level 3 — Managed                                                                                                                                                                                         |
| Dependencies                   | FinOps & Cost Optimization, Target-State Architecture Design, Migration Metrics & Reporting                                                                                                               |
| Workbench Automation Potential | Consumption summary generator, cost driver analyzer, optimization recommendation engine, FinOps dashboard generation                                                                                      |

### Notes

This capability ensures modernization value includes sustainable platform economics. FinOps should be considered during architecture and execution, not only after costs grow.

---

## 38.8 Capability — DMAF-CAP-POV-006 — Platform KPI & Value Realization Tracking

| Field                          | Description                                                                                                                                                           |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-006                                                                                                                                                      |
| Capability Name                | Platform KPI & Value Realization Tracking                                                                                                                             |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                                     |
| Business Objective             | Track whether the modernized platform is producing expected outcomes across adoption, performance, delivery speed, governance, cost, reliability, and business value. |
| Lifecycle Stages               | Stage 1 — Strategy & Business Value; Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence     |
| Inputs                         | Success metrics, business value map, platform goals, migration metrics, adoption metrics, operational metrics, cost metrics, stakeholder feedback                     |
| Outputs                        | Platform KPI model, value realization dashboard, benefits tracking summary, outcome narrative, improvement recommendations                                            |
| Methods                        | KPI design, value realization tracking, outcome measurement, platform performance review, executive value reporting                                                   |
| Assets                         | Platform KPI template, value realization tracker, KPI dashboard concept, benefits realization summary                                                                 |
| Owner                          | Platform Lead / Engagement Lead                                                                                                                                       |
| KPIs                           | KPI coverage, value realization visibility, outcome traceability, executive confidence, improvement action closure                                                    |
| Maturity Target                | Level 3 — Managed                                                                                                                                                     |
| Dependencies                   | Success Metric Definition, Transformation Value Communication, FinOps & Consumption Management                                                                        |
| Workbench Automation Potential | KPI dashboard generation, value realization narrative generator, outcome-to-metric mapper, improvement recommendation engine                                          |

### Notes

This capability reinforces that platform value is the destination. It connects modernization outcomes back to the value logic defined earlier in the lifecycle.

---

## 38.9 Capability — DMAF-CAP-POV-007 — Governance Maturity Improvement

| Field                          | Description                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Capability ID                  | DMAF-CAP-POV-007                                                                                                                                                   |
| Capability Name                | Governance Maturity Improvement                                                                                                                                    |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                                  |
| Business Objective             | Improve data governance, security, policy adoption, access management, lineage practices, and platform controls as the modernized platform matures.                |
| Lifecycle Stages               | Stage 3 — Modernization Architecture; Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence |
| Inputs                         | Governance architecture, security requirements, platform operating model, access patterns, audit needs, policy gaps, lineage needs, governance maturity baseline   |
| Outputs                        | Governance maturity assessment, improvement backlog, control adoption plan, policy improvement recommendations, governance operating cadence                       |
| Methods                        | Governance maturity review, access control review, policy gap analysis, control adoption planning                                                                  |
| Assets                         | Governance maturity assessment, Unity Catalog maturity checklist, access control review template, governance improvement backlog                                   |
| Owner                          | Platform Lead / Governance Lead                                                                                                                                    |
| KPIs                           | Governance maturity level, policy adoption, access review completion, unresolved governance gaps, control effectiveness                                            |
| Maturity Target                | Level 3 — Managed                                                                                                                                                  |
| Dependencies                   | Governance Architecture Design, Governance & Security, Risk & Compliance                                                                                           |
| Workbench Automation Potential | Governance maturity scoring, access review summarization, policy gap detection, governance improvement recommendation                                              |

### Notes

This capability supports long-term platform trust. Governance maturity should improve as platform adoption expands.

---

## 38.10 Capability — DMAF-CAP-POV-008 — Continuous Optimization Management

| Field                          | Description                                                                                                                                          |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Capability ID                  | DMAF-CAP-POV-008                                                                                                                                     |
| Capability Name                | Continuous Optimization Management                                                                                                                   |
| Practice Domain                | Platform Operations, Adoption & Value Realization                                                                                                    |
| Business Objective             | Maintain an ongoing backlog of platform, workload, governance, cost, adoption, performance, and value improvement opportunities after modernization. |
| Lifecycle Stages               | Stage 9 — Platform Operations, Adoption & Value Realization; Stage 10 — Continuous Optimization & Modernization Intelligence                         |
| Inputs                         | Platform KPIs, FinOps insights, incident trends, adoption feedback, governance gaps, performance observations, lessons learned, user requests        |
| Outputs                        | Continuous optimization backlog, improvement roadmap, prioritized optimization actions, lessons learned updates, value improvement recommendations   |
| Methods                        | Optimization review, improvement backlog management, prioritization, lessons learned capture, continuous improvement cadence                         |
| Assets                         | Optimization backlog template, improvement prioritization matrix, lessons learned template, continuous improvement cadence guide                     |
| Owner                          | Platform Lead / Practice Lead                                                                                                                        |
| KPIs                           | Optimization backlog closure rate, improvement value delivered, recurring issue reduction, cost optimization outcomes, adoption improvement          |
| Maturity Target                | Level 3 — Managed                                                                                                                                    |
| Dependencies                   | Platform KPI & Value Realization Tracking, FinOps & Consumption Management, Knowledge Management                                                     |
| Workbench Automation Potential | Optimization recommendation engine, improvement backlog generator, KPI trend analyzer, lessons learned extraction                                    |

### Notes

This capability ensures modernization learning and platform feedback are converted into continuous improvement rather than lost after project closure.

---

# 39. Platform Operations, Adoption & Value Realization Capability Map

| Capability ID    | Capability                                 | Supports Operations | Supports Adoption | Supports Value | Supports Workbench |
| ---------------- | ------------------------------------------ | ------------------- | ----------------- | -------------- | ------------------ |
| DMAF-CAP-POV-001 | Platform Operating Model Design            | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-002 | Adoption & Enablement Planning             | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-003 | Support Model Transition                   | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-004 | Runbook & Operational Readiness Management | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-005 | FinOps & Consumption Management            | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-006 | Platform KPI & Value Realization Tracking  | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-007 | Governance Maturity Improvement            | Yes                 | Yes               | Yes            | Yes                |
| DMAF-CAP-POV-008 | Continuous Optimization Management         | Yes                 | Yes               | Yes            | Yes                |

---

# 40. Platform Operations, Adoption & Value Realization Capability Governance

The Platform Operations, Adoption & Value Realization capabilities should be governed according to the following rules:

1. Do not treat production cutover as the end of modernization.
2. Do not transition to operations without clear ownership.
3. Do not assume adoption without an enablement plan.
4. Do not operate the platform without support responsibilities and escalation paths.
5. Do not ignore cost and consumption after migration.
6. Do not claim value realization without defined metrics.
7. Do not allow governance maturity to remain static as adoption grows.
8. Ensure continuous optimization improves platform value, operating practices, reusable assets, and future DMAF intelligence.

---

# 41. Future Enhancements

Future versions of this domain section may include:

* platform operating model template;
* adoption and enablement roadmap;
* support model template;
* runbook package template;
* FinOps dashboard concept;
* platform KPI library;
* value realization tracker;
* governance maturity assessment;
* continuous optimization backlog;
* Workbench value realization dashboard.

---

# 42. Status

This Practice Capability Catalogue is currently in **Draft v0.9.0** status.

The following practice domains have been drafted:

* Strategy & Business Value
* Discovery & Assessment
* Modernization Architecture
* Migration Factory
* Coexistence & Validation
* AI & Automation
* Executive Advisory
* Platform Operations, Adoption & Value Realization

Remaining capability domain:

* Modernization Intelligence Workbench

