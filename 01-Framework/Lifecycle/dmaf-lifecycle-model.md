---

asset_id: DMAF-FWK-004
title: DMAF Lifecycle Model
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
- Platform Operations, Adoption & Value Realization

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
- Databricks by Design
- Modernization Is an Operating Model
- Industrialize Delivery
- Coexistence Is Intentional
- Trust Is Earned Through Validation
- Platform Value Is the Destination
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md

last_updated: 2026-06-26

---

# DMAF Lifecycle Model

## 1. Purpose

The purpose of this document is to define the lifecycle model for the Databricks Modernization Advisory Framework, referred to as DMAF.

The DMAF Lifecycle describes the major stages through which a Databricks-led modernization opportunity, engagement, delivery program, and platform adoption journey progress.

The lifecycle helps practitioners understand:

* when work occurs;
* what each stage is intended to achieve;
* what typical activities occur in each stage;
* what outputs are expected;
* which practice domains are most relevant;
* how modernization moves from opportunity shaping to sustained platform value;
* how learning from modernization feeds future advisory intelligence.

---

## 2. Source of Truth

The source of truth for this lifecycle model is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This document does not replace the Foundation Architecture.

It extracts and expands the approved DMAF Lifecycle so it can be used more easily by account executives, engagement leads, architects, delivery leads, validation leads, platform teams, and future Workbench capabilities.

---

## 3. Lifecycle Definition

A **lifecycle stage** describes when work occurs across the modernization journey.

A lifecycle stage is not the same as a practice domain.

* A **practice domain** describes what kind of capability is applied.
* A **lifecycle stage** describes when that capability is applied.
* A **method** describes how work is performed.
* An **asset** describes what reusable material supports the work.
* A **platform service** describes how the Workbench may automate or assist the work.

---

## 4. Lifecycle Principles

The DMAF Lifecycle follows these principles:

1. Modernization begins before formal discovery.
2. Opportunity qualification is part of the lifecycle.
3. Business value must shape modernization before technical decisions dominate.
4. Discovery creates the evidence base for architecture and planning.
5. Architecture must define both target state and transition path.
6. Migration should be industrialized through factory planning and execution.
7. Reference implementation or pilot work should reduce risk before scale.
8. Coexistence and validation must be intentional.
9. Production cutover must be controlled and supportable.
10. Platform adoption and value realization continue after migration.
11. Modernization learning should improve future assets, patterns, and Workbench intelligence.

---

## 5. Approved DMAF Lifecycle Stages

The approved DMAF Lifecycle contains eleven stages:

| Stage | Name                                                 |
| ----- | ---------------------------------------------------- |
| 0     | Opportunity Qualification & Modernization Strategy   |
| 1     | Strategy & Business Value                            |
| 2     | Discovery & Assessment                               |
| 3     | Modernization Architecture                           |
| 4     | Migration Factory Planning                           |
| 5     | Reference Implementation / Pilot                     |
| 6     | Migration Factory Execution                          |
| 7     | Coexistence & Validation                             |
| 8     | Production Cutover                                   |
| 9     | Platform Operations, Adoption & Value Realization    |
| 10    | Continuous Optimization & Modernization Intelligence |

The lifecycle begins at Stage 0 because DMAF starts when a modernization opportunity is shaped, not when formal discovery begins.

---

# 6. Stage 0 — Opportunity Qualification & Modernization Strategy

## 6.1 Purpose

Stage 0 determines whether a modernization opportunity is real, valuable, actionable, and strategically aligned.

This stage occurs before formal delivery begins.

## 6.2 Key Questions

* What business problem is driving modernization?
* Why now?
* Why Databricks?
* What legacy platforms or workloads are in scope?
* Is the client seeking tool replacement, platform modernization, cost reduction, risk reduction, AI readiness, or operating model change?
* Is there executive sponsorship?
* What is the likely scale and complexity?
* What constraints are already known?
* Is there a compelling reason to engage?

## 6.3 Typical Activities

* initial opportunity review;
* executive sponsor identification;
* modernization driver assessment;
* initial scope framing;
* current-state hypothesis development;
* preliminary risk identification;
* Databricks fit assessment;
* initial value hypothesis development;
* recommended next-step planning.

## 6.4 Typical Outputs

* opportunity qualification notes;
* modernization hypothesis;
* initial executive narrative;
* high-level scope framing;
* preliminary risk view;
* initial value hypothesis;
* recommended next step.

## 6.5 Primary Practice Domains

* Strategy & Business Value
* Executive Advisory
* Modernization Intelligence Workbench

## 6.6 Exit Criteria

Stage 0 may be considered complete when:

* the modernization opportunity has a clear business driver;
* an initial value hypothesis exists;
* initial scope is understood well enough to recommend next steps;
* key constraints are documented;
* there is a decision to proceed, defer, reshape, or decline the opportunity.

---

# 7. Stage 1 — Strategy & Business Value

## 7.1 Purpose

Stage 1 defines the business rationale and strategic value of modernization.

Its purpose is to connect modernization to executive priorities, business outcomes, risk reduction, platform value, and investment logic.

## 7.2 Typical Activities

* stakeholder alignment;
* business objective clarification;
* modernization driver analysis;
* value hypothesis development;
* business case framing;
* funding and sponsorship discussion;
* strategic sequencing;
* success metric identification.

## 7.3 Typical Outputs

* business value narrative;
* modernization strategy brief;
* executive alignment summary;
* value driver map;
* initial roadmap themes;
* success metric model.

## 7.4 Primary Practice Domains

* Strategy & Business Value
* Executive Advisory
* Platform Operations, Adoption & Value Realization

## 7.5 Exit Criteria

Stage 1 may be considered complete when:

* modernization objectives are documented;
* value drivers are understood;
* success measures are defined;
* executive stakeholders understand the modernization rationale;
* the engagement has enough business context to move into structured discovery.

---

# 8. Stage 2 — Discovery & Assessment

## 8.1 Purpose

Stage 2 establishes the evidence base for modernization decisions.

Its purpose is to understand the current-state environment, including applications, workflows, data stores, dependencies, business rules, constraints, risks, and operating context.

## 8.2 Typical Activities

* application inventory collection;
* workflow and pipeline discovery;
* source and target system analysis;
* dependency mapping;
* stakeholder interviews;
* current-state architecture review;
* complexity scoring;
* risk assessment;
* readiness assessment;
* discovery evidence review.

## 8.3 Typical Outputs

* discovery findings;
* application inventory;
* complexity scoring model;
* dependency map;
* current-state architecture summary;
* risk register;
* modernization readiness assessment;
* candidate migration segments.

## 8.4 Primary Practice Domains

* Discovery & Assessment
* Modernization Architecture
* Migration Factory
* AI & Automation

## 8.5 Exit Criteria

Stage 2 may be considered complete when:

* current-state information is sufficient to support architecture and planning;
* major applications, workflows, data stores, and dependencies are identified;
* complexity and risk are assessed at an initial level;
* evidence gaps are documented;
* candidate modernization segments are identified.

---

# 9. Stage 3 — Modernization Architecture

## 9.1 Purpose

Stage 3 defines the target-state and transitional architecture.

Its purpose is to translate discovery findings and business objectives into a coherent Databricks-centered architecture direction.

## 9.2 Typical Activities

* target-state architecture design;
* transitional architecture design;
* Databricks capability mapping;
* lakehouse pattern selection;
* governance and security model alignment;
* orchestration pattern definition;
* data product strategy;
* integration model design;
* architecture decision documentation;
* reference architecture selection.

## 9.3 Typical Outputs

* target-state architecture;
* transitional architecture;
* architecture decision records;
* Databricks capability map;
* governance and security model;
* integration model;
* reference architecture alignment;
* architecture roadmap.

## 9.4 Primary Practice Domains

* Modernization Architecture
* Coexistence & Validation
* Governance & Security
* Executive Advisory

## 9.5 Exit Criteria

Stage 3 may be considered complete when:

* a target-state architecture direction is documented;
* transitional architecture considerations are identified;
* key architecture decisions are captured;
* Databricks capabilities are mapped to modernization objectives;
* major coexistence, governance, security, and integration implications are understood.

---

# 10. Stage 4 — Migration Factory Planning

## 10.1 Purpose

Stage 4 defines how modernization work will be sequenced, organized, governed, and measured.

Its purpose is to turn modernization strategy and architecture into an executable migration factory model.

## 10.2 Typical Activities

* migration wave planning;
* factory backlog creation;
* application segmentation;
* complexity-based sequencing;
* delivery capacity planning;
* resource model definition;
* migration pattern identification;
* estimation;
* dependency sequencing;
* delivery governance design;
* factory metrics definition.

## 10.3 Typical Outputs

* migration factory plan;
* migration waves;
* delivery backlog;
* estimation model;
* resource plan;
* migration roadmap;
* factory operating model;
* factory KPIs.

## 10.4 Primary Practice Domains

* Migration Factory
* Discovery & Assessment
* Modernization Architecture
* Executive Advisory

## 10.5 Exit Criteria

Stage 4 may be considered complete when:

* migration waves are defined;
* the factory backlog is established;
* delivery capacity is understood;
* dependencies are reflected in sequencing;
* factory governance and KPIs are defined;
* the plan is ready to be tested through a pilot or reference implementation.

---

# 11. Stage 5 — Reference Implementation / Pilot

## 11.1 Purpose

Stage 5 validates the modernization approach through a controlled implementation.

Its purpose is to prove the architecture, migration approach, validation method, delivery model, and governance assumptions before scaling.

## 11.2 Typical Activities

* pilot scope selection;
* representative workload selection;
* architecture validation;
* conversion approach validation;
* data reconciliation testing;
* performance assessment;
* operating model testing;
* delivery pattern refinement;
* lessons learned capture.

## 11.3 Typical Outputs

* reference implementation;
* pilot results;
* validated migration pattern;
* refined architecture decisions;
* validation evidence;
* updated estimates;
* updated factory plan;
* lessons learned.

## 11.4 Primary Practice Domains

* Modernization Architecture
* Migration Factory
* Coexistence & Validation
* AI & Automation

## 11.5 Exit Criteria

Stage 5 may be considered complete when:

* the selected workload has been implemented or prototyped;
* architecture assumptions have been tested;
* migration approach assumptions have been tested;
* validation approach has been tested;
* lessons learned have been captured;
* the migration factory plan is updated based on evidence.

---

# 12. Stage 6 — Migration Factory Execution

## 12.1 Purpose

Stage 6 executes modernization at scale.

Its purpose is to migrate, convert, rebuild, validate, and transition workloads through a repeatable factory model.

## 12.2 Typical Activities

* wave execution;
* backlog management;
* code conversion or redevelopment;
* data pipeline implementation;
* unit testing;
* system testing;
* defect management;
* pattern reuse;
* progress tracking;
* delivery governance;
* knowledge transfer.

## 12.3 Typical Outputs

* migrated workloads;
* updated backlog;
* test evidence;
* defect reports;
* delivery metrics;
* migration status reports;
* reusable patterns;
* updated accelerators.

## 12.4 Primary Practice Domains

* Migration Factory
* AI & Automation
* Coexistence & Validation
* Platform Operations, Adoption & Value Realization

## 12.5 Exit Criteria

Stage 6 may be considered complete for a migration wave when:

* planned workloads for the wave are migrated or rebuilt;
* test evidence exists;
* defects are tracked and addressed;
* reusable patterns are captured;
* delivery metrics are updated;
* workloads are ready for coexistence, validation, or cutover planning.

---

# 13. Stage 7 — Coexistence & Validation

## 13.1 Purpose

Stage 7 ensures that legacy and modern platforms can safely coexist during transition and that modernized outcomes are trusted.

Its purpose is to validate accuracy, completeness, reconciliation, downstream impact, operational readiness, and business acceptance.

## 13.2 Typical Activities

* coexistence architecture implementation;
* parallel run planning;
* reconciliation testing;
* record count comparison;
* hash total comparison;
* control total validation;
* business rule validation;
* downstream output comparison;
* exception handling;
* validation evidence management;
* cutover readiness review.

## 13.3 Typical Outputs

* validation strategy;
* reconciliation results;
* parallel run evidence;
* exception reports;
* validation sign-off;
* cutover readiness assessment;
* business acceptance evidence.

## 13.4 Primary Practice Domains

* Coexistence & Validation
* Migration Factory
* Modernization Architecture
* Executive Advisory

## 13.5 Exit Criteria

Stage 7 may be considered complete when:

* validation evidence is sufficient for stakeholder confidence;
* reconciliation exceptions are understood and resolved or accepted;
* cutover readiness is assessed;
* business acceptance evidence is captured;
* known limitations are documented;
* production transition can proceed with controlled risk.

---

# 14. Stage 8 — Production Cutover

## 14.1 Purpose

Stage 8 transitions the modernized workloads into production use.

Its purpose is to execute the controlled movement from legacy operation to modernized operation.

## 14.2 Typical Activities

* cutover planning;
* deployment readiness review;
* rollback planning;
* operational handoff;
* production scheduling;
* final validation;
* stakeholder communication;
* go-live support;
* incident response planning;
* post-cutover verification.

## 14.3 Typical Outputs

* cutover plan;
* go-live checklist;
* rollback plan;
* production readiness approval;
* operational handoff package;
* go-live confirmation;
* post-cutover validation report.

## 14.4 Primary Practice Domains

* Coexistence & Validation
* Migration Factory
* Platform Operations, Adoption & Value Realization
* Executive Advisory

## 14.5 Exit Criteria

Stage 8 may be considered complete when:

* production readiness has been approved;
* operational handoff is complete;
* go-live is confirmed;
* rollback plan exists or is explicitly not required;
* post-cutover validation is complete;
* support responsibilities are clear.

---

# 15. Stage 9 — Platform Operations, Adoption & Value Realization

## 15.1 Purpose

Stage 9 ensures the client can operate, adopt, govern, optimize, and derive value from the modernized platform.

Its purpose is to move beyond migration completion toward sustained platform value.

## 15.2 Typical Activities

* operating model implementation;
* support model transition;
* runbook creation;
* platform monitoring;
* enablement and training;
* adoption tracking;
* FinOps monitoring;
* governance maturity improvement;
* value realization tracking;
* continuous improvement planning.

## 15.3 Typical Outputs

* operating model;
* support model;
* runbooks;
* adoption plan;
* platform KPI dashboard;
* FinOps dashboard;
* value realization report;
* continuous improvement backlog.

## 15.4 Primary Practice Domains

* Platform Operations, Adoption & Value Realization
* Governance & Security
* FinOps & Cost Optimization
* Executive Advisory

## 15.5 Exit Criteria

Stage 9 may be considered complete when:

* the platform has an operating model;
* support responsibilities are clear;
* adoption and enablement activities are underway;
* platform KPIs are defined;
* cost and consumption visibility exists;
* value realization is being tracked.

---

# 16. Stage 10 — Continuous Optimization & Modernization Intelligence

## 16.1 Purpose

Stage 10 converts modernization learning into ongoing optimization and reusable intelligence.

Its purpose is to continuously improve DMAF, the client platform, reusable assets, and the Modernization Intelligence Workbench.

## 16.2 Typical Activities

* lessons learned capture;
* reusable asset updates;
* pattern library refinement;
* platform optimization;
* knowledge graph updates;
* Workbench improvement;
* research updates;
* capability maturity review;
* roadmap refresh;
* advisory insight generation.

## 16.3 Typical Outputs

* lessons learned repository;
* updated assets;
* updated reference architectures;
* updated capability models;
* optimization backlog;
* modernization intelligence insights;
* future roadmap recommendations.

## 16.4 Primary Practice Domains

* Modernization Intelligence Workbench
* Platform Operations, Adoption & Value Realization
* AI & Automation
* Strategy & Business Value
* Executive Advisory

## 16.5 Exit Criteria

Stage 10 is continuous rather than terminal.

It is operating effectively when:

* lessons learned are captured;
* reusable DMAF assets are improved;
* patterns are refined;
* Workbench knowledge is updated;
* platform optimization opportunities are identified;
* insights inform future modernization opportunities.

---

# 17. Lifecycle Operating View

The DMAF Lifecycle should be understood as a continuous loop:

```text
Opportunity Qualification
        ↓
Strategy & Business Value
        ↓
Discovery & Assessment
        ↓
Modernization Architecture
        ↓
Migration Factory Planning
        ↓
Reference Implementation / Pilot
        ↓
Migration Factory Execution
        ↓
Coexistence & Validation
        ↓
Production Cutover
        ↓
Platform Operations, Adoption & Value Realization
        ↓
Continuous Optimization & Modernization Intelligence
        ↺
```

The output of each stage informs future modernization opportunities, updated assets, improved reference architectures, better proposals, and more intelligent Workbench capabilities.

---

# 18. Lifecycle-to-Domain Alignment

| Lifecycle Stage                                                 | Primary Practice Domains                                                                                                                                |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Stage 0 — Opportunity Qualification & Modernization Strategy    | Strategy & Business Value; Executive Advisory; Modernization Intelligence Workbench                                                                     |
| Stage 1 — Strategy & Business Value                             | Strategy & Business Value; Executive Advisory; Platform Operations, Adoption & Value Realization                                                        |
| Stage 2 — Discovery & Assessment                                | Discovery & Assessment; Modernization Architecture; Migration Factory; AI & Automation                                                                  |
| Stage 3 — Modernization Architecture                            | Modernization Architecture; Coexistence & Validation; Executive Advisory                                                                                |
| Stage 4 — Migration Factory Planning                            | Migration Factory; Discovery & Assessment; Modernization Architecture; Executive Advisory                                                               |
| Stage 5 — Reference Implementation / Pilot                      | Modernization Architecture; Migration Factory; Coexistence & Validation; AI & Automation                                                                |
| Stage 6 — Migration Factory Execution                           | Migration Factory; AI & Automation; Coexistence & Validation; Platform Operations, Adoption & Value Realization                                         |
| Stage 7 — Coexistence & Validation                              | Coexistence & Validation; Migration Factory; Modernization Architecture; Executive Advisory                                                             |
| Stage 8 — Production Cutover                                    | Coexistence & Validation; Migration Factory; Platform Operations, Adoption & Value Realization; Executive Advisory                                      |
| Stage 9 — Platform Operations, Adoption & Value Realization     | Platform Operations, Adoption & Value Realization; Governance & Security; FinOps & Cost Optimization; Executive Advisory                                |
| Stage 10 — Continuous Optimization & Modernization Intelligence | Modernization Intelligence Workbench; Platform Operations, Adoption & Value Realization; AI & Automation; Strategy & Business Value; Executive Advisory |

---

# 19. Lifecycle Governance Rules

The DMAF Lifecycle should be governed according to the following rules:

1. Do not remove Stage 0 without governance approval.
2. Do not treat the lifecycle as a strict waterfall.
3. Do not skip business value framing unless explicitly justified.
4. Do not move to architecture without sufficient discovery evidence.
5. Do not scale migration without a tested migration and validation approach.
6. Do not treat coexistence as an afterthought.
7. Do not treat production cutover as the end of modernization.
8. Do not mark modernization complete without platform adoption and value realization considerations.
9. Do not introduce new lifecycle stages without updating the taxonomy, roadmap, and baseline register.
10. Ensure lifecycle changes are reflected in related playbooks, assets, and Workbench concepts.

---

# 20. Future Enhancements

Future versions of this Lifecycle Model may include:

* detailed stage gates;
* stage-level RACI model;
* lifecycle-to-asset mapping;
* lifecycle-to-capability mapping;
* lifecycle maturity model;
* stage-specific checklists;
* stage-specific Workbench services;
* lifecycle dashboard concept;
* executive lifecycle visualization;
* delivery methodology overlays by modernization scenario.

These enhancements are expected to be developed in later sprints and releases.

---

# 21. Review Checklist

Before approving changes to this document, reviewers should ask:

1. Are all eleven lifecycle stages represented?
2. Is Stage 0 preserved?
3. Is the lifecycle described as a continuous cycle?
4. Are lifecycle stages clearly distinguished from practice domains?
5. Are stage purposes clear?
6. Are typical activities and outputs consistent with the Foundation Architecture?
7. Are stage exit criteria practical?
8. Does the Workbench remain a horizontal enablement layer?
9. Are domain alignments consistent with the Practice Domain Model?
10. Does the document support future playbook and asset development?

---

# 22. Status

This Lifecycle Model is currently in **Draft v0.1.0** status.

It is the third substantive framework artifact created in Sprint 2.
