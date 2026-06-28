---

asset_id: DMAF-ASSET-CHK-001
title: DMAF Opportunity Qualification Checklist
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Checklist

practice_domain:
- Strategy & Business Value

capability:
- DMAF-CAP-SBV-001 — Modernization Opportunity Qualification

cross_cutting_capabilities:
- Risk & Compliance
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Strategy & Business Value

guiding_principles:
- Business Value Before Technology
- Databricks by Design
- Modernization Is an Operating Model
- Everything Is Traceable

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

## last_updated: 2026-06-28

---

# DMAF Opportunity Qualification Checklist

## 1. Purpose

The purpose of this checklist is to determine whether a modernization opportunity is real, strategically aligned, valuable, actionable, and appropriate for a Databricks-led advisory or delivery motion.

This checklist supports:

```text id="lhyk5i"
DMAF-CAP-SBV-001 — Modernization Opportunity Qualification
```

It is intended for early-stage opportunity review before detailed discovery, architecture, estimation, or proposal development begins.

---

## 2. Intended Audience

This checklist is intended for:

* account executives;
* engagement leads;
* practice leads;
* solution architects;
* Databricks practice leaders;
* advisory team members involved in early opportunity shaping.

---

## 3. When to Use This Checklist

Use this checklist when:

* a client raises a modernization need;
* a legacy data platform migration is being discussed;
* a Databricks modernization opportunity is emerging;
* a proposal or discovery phase is being considered;
* the client has a deadline, mandate, risk, cost, platform, or AI-readiness driver;
* the team needs to decide whether to proceed, defer, reshape, or decline the opportunity.

---

## 4. Qualification Summary

| Field                        | Response                                            |
| ---------------------------- | --------------------------------------------------- |
| Client / Account             |                                                     |
| Opportunity Name             |                                                     |
| Date Reviewed                |                                                     |
| Reviewed By                  |                                                     |
| Primary Client Sponsor       |                                                     |
| Current Stage                |                                                     |
| Recommended Next Step        |                                                     |
| Overall Qualification Status | Proceed / Proceed with Conditions / Defer / Decline |

---

# 5. Business Driver Qualification

## 5.1 Business Driver Questions

| Question                                                                                                                                            | Response | Notes |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----- |
| What business problem is driving the modernization discussion?                                                                                      |          |       |
| Why is the client considering modernization now?                                                                                                    |          |       |
| Is there a deadline, mandate, risk event, funding trigger, or platform constraint?                                                                  |          |       |
| Is the driver business value, cost reduction, risk reduction, technology deprecation, regulatory pressure, AI readiness, or operating model change? |          |       |
| Is the problem important enough to justify executive attention?                                                                                     |          |       |
| Is there evidence that the current-state platform is limiting business outcomes?                                                                    |          |       |

## 5.2 Business Driver Assessment

| Assessment Item                                      | Yes / No / Unknown | Notes |
| ---------------------------------------------------- | ------------------ | ----- |
| Business driver is clear                             |                    |       |
| Timing driver is clear                               |                    |       |
| Pain point is material                               |                    |       |
| Modernization need is credible                       |                    |       |
| Opportunity is more than generic technology interest |                    |       |
| Business impact can be described                     |                    |       |

---

# 6. Databricks Fit Qualification

## 6.1 Databricks Fit Questions

| Question                                                                                                        | Response | Notes |
| --------------------------------------------------------------------------------------------------------------- | -------- | ----- |
| Why is Databricks relevant to this opportunity?                                                                 |          |       |
| Is the client already using Databricks?                                                                         |          |       |
| Is the client evaluating Databricks?                                                                            |          |       |
| Is the target-state direction already Databricks-centered?                                                      |          |       |
| Are lakehouse, Delta Lake, Unity Catalog, data engineering, analytics, or AI-readiness needs present?           |          |       |
| Is there an opportunity to position Databricks as a modernization platform rather than only a migration target? |          |       |

## 6.2 Databricks Fit Assessment

| Assessment Item                              | Yes / No / Unknown | Notes |
| -------------------------------------------- | ------------------ | ----- |
| Databricks relevance is clear                |                    |       |
| Modernization aligns to Databricks strengths |                    |       |
| Platform value can be articulated            |                    |       |
| Governance or Unity Catalog relevance exists |                    |       |
| AI-readiness relevance exists                |                    |       |
| Databricks-first positioning is appropriate  |                    |       |

---

# 7. Current-State Qualification

## 7.1 Current-State Questions

| Question                                                                                             | Response | Notes |
| ---------------------------------------------------------------------------------------------------- | -------- | ----- |
| What current-state platforms, tools, or workloads are in scope?                                      |          |       |
| Are legacy ETL, data warehouse, mainframe, reporting, batch, or data integration workloads involved? |          |       |
| Are applications, workflows, tables, files, jobs, or data products known?                            |          |       |
| Is an inventory available?                                                                           |          |       |
| Are upstream and downstream dependencies known?                                                      |          |       |
| Is the current environment stable, fragile, costly, constrained, or being retired?                   |          |       |

## 7.2 Current-State Assessment

| Assessment Item                                    | Yes / No / Unknown | Notes |
| -------------------------------------------------- | ------------------ | ----- |
| Source platform is known                           |                    |       |
| Initial scope is understood                        |                    |       |
| Inventory exists or can be created                 |                    |       |
| Key dependencies are at least partially understood |                    |       |
| Current-state pain points are credible             |                    |       |
| Discovery is feasible                              |                    |       |

---

# 8. Executive Sponsorship Qualification

## 8.1 Sponsorship Questions

| Question                                                           | Response | Notes |
| ------------------------------------------------------------------ | -------- | ----- |
| Who owns the modernization problem?                                |          |       |
| Who controls or influences funding?                                |          |       |
| Who will approve next steps?                                       |          |       |
| Is there an executive sponsor?                                     |          |       |
| Are business, technology, data, and platform stakeholders aligned? |          |       |
| Is there a known decision path?                                    |          |       |

## 8.2 Sponsorship Assessment

| Assessment Item                          | Yes / No / Unknown | Notes |
| ---------------------------------------- | ------------------ | ----- |
| Executive sponsor identified             |                    |       |
| Business owner identified                |                    |       |
| Technology owner identified              |                    |       |
| Funding path is understood               |                    |       |
| Decision path is understood              |                    |       |
| Stakeholder alignment risk is manageable |                    |       |

---

# 9. Scope and Complexity Qualification

## 9.1 Scope Questions

| Question                                                                                                                                 | Response | Notes |
| ---------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----- |
| What is the likely modernization scope?                                                                                                  |          |       |
| Is the scope one workload, one application, multiple applications, or an enterprise portfolio?                                           |          |       |
| Are known source platforms involved, such as Informatica, mainframe, SSIS, DataStage, Hadoop, Teradata, Oracle ETL, or custom pipelines? |          |       |
| Are there major data volumes, batch windows, business rules, or downstream impacts?                                                      |          |       |
| Are there coexistence or parallel run expectations?                                                                                      |          |       |
| Are there validation, audit, or reconciliation requirements?                                                                             |          |       |

## 9.2 Scope Assessment

| Assessment Item                                  | Yes / No / Unknown | Notes |
| ------------------------------------------------ | ------------------ | ----- |
| Initial scope can be described                   |                    |       |
| Complexity appears manageable for discovery      |                    |       |
| Major unknowns are documented                    |                    |       |
| Coexistence needs are identified                 |                    |       |
| Validation needs are identified                  |                    |       |
| Scope is suitable for a structured DMAF approach |                    |       |

---

# 10. Risk and Constraint Qualification

## 10.1 Risk Questions

| Question                                                                                                                | Response | Notes |
| ----------------------------------------------------------------------------------------------------------------------- | -------- | ----- |
| What are the known risks?                                                                                               |          |       |
| What constraints are already known?                                                                                     |          |       |
| Are there deadline, budget, platform, security, regulatory, data quality, environment, or SME availability constraints? |          |       |
| Are there production parallel run limitations?                                                                          |          |       |
| Are there data access or governance barriers?                                                                           |          |       |
| Are there risks that should prevent immediate pursuit?                                                                  |          |       |

## 10.2 Risk Assessment

| Assessment Item                                  | Yes / No / Unknown | Notes |
| ------------------------------------------------ | ------------------ | ----- |
| Major risks are identified                       |                    |       |
| Major constraints are identified                 |                    |       |
| Risks are not disqualifying                      |                    |       |
| Constraints can be explored through discovery    |                    |       |
| Assumptions are documented                       |                    |       |
| Opportunity can proceed with appropriate caveats |                    |       |

---

# 11. Value Hypothesis

## 11.1 Candidate Value Drivers

Select all that apply.

| Value Driver                                    | Applies | Notes |
| ----------------------------------------------- | ------- | ----- |
| Reduce legacy platform risk                     |         |       |
| Retire or reduce dependency on legacy tooling   |         |       |
| Improve data engineering speed                  |         |       |
| Improve data quality, trust, and validation     |         |       |
| Improve governance and access control           |         |       |
| Improve cost transparency or platform economics |         |       |
| Enable AI, analytics, or data products          |         |       |
| Improve operating model maturity                |         |       |
| Improve scalability or performance              |         |       |
| Improve auditability or compliance posture      |         |       |

## 11.2 Initial Value Hypothesis

Write the initial value hypothesis below.

```text id="sp8kn1"
Modernization may create value by...
```

---

# 12. Recommended Next Step

## 12.1 Decision Options

| Option                  | Use When                                                                                                 |
| ----------------------- | -------------------------------------------------------------------------------------------------------- |
| Proceed to Discovery    | Business driver, sponsor, scope, and Databricks fit are credible enough to begin structured discovery.   |
| Proceed with Conditions | Opportunity is promising, but specific gaps or risks must be clarified before full pursuit.              |
| Defer                   | Opportunity is real but timing, sponsorship, scope, or funding is not ready.                             |
| Reshape                 | Opportunity needs to be reframed around a clearer business driver, scope, value case, or decision path.  |
| Decline                 | Opportunity is not aligned to DMAF, Databricks modernization, or realistic advisory/delivery conditions. |

## 12.2 Recommendation

| Field                    | Response                                                      |
| ------------------------ | ------------------------------------------------------------- |
| Recommended Decision     | Proceed / Proceed with Conditions / Defer / Reshape / Decline |
| Rationale                |                                                               |
| Conditions or Caveats    |                                                               |
| Recommended Next Meeting |                                                               |
| Recommended Next Asset   |                                                               |
| Owner                    |                                                               |
| Target Date              |                                                               |

---

# 13. Review Checklist

Before closing the qualification review, confirm:

| Review Item                                | Complete |
| ------------------------------------------ | -------- |
| Business driver is documented              |          |
| Databricks relevance is documented         |          |
| Current-state scope is described           |          |
| Sponsor or decision path is identified     |          |
| Known risks and constraints are documented |          |
| Initial value hypothesis is written        |          |
| Assumptions are separated from facts       |          |
| Recommended next step is clear             |          |
| Decision rationale is documented           |          |
| Follow-up owner is assigned                |          |

---

# 14. Workbench Potential

This asset may eventually support the following Modernization Intelligence Workbench capabilities:

* opportunity intake;
* modernization signal detection;
* value hypothesis generation;
* sponsor and decision-path capture;
* risk and constraint extraction;
* recommended next-step generation;
* qualification scoring;
* engagement workspace creation.

---

# 15. Status

This Opportunity Qualification Checklist is currently in Draft v0.1.0 status.

It is the first reusable asset created in Sprint 5.
