---

asset_id: DMAF-ASSET-TPL-004
title: DMAF Platform Operating Model Template
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Template

practice_domain:
- Platform Operations, Adoption & Value Realization

capability:
- DMAF-CAP-POV-001 — Platform Operating Model Design

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- FinOps & Cost Optimization
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Platform Operations, Adoption & Value Realization
- Production Cutover
- Continuous Optimization & Modernization Intelligence

guiding_principles:
- Modernization Is an Operating Model
- Databricks by Design
- Platform Value Is the Destination
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

## last_updated: 2026-06-28

---

# DMAF Platform Operating Model Template

## 1. Purpose

The purpose of this template is to define the operating model required to sustain, govern, support, optimize, and continuously improve a Databricks-led modernization platform after initial delivery.

This template supports:

```text id="u6dh4p"
DMAF-CAP-POV-001 — Platform Operating Model Design
```

Modernization does not end when workloads are migrated. Platform value is realized when ownership, governance, support, cost management, enablement, service delivery, and continuous improvement are embedded into the operating model.

---

## 2. Intended Audience

This template is intended for:

* platform owners;
* data platform leads;
* operations leaders;
* data engineering managers;
* governance leads;
* security leads;
* FinOps leads;
* service management teams;
* solution architects;
* delivery leads;
* executive sponsors.

---

## 3. When to Use This Template

Use this template when:

* a Databricks modernization program is moving toward production;
* platform ownership needs to be clarified;
* support and escalation models need to be defined;
* governance responsibilities need to be operationalized;
* cost management and optimization practices are required;
* adoption and enablement need to be planned;
* the client needs a target operating model for platform value realization.

---

## 4. Operating Model Summary

| Field                        | Response                              |
| ---------------------------- | ------------------------------------- |
| Client / Account             |                                       |
| Engagement / Initiative Name |                                       |
| Operating Model Version      |                                       |
| Date                         |                                       |
| Prepared By                  |                                       |
| Reviewed By                  |                                       |
| Target Platform              | Databricks / Other                    |
| Operating Model Status       | Draft / Review / Approved / Baselined |
| Primary Platform Owner       |                                       |
| Primary Operations Owner     |                                       |
| Primary Governance Owner     |                                       |
| Recommended Next Step        |                                       |

---

# 5. Operating Model Objectives

## 5.1 Primary Objectives

| Objective                   | Description                                                                       | Success Indicator                                                |
| --------------------------- | --------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Define ownership            | Clarify who owns the platform, workloads, data products, governance, and support. | Named owners and responsibilities are agreed.                    |
| Operationalize governance   | Move governance from policy intent into repeatable platform processes.            | Access, lineage, catalog, and controls are managed consistently. |
| Enable reliable support     | Define how incidents, requests, issues, and escalations are handled.              | Support model and escalation paths are clear.                    |
| Manage cost and consumption | Establish FinOps visibility, accountability, and optimization practices.          | Usage and cost trends are monitored and acted on.                |
| Drive adoption              | Enable users, teams, and stakeholders to use the platform effectively.            | Training, onboarding, and enablement plans exist.                |
| Realize platform value      | Measure business and operational outcomes from modernization.                     | KPIs and value measures are tracked.                             |

## 5.2 Engagement-Specific Objectives

| Objective | Description | Owner |
| --------- | ----------- | ----- |
|           |             |       |
|           |             |       |

---

# 6. Platform Scope

## 6.1 In-Scope Platform Areas

| Area                          | In Scope       | Notes |
| ----------------------------- | -------------- | ----- |
| Workspaces / environments     | Yes / No / TBD |       |
| Data engineering workloads    | Yes / No / TBD |       |
| SQL analytics workloads       | Yes / No / TBD |       |
| ML / AI workloads             | Yes / No / TBD |       |
| Governance and Unity Catalog  | Yes / No / TBD |       |
| Data products                 | Yes / No / TBD |       |
| Integration and orchestration | Yes / No / TBD |       |
| Monitoring and support        | Yes / No / TBD |       |
| Cost management               | Yes / No / TBD |       |
| Adoption and enablement       | Yes / No / TBD |       |

## 6.2 Out-of-Scope Areas

| Area | Reason Out of Scope | Risk / Impact |
| ---- | ------------------- | ------------- |
|      |                     |               |

---

# 7. Operating Model Roles

## 7.1 Core Roles

| Role                      | Primary Responsibility                                                                   | Named Owner / Team |
| ------------------------- | ---------------------------------------------------------------------------------------- | ------------------ |
| Executive Sponsor         | Owns executive alignment, funding, and strategic direction.                              |                    |
| Platform Owner            | Owns platform roadmap, platform value, and service accountability.                       |                    |
| Platform Engineering Team | Manages platform configuration, environment setup, automation, and technical enablement. |                    |
| Data Engineering Team     | Builds, maintains, and improves data pipelines and data products.                        |                    |
| Governance Owner          | Owns data governance practices, cataloging, lineage, and policy alignment.               |                    |
| Security Owner            | Owns identity, access, security controls, and risk alignment.                            |                    |
| Operations / Support Lead | Owns incident management, service requests, escalation, and operational readiness.       |                    |
| FinOps Owner              | Owns cost visibility, usage reporting, optimization, and accountability.                 |                    |
| Business Data Owner       | Owns business meaning, data quality expectations, and acceptance criteria.               |                    |
| Product Owner             | Owns backlog, prioritization, outcomes, and stakeholder alignment for data products.     |                    |

## 7.2 RACI Model

| Activity                    | Executive Sponsor | Platform Owner | Platform Engineering | Data Engineering | Governance | Security | Operations | FinOps | Business Owner |
| --------------------------- | ----------------- | -------------- | -------------------- | ---------------- | ---------- | -------- | ---------- | ------ | -------------- |
| Platform roadmap            | A                 | R              | C                    | C                | C          | C        | C          | C      | C              |
| Workspace provisioning      | I                 | A              | R                    | C                | C          | C        | C          | I      | I              |
| Access management           | I                 | A              | C                    | I                | C          | R        | C          | I      | C              |
| Data product ownership      | I                 | C              | C                    | R                | C          | C        | I          | I      | A              |
| Job monitoring              | I                 | A              | C                    | R                | I          | I        | R          | I      | I              |
| Incident response           | I                 | A              | C                    | R                | I          | C        | R          | I      | I              |
| Cost monitoring             | I                 | A              | C                    | C                | I          | I        | I          | R      | I              |
| Governance policy execution | I                 | A              | C                    | C                | R          | C        | I          | I      | C              |
| Release management          | I                 | A              | C                    | R                | C          | C        | R          | I      | I              |
| Value reporting             | A                 | R              | C                    | C                | C          | I        | C          | C      | C              |

Legend:

```text id="8vlekq"
R = Responsible
A = Accountable
C = Consulted
I = Informed
```

---

# 8. Platform Services

## 8.1 Service Catalogue

| Platform Service          | Description                                                     | Service Owner | Users / Consumers |
| ------------------------- | --------------------------------------------------------------- | ------------- | ----------------- |
| Workspace provisioning    | Create and configure workspaces or environments.                |               |                   |
| Access provisioning       | Manage user, group, role, and permission requests.              |               |                   |
| Data pipeline deployment  | Promote and deploy workloads across environments.               |               |                   |
| Job monitoring            | Monitor workflow execution, failures, and performance.          |               |                   |
| Incident management       | Respond to production issues and service disruptions.           |               |                   |
| Data governance support   | Support catalog, lineage, classification, and policy execution. |               |                   |
| Cost reporting            | Provide usage, cost, and optimization reporting.                |               |                   |
| Enablement and onboarding | Help teams adopt platform standards and practices.              |               |                   |

## 8.2 Service Expectations

| Service                 | Expected Response | Expected Resolution / Outcome | Notes |
| ----------------------- | ----------------- | ----------------------------- | ----- |
| Access request          |                   |                               |       |
| Job failure             |                   |                               |       |
| Production incident     |                   |                               |       |
| New workload onboarding |                   |                               |       |
| Cost anomaly review     |                   |                               |       |
| Governance issue        |                   |                               |       |

---

# 9. Support and Escalation Model

## 9.1 Support Levels

| Support Level                                 | Description                                                                   | Owner |
| --------------------------------------------- | ----------------------------------------------------------------------------- | ----- |
| Level 0 — Self-Service                        | Documentation, FAQs, standards, reusable templates, and enablement materials. |       |
| Level 1 — Initial Support                     | Intake, triage, common request handling, and basic issue routing.             |       |
| Level 2 — Platform / Data Engineering Support | Technical investigation, workload issue resolution, pipeline support.         |       |
| Level 3 — Specialist / Vendor Support         | Advanced platform, architecture, security, or Databricks support escalation.  |       |

## 9.2 Escalation Path

| Trigger                     | Escalation Path | Target Response | Notes |
| --------------------------- | --------------- | --------------- | ----- |
| Production job failure      |                 |                 |       |
| Data quality issue          |                 |                 |       |
| Access or permission issue  |                 |                 |       |
| Cost anomaly                |                 |                 |       |
| Security concern            |                 |                 |       |
| Governance policy exception |                 |                 |       |

---

# 10. Governance Operations

## 10.1 Governance Practices

| Governance Practice          | Operating Model Requirement                                     | Owner |
| ---------------------------- | --------------------------------------------------------------- | ----- |
| Catalog and schema standards | Define and maintain naming, ownership, and usage standards.     |       |
| Access control               | Manage roles, groups, permissions, and privileged access.       |       |
| Data classification          | Classify data according to sensitivity and usage expectations.  |       |
| Lineage management           | Monitor and use lineage for impact analysis and trust.          |       |
| Data quality management      | Define data quality expectations, rules, and remediation paths. |       |
| Policy exception management  | Track, approve, and review governance exceptions.               |       |
| Audit readiness              | Maintain evidence for access, lineage, changes, and controls.   |       |

## 10.2 Governance Review Cadence

| Review                     | Frequency           | Participants | Output |
| -------------------------- | ------------------- | ------------ | ------ |
| Access review              | Monthly / Quarterly |              |        |
| Data quality review        | Monthly / Quarterly |              |        |
| Catalog ownership review   | Quarterly           |              |        |
| Policy exception review    | Monthly / Quarterly |              |        |
| Platform governance review | Quarterly           |              |        |

---

# 11. FinOps and Cost Management

## 11.1 Cost Drivers

| Cost Driver                   | Monitoring Approach | Owner |
| ----------------------------- | ------------------- | ----- |
| Compute usage                 |                     |       |
| Job frequency and duration    |                     |       |
| Cluster / warehouse sizing    |                     |       |
| Storage growth                |                     |       |
| Data movement                 |                     |       |
| Environment duplication       |                     |       |
| Premium platform capabilities |                     |       |

## 11.2 FinOps Practices

| Practice              | Description                                                               | Cadence             |
| --------------------- | ------------------------------------------------------------------------- | ------------------- |
| Usage reporting       | Provide regular reporting on consumption and trends.                      | Weekly / Monthly    |
| Cost allocation       | Attribute platform usage to teams, products, or workloads where possible. | Monthly             |
| Cost anomaly review   | Investigate unusual spikes or consumption patterns.                       | Weekly / Monthly    |
| Optimization backlog  | Track cost optimization actions and ownership.                            | Monthly             |
| Workload right-sizing | Review compute sizing, scheduling, and performance.                       | Monthly / Quarterly |

---

# 12. Adoption and Enablement

## 12.1 Stakeholder Groups

| Stakeholder Group   | Adoption Need                                                   | Enablement Approach |
| ------------------- | --------------------------------------------------------------- | ------------------- |
| Data engineers      | Platform standards, pipeline patterns, deployment practices.    |                     |
| Analysts            | SQL access, governed data discovery, reporting patterns.        |                     |
| Business users      | Data product usage, trust signals, support paths.               |                     |
| Platform operations | Monitoring, incident response, escalation, cost controls.       |                     |
| Governance team     | Catalog, lineage, access, data classification, audit practices. |                     |
| Executives          | Value realization, KPI reporting, risk and adoption progress.   |                     |

## 12.2 Enablement Plan

| Enablement Activity                 | Audience | Owner | Target Date |
| ----------------------------------- | -------- | ----- | ----------- |
| Platform onboarding session         |          |       |             |
| Governance standards walkthrough    |          |       |             |
| Data engineering pattern review     |          |       |             |
| Job monitoring and support training |          |       |             |
| FinOps reporting walkthrough        |          |       |             |

---

# 13. Operational Readiness

## 13.1 Readiness Areas

| Readiness Area                         | Status                               | Notes |
| -------------------------------------- | ------------------------------------ | ----- |
| Platform ownership defined             | Not Started / In Progress / Complete |       |
| Support model defined                  | Not Started / In Progress / Complete |       |
| Escalation paths defined               | Not Started / In Progress / Complete |       |
| Governance operating processes defined | Not Started / In Progress / Complete |       |
| FinOps reporting defined               | Not Started / In Progress / Complete |       |
| Monitoring approach defined            | Not Started / In Progress / Complete |       |
| Release management defined             | Not Started / In Progress / Complete |       |
| Documentation created                  | Not Started / In Progress / Complete |       |
| Enablement plan created                | Not Started / In Progress / Complete |       |
| Value realization reporting defined    | Not Started / In Progress / Complete |       |

## 13.2 Cutover Readiness Link

| Cutover Dependency  | Operating Model Requirement                  | Status                               |
| ------------------- | -------------------------------------------- | ------------------------------------ |
| Production support  | Support owner and process confirmed          | Not Started / In Progress / Complete |
| Incident response   | Escalation path confirmed                    | Not Started / In Progress / Complete |
| Access management   | Ownership and approval path confirmed        | Not Started / In Progress / Complete |
| Cost monitoring     | Reporting and owner confirmed                | Not Started / In Progress / Complete |
| Governance controls | Policy execution and evidence path confirmed | Not Started / In Progress / Complete |

---

# 14. Value Realization

## 14.1 Platform KPIs

| KPI                  | Description                                                                    | Owner | Reporting Cadence |
| -------------------- | ------------------------------------------------------------------------------ | ----- | ----------------- |
| Platform adoption    | Number of teams, users, workloads, or data products onboarded.                 |       |                   |
| Delivery throughput  | Number of workloads delivered or modernized over time.                         |       |                   |
| Job reliability      | Success rate, failure rate, restart frequency, or SLA performance.             |       |                   |
| Data quality         | Quality rule pass rate, defect trends, or exception volume.                    |       |                   |
| Governance coverage  | Percentage of assets with owner, classification, lineage, and access controls. |       |                   |
| Cost transparency    | Percentage of cost attributable to teams, products, or workloads.              |       |                   |
| Optimization savings | Cost or efficiency improvements from optimization actions.                     |       |                   |
| User satisfaction    | Feedback from users, teams, or stakeholders.                                   |       |                   |

## 14.2 Value Reporting

| Value Area            | Metric | Baseline | Target | Current |
| --------------------- | ------ | -------: | -----: | ------: |
| Risk reduction        |        |          |        |         |
| Cost optimization     |        |          |        |         |
| Delivery acceleration |        |          |        |         |
| Governance maturity   |        |          |        |         |
| Data trust            |        |          |        |         |
| AI readiness          |        |          |        |         |

---

# 15. Continuous Improvement

## 15.1 Improvement Backlog

| Improvement Item | Category                                                          | Priority            | Owner | Status                               |
| ---------------- | ----------------------------------------------------------------- | ------------------- | ----- | ------------------------------------ |
|                  | Governance / Operations / FinOps / Adoption / Reliability / Other | High / Medium / Low |       | Not Started / In Progress / Complete |
|                  | Governance / Operations / FinOps / Adoption / Reliability / Other | High / Medium / Low |       | Not Started / In Progress / Complete |

## 15.2 Review Cadence

| Review                     | Frequency           | Purpose                                                             |
| -------------------------- | ------------------- | ------------------------------------------------------------------- |
| Platform operations review | Weekly / Monthly    | Review incidents, service requests, reliability, and support needs. |
| Governance review          | Monthly / Quarterly | Review access, policy exceptions, data quality, and lineage.        |
| FinOps review              | Monthly             | Review cost trends, anomalies, and optimization actions.            |
| Value realization review   | Monthly / Quarterly | Review platform value, adoption, KPIs, and executive reporting.     |
| Roadmap review             | Quarterly           | Review future platform needs and modernization priorities.          |

---

# 16. Risks, Assumptions, Issues, and Dependencies

## 16.1 Risks

| Risk                              | Impact                                                | Mitigation                                                         | Owner |
| --------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------ | ----- |
| Ownership is unclear              | Platform issues may not be resolved effectively.      | Confirm accountable owners before production cutover.              |       |
| Support model is immature         | Incidents and requests may be handled inconsistently. | Define support levels, escalation paths, and service expectations. |       |
| Governance is not operationalized | Policies may exist but not be consistently applied.   | Define operational governance practices and review cadence.        |       |
| Costs are not transparent         | Consumption may grow without accountability.          | Establish FinOps reporting and optimization backlog.               |       |
| Adoption is weak                  | Platform value may not be realized.                   | Create enablement plan and adoption KPIs.                          |       |

## 16.2 Assumptions

| Assumption                                                                | Validation Needed                      | Owner |
| ------------------------------------------------------------------------- | -------------------------------------- | ----- |
| Platform ownership can be assigned.                                       | Confirm named owner or team.           |       |
| Governance and security teams will participate in operating model design. | Confirm stakeholder availability.      |       |
| Cost and usage data will be available for reporting.                      | Confirm reporting source and access.   |       |
| Support processes can align with existing enterprise service management.  | Confirm ITSM integration expectations. |       |

## 16.3 Issues

| Issue | Impact | Resolution Path | Owner |
| ----- | ------ | --------------- | ----- |
|       |        |                 |       |

## 16.4 Dependencies

| Dependency                  | Related Area          | Status                               | Owner |
| --------------------------- | --------------------- | ------------------------------------ | ----- |
| Platform ownership decision | Operating model       | Not Started / In Progress / Complete |       |
| Governance standards        | Governance operations | Not Started / In Progress / Complete |       |
| Security model              | Access and controls   | Not Started / In Progress / Complete |       |
| Cost reporting access       | FinOps                | Not Started / In Progress / Complete |       |
| Support process alignment   | Operations            | Not Started / In Progress / Complete |       |

---

# 17. Operating Model Review Checklist

| Review Item                                                 | Complete |
| ----------------------------------------------------------- | -------- |
| Platform scope is defined                                   |          |
| Platform owner is identified                                |          |
| Core roles are documented                                   |          |
| RACI model is reviewed                                      |          |
| Platform services are documented                            |          |
| Support levels are defined                                  |          |
| Escalation paths are defined                                |          |
| Governance operating practices are documented               |          |
| FinOps practices are documented                             |          |
| Adoption and enablement needs are documented                |          |
| Operational readiness areas are reviewed                    |          |
| Value realization KPIs are identified                       |          |
| Continuous improvement cadence is defined                   |          |
| Risks, assumptions, issues, and dependencies are documented |          |

---

# 18. Workbench Potential

This asset may eventually support the following Modernization Intelligence Workbench capabilities:

* operating model draft generation;
* RACI model generation;
* platform ownership gap detection;
* support model recommendation;
* governance operating model assessment;
* FinOps practice assessment;
* adoption plan generation;
* operational readiness scoring;
* value realization dashboard input generation.

---

# 19. Status

This Platform Operating Model Template is currently in Draft v0.1.0 status.

It is the ninth reusable asset created in Sprint 5.
