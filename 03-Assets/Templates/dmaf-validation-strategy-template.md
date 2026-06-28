---

asset_id: DMAF-ASSET-TPL-002
title: DMAF Validation Strategy Template
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Template

practice_domain:
- Coexistence & Validation

capability:
- DMAF-CAP-COV-004 — Validation Strategy Design

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Coexistence & Validation
- Reference Implementation / Pilot
- Migration Factory Execution
- Production Cutover

guiding_principles:
- Coexistence Is Intentional
- Trust Is Earned Through Validation
- Modernization Is an Operating Model
- Everything Is Traceable

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

## last_updated: 2026-06-28

---

# DMAF Validation Strategy Template

## 1. Purpose

The purpose of this template is to define how migrated or modernized workloads will be validated against legacy outputs, business expectations, operational requirements, and cutover acceptance criteria.

This template supports:

```text id="xkq7ot"
DMAF-CAP-COV-004 — Validation Strategy Design
```

It provides a structured way to define validation scope, comparison methods, reconciliation rules, exception handling, evidence capture, sign-off criteria, and cutover readiness.

---

## 2. Intended Audience

This template is intended for:

* migration leads;
* data engineers;
* QA leads;
* business SMEs;
* platform owners;
* data owners;
* solution architects;
* risk and compliance reviewers;
* production readiness stakeholders.

---

## 3. When to Use This Template

Use this template when:

* legacy and modernized workloads must be compared;
* migrated pipelines need business and technical validation;
* downstream outputs must be reconciled;
* parallel run expectations exist;
* production cutover requires evidence-based acceptance;
* validation rules, tolerances, and ownership need to be agreed before execution.

---

## 4. Validation Strategy Summary

| Field                         | Response                              |
| ----------------------------- | ------------------------------------- |
| Client / Account              |                                       |
| Engagement / Opportunity Name |                                       |
| Validation Strategy Version   |                                       |
| Date                          |                                       |
| Prepared By                   |                                       |
| Reviewed By                   |                                       |
| Source Platform(s)            |                                       |
| Target Platform               | Databricks / Other                    |
| Validation Status             | Draft / Review / Approved / Baselined |
| Primary Validation Owner      |                                       |
| Primary Business Approver     |                                       |
| Recommended Next Step         |                                       |

---

# 5. Validation Objectives

## 5.1 Primary Objectives

| Objective              | Description                                                               | Success Indicator                                |
| ---------------------- | ------------------------------------------------------------------------- | ------------------------------------------------ |
| Output equivalence     | Confirm that target outputs align to approved legacy or expected outputs. | Differences are within approved tolerance.       |
| Data completeness      | Confirm that expected records, files, tables, and data sets are present.  | Counts and coverage are reconciled.              |
| Business rule accuracy | Confirm that critical transformations and calculations are correct.       | Business rules pass agreed validation tests.     |
| Downstream readiness   | Confirm that downstream consumers can use target outputs.                 | Downstream acceptance is obtained.               |
| Operational readiness  | Confirm that validation can be repeated and evidenced.                    | Validation process is documented and repeatable. |

## 5.2 Engagement-Specific Objectives

| Objective | Description | Owner |
| --------- | ----------- | ----- |
|           |             |       |
|           |             |       |

---

# 6. Validation Scope

## 6.1 In-Scope Workloads

| Workload / Application | Source Platform | Target Platform | Validation Type                                                 | Owner |
| ---------------------- | --------------- | --------------- | --------------------------------------------------------------- | ----- |
|                        |                 |                 | Record count / Hash / Business rule / Output comparison / Other |       |
|                        |                 |                 | Record count / Hash / Business rule / Output comparison / Other |       |

## 6.2 Out-of-Scope Items

| Item | Reason Out of Scope | Risk / Impact |
| ---- | ------------------- | ------------- |
|      |                     |               |

## 6.3 Validation Boundary

Describe the validation boundary.

```text id="mry1xx"
Validation will begin at...
Validation will end at...
```

---

# 7. Validation Approach

## 7.1 Validation Method Summary

| Validation Method            | Description                                                             | Use When                                                     |
| ---------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------ |
| Record count comparison      | Compare row, file, or transaction counts between source and target.     | Completeness needs to be confirmed.                          |
| Hash comparison              | Compare hash totals or control totals across equivalent data sets.      | Field-level or record-level equality needs evidence.         |
| Control total reconciliation | Compare aggregated totals, balances, or financial controls.             | Financial, ledger, or reconciliation workloads are involved. |
| Business rule validation     | Validate calculations, filters, transformations, or derivations.        | Business logic is material to acceptance.                    |
| Downstream output comparison | Compare files, tables, feeds, reports, or extracts consumed downstream. | Existing consumers depend on legacy outputs.                 |
| Exception review             | Identify and explain mismatches or expected differences.                | Tolerances are exceeded or differences require triage.       |
| SME review                   | Business or technical SMEs review sampled outputs.                      | Automated comparison is insufficient.                        |

## 7.2 Selected Validation Methods

| Workload / Output | Selected Method | Rationale | Owner |
| ----------------- | --------------- | --------- | ----- |
|                   |                 |           |       |
|                   |                 |           |       |

---

# 8. Source-to-Target Comparison Design

## 8.1 Comparison Inputs

| Input               | Source Location | Target Location | Frequency                        | Notes |
| ------------------- | --------------- | --------------- | -------------------------------- | ----- |
| Source data extract |                 |                 | Daily / Weekly / Monthly / Other |       |
| Target data set     |                 |                 | Daily / Weekly / Monthly / Other |       |
| Legacy output file  |                 |                 | Daily / Weekly / Monthly / Other |       |
| Target output file  |                 |                 | Daily / Weekly / Monthly / Other |       |
| Control totals      |                 |                 | Daily / Weekly / Monthly / Other |       |

## 8.2 Comparison Keys

| Data Set / Output | Primary Comparison Key | Secondary Key | Notes |
| ----------------- | ---------------------- | ------------- | ----- |
|                   |                        |               |       |

## 8.3 Comparison Rules

| Rule ID      | Rule Description | Applies To | Expected Result |
| ------------ | ---------------- | ---------- | --------------- |
| VAL-RULE-001 |                  |            |                 |
| VAL-RULE-002 |                  |            |                 |

---

# 9. Tolerance and Exception Rules

## 9.1 Tolerance Model

| Validation Area        | Tolerance                      | Rationale | Approver |
| ---------------------- | ------------------------------ | --------- | -------- |
| Record counts          | Exact / Percentage / Threshold |           |          |
| Hash totals            | Exact / Threshold              |           |          |
| Financial totals       | Exact / Threshold              |           |          |
| Date/time fields       | Exact / Time-window tolerance  |           |          |
| Formatting differences | Allowed / Not allowed          |           |          |
| Null handling          | Allowed / Not allowed          |           |          |

## 9.2 Exception Classification

| Exception Type        | Description                                                                  | Severity      | Resolution Path             |
| --------------------- | ---------------------------------------------------------------------------- | ------------- | --------------------------- |
| Expected difference   | Difference caused by approved logic, timing, rounding, or platform behavior. | Low / Medium  | Document and approve.       |
| Data quality issue    | Difference caused by source data issue.                                      | Medium / High | Escalate to data owner.     |
| Transformation defect | Difference caused by target implementation.                                  | High          | Fix and retest.             |
| Mapping defect        | Difference caused by incorrect field, table, or business rule mapping.       | High          | Correct mapping and retest. |
| Timing issue          | Difference caused by batch timing, late data, or cutoff mismatch.            | Medium        | Adjust comparison window.   |
| Unknown variance      | Difference cannot yet be explained.                                          | High          | Triage before acceptance.   |

---

# 10. Validation Evidence

## 10.1 Evidence Required

| Evidence Type          | Description                                 | Storage Location | Owner |
| ---------------------- | ------------------------------------------- | ---------------- | ----- |
| Validation result file | Comparison results for each validation run. |                  |       |
| Exception log          | List of mismatches and disposition.         |                  |       |
| Control total report   | Summary totals and reconciliation results.  |                  |       |
| Test execution summary | Summary of validation tests run.            |                  |       |
| SME approval record    | Evidence of business or technical approval. |                  |       |
| Sign-off record        | Final acceptance decision.                  |                  |       |

## 10.2 Evidence Retention

| Evidence Category | Retention Requirement | Notes |
| ----------------- | --------------------- | ----- |
| Test results      |                       |       |
| Exception logs    |                       |       |
| Sign-offs         |                       |       |
| Audit artifacts   |                       |       |

---

# 11. Roles and Responsibilities

| Role                   | Responsibility                                           | Named Owner |
| ---------------------- | -------------------------------------------------------- | ----------- |
| Validation Lead        | Own validation strategy and execution coordination.      |             |
| Data Engineer          | Build or execute validation logic.                       |             |
| QA Lead                | Manage test planning, tracking, and defect coordination. |             |
| Business SME           | Confirm business correctness and approve exceptions.     |             |
| Data Owner             | Approve data interpretation and tolerance rules.         |             |
| Platform Owner         | Confirm target platform readiness.                       |             |
| Release / Cutover Lead | Confirm validation acceptance before cutover.            |             |

---

# 12. Validation Execution Plan

## 12.1 Validation Phases

| Phase                              | Description                                                           | Entry Criteria                     | Exit Criteria                                         |
| ---------------------------------- | --------------------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------- |
| Phase 1 — Technical Validation     | Validate counts, keys, files, schemas, and basic completeness.        | Target output created.             | Technical comparison passes or exceptions are logged. |
| Phase 2 — Business Rule Validation | Validate transformations, calculations, mappings, and business rules. | Technical validation complete.     | Business rules pass or exceptions are approved.       |
| Phase 3 — Downstream Validation    | Validate downstream outputs, files, tables, reports, or feeds.        | Business rule validation complete. | Downstream acceptance received.                       |
| Phase 4 — Cutover Validation       | Confirm readiness for production migration or cutover.                | Prior phases complete.             | Cutover sign-off obtained.                            |

## 12.2 Validation Schedule

| Validation Activity | Target Date | Owner | Status                               |
| ------------------- | ----------- | ----- | ------------------------------------ |
|                     |             |       | Not Started / In Progress / Complete |
|                     |             |       | Not Started / In Progress / Complete |

---

# 13. Parallel Run Considerations

## 13.1 Parallel Run Requirement

| Question                                   | Response           |
| ------------------------------------------ | ------------------ |
| Is parallel run required?                  | Yes / No / Unknown |
| If yes, what must run in parallel?         |                    |
| For how long?                              |                    |
| What outputs will be compared?             |                    |
| What prevents or limits full parallel run? |                    |

## 13.2 Parallel Run Constraints

| Constraint                                                     | Impact                                       | Mitigation                                                                            |
| -------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------------------------- |
| Legacy and target cannot write to the same production database | Limits apple-to-apple production comparison  | Use controlled extracts, record counts, hash totals, or dedicated validation schemas. |
| Target environment does not have production-like data volume   | Limits performance and completeness evidence | Use sampled validation plus production-volume extraction when available.              |
| Downstream consumers cannot consume duplicate outputs          | Limits full end-to-end parallel testing      | Compare staged outputs before downstream handoff.                                     |
| Batch timing differs between legacy and target                 | Causes apparent mismatches                   | Align comparison windows and cutoff times.                                            |

---

# 14. Cutover Acceptance Criteria

| Acceptance Criterion                          | Required Evidence    | Approver | Status                               |
| --------------------------------------------- | -------------------- | -------- | ------------------------------------ |
| Critical validation tests passed              | Validation results   |          | Not Started / In Progress / Complete |
| High-severity exceptions resolved or approved | Exception log        |          | Not Started / In Progress / Complete |
| Control totals reconciled                     | Control total report |          | Not Started / In Progress / Complete |
| Downstream consumers approved outputs         | Downstream sign-off  |          | Not Started / In Progress / Complete |
| Operational runbook is ready                  | Runbook review       |          | Not Started / In Progress / Complete |
| Rollback or contingency path is documented    | Cutover plan         |          | Not Started / In Progress / Complete |
| Business owner approves cutover               | Sign-off record      |          | Not Started / In Progress / Complete |

---

# 15. Risks, Assumptions, Issues, and Dependencies

## 15.1 Risks

| Risk                            | Impact                                   | Mitigation                                                          | Owner |
| ------------------------------- | ---------------------------------------- | ------------------------------------------------------------------- | ----- |
| Validation data is incomplete   | Acceptance evidence may be weak          | Confirm data access and extraction early.                           |       |
| Business rules are undocumented | Defects may be hard to identify          | Involve SMEs and infer rules from legacy outputs where appropriate. |       |
| Legacy outputs are not stable   | Comparisons may produce false mismatches | Define approved comparison windows and source baselines.            |       |
| Parallel run is not feasible    | Full equivalence testing may be limited  | Use counts, hashes, control totals, and staged output comparisons.  |       |

## 15.2 Assumptions

| Assumption                                                 | Validation Needed                       | Owner |
| ---------------------------------------------------------- | --------------------------------------- | ----- |
| Source and target outputs can be extracted for comparison. | Confirm access and extraction path.     |       |
| Business SMEs will be available to review exceptions.      | Confirm SME availability.               |       |
| Tolerance rules can be agreed before cutover.              | Confirm approvers and decision process. |       |

## 15.3 Issues

| Issue | Impact | Resolution Path | Owner |
| ----- | ------ | --------------- | ----- |
|       |        |                 |       |

## 15.4 Dependencies

| Dependency                 | Related Area         | Status                               | Owner |
| -------------------------- | -------------------- | ------------------------------------ | ----- |
| Source data access         | Technical validation | Not Started / In Progress / Complete |       |
| Target output availability | Validation execution | Not Started / In Progress / Complete |       |
| SME review availability    | Business validation  | Not Started / In Progress / Complete |       |
| Cutover decision path      | Acceptance           | Not Started / In Progress / Complete |       |

---

# 16. Validation Review Checklist

| Review Item                                                 | Complete |
| ----------------------------------------------------------- | -------- |
| Validation objectives are documented                        |          |
| In-scope and out-of-scope workloads are defined             |          |
| Validation boundary is clear                                |          |
| Comparison inputs are identified                            |          |
| Comparison keys are identified                              |          |
| Validation methods are selected                             |          |
| Tolerance model is documented                               |          |
| Exception classification is documented                      |          |
| Evidence requirements are documented                        |          |
| Roles and responsibilities are assigned                     |          |
| Parallel run requirement is documented                      |          |
| Parallel run constraints are documented                     |          |
| Cutover acceptance criteria are documented                  |          |
| Risks, assumptions, issues, and dependencies are documented |          |

---

# 17. Workbench Potential

This asset may eventually support the following Modernization Intelligence Workbench capabilities:

* validation strategy draft generation;
* comparison rule extraction;
* validation evidence tracking;
* exception classification;
* cutover readiness scoring;
* risk and constraint detection;
* parallel run feasibility analysis;
* validation dashboard generation.

---

# 18. Status

This Validation Strategy Template is currently in Draft v0.1.0 status.

It is the sixth reusable asset created in Sprint 5.
