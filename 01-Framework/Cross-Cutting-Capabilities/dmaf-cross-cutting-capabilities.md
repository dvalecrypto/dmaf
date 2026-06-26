---

asset_id: DMAF-FWK-005
title: DMAF Cross-Cutting Capabilities
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0

practice_domain:
- Modernization Architecture
- Migration Factory
- Coexistence & Validation
- AI & Automation
- Platform Operations, Adoption & Value Realization

cross_cutting_capabilities:
  - Governance & Security
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
- Databricks by Design
- Modernization Is an Operating Model
- Coexistence Is Intentional
- Trust Is Earned Through Validation
- AI Accelerates, People Govern
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md

last_updated: 2026-06-26

---

# DMAF Cross-Cutting Capabilities

## 1. Purpose

The purpose of this document is to define the cross-cutting capabilities of the Databricks Modernization Advisory Framework, referred to as DMAF.

Cross-cutting capabilities are shared concerns that apply across multiple practice domains and lifecycle stages. They ensure that modernization is not treated as a disconnected sequence of activities, but as a governed, secure, risk-aware, cost-conscious, AI-enabled, reusable, and knowledge-driven transformation.

This document provides a standalone reference for the seven approved DMAF cross-cutting capabilities.

---

## 2. Source of Truth

The source of truth for this model is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This document does not replace the Foundation Architecture.

It extracts and organizes the approved cross-cutting capabilities so they can be applied consistently across DMAF playbooks, assets, reference architectures, industry packs, Workbench modules, and future automation.

---

## 3. Cross-Cutting Capability Definition

A **cross-cutting capability** is a shared concern that applies across multiple practice domains and lifecycle stages.

A cross-cutting capability is not owned by only one practice domain. Instead, it acts as a governing or enabling layer that must be considered throughout modernization strategy, discovery, architecture, migration planning, execution, validation, production cutover, adoption, and continuous optimization.

Cross-cutting capabilities help DMAF maintain continuity across the full modernization journey.

---

## 4. Approved Cross-Cutting Capabilities

DMAF contains seven approved cross-cutting capabilities:

1. Governance & Security
2. Risk & Compliance
3. FinOps & Cost Optimization
4. AI Enablement
5. Automation
6. Knowledge Management
7. Reusable Accelerators

---

# 5. Cross-Cutting Capability 1 — Governance & Security

## 5.1 Definition

Governance & Security defines how data, access, policies, standards, controls, and security expectations are managed across the modernization lifecycle.

In a Databricks-centered modernization program, this capability ensures that modernization improves the trust, control, and manageability of the data platform rather than simply moving workloads to a new technical environment.

## 5.2 Primary Objective

Ensure that modernized data platforms are governed, secure, auditable, and aligned to enterprise control expectations.

## 5.3 Typical Concerns

* data access governance;
* Unity Catalog alignment;
* security model design;
* data classification;
* lineage expectations;
* policy enforcement;
* platform guardrails;
* environment separation;
* role-based access;
* auditability;
* operational controls.

## 5.4 Lifecycle Relevance

Governance & Security applies across all lifecycle stages, with particular importance in:

* Stage 2 — Discovery & Assessment;
* Stage 3 — Modernization Architecture;
* Stage 4 — Migration Factory Planning;
* Stage 7 — Coexistence & Validation;
* Stage 8 — Production Cutover;
* Stage 9 — Platform Operations, Adoption & Value Realization.

## 5.5 Related Practice Domains

* Discovery & Assessment
* Modernization Architecture
* Coexistence & Validation
* Platform Operations, Adoption & Value Realization
* Modernization Intelligence Workbench

## 5.6 Typical Assets

* governance assessment checklist;
* Unity Catalog alignment checklist;
* security model template;
* data classification guide;
* access control design pattern;
* architecture decision record template;
* governance maturity assessment.

## 5.7 Workbench Automation Potential

Future Workbench capabilities may include:

* governance gap detection;
* metadata and classification analysis;
* policy mapping support;
* Unity Catalog readiness assessment;
* governance recommendation generation;
* security checklist generation.

---

# 6. Cross-Cutting Capability 2 — Risk & Compliance

## 6.1 Definition

Risk & Compliance defines how modernization risk is identified, assessed, communicated, mitigated, and governed.

Risk is not only a delivery concern. It influences strategy, architecture, migration sequencing, coexistence, validation, cutover, adoption, and executive decision-making.

## 6.2 Primary Objective

Ensure that modernization decisions are risk-aware, compliant, transparent, and controlled.

## 6.3 Typical Concerns

* delivery risk;
* architecture risk;
* data quality risk;
* downstream impact risk;
* operational risk;
* regulatory risk;
* security risk;
* coexistence risk;
* cutover risk;
* validation risk;
* stakeholder adoption risk.

## 6.4 Lifecycle Relevance

Risk & Compliance applies across all lifecycle stages, with particular importance in:

* Stage 0 — Opportunity Qualification & Modernization Strategy;
* Stage 1 — Strategy & Business Value;
* Stage 2 — Discovery & Assessment;
* Stage 4 — Migration Factory Planning;
* Stage 7 — Coexistence & Validation;
* Stage 8 — Production Cutover.

## 6.5 Related Practice Domains

* Strategy & Business Value
* Discovery & Assessment
* Modernization Architecture
* Migration Factory
* Coexistence & Validation
* Executive Advisory

## 6.6 Typical Assets

* modernization risk register;
* risk scoring model;
* compliance impact checklist;
* cutover risk assessment;
* coexistence risk assessment;
* validation risk checklist;
* executive risk summary template.

## 6.7 Workbench Automation Potential

Future Workbench capabilities may include:

* risk extraction from discovery notes;
* automated risk categorization;
* risk-to-lifecycle mapping;
* compliance concern detection;
* recommended mitigation generation;
* executive risk summary generation.

---

# 7. Cross-Cutting Capability 3 — FinOps & Cost Optimization

## 7.1 Definition

FinOps & Cost Optimization defines how modernization decisions consider cost transparency, platform efficiency, consumption management, and long-term financial sustainability.

In a Databricks modernization context, FinOps should be considered before, during, and after migration.

## 7.2 Primary Objective

Ensure that modernization improves financial transparency and supports sustainable platform economics.

## 7.3 Typical Concerns

* workload cost estimation;
* cluster and compute cost considerations;
* storage cost implications;
* job scheduling efficiency;
* environment sizing;
* consumption visibility;
* cost allocation;
* chargeback or showback models;
* optimization opportunities;
* value realization tracking.

## 7.4 Lifecycle Relevance

FinOps & Cost Optimization applies across the lifecycle, with particular importance in:

* Stage 1 — Strategy & Business Value;
* Stage 3 — Modernization Architecture;
* Stage 4 — Migration Factory Planning;
* Stage 6 — Migration Factory Execution;
* Stage 9 — Platform Operations, Adoption & Value Realization;
* Stage 10 — Continuous Optimization & Modernization Intelligence.

## 7.5 Related Practice Domains

* Strategy & Business Value
* Modernization Architecture
* Migration Factory
* Platform Operations, Adoption & Value Realization
* Executive Advisory

## 7.6 Typical Assets

* modernization cost driver model;
* Databricks workload cost estimation template;
* FinOps readiness checklist;
* cost optimization playbook;
* platform consumption dashboard concept;
* showback / chargeback model template;
* value realization tracking template.

## 7.7 Workbench Automation Potential

Future Workbench capabilities may include:

* workload cost estimation support;
* cost driver identification;
* consumption pattern analysis;
* FinOps recommendations;
* value realization dashboarding;
* cost-risk trade-off analysis.

---

# 8. Cross-Cutting Capability 4 — AI Enablement

## 8.1 Definition

AI Enablement defines how modernization prepares the client for AI adoption and how AI can accelerate modernization work.

This capability has two dimensions:

1. **AI-ready modernization** — designing data platforms, governance, lineage, quality, and data products so they can support AI use cases.
2. **AI-assisted modernization** — using AI to accelerate discovery, analysis, documentation, mapping, testing, risk detection, and recommendation generation.

## 8.2 Primary Objective

Ensure that modernization both enables future AI value and uses AI responsibly to improve modernization delivery.

## 8.3 Typical Concerns

* AI-ready data foundations;
* metadata quality;
* lineage and governance;
* data product readiness;
* AI-assisted discovery;
* code interpretation;
* document analysis;
* mapping assistance;
* test case generation;
* recommendation drafting;
* human review and governance.

## 8.4 Lifecycle Relevance

AI Enablement applies across the lifecycle, with particular importance in:

* Stage 0 — Opportunity Qualification & Modernization Strategy;
* Stage 2 — Discovery & Assessment;
* Stage 3 — Modernization Architecture;
* Stage 4 — Migration Factory Planning;
* Stage 6 — Migration Factory Execution;
* Stage 10 — Continuous Optimization & Modernization Intelligence.

## 8.5 Related Practice Domains

* AI & Automation
* Discovery & Assessment
* Modernization Architecture
* Migration Factory
* Executive Advisory
* Modernization Intelligence Workbench

## 8.6 Typical Assets

* AI readiness assessment;
* AI-assisted discovery prompt library;
* code interpretation prompt library;
* AI governance checklist;
* recommendation review checklist;
* AI-enabled modernization opportunity map;
* Workbench agent design template.

## 8.7 Workbench Automation Potential

Future Workbench capabilities may include:

* AI-assisted document interpretation;
* code and metadata analysis;
* recommendation generation;
* test case generation;
* gap detection;
* pattern matching;
* advisory agent orchestration.

---

# 9. Cross-Cutting Capability 5 — Automation

## 9.1 Definition

Automation defines how repeatable modernization activities can be standardized, scripted, templated, or productized.

Automation is central to DMAF because the framework is designed to scale beyond individual practitioners.

## 9.2 Primary Objective

Increase modernization speed, consistency, quality, and reuse by automating repeatable work where practical.

## 9.3 Typical Concerns

* metadata extraction;
* repository setup;
* application inventory generation;
* complexity scoring;
* wave planning;
* diagram generation;
* document creation;
* validation checks;
* reconciliation reporting;
* asset indexing;
* Workbench workflows.

## 9.4 Lifecycle Relevance

Automation applies across all lifecycle stages, with particular importance in:

* Stage 2 — Discovery & Assessment;
* Stage 4 — Migration Factory Planning;
* Stage 6 — Migration Factory Execution;
* Stage 7 — Coexistence & Validation;
* Stage 10 — Continuous Optimization & Modernization Intelligence.

## 9.5 Related Practice Domains

* Discovery & Assessment
* Migration Factory
* Coexistence & Validation
* AI & Automation
* Modernization Intelligence Workbench

## 9.6 Typical Assets

* repository bootstrap script;
* metadata extraction script;
* complexity scoring workbook;
* wave planning workbook;
* validation checklist;
* reconciliation script concept;
* reusable prompt library;
* Workbench workflow specification.

## 9.7 Workbench Automation Potential

Future Workbench capabilities may include:

* engagement workspace creation;
* file ingestion;
* metadata extraction;
* application inventory interpretation;
* automated scoring assistance;
* artifact generation;
* knowledge graph indexing;
* dashboard generation.

---

# 10. Cross-Cutting Capability 6 — Knowledge Management

## 10.1 Definition

Knowledge Management defines how engagement learning, patterns, decisions, assumptions, risks, and assets are captured and reused.

DMAF should prevent modernization knowledge from remaining trapped in individual projects, documents, folders, or practitioners.

## 10.2 Primary Objective

Ensure that every engagement strengthens DMAF through reusable knowledge and improved assets.

## 10.3 Typical Concerns

* asset metadata;
* reusable templates;
* decision records;
* reference architectures;
* pattern libraries;
* lessons learned;
* research notes;
* proposal language;
* industry observations;
* modernization case examples;
* Workbench knowledge repositories.

## 10.4 Lifecycle Relevance

Knowledge Management applies across all lifecycle stages, with particular importance in:

* Stage 2 — Discovery & Assessment;
* Stage 3 — Modernization Architecture;
* Stage 5 — Reference Implementation / Pilot;
* Stage 6 — Migration Factory Execution;
* Stage 9 — Platform Operations, Adoption & Value Realization;
* Stage 10 — Continuous Optimization & Modernization Intelligence.

## 10.5 Related Practice Domains

* Executive Advisory
* Modernization Architecture
* Migration Factory
* AI & Automation
* Modernization Intelligence Workbench

## 10.6 Typical Assets

* lessons learned template;
* architecture decision record template;
* pattern library;
* asset metadata standard;
* research note template;
* proposal language library;
* engagement retrospective template;
* reusable case example template.

## 10.7 Workbench Automation Potential

Future Workbench capabilities may include:

* asset indexing;
* knowledge graph search;
* pattern recommendation;
* lessons learned extraction;
* reusable language suggestion;
* engagement-to-asset conversion support;
* practice intelligence dashboarding.

---

# 11. Cross-Cutting Capability 7 — Reusable Accelerators

## 11.1 Definition

Reusable Accelerators define the tools, templates, scripts, calculators, diagrams, prompts, and workbooks that improve modernization speed and quality.

Accelerators should be governed like product assets.

## 11.2 Primary Objective

Improve modernization consistency and speed by providing reusable, governed, high-quality assets.

## 11.3 Typical Concerns

* discovery questionnaires;
* application inventory templates;
* complexity scoring workbooks;
* migration wave planning tools;
* coexistence decision trees;
* validation checklists;
* architecture diagram templates;
* executive presentation templates;
* proposal accelerators;
* industry pack templates;
* Workbench prompts;
* metadata extraction scripts.

## 11.4 Lifecycle Relevance

Reusable Accelerators apply across the lifecycle, with particular importance in:

* Stage 0 — Opportunity Qualification & Modernization Strategy;
* Stage 2 — Discovery & Assessment;
* Stage 3 — Modernization Architecture;
* Stage 4 — Migration Factory Planning;
* Stage 6 — Migration Factory Execution;
* Stage 7 — Coexistence & Validation;
* Stage 10 — Continuous Optimization & Modernization Intelligence.

## 11.5 Related Practice Domains

* Discovery & Assessment
* Modernization Architecture
* Migration Factory
* Coexistence & Validation
* Executive Advisory
* Modernization Intelligence Workbench

## 11.6 Typical Assets

* discovery kit;
* assessment workbook;
* complexity scoring workbook;
* migration planning workbook;
* architecture diagram library;
* validation checklist;
* executive briefing template;
* proposal accelerator;
* Workbench prompt library.

## 11.7 Workbench Automation Potential

Future Workbench capabilities may include:

* accelerator recommendation;
* asset retrieval;
* template generation;
* prompt library execution;
* diagram generation support;
* engagement-specific asset packaging;
* asset reuse tracking.

---

# 12. Cross-Cutting Capability-to-Lifecycle Matrix

| Cross-Cutting Capability   | Most Relevant Lifecycle Stages                                 |
| -------------------------- | -------------------------------------------------------------- |
| Governance & Security      | Stage 2, Stage 3, Stage 4, Stage 7, Stage 8, Stage 9           |
| Risk & Compliance          | Stage 0, Stage 1, Stage 2, Stage 4, Stage 7, Stage 8           |
| FinOps & Cost Optimization | Stage 1, Stage 3, Stage 4, Stage 6, Stage 9, Stage 10          |
| AI Enablement              | Stage 0, Stage 2, Stage 3, Stage 4, Stage 6, Stage 10          |
| Automation                 | Stage 2, Stage 4, Stage 6, Stage 7, Stage 10                   |
| Knowledge Management       | Stage 2, Stage 3, Stage 5, Stage 6, Stage 9, Stage 10          |
| Reusable Accelerators      | Stage 0, Stage 2, Stage 3, Stage 4, Stage 6, Stage 7, Stage 10 |

---

# 13. Cross-Cutting Capability-to-Domain Matrix

| Cross-Cutting Capability   | Strongest Related Practice Domains                                                                                                                        |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Governance & Security      | Discovery & Assessment; Modernization Architecture; Coexistence & Validation; Platform Operations, Adoption & Value Realization                           |
| Risk & Compliance          | Strategy & Business Value; Discovery & Assessment; Migration Factory; Coexistence & Validation; Executive Advisory                                        |
| FinOps & Cost Optimization | Strategy & Business Value; Modernization Architecture; Migration Factory; Platform Operations, Adoption & Value Realization                               |
| AI Enablement              | AI & Automation; Discovery & Assessment; Modernization Architecture; Migration Factory; Modernization Intelligence Workbench                              |
| Automation                 | Discovery & Assessment; Migration Factory; Coexistence & Validation; AI & Automation; Modernization Intelligence Workbench                                |
| Knowledge Management       | Executive Advisory; Modernization Architecture; Migration Factory; AI & Automation; Modernization Intelligence Workbench                                  |
| Reusable Accelerators      | Discovery & Assessment; Modernization Architecture; Migration Factory; Coexistence & Validation; Executive Advisory; Modernization Intelligence Workbench |

---

# 14. Governance Rules

Cross-cutting capabilities should be governed according to the following rules:

1. Do not treat cross-cutting capabilities as lifecycle stages.
2. Do not treat cross-cutting capabilities as practice domains.
3. Ensure major DMAF assets identify relevant cross-cutting capabilities where applicable.
4. Ensure cross-cutting concerns are considered during asset reviews.
5. Ensure Governance & Security, Risk & Compliance, and FinOps are considered early, not only after implementation.
6. Ensure AI Enablement and Automation remain governed by human review.
7. Ensure Knowledge Management and Reusable Accelerators are used to improve the DMAF asset base.

---

# 15. Future Enhancements

Future versions of this document may include:

* cross-cutting capability maturity model;
* cross-cutting capability assessment checklist;
* governance/security reference checklist;
* FinOps modernization model;
* AI enablement assessment;
* automation opportunity catalogue;
* reusable accelerator catalogue;
* Workbench automation mapping.

These enhancements are expected to be developed in later sprints and releases.

---

# 16. Review Checklist

Before approving changes to this document, reviewers should ask:

1. Are all seven approved cross-cutting capabilities represented?
2. Are cross-cutting capabilities clearly distinguished from practice domains?
3. Are cross-cutting capabilities clearly distinguished from lifecycle stages?
4. Are lifecycle alignments practical?
5. Are related practice domains accurate?
6. Are future Workbench opportunities identified without overcommitting implementation?
7. Are governance rules clear?
8. Is terminology consistent with the DMAF taxonomy?
9. Does the document align with the Foundation Architecture?
10. Does the document support future playbook and asset development?

---

# 17. Status

This Cross-Cutting Capabilities document is currently in **Draft v0.1.0** status.

It is the fourth substantive framework artifact created in Sprint 2.
