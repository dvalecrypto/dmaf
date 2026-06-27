---

asset_id: DMAF-FWK-010
title: DMAF Capability Method Asset Map
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

- Knowledge Management
- Reusable Accelerators
- Automation

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

- Industrialize Delivery
- Knowledge Compounds
- Everything Is Traceable

dependencies:

- 00-Governance/Governance/dmaf-traceability-and-integration-review.md
- 01-Framework/Capability-Model/dmaf-capability-model.md
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Knowledge-Graph/dmaf-knowledge-graph.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

last_updated: 2026-06-26
---

# DMAF Capability Method Asset Map

## 1. Purpose

The purpose of this document is to map approved DMAF capabilities to candidate methods and reusable assets.

This document begins Sprint 4 — Methods and Asset Mapping.

Sprint 4 ensures that future methods, templates, workbooks, diagrams, playbooks, prompts, and Workbench services are not created randomly. They must map back to approved capabilities in the Practice Capability Catalogue.

---

## 2. Source of Truth

This document is governed by:

```text
01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
```

It also depends on the DMAF Traceability and Integration Review:

```text
00-Governance/Governance/dmaf-traceability-and-integration-review.md
```

---

## 3. Sprint 4 Control Rule

No method or asset should be created unless it maps to an approved capability.

Each method or asset should identify:

* related practice domain;
* related capability;
* related lifecycle stage;
* related guiding principle;
* related cross-cutting capability where applicable;
* intended audience;
* reusable asset type;
* owner;
* status;
* version.

---

## 4. Mapping Definitions

| Term                | Definition                                                                                                          |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Capability          | What DMAF must be able to do.                                                                                       |
| Method              | How the capability is performed.                                                                                    |
| Asset               | A reusable work product that supports the method or capability.                                                     |
| Priority            | Relative importance for future build-out.                                                                           |
| Asset Type          | The reusable artifact format, such as template, workbook, checklist, diagram, deck, prompt, or script.              |
| Workbench Potential | Whether the method or asset could eventually be automated or supported by the Modernization Intelligence Workbench. |

---

## 5. Mapping Priority Levels

| Priority | Definition                                                                                                                   |
| -------- | ---------------------------------------------------------------------------------------------------------------------------- |
| High     | Needed early because it supports sales, discovery, architecture, migration planning, validation, or executive communication. |
| Medium   | Useful for repeatability but not required before core methods and assets exist.                                              |
| Low      | Valuable later, once core practice assets mature.                                                                            |

---

## 6. Initial Mapping Structure

The mapping will be organized by the nine approved DMAF practice domains:

1. Strategy & Business Value
2. Discovery & Assessment
3. Modernization Architecture
4. Migration Factory
5. Coexistence & Validation
6. AI & Automation
7. Executive Advisory
8. Platform Operations, Adoption & Value Realization
9. Modernization Intelligence Workbench

Each domain section will map capabilities to candidate methods and assets.

---

## 7. Mapping Table Template

Each domain should use the following structure:

| Capability ID | Capability | Candidate Method | Candidate Asset | Asset Type | Priority | Workbench Potential |
| ------------- | ---------- | ---------------- | --------------- | ---------- | -------- | ------------------- |
| TBD           | TBD        | TBD              | TBD             | TBD        | TBD      | TBD                 |

---

# 8. Domain 1 — Strategy & Business Value

## 8.1 Method and Asset Map

| Capability ID    | Capability                              | Candidate Method                 | Candidate Asset                          | Asset Type | Priority | Workbench Potential |
| ---------------- | --------------------------------------- | -------------------------------- | ---------------------------------------- | ---------- | -------- | ------------------- |
| DMAF-CAP-SBV-001 | Modernization Opportunity Qualification | Opportunity Qualification Method | Opportunity Qualification Checklist      | Checklist  | High     | Yes                 |
| DMAF-CAP-SBV-001 | Modernization Opportunity Qualification | Modernization Hypothesis Framing | Modernization Hypothesis Template        | Template   | High     | Yes                 |
| DMAF-CAP-SBV-002 | Business Value Framing                  | Value Driver Mapping             | Business Value Framing Worksheet         | Worksheet  | High     | Yes                 |
| DMAF-CAP-SBV-002 | Business Value Framing                  | Executive Value Narrative Method | Executive Value Narrative Template       | Template   | High     | Yes                 |
| DMAF-CAP-SBV-003 | Executive Sponsor Alignment             | Stakeholder Alignment Method     | Sponsor Alignment Checklist              | Checklist  | High     | Yes                 |
| DMAF-CAP-SBV-003 | Executive Sponsor Alignment             | Decision Path Mapping            | Stakeholder and Decision Path Map        | Template   | Medium   | Yes                 |
| DMAF-CAP-SBV-004 | Modernization Value Mapping             | Outcome Traceability Method      | Modernization Value Map                  | Template   | High     | Yes                 |
| DMAF-CAP-SBV-004 | Modernization Value Mapping             | Benefits Dependency Mapping      | Value Realization Planning Template      | Template   | Medium   | Yes                 |
| DMAF-CAP-SBV-005 | Strategic Roadmap Framing               | Roadmap Framing Method           | Strategic Modernization Roadmap Template | Template   | High     | Yes                 |
| DMAF-CAP-SBV-005 | Strategic Roadmap Framing               | Executive Roadmap Storytelling   | Executive Roadmap View                   | Diagram    | High     | Yes                 |
| DMAF-CAP-SBV-006 | Investment Case Development             | Investment Framing Method        | Investment Case Narrative Template       | Template   | Medium   | Yes                 |
| DMAF-CAP-SBV-006 | Investment Case Development             | Cost Driver Analysis             | Modernization Cost Driver Worksheet      | Worksheet  | Medium   | Yes                 |
| DMAF-CAP-SBV-007 | Success Metric Definition               | KPI Definition Method            | Success Metric Template                  | Template   | High     | Yes                 |
| DMAF-CAP-SBV-007 | Success Metric Definition               | Value Realization Metric Design  | Value Realization Tracker                | Workbook   | Medium   | Yes                 |

---

## 8.2 Priority Asset Candidates

The highest priority Strategy & Business Value assets are:

1. Opportunity Qualification Checklist
2. Modernization Hypothesis Template
3. Business Value Framing Worksheet
4. Modernization Value Map
5. Strategic Modernization Roadmap Template
6. Executive Roadmap View
7. Success Metric Template

---

## 8.3 Notes

Strategy & Business Value assets should be built early because they support opportunity shaping, executive alignment, proposal positioning, and the first client conversations.

These assets also provide the value foundation for later discovery, architecture, migration planning, validation, and platform adoption work.

---

# 9. Domain 2 — Discovery & Assessment

## 9.1 Method and Asset Map

| Capability ID    | Capability                                | Candidate Method                   | Candidate Asset                                | Asset Type | Priority | Workbench Potential |
| ---------------- | ----------------------------------------- | ---------------------------------- | ---------------------------------------------- | ---------- | -------- | ------------------- |
| DMAF-CAP-DAS-001 | Discovery Intake & Evidence Management    | Discovery Intake Method            | Discovery Intake Checklist                     | Checklist  | High     | Yes                 |
| DMAF-CAP-DAS-001 | Discovery Intake & Evidence Management    | Evidence Classification Method     | Discovery Evidence Register                    | Template   | High     | Yes                 |
| DMAF-CAP-DAS-002 | Application & Workflow Inventory Analysis | Inventory Normalization Method     | Application Inventory Workbook                 | Workbook   | High     | Yes                 |
| DMAF-CAP-DAS-002 | Application & Workflow Inventory Analysis | Workflow Classification Method     | Workflow Inventory Workbook                    | Workbook   | High     | Yes                 |
| DMAF-CAP-DAS-003 | Data Source & Dependency Mapping          | Dependency Mapping Method          | Dependency Mapping Template                    | Template   | High     | Yes                 |
| DMAF-CAP-DAS-003 | Data Source & Dependency Mapping          | Source-to-Target Analysis          | Source-to-Target Matrix                        | Workbook   | High     | Yes                 |
| DMAF-CAP-DAS-004 | Current-State Architecture Assessment     | Current-State Architecture Review  | Current-State Architecture Assessment Template | Template   | High     | Yes                 |
| DMAF-CAP-DAS-004 | Current-State Architecture Assessment     | Architecture Gap Analysis          | Architecture Gap Worksheet                     | Worksheet  | Medium   | Yes                 |
| DMAF-CAP-DAS-005 | Modernization Complexity Scoring          | Complexity Scoring Method          | Modernization Complexity Scoring Workbook      | Workbook   | High     | Yes                 |
| DMAF-CAP-DAS-005 | Modernization Complexity Scoring          | Complexity Calibration Method      | Complexity Scoring Rubric                      | Guide      | High     | Yes                 |
| DMAF-CAP-DAS-006 | Migration Readiness Assessment            | Readiness Assessment Method        | Migration Readiness Checklist                  | Checklist  | High     | Yes                 |
| DMAF-CAP-DAS-006 | Migration Readiness Assessment            | Pilot Candidate Selection          | Pilot Selection Criteria Template              | Template   | Medium   | Yes                 |
| DMAF-CAP-DAS-007 | Risk & Constraint Identification          | Risk Identification Method         | Modernization Risk Register                    | Template   | High     | Yes                 |
| DMAF-CAP-DAS-007 | Risk & Constraint Identification          | Assumption and Constraint Capture  | Assumption and Constraint Log                  | Template   | High     | Yes                 |
| DMAF-CAP-DAS-008 | Discovery Findings Synthesis              | Findings Synthesis Method          | Discovery Findings Report Template             | Template   | High     | Yes                 |
| DMAF-CAP-DAS-008 | Discovery Findings Synthesis              | Evidence-to-Recommendation Mapping | Findings-to-Recommendations Matrix             | Worksheet  | High     | Yes                 |

---

## 9.2 Priority Asset Candidates

The highest priority Discovery & Assessment assets are:

1. Discovery Intake Checklist
2. Discovery Evidence Register
3. Application Inventory Workbook
4. Workflow Inventory Workbook
5. Dependency Mapping Template
6. Source-to-Target Matrix
7. Current-State Architecture Assessment Template
8. Modernization Complexity Scoring Workbook
9. Migration Readiness Checklist
10. Modernization Risk Register
11. Assumption and Constraint Log
12. Discovery Findings Report Template
13. Findings-to-Recommendations Matrix

---

## 9.3 Notes

Discovery & Assessment assets should be prioritized early because they create the evidence base for the rest of DMAF.

Without these assets, later architecture, migration planning, validation, executive advisory, and Workbench automation will rely on inconsistent or incomplete inputs.

The most important Sprint 4 build candidates from this domain are:

* Application Inventory Workbook
* Workflow Inventory Workbook
* Modernization Complexity Scoring Workbook
* Discovery Findings Report Template

These assets are likely to become reusable across most modernization opportunities.

---

# 10. Domain 3 — Modernization Architecture

## 10.1 Method and Asset Map

| Capability ID    | Capability                       | Candidate Method                      | Candidate Asset                            | Asset Type | Priority | Workbench Potential |
| ---------------- | -------------------------------- | ------------------------------------- | ------------------------------------------ | ---------- | -------- | ------------------- |
| DMAF-CAP-MAR-001 | Target-State Architecture Design | Target-State Architecture Method      | Target-State Architecture Template         | Template   | High     | Yes                 |
| DMAF-CAP-MAR-001 | Target-State Architecture Design | Architecture Capability Mapping       | Databricks Platform Capability Map         | Diagram    | High     | Yes                 |
| DMAF-CAP-MAR-002 | Transitional Architecture Design | Transitional Architecture Planning    | Transitional Architecture Template         | Template   | High     | Yes                 |
| DMAF-CAP-MAR-002 | Transitional Architecture Design | Transition-State Mapping              | Transition-State Diagram Template          | Diagram    | High     | Yes                 |
| DMAF-CAP-MAR-003 | Databricks Capability Mapping    | Databricks Fit Assessment             | Databricks Capability Fit Checklist        | Checklist  | High     | Yes                 |
| DMAF-CAP-MAR-003 | Databricks Capability Mapping    | Use-Case-to-Platform Mapping          | Databricks Use Case Alignment Worksheet    | Worksheet  | Medium   | Yes                 |
| DMAF-CAP-MAR-004 | Lakehouse Pattern Selection      | Lakehouse Pattern Selection Method    | Lakehouse Pattern Catalogue                | Guide      | High     | Yes                 |
| DMAF-CAP-MAR-004 | Lakehouse Pattern Selection      | Workload-to-Pattern Mapping           | Workload-to-Pattern Matrix                 | Worksheet  | High     | Yes                 |
| DMAF-CAP-MAR-005 | Governance Architecture Design   | Governance Architecture Method        | Governance Architecture Template           | Template   | High     | Yes                 |
| DMAF-CAP-MAR-005 | Governance Architecture Design   | Unity Catalog Readiness Review        | Unity Catalog Readiness Checklist          | Checklist  | High     | Yes                 |
| DMAF-CAP-MAR-006 | Integration Architecture Design  | Integration Architecture Method       | Integration Architecture Template          | Template   | High     | Yes                 |
| DMAF-CAP-MAR-006 | Integration Architecture Design  | Interface and Orchestration Review    | Interface Inventory Template               | Template   | High     | Yes                 |
| DMAF-CAP-MAR-007 | Architecture Decision Management | Architecture Decision Record Method   | Architecture Decision Record Template      | Template   | High     | Yes                 |
| DMAF-CAP-MAR-007 | Architecture Decision Management | Architecture Trade-Off Analysis       | Architecture Trade-Off Worksheet           | Worksheet  | Medium   | Yes                 |
| DMAF-CAP-MAR-008 | Reference Architecture Selection | Reference Architecture Fit Assessment | Reference Architecture Selection Checklist | Checklist  | High     | Yes                 |
| DMAF-CAP-MAR-008 | Reference Architecture Selection | Reference Architecture Fit-Gap Review | Reference Architecture Fit-Gap Worksheet   | Worksheet  | Medium   | Yes                 |

---

## 10.2 Priority Asset Candidates

The highest priority Modernization Architecture assets are:

1. Target-State Architecture Template
2. Databricks Platform Capability Map
3. Transitional Architecture Template
4. Transition-State Diagram Template
5. Databricks Capability Fit Checklist
6. Lakehouse Pattern Catalogue
7. Workload-to-Pattern Matrix
8. Governance Architecture Template
9. Unity Catalog Readiness Checklist
10. Integration Architecture Template
11. Interface Inventory Template
12. Architecture Decision Record Template
13. Reference Architecture Selection Checklist

---

## 10.3 Notes

Modernization Architecture assets should be built early because they translate discovery evidence and business objectives into a target-state and transition-state design.

The most important Sprint 4 build candidates from this domain are:

* Target-State Architecture Template
* Transitional Architecture Template
* Databricks Platform Capability Map
* Lakehouse Pattern Catalogue
* Architecture Decision Record Template

These assets will also provide the foundation for future reference architectures under:

```text
04-Reference-Architectures/
```

Architecture assets should remain reusable and pattern-based. Client-specific target architectures should only enter the DMAF repository after being sanitized and generalized.

---

# 11. Domain 4 — Migration Factory

## 11.1 Method and Asset Map

| Capability ID    | Capability                              | Candidate Method                   | Candidate Asset                          | Asset Type | Priority | Workbench Potential |
| ---------------- | --------------------------------------- | ---------------------------------- | ---------------------------------------- | ---------- | -------- | ------------------- |
| DMAF-CAP-MGF-001 | Migration Wave Planning                 | Complexity-Based Wave Sequencing   | Migration Wave Planning Workbook         | Workbook   | High     | Yes                 |
| DMAF-CAP-MGF-001 | Migration Wave Planning                 | Migration Segmentation Method      | Migration Wave Roadmap Template          | Template   | High     | Yes                 |
| DMAF-CAP-MGF-002 | Factory Backlog Management              | Factory Backlog Structuring        | Factory Backlog Template                 | Template   | High     | Yes                 |
| DMAF-CAP-MGF-002 | Factory Backlog Management              | Backlog Health Review              | Factory Backlog Health Dashboard Concept | Dashboard  | Medium   | Yes                 |
| DMAF-CAP-MGF-003 | Migration Pattern Management            | Migration Pattern Identification   | Migration Pattern Catalogue              | Guide      | High     | Yes                 |
| DMAF-CAP-MGF-003 | Migration Pattern Management            | Pattern Fit Assessment             | Migration Pattern Selection Matrix       | Worksheet  | High     | Yes                 |
| DMAF-CAP-MGF-004 | Delivery Capacity & Throughput Planning | Delivery Capacity Planning         | Delivery Capacity Planning Worksheet     | Worksheet  | High     | Yes                 |
| DMAF-CAP-MGF-004 | Delivery Capacity & Throughput Planning | Throughput Modeling                | Migration Throughput Model               | Workbook   | High     | Yes                 |
| DMAF-CAP-MGF-005 | Migration Estimation & Sizing           | Complexity-Based Estimation        | Migration Estimation Workbook            | Workbook   | High     | Yes                 |
| DMAF-CAP-MGF-005 | Migration Estimation & Sizing           | Estimate Confidence Assessment     | Estimation Assumption Log                | Template   | High     | Yes                 |
| DMAF-CAP-MGF-006 | Dependency-Based Sequencing             | Dependency-Based Sequencing Method | Dependency Sequencing Worksheet          | Worksheet  | High     | Yes                 |
| DMAF-CAP-MGF-006 | Dependency-Based Sequencing             | Blocker Assessment                 | Migration Dependency Blocker Tracker     | Template   | Medium   | Yes                 |
| DMAF-CAP-MGF-007 | Factory Execution Governance            | Factory Governance Cadence         | Migration Factory Governance Model       | Template   | High     | Yes                 |
| DMAF-CAP-MGF-007 | Factory Execution Governance            | Quality Gate Review                | Migration Quality Gate Checklist         | Checklist  | High     | Yes                 |
| DMAF-CAP-MGF-008 | Migration Metrics & Reporting           | Factory KPI Definition             | Migration Factory KPI Library            | Guide      | High     | Yes                 |
| DMAF-CAP-MGF-008 | Migration Metrics & Reporting           | Executive Migration Reporting      | Executive Migration Status Template      | Template   | High     | Yes                 |

---

## 11.2 Priority Asset Candidates

The highest priority Migration Factory assets are:

1. Migration Wave Planning Workbook
2. Migration Wave Roadmap Template
3. Factory Backlog Template
4. Migration Pattern Catalogue
5. Migration Pattern Selection Matrix
6. Delivery Capacity Planning Worksheet
7. Migration Throughput Model
8. Migration Estimation Workbook
9. Estimation Assumption Log
10. Dependency Sequencing Worksheet
11. Migration Factory Governance Model
12. Migration Quality Gate Checklist
13. Migration Factory KPI Library
14. Executive Migration Status Template

---

## 11.3 Notes

Migration Factory assets are central to making DMAF repeatable and scalable.

The most important Sprint 4 build candidates from this domain are:

* Migration Wave Planning Workbook
* Migration Estimation Workbook
* Migration Pattern Catalogue
* Migration Quality Gate Checklist
* Executive Migration Status Template

These assets will likely become core delivery accelerators because they directly support planning, sequencing, execution governance, and executive reporting.

Migration Factory assets should be designed to support multiple source platforms, including Informatica, mainframe, SSIS, DataStage, Hadoop, Teradata, Oracle ETL, and other legacy data platforms.

The assets should remain Databricks-first while being source-platform adaptive.

---

# 12. Domain 5 — Coexistence & Validation

## 12.1 Method and Asset Map

| Capability ID    | Capability                            | Candidate Method                   | Candidate Asset                      | Asset Type    | Priority | Workbench Potential |
| ---------------- | ------------------------------------- | ---------------------------------- | ------------------------------------ | ------------- | -------- | ------------------- |
| DMAF-CAP-COV-001 | Coexistence Strategy Design           | Coexistence Pattern Assessment     | Coexistence Strategy Template        | Template      | High     | Yes                 |
| DMAF-CAP-COV-001 | Coexistence Strategy Design           | Transition-State Mapping           | Coexistence Decision Tree            | Decision Tree | High     | Yes                 |
| DMAF-CAP-COV-002 | Parallel Run Planning                 | Parallel Run Planning Method       | Parallel Run Planning Template       | Template      | High     | Yes                 |
| DMAF-CAP-COV-002 | Parallel Run Planning                 | Output Comparison Planning         | Output Comparison Checklist          | Checklist     | High     | Yes                 |
| DMAF-CAP-COV-003 | Reconciliation Design                 | Reconciliation Rule Design         | Reconciliation Design Workbook       | Workbook      | High     | Yes                 |
| DMAF-CAP-COV-003 | Reconciliation Design                 | Control Total Design               | Control Totals Checklist             | Checklist     | High     | Yes                 |
| DMAF-CAP-COV-004 | Validation Strategy Design            | Validation Strategy Method         | Validation Strategy Template         | Template      | High     | Yes                 |
| DMAF-CAP-COV-004 | Validation Strategy Design            | Acceptance Criteria Definition     | Acceptance Criteria Template         | Template      | High     | Yes                 |
| DMAF-CAP-COV-005 | Exception Handling & Resolution Model | Exception Triage Method            | Exception Handling Model             | Template      | High     | Yes                 |
| DMAF-CAP-COV-005 | Exception Handling & Resolution Model | Variance Classification Method     | Approved Variance Register           | Template      | Medium   | Yes                 |
| DMAF-CAP-COV-006 | Cutover Readiness Assessment          | Go/No-Go Readiness Review          | Cutover Readiness Checklist          | Checklist     | High     | Yes                 |
| DMAF-CAP-COV-006 | Cutover Readiness Assessment          | Cutover Risk Review                | Cutover Risk Summary Template        | Template      | High     | Yes                 |
| DMAF-CAP-COV-007 | Validation Evidence Management        | Evidence Capture Method            | Validation Evidence Register         | Template      | High     | Yes                 |
| DMAF-CAP-COV-007 | Validation Evidence Management        | Validation Package Assembly        | Validation Evidence Package Template | Template      | High     | Yes                 |
| DMAF-CAP-COV-008 | Production Readiness Support          | Operational Handoff Planning       | Production Readiness Checklist       | Checklist     | High     | Yes                 |
| DMAF-CAP-COV-008 | Production Readiness Support          | Post-Cutover Verification Planning | Post-Cutover Validation Template     | Template      | Medium   | Yes                 |

---

## 12.2 Priority Asset Candidates

The highest priority Coexistence & Validation assets are:

1. Coexistence Strategy Template
2. Coexistence Decision Tree
3. Parallel Run Planning Template
4. Output Comparison Checklist
5. Reconciliation Design Workbook
6. Control Totals Checklist
7. Validation Strategy Template
8. Acceptance Criteria Template
9. Exception Handling Model
10. Cutover Readiness Checklist
11. Cutover Risk Summary Template
12. Validation Evidence Register
13. Validation Evidence Package Template
14. Production Readiness Checklist

---

## 12.3 Notes

Coexistence & Validation assets should be prioritized because they are directly tied to trust, risk reduction, business acceptance, auditability, and production readiness.

The most important Sprint 4 build candidates from this domain are:

* Coexistence Strategy Template
* Reconciliation Design Workbook
* Validation Strategy Template
* Cutover Readiness Checklist
* Validation Evidence Register

These assets are especially important in enterprise environments where parallel run may be constrained, downstream impacts are significant, or validation evidence must support business and audit review.

Coexistence & Validation assets should clearly distinguish:

* validation strategy;
* reconciliation approach;
* parallel run feasibility;
* exception handling;
* accepted variances;
* cutover readiness;
* production readiness;
* retained evidence.

---

# 13. Domain 6 — AI & Automation

## 13.1 Method and Asset Map

| Capability ID    | Capability                               | Candidate Method                      | Candidate Asset                         | Asset Type       | Priority | Workbench Potential |
| ---------------- | ---------------------------------------- | ------------------------------------- | --------------------------------------- | ---------------- | -------- | ------------------- |
| DMAF-CAP-AIA-001 | AI-Assisted Discovery Interpretation     | AI-Assisted Discovery Review          | Discovery Interpretation Prompt Library | Prompt Library   | High     | Yes                 |
| DMAF-CAP-AIA-001 | AI-Assisted Discovery Interpretation     | Evidence Gap Detection                | Evidence Gap Analyzer Checklist         | Checklist        | High     | Yes                 |
| DMAF-CAP-AIA-002 | Metadata Extraction Automation           | Metadata Extraction Method            | Metadata Extraction Script Catalogue    | Script Catalogue | High     | Yes                 |
| DMAF-CAP-AIA-002 | Metadata Extraction Automation           | Extraction Quality Review             | Metadata Extraction Quality Checklist   | Checklist        | High     | Yes                 |
| DMAF-CAP-AIA-003 | Code & Logic Interpretation Support      | Code Interpretation Method            | Code Interpretation Prompt Library      | Prompt Library   | High     | Yes                 |
| DMAF-CAP-AIA-003 | Code & Logic Interpretation Support      | Business Rule Extraction              | Business Rule Extraction Worksheet      | Worksheet        | High     | Yes                 |
| DMAF-CAP-AIA-004 | Recommendation Drafting & Review Support | Evidence-to-Recommendation Mapping    | Recommendation Drafting Prompt Library  | Prompt Library   | High     | Yes                 |
| DMAF-CAP-AIA-004 | Recommendation Drafting & Review Support | Recommendation Review Method          | Recommendation Review Checklist         | Checklist        | High     | Yes                 |
| DMAF-CAP-AIA-005 | Test Case & Validation Support           | AI-Assisted Test Scenario Generation  | Test Case Generation Prompt Library     | Prompt Library   | Medium   | Yes                 |
| DMAF-CAP-AIA-005 | Test Case & Validation Support           | Validation Coverage Review            | Validation Coverage Gap Checklist       | Checklist        | Medium   | Yes                 |
| DMAF-CAP-AIA-006 | Automated Artifact Generation            | Template-Based Artifact Generation    | Artifact Generation Prompt Library      | Prompt Library   | High     | Yes                 |
| DMAF-CAP-AIA-006 | Automated Artifact Generation            | Generated Artifact Review             | Generated Artifact Quality Checklist    | Checklist        | High     | Yes                 |
| DMAF-CAP-AIA-007 | Automation Pattern Management            | Automation Opportunity Identification | Automation Opportunity Register         | Template         | Medium   | Yes                 |
| DMAF-CAP-AIA-007 | Automation Pattern Management            | Automation Pattern Governance         | Automation Pattern Catalogue            | Guide            | Medium   | Yes                 |
| DMAF-CAP-AIA-008 | AI Governance & Human Review Model       | Human-in-the-Loop Review Method       | AI Output Review Checklist              | Checklist        | High     | Yes                 |
| DMAF-CAP-AIA-008 | AI Governance & Human Review Model       | Prompt Governance Method              | Prompt Quality Standard                 | Standard         | High     | Yes                 |

---

## 13.2 Priority Asset Candidates

The highest priority AI & Automation assets are:

1. Discovery Interpretation Prompt Library
2. Evidence Gap Analyzer Checklist
3. Metadata Extraction Script Catalogue
4. Metadata Extraction Quality Checklist
5. Code Interpretation Prompt Library
6. Business Rule Extraction Worksheet
7. Recommendation Drafting Prompt Library
8. Recommendation Review Checklist
9. Artifact Generation Prompt Library
10. Generated Artifact Quality Checklist
11. AI Output Review Checklist
12. Prompt Quality Standard

---

## 13.3 Notes

AI & Automation assets should be built carefully because they can accelerate the entire DMAF practice, but they also introduce quality, trust, and governance risk.

The most important Sprint 4 build candidates from this domain are:

* AI Output Review Checklist
* Prompt Quality Standard
* Discovery Interpretation Prompt Library
* Recommendation Review Checklist
* Artifact Generation Prompt Library

AI & Automation assets should follow these principles:

* AI accelerates, people govern.
* AI-generated outputs require review.
* Prompts should be reusable and versioned.
* Generated recommendations must be traceable to evidence.
* Code interpretation should not be treated as automatic code conversion.
* Automation patterns should be governed as reusable assets.
* Workbench automation should operationalize approved DMAF concepts rather than inventing new methodology.

This domain should also influence the future Workbench build because many Workbench services will depend on these methods and assets.

---

# 14. Status

This Capability Method Asset Map is currently in Draft v0.6.0 status.

The following domains have been mapped:

* Strategy & Business Value
* Discovery & Assessment
* Modernization Architecture
* Migration Factory
* Coexistence & Validation
* AI & Automation

Remaining domains are pending.




