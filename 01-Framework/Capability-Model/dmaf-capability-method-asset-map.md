---

asset_id: DMAF-FWK-010
title: DMAF Capability Method Asset Map
status: Draft
version: 1.0.0
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

# 14. Domain 7 — Executive Advisory

## 14.1 Method and Asset Map

| Capability ID    | Capability                              | Candidate Method                    | Candidate Asset                        | Asset Type | Priority | Workbench Potential |
| ---------------- | --------------------------------------- | ----------------------------------- | -------------------------------------- | ---------- | -------- | ------------------- |
| DMAF-CAP-EXA-001 | Executive Narrative Development         | Executive Story Framing             | Executive Narrative Template           | Template   | High     | Yes                 |
| DMAF-CAP-EXA-001 | Executive Narrative Development         | Modernization Message Structuring   | Modernization Story Arc Template       | Template   | High     | Yes                 |
| DMAF-CAP-EXA-002 | Advisory Workshop Facilitation          | Advisory Workshop Design            | Advisory Workshop Agenda Template      | Template   | High     | Yes                 |
| DMAF-CAP-EXA-002 | Advisory Workshop Facilitation          | Decision Capture Method             | Workshop Decision Capture Template     | Template   | High     | Yes                 |
| DMAF-CAP-EXA-003 | Decision Framing & Options Analysis     | Options Analysis Method             | Executive Decision Brief Template      | Template   | High     | Yes                 |
| DMAF-CAP-EXA-003 | Decision Framing & Options Analysis     | Trade-Off Analysis                  | Options and Trade-Off Matrix           | Worksheet  | High     | Yes                 |
| DMAF-CAP-EXA-004 | Modernization Roadmap Storytelling      | Roadmap Storytelling Method         | Executive Roadmap Briefing Template    | Template   | High     | Yes                 |
| DMAF-CAP-EXA-004 | Modernization Roadmap Storytelling      | Modernization Journey Visualization | Modernization Journey Diagram          | Diagram    | High     | Yes                 |
| DMAF-CAP-EXA-005 | Proposal Positioning & Pursuit Support  | Pursuit Positioning Method          | Modernization Proposal Outline         | Template   | High     | Yes                 |
| DMAF-CAP-EXA-005 | Proposal Positioning & Pursuit Support  | Value Proposition Framing           | Proposal Positioning Statement Library | Library    | High     | Yes                 |
| DMAF-CAP-EXA-006 | Executive Visual Design                 | Executive Visual Storytelling       | Executive One-Page Template            | Template   | High     | Yes                 |
| DMAF-CAP-EXA-006 | Executive Visual Design                 | Before-and-After Framing            | Modernization Before-and-After Diagram | Diagram    | High     | Yes                 |
| DMAF-CAP-EXA-007 | Transformation Value Communication      | Value Realization Communication     | Executive Value Update Template        | Template   | Medium   | Yes                 |
| DMAF-CAP-EXA-007 | Transformation Value Communication      | KPI-to-Narrative Method             | KPI Interpretation Guide               | Guide      | Medium   | Yes                 |
| DMAF-CAP-EXA-008 | Executive Governance & Steering Support | Executive Steering Support Method   | Steering Committee Deck Template       | Deck       | High     | Yes                 |
| DMAF-CAP-EXA-008 | Executive Governance & Steering Support | Executive Status Synthesis          | Executive Status Report Template       | Template   | High     | Yes                 |

---

## 14.2 Priority Asset Candidates

The highest priority Executive Advisory assets are:

1. Executive Narrative Template
2. Modernization Story Arc Template
3. Advisory Workshop Agenda Template
4. Workshop Decision Capture Template
5. Executive Decision Brief Template
6. Options and Trade-Off Matrix
7. Executive Roadmap Briefing Template
8. Modernization Journey Diagram
9. Modernization Proposal Outline
10. Proposal Positioning Statement Library
11. Executive One-Page Template
12. Modernization Before-and-After Diagram
13. Steering Committee Deck Template
14. Executive Status Report Template

---

## 14.3 Notes

Executive Advisory assets should be prioritized because they help translate DMAF into language that executives, sponsors, and decision-makers can act on.

The most important Sprint 4 build candidates from this domain are:

* Executive Narrative Template
* Executive One-Page Template
* Executive Decision Brief Template
* Modernization Proposal Outline
* Modernization Before-and-After Diagram
* Steering Committee Deck Template

Executive Advisory assets should be concise, visual, decision-oriented, and traceable to evidence.

These assets should avoid overly technical language unless the intended audience is technical leadership. They should help explain:

* why modernization matters;
* why Databricks is relevant;
* what decision is required;
* what options exist;
* what risks or constraints apply;
* what value is expected;
* what happens next.

---

# 15. Domain 8 — Platform Operations, Adoption & Value Realization

## 15.1 Method and Asset Map

| Capability ID    | Capability                                 | Candidate Method                | Candidate Asset                        | Asset Type | Priority | Workbench Potential |
| ---------------- | ------------------------------------------ | ------------------------------- | -------------------------------------- | ---------- | -------- | ------------------- |
| DMAF-CAP-POV-001 | Platform Operating Model Design            | Platform Operating Model Method | Platform Operating Model Template      | Template   | High     | Yes                 |
| DMAF-CAP-POV-001 | Platform Operating Model Design            | Role and Responsibility Mapping | Platform RACI Template                 | Template   | High     | Yes                 |
| DMAF-CAP-POV-002 | Adoption & Enablement Planning             | Adoption Planning Method        | Adoption and Enablement Plan Template  | Template   | High     | Yes                 |
| DMAF-CAP-POV-002 | Adoption & Enablement Planning             | Stakeholder Enablement Mapping  | Stakeholder Adoption Matrix            | Worksheet  | Medium   | Yes                 |
| DMAF-CAP-POV-003 | Support Model Transition                   | Support Transition Planning     | Support Model Template                 | Template   | High     | Yes                 |
| DMAF-CAP-POV-003 | Support Model Transition                   | Escalation Path Mapping         | Support Escalation Matrix              | Template   | High     | Yes                 |
| DMAF-CAP-POV-004 | Runbook & Operational Readiness Management | Runbook Development Method      | Operational Runbook Template           | Template   | High     | Yes                 |
| DMAF-CAP-POV-004 | Runbook & Operational Readiness Management | Operational Readiness Review    | Operational Readiness Checklist        | Checklist  | High     | Yes                 |
| DMAF-CAP-POV-005 | FinOps & Consumption Management            | Cost Driver Analysis            | FinOps Cost Driver Worksheet           | Worksheet  | High     | Yes                 |
| DMAF-CAP-POV-005 | FinOps & Consumption Management            | Consumption Review Method       | Platform Consumption Dashboard Concept | Dashboard  | Medium   | Yes                 |
| DMAF-CAP-POV-006 | Platform KPI & Value Realization Tracking  | Platform KPI Definition         | Platform KPI Library                   | Guide      | High     | Yes                 |
| DMAF-CAP-POV-006 | Platform KPI & Value Realization Tracking  | Value Realization Tracking      | Value Realization Tracker              | Workbook   | High     | Yes                 |
| DMAF-CAP-POV-007 | Governance Maturity Improvement            | Governance Maturity Review      | Governance Maturity Assessment         | Assessment | High     | Yes                 |
| DMAF-CAP-POV-007 | Governance Maturity Improvement            | Policy and Control Gap Review   | Governance Improvement Backlog         | Template   | Medium   | Yes                 |
| DMAF-CAP-POV-008 | Continuous Optimization Management         | Optimization Backlog Management | Continuous Optimization Backlog        | Template   | High     | Yes                 |
| DMAF-CAP-POV-008 | Continuous Optimization Management         | Continuous Improvement Cadence  | Continuous Improvement Review Template | Template   | Medium   | Yes                 |

---

## 15.2 Priority Asset Candidates

The highest priority Platform Operations, Adoption & Value Realization assets are:

1. Platform Operating Model Template
2. Platform RACI Template
3. Adoption and Enablement Plan Template
4. Support Model Template
5. Support Escalation Matrix
6. Operational Runbook Template
7. Operational Readiness Checklist
8. FinOps Cost Driver Worksheet
9. Platform KPI Library
10. Value Realization Tracker
11. Governance Maturity Assessment
12. Continuous Optimization Backlog

---

## 15.3 Notes

Platform Operations, Adoption & Value Realization assets should be prioritized because they prevent modernization from ending at technical cutover.

The most important Sprint 4 build candidates from this domain are:

* Platform Operating Model Template
* Operational Readiness Checklist
* Support Model Template
* Platform KPI Library
* Value Realization Tracker
* Continuous Optimization Backlog

These assets should help answer whether the modernized Databricks platform is:

* owned;
* governed;
* supportable;
* adopted;
* cost-aware;
* measurable;
* continuously improving.

This domain should also feed future executive value reporting and Workbench practice intelligence.

---

# 16. Domain 9 — Modernization Intelligence Workbench

## 16.1 Method and Asset Map

| Capability ID    | Capability                             | Candidate Method                  | Candidate Asset                                     | Asset Type     | Priority | Workbench Potential |
| ---------------- | -------------------------------------- | --------------------------------- | --------------------------------------------------- | -------------- | -------- | ------------------- |
| DMAF-CAP-MIW-001 | Engagement Workspace Management        | Engagement Workspace Setup Method | Engagement Workspace Template                       | Template       | High     | Yes                 |
| DMAF-CAP-MIW-001 | Engagement Workspace Management        | Input and Output Registering      | Engagement Input and Output Register                | Template       | High     | Yes                 |
| DMAF-CAP-MIW-002 | Input Ingestion & Normalization        | Input Ingestion Method            | Input Ingestion Standard                            | Standard       | High     | Yes                 |
| DMAF-CAP-MIW-002 | Input Ingestion & Normalization        | Evidence Normalization Method     | Normalized Input Schema                             | Schema         | High     | Yes                 |
| DMAF-CAP-MIW-003 | Modernization Context Interpretation   | Context Interpretation Method     | Modernization Context Interpretation Prompt Library | Prompt Library | High     | Yes                 |
| DMAF-CAP-MIW-003 | Modernization Context Interpretation   | Lifecycle and Domain Mapping      | Lifecycle and Domain Mapping Guide                  | Guide          | High     | Yes                 |
| DMAF-CAP-MIW-004 | Asset Retrieval & Recommendation       | Asset Recommendation Method       | Capability-to-Asset Recommendation Rules            | Guide          | High     | Yes                 |
| DMAF-CAP-MIW-004 | Asset Retrieval & Recommendation       | Engagement Asset Packaging        | Engagement Asset Pack Template                      | Template       | Medium   | Yes                 |
| DMAF-CAP-MIW-005 | Knowledge Graph Indexing               | Knowledge Graph Indexing Method   | Knowledge Graph Schema                              | Schema         | High     | Yes                 |
| DMAF-CAP-MIW-005 | Knowledge Graph Indexing               | Metadata Validation Method        | Metadata Validation Checklist                       | Checklist      | High     | Yes                 |
| DMAF-CAP-MIW-006 | Advisory Output Generation             | Advisory Output Generation Method | Advisory Output Generation Prompt Library           | Prompt Library | High     | Yes                 |
| DMAF-CAP-MIW-006 | Advisory Output Generation             | Output Quality Review             | Advisory Output Review Checklist                    | Checklist      | High     | Yes                 |
| DMAF-CAP-MIW-007 | Practice Intelligence Dashboarding     | Practice Metrics Definition       | Practice Intelligence Dashboard Concept             | Dashboard      | Medium   | Yes                 |
| DMAF-CAP-MIW-007 | Practice Intelligence Dashboarding     | Asset Reuse Tracking              | Asset Reuse Tracker                                 | Workbook       | Medium   | Yes                 |
| DMAF-CAP-MIW-008 | Workbench Governance & Quality Control | Workbench Quality Control Method  | Workbench Quality Checklist                         | Checklist      | High     | Yes                 |
| DMAF-CAP-MIW-008 | Workbench Governance & Quality Control | Workbench Review Workflow         | Workbench Review Queue Model                        | Workflow       | High     | Yes                 |

---

## 16.2 Priority Asset Candidates

The highest priority Modernization Intelligence Workbench assets are:

1. Engagement Workspace Template
2. Engagement Input and Output Register
3. Input Ingestion Standard
4. Normalized Input Schema
5. Modernization Context Interpretation Prompt Library
6. Lifecycle and Domain Mapping Guide
7. Capability-to-Asset Recommendation Rules
8. Knowledge Graph Schema
9. Metadata Validation Checklist
10. Advisory Output Generation Prompt Library
11. Advisory Output Review Checklist
12. Workbench Quality Checklist
13. Workbench Review Queue Model

---

## 16.3 Notes

Modernization Intelligence Workbench assets should be treated as future product-enablement assets.

The most important Sprint 4 build candidates from this domain are:

* Engagement Workspace Template
* Input Ingestion Standard
* Normalized Input Schema
* Knowledge Graph Schema
* Metadata Validation Checklist
* Workbench Quality Checklist

These assets should not be built as standalone software requirements too early. They should first define how DMAF knowledge, inputs, assets, outputs, metadata, and review workflows should behave.

The Workbench should operationalize DMAF. It should not replace:

* the Foundation Architecture;
* the Framework Core;
* the Practice Capability Catalogue;
* human review;
* governance;
* asset ownership;
* quality gates.

---

# 17. Sprint 4 Mapping Summary

## 17.1 Domain Mapping Completion

All nine approved DMAF practice domains have now been mapped to candidate methods and assets.

| Practice Domain                                   | Status |
| ------------------------------------------------- | ------ |
| Strategy & Business Value                         | Mapped |
| Discovery & Assessment                            | Mapped |
| Modernization Architecture                        | Mapped |
| Migration Factory                                 | Mapped |
| Coexistence & Validation                          | Mapped |
| AI & Automation                                   | Mapped |
| Executive Advisory                                | Mapped |
| Platform Operations, Adoption & Value Realization | Mapped |
| Modernization Intelligence Workbench              | Mapped |

---

## 17.2 Initial Mapping Counts

Most domains include 16 method-to-asset mapping rows. Strategy & Business Value includes 14 rows because it contains seven initial capabilities, while the remaining domains contain eight capabilities each.

| Practice Domain                                   | Mapping Rows |
| ------------------------------------------------- | -----------: |
| Strategy & Business Value                         |           14 |
| Discovery & Assessment                            |           16 |
| Modernization Architecture                        |           16 |
| Migration Factory                                 |           16 |
| Coexistence & Validation                          |           16 |
| AI & Automation                                   |           16 |
| Executive Advisory                                |           16 |
| Platform Operations, Adoption & Value Realization |           16 |
| Modernization Intelligence Workbench              |           16 |
| **Total**                                         |      **142** |

---

## 17.3 Recommended Priority Build List

The following assets should be considered the first high-value build candidates for future sprints:

| Priority | Asset                                     | Related Domain                                    |
| -------- | ----------------------------------------- | ------------------------------------------------- |
| 1        | Opportunity Qualification Checklist       | Strategy & Business Value                         |
| 2        | Business Value Framing Worksheet          | Strategy & Business Value                         |
| 3        | Application Inventory Workbook            | Discovery & Assessment                            |
| 4        | Workflow Inventory Workbook               | Discovery & Assessment                            |
| 5        | Modernization Complexity Scoring Workbook | Discovery & Assessment                            |
| 6        | Target-State Architecture Template        | Modernization Architecture                        |
| 7        | Databricks Platform Capability Map        | Modernization Architecture                        |
| 8        | Migration Wave Planning Workbook          | Migration Factory                                 |
| 9        | Migration Estimation Workbook             | Migration Factory                                 |
| 10       | Coexistence Strategy Template             | Coexistence & Validation                          |
| 11       | Validation Strategy Template              | Coexistence & Validation                          |
| 12       | AI Output Review Checklist                | AI & Automation                                   |
| 13       | Prompt Quality Standard                   | AI & Automation                                   |
| 14       | Executive One-Page Template               | Executive Advisory                                |
| 15       | Modernization Proposal Outline            | Executive Advisory                                |
| 16       | Platform Operating Model Template         | Platform Operations, Adoption & Value Realization |
| 17       | Value Realization Tracker                 | Platform Operations, Adoption & Value Realization |
| 18       | Engagement Workspace Template             | Modernization Intelligence Workbench              |
| 19       | Knowledge Graph Schema                    | Modernization Intelligence Workbench              |
| 20       | Workbench Quality Checklist               | Modernization Intelligence Workbench              |

---

# 18. Sprint 4 QA Review

## 18.1 QA Verdict

The DMAF Capability Method Asset Map is structurally complete at draft level.

All nine approved DMAF practice domains have been mapped to candidate methods and reusable assets.

The map is ready to support future development of:

* reusable methods;
* templates;
* workbooks;
* checklists;
* diagrams;
* prompt libraries;
* dashboards;
* Workbench specifications;
* asset backlog prioritization.

Sprint 4 confirms that DMAF is now traceable from framework concepts to capabilities, methods, and candidate assets.

---

## 18.2 Mapping Count Summary

| Practice Domain                                   | Mapping Rows | Status     |
| ------------------------------------------------- | -----------: | ---------- |
| Strategy & Business Value                         |           14 | Mapped     |
| Discovery & Assessment                            |           16 | Mapped     |
| Modernization Architecture                        |           16 | Mapped     |
| Migration Factory                                 |           16 | Mapped     |
| Coexistence & Validation                          |           16 | Mapped     |
| AI & Automation                                   |           16 | Mapped     |
| Executive Advisory                                |           16 | Mapped     |
| Platform Operations, Adoption & Value Realization |           16 | Mapped     |
| Modernization Intelligence Workbench              |           16 | Mapped     |
| **Total**                                         |      **142** | **Mapped** |

---

## 18.3 QA Results

| QA Area                               | Result | Notes                                                                                                                                                                 |
| ------------------------------------- | ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Approved practice domains represented | Pass   | All nine approved DMAF practice domains are included.                                                                                                                 |
| Capability coverage                   | Pass   | All 71 initial capabilities are represented through candidate method and asset mappings.                                                                              |
| Method mapping                        | Pass   | Each capability has at least one candidate method.                                                                                                                    |
| Asset mapping                         | Pass   | Each capability has at least one candidate reusable asset.                                                                                                            |
| Asset type classification             | Pass   | Candidate assets are identified as templates, workbooks, checklists, diagrams, guides, prompt libraries, dashboards, schemas, workflows, or related reusable formats. |
| Priority classification               | Pass   | Each mapping includes a priority level.                                                                                                                               |
| Workbench potential                   | Pass   | Each mapping identifies whether future Workbench support is possible.                                                                                                 |
| Traceability                          | Pass   | Mappings trace from capability to method to asset.                                                                                                                    |
| Terminology consistency               | Pass   | Practice domain and capability terminology align to the Practice Capability Catalogue.                                                                                |
| Sprint 4 control rule                 | Pass   | No methods or assets were introduced without being mapped to approved capabilities.                                                                                   |

---

## 18.4 Integration Result

Sprint 4 extends the DMAF traceability chain as follows:

```text
Foundation Architecture
        ↓
Framework Core
        ↓
Practice Capability Catalogue
        ↓
Capability Method Asset Map
        ↓
Future Methods
        ↓
Future Assets
        ↓
Future Workbench Services
```

This confirms that DMAF is no longer only a conceptual framework.

It now has a controlled path toward reusable consulting assets and future Workbench automation.

---

## 18.5 Priority Build Observations

The first reusable assets should focus on the highest leverage areas:

1. opportunity qualification;
2. discovery intake;
3. application and workflow inventory;
4. complexity scoring;
5. target-state architecture;
6. migration wave planning;
7. validation strategy;
8. AI output review;
9. executive one-page storytelling;
10. platform operating model;
11. Workbench metadata and quality control.

These assets will provide the strongest foundation for repeatable advisory and delivery work.

---

## 18.6 Recommended Next Sprint

The recommended next sprint is:

```text
Sprint 5 — Priority Asset Build Pack
```

Sprint 5 should not attempt to build all mapped assets.

It should select a small, high-value starter pack of reusable assets that can be used in real client-facing or internal practice scenarios.

Recommended Sprint 5 starter assets:

| Priority | Asset                                     | Domain                                            |
| -------- | ----------------------------------------- | ------------------------------------------------- |
| 1        | Opportunity Qualification Checklist       | Strategy & Business Value                         |
| 2        | Application Inventory Workbook            | Discovery & Assessment                            |
| 3        | Modernization Complexity Scoring Workbook | Discovery & Assessment                            |
| 4        | Target-State Architecture Template        | Modernization Architecture                        |
| 5        | Migration Wave Planning Workbook          | Migration Factory                                 |
| 6        | Validation Strategy Template              | Coexistence & Validation                          |
| 7        | AI Output Review Checklist                | AI & Automation                                   |
| 8        | Executive One-Page Template               | Executive Advisory                                |
| 9        | Platform Operating Model Template         | Platform Operations, Adoption & Value Realization |
| 10       | Workbench Quality Checklist               | Modernization Intelligence Workbench              |

---

## 18.7 Sprint 5 Entry Criteria

Sprint 5 may begin when the following conditions are true:

| Entry Criterion                          | Status   |
| ---------------------------------------- | -------- |
| All nine practice domains mapped         | Complete |
| Capabilities mapped to candidate methods | Complete |
| Capabilities mapped to candidate assets  | Complete |
| Candidate asset types identified         | Complete |
| Priority levels assigned                 | Complete |
| Workbench potential identified           | Complete |
| Priority build list created              | Complete |
| Sprint 4 QA review completed             | Complete |

---

# 19. Status

This Capability Method Asset Map is currently in Draft v1.0.0 status.

Sprint 4 has passed QA review.

All nine approved DMAF practice domains have been mapped to candidate methods and reusable assets, producing **142 initial method-to-asset mapping rows**.

The document is ready for Sprint 4 closure after commit.








