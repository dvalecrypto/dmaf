---

title: DMAF Example Scenario Pack Plan
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
artifact_type: Example Pack Plan

practice_domain:
- Strategy & Business Value
- Discovery & Assessment
- Modernization Architecture
- Migration Factory
- Coexistence & Validation
- Executive Advisory
- Platform Operations, Adoption & Value Realization

lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Coexistence & Validation
- Executive Advisory
- Platform Operations, Adoption & Value Realization

guiding_principles:
- Business Value Before Technology
- Databricks by Design
- Modernization Is an Operating Model
- Industrialize Delivery
- Coexistence Is Intentional
- Trust Is Earned Through Validation
- Executive Storytelling Matters
- Platform Value Is the Destination
- Everything Is Traceable

dependencies:
- 03-Assets/README.md
- 03-Assets/dmaf-client-ready-starter-pack.md
- 00-Governance/Governance/dmaf-asset-metadata-standard.md
- 00-Governance/Release-Notes/release-2.0-consulting-assets.md

## last_updated: 2026-06-29

---

# DMAF Example Scenario Pack Plan

## 1. Purpose

The purpose of this plan is to define how example-filled versions of DMAF assets should be created.

Example scenarios help demonstrate how DMAF assets can be used in realistic modernization conversations without exposing client-confidential information.

The Example Scenario Pack should provide reusable sample content for:

* opportunity qualification;
* discovery intake;
* complexity scoring;
* target-state architecture;
* migration wave planning;
* validation strategy;
* executive storytelling;
* platform operating model planning.

---

## 2. Scenario Pack Objective

The Example Scenario Pack should help users understand how to complete DMAF assets by showing realistic sample inputs, outputs, assumptions, recommendations, and decision points.

The examples should be:

* realistic;
* reusable;
* anonymized;
* Databricks-aligned;
* framework-traceable;
* safe for internal practice enablement;
* adaptable for client-facing demonstrations after review.

---

# 3. Recommended Example Scenario

## 3.1 Scenario Name

```text id="scenario-name"
Regional Financial Services Data Modernization
```

## 3.2 Scenario Summary

A regional financial services organization is evaluating modernization of legacy data integration and reporting workloads onto a Databricks-centered lakehouse architecture.

The current environment includes legacy ETL workflows, batch file movement, relational database staging, downstream reporting extracts, manual reconciliation, and limited data governance visibility.

The organization wants to reduce legacy platform risk, improve delivery speed, improve data trust, strengthen governance, and create a foundation for future analytics and AI use cases.

---

## 3.3 Scenario Characteristics

| Area                 | Example Scenario Detail                                                           |
| -------------------- | --------------------------------------------------------------------------------- |
| Industry             | Financial services                                                                |
| Current platforms    | Legacy ETL tool, relational database staging, batch scheduler, BI reporting tools |
| Target platform      | Azure Databricks                                                                  |
| Primary driver       | Legacy modernization and platform risk reduction                                  |
| Secondary drivers    | Delivery speed, governance, AI readiness, validation, operating model maturity    |
| Workload type        | Batch data integration and reporting extracts                                     |
| Scope size           | Medium portfolio                                                                  |
| Complexity           | Mixed low, medium, and high complexity workloads                                  |
| Governance need      | High                                                                              |
| Validation need      | High                                                                              |
| Executive visibility | High                                                                              |
| Coexistence need     | Medium to high                                                                    |

---

# 4. Assets to Create Example Versions For

| Priority | Base Asset                                | Example Version                        | Purpose                                                                  |
| -------: | ----------------------------------------- | -------------------------------------- | ------------------------------------------------------------------------ |
|        1 | Opportunity Qualification Checklist       | Example-filled qualification checklist | Show how to qualify a modernization opportunity.                         |
|        2 | Application Inventory Workbook            | Example-filled inventory workbook      | Show how to capture applications, workflows, and dependencies.           |
|        3 | Modernization Complexity Scoring Workbook | Example-filled scoring workbook        | Show how complexity and priority can be scored.                          |
|        4 | Target-State Architecture Template        | Example-filled architecture template   | Show how to frame a Databricks target state.                             |
|        5 | Migration Wave Planning Workbook          | Example-filled wave plan workbook      | Show how to sequence workloads into migration waves.                     |
|        6 | Validation Strategy Template              | Example-filled validation strategy     | Show how to define comparison, evidence, and acceptance.                 |
|        7 | Executive One-Page Template               | Example-filled executive one-page      | Show how to summarize the modernization story.                           |
|        8 | Platform Operating Model Template         | Example-filled operating model         | Show how to define ownership, support, governance, FinOps, and adoption. |

---

# 5. Proposed Repository Structure

Create a dedicated example scenario folder.

```text id="example-folder-structure"
03-Assets/Examples/
└── Regional-Financial-Services-Modernization/
    ├── README.md
    ├── dmaf-example-opportunity-qualification-checklist.md
    ├── dmaf-example-application-inventory-workbook.xlsx
    ├── dmaf-example-modernization-complexity-scoring-workbook.xlsx
    ├── dmaf-example-target-state-architecture.md
    ├── dmaf-example-migration-wave-planning-workbook.xlsx
    ├── dmaf-example-validation-strategy.md
    ├── dmaf-example-executive-one-page.md
    └── dmaf-example-platform-operating-model.md
```

---

# 6. Example Scenario Inputs

## 6.1 Opportunity Inputs

| Input Area        | Example Content                                                                         |
| ----------------- | --------------------------------------------------------------------------------------- |
| Business driver   | Legacy data integration environment is becoming costly, slow, and difficult to support. |
| Timing driver     | Platform modernization funding window and upcoming support-risk review.                 |
| Executive sponsor | Chief Data Officer and Head of Enterprise Platforms.                                    |
| Business sponsor  | Finance and Risk reporting stakeholders.                                                |
| Target direction  | Databricks-centered lakehouse architecture.                                             |
| Primary decision  | Whether to proceed with structured discovery and modernization planning.                |

---

## 6.2 Discovery Inputs

| Input Area           | Example Content                                                                     |
| -------------------- | ----------------------------------------------------------------------------------- |
| Application count    | 5 candidate application groups                                                      |
| Workflow count       | 120 candidate workflows                                                             |
| Data sources         | Core banking extracts, CRM data, finance reference data, risk feeds                 |
| Downstream consumers | Finance reporting, risk analytics, operational dashboards                           |
| Dependencies         | Batch scheduler, relational staging database, file transfer processes               |
| Known pain points    | Manual reconciliation, long batch windows, unclear ownership, inconsistent metadata |

---

## 6.3 Complexity Inputs

| Criteria              | Example Scoring Consideration                                    |
| --------------------- | ---------------------------------------------------------------- |
| Workflow complexity   | Some workflows have many dependencies and transformation steps.  |
| Data volume           | Moderate volume with several large monthly reporting extracts.   |
| Business criticality  | High for finance and risk reporting workloads.                   |
| Dependency complexity | Medium to high due to downstream reporting and batch scheduling. |
| Validation complexity | High because control totals and reconciliation are required.     |
| Governance complexity | High due to sensitive financial data.                            |

---

# 7. Example Scenario Outputs

## 7.1 Expected Qualification Output

The example qualification output should demonstrate:

* clear business driver;
* clear modernization timing driver;
* Databricks fit;
* sponsor and decision-path identification;
* initial scope definition;
* risk and constraint capture;
* proceed-with-conditions recommendation.

Recommended example decision:

```text id="example-qualification-decision"
Proceed with Conditions
```

Rationale:

```text id="example-qualification-rationale"
The opportunity is credible and aligned to Databricks modernization, but structured discovery is required to validate inventory, dependencies, coexistence constraints, and validation complexity.
```

---

## 7.2 Expected Architecture Output

The example architecture output should demonstrate a Databricks-centered target state including:

* source ingestion;
* landing / bronze / silver / gold data layers;
* Delta Lake storage;
* Unity Catalog governance;
* Databricks Workflows orchestration;
* Databricks SQL consumption;
* validation and reconciliation layer;
* monitoring and operational readiness;
* future AI-readiness foundation.

---

## 7.3 Expected Migration Planning Output

The example migration planning output should demonstrate:

* candidate grouping;
* complexity-based prioritization;
* dependency-aware sequencing;
* pilot wave definition;
* migration wave plan;
* capacity assumptions;
* risk-based deferrals;
* validation requirements by wave.

Example wave structure:

| Wave   | Focus                       | Example Workloads                             |
| ------ | --------------------------- | --------------------------------------------- |
| Wave 0 | Foundation and pilot        | Low-risk reference data pipelines             |
| Wave 1 | Initial reporting workloads | Finance reporting extracts                    |
| Wave 2 | Dependency-heavy workflows  | Risk data integration workflows               |
| Wave 3 | High-criticality workloads  | Production finance and risk reporting feeds   |
| Wave 4 | Optimization and retirement | Legacy cleanup and operating model transition |

---

## 7.4 Expected Validation Output

The example validation output should demonstrate:

* record count comparison;
* hash or control total comparison;
* business rule validation;
* downstream output comparison;
* exception classification;
* tolerance rules;
* evidence storage;
* cutover acceptance criteria.

---

## 7.5 Expected Executive Output

The example executive one-page should communicate:

* why modernization matters now;
* what the current-state challenge is;
* why Databricks is the recommended direction;
* what value is expected;
* what decision is required;
* what the recommended next step is.

Recommended executive call to action:

```text id="example-executive-action"
Approve a structured discovery and target-state architecture phase to validate scope, complexity, dependencies, and migration roadmap.
```

---

# 8. Example Data Rules

Example scenario data should follow these rules:

| Rule                     | Requirement                                                                                                      |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| No real client names     | Use fictional or generic names only.                                                                             |
| No confidential data     | Do not include actual client data, credentials, file names, internal system identifiers, or proprietary details. |
| Realistic counts allowed | Use plausible sample counts and workload types.                                                                  |
| Label assumptions        | Clearly label assumptions as assumptions.                                                                        |
| Avoid false precision    | Do not invent overly specific details unless they are clearly fictional examples.                                |
| Keep reusable            | Ensure examples can be adapted to multiple modernization contexts.                                               |

---

# 9. Example Pack Build Sequence

Recommended build sequence:

| Step | Example Artifact                            | Rationale                                        |
| ---: | ------------------------------------------- | ------------------------------------------------ |
|    1 | Example Scenario README                     | Establish scenario context and assumptions.      |
|    2 | Example Opportunity Qualification Checklist | Define the opportunity and decision path.        |
|    3 | Example Application Inventory Workbook      | Create structured discovery input.               |
|    4 | Example Complexity Scoring Workbook         | Score candidate workloads.                       |
|    5 | Example Target-State Architecture Template  | Translate discovery into architecture direction. |
|    6 | Example Migration Wave Planning Workbook    | Sequence the modernization effort.               |
|    7 | Example Validation Strategy Template        | Define trust and acceptance approach.            |
|    8 | Example Executive One-Page Template         | Summarize for decision makers.                   |
|    9 | Example Platform Operating Model Template   | Define sustainability and value realization.     |

---

# 10. Example Pack Acceptance Criteria

The example pack should be considered complete when:

| Acceptance Criterion                                                  | Status  |
| --------------------------------------------------------------------- | ------- |
| Scenario README is created                                            | Planned |
| Example assets use fictional, safe scenario data                      | Planned |
| Example assets map back to base assets                                | Planned |
| Example assets remain aligned to approved DMAF capabilities           | Planned |
| Workbooks contain realistic sample rows                               | Planned |
| Markdown examples contain realistic completed sections                | Planned |
| Assumptions are clearly labeled                                       | Planned |
| No confidential or client-identifying information is included         | Planned |
| Example pack can support internal enablement                          | Planned |
| Example pack can support controlled client demonstration after review | Planned |

---

# 11. Workbench Potential

This example scenario pack may eventually support the following Workbench capabilities:

* sample engagement workspace generation;
* synthetic modernization scenario generation;
* asset demonstration mode;
* training data for asset recommendation;
* example-based prompt testing;
* output quality benchmarking;
* Workbench onboarding and enablement.

---

# 12. Status

This Example Scenario Pack Plan is currently in Draft v0.1.0 status.

It is the fifth packaging artifact created in Sprint 6.
