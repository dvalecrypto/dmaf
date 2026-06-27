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
| Strategy & Business Value                         |                        7 | Drafted     |
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

# 14. Status

This Practice Capability Catalogue is currently in **Draft v0.2.0** status.

The Strategy & Business Value domain capabilities have been drafted.

Remaining capability domains are pending.
