---

asset_id: DMAF-ASSET-TPL-001
title: DMAF Target-State Architecture Template
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Template

practice_domain:
- Modernization Architecture

capability:
- DMAF-CAP-MAR-001 — Target-State Architecture Design

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- FinOps & Cost Optimization
- AI Enablement
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Modernization Architecture
- Reference Implementation / Pilot
- Platform Operations, Adoption & Value Realization

guiding_principles:
- Business Value Before Technology
- Databricks by Design
- Modernization Is an Operating Model
- Platform Value Is the Destination
- Everything Is Traceable

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Practice-Domains/dmaf-practice-domain-model.md
- 01-Framework/Lifecycle/dmaf-lifecycle-model.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

## last_updated: 2026-06-28

---

# DMAF Target-State Architecture Template

## 1. Purpose

The purpose of this template is to define a structured target-state architecture for a Databricks-led modernization engagement.

This template supports:

```text
DMAF-CAP-MAR-001 — Target-State Architecture Design
```

It helps architecture teams connect business objectives, discovery findings, current-state constraints, Databricks platform capabilities, governance needs, integration requirements, migration strategy, and future operating model considerations into a coherent architecture direction.

---

## 2. Intended Audience

This template is intended for:

* solution architects;
* enterprise architects;
* data architects;
* Databricks practice leads;
* migration leads;
* platform leads;
* engagement leads;
* executive stakeholders requiring architecture-level clarity.

---

## 3. When to Use This Template

Use this template when:

* a modernization opportunity has completed initial discovery;
* the target-state platform direction is Databricks-centered;
* the team needs to define architecture before migration planning;
* the client needs a structured architecture recommendation;
* there are coexistence, governance, integration, or validation implications;
* the architecture will inform a pilot, reference implementation, roadmap, or migration factory plan.

---

## 4. Architecture Summary

| Field                         | Response                                                   |
| ----------------------------- | ---------------------------------------------------------- |
| Client / Account              |                                                            |
| Engagement / Opportunity Name |                                                            |
| Architecture Version          |                                                            |
| Date                          |                                                            |
| Prepared By                   |                                                            |
| Reviewed By                   |                                                            |
| Primary Business Sponsor      |                                                            |
| Primary Technology Sponsor    |                                                            |
| Architecture Status           | Draft / Review / Approved / Baselined                      |
| Target Platform               | Azure Databricks / AWS Databricks / GCP Databricks / Other |
| Source Platform(s)            |                                                            |
| Primary Modernization Pattern | Replatform / Refactor / Rebuild / Replace / Hybrid         |
| Recommended Next Step         |                                                            |

---

# 5. Executive Architecture Overview

## 5.1 Architecture Narrative

Provide a concise executive-level explanation of the target-state architecture.

```text
The proposed target-state architecture modernizes the current data environment by...
```

## 5.2 Business Outcomes Supported

| Business Outcome | Architecture Implication | Notes |
| ---------------- | ------------------------ | ----- |
|                  |                          |       |
|                  |                          |       |
|                  |                          |       |

## 5.3 Key Architecture Messages

| Message | Intended Audience                | Notes |
| ------- | -------------------------------- | ----- |
|         | Executive stakeholders           |       |
|         | Architecture stakeholders        |       |
|         | Delivery stakeholders            |       |
|         | Platform operations stakeholders |       |

---

# 6. Current-State Architecture Context

## 6.1 Current-State Summary

Describe the current-state environment at a level sufficient to explain the target-state architecture.

| Area                    | Current-State Description | Pain Points / Constraints |
| ----------------------- | ------------------------- | ------------------------- |
| Source platforms        |                           |                           |
| ETL / data integration  |                           |                           |
| Data storage            |                           |                           |
| Reporting / consumption |                           |                           |
| Orchestration           |                           |                           |
| Governance / security   |                           |                           |
| Operations / support    |                           |                           |
| Cost / consumption      |                           |                           |
| AI readiness            |                           |                           |

## 6.2 Current-State Limitations

| Limitation | Business / Technical Impact | Target-State Response |
| ---------- | --------------------------- | --------------------- |
|            |                             |                       |
|            |                             |                       |
|            |                             |                       |

## 6.3 Discovery Evidence Used

| Evidence Source        | Description | Confidence          |
| ---------------------- | ----------- | ------------------- |
| Application inventory  |             | High / Medium / Low |
| Workflow inventory     |             | High / Medium / Low |
| Architecture diagrams  |             | High / Medium / Low |
| Stakeholder interviews |             | High / Medium / Low |
| Platform metadata      |             | High / Medium / Low |
| Data samples           |             | High / Medium / Low |
| Other                  |             | High / Medium / Low |

---

# 7. Target-State Architecture Principles

Define the architecture principles that guide the target-state design.

| Principle                      | Description                                                                        | Rationale                                    |
| ------------------------------ | ---------------------------------------------------------------------------------- | -------------------------------------------- |
| Databricks-first modernization | Target-state architecture should be designed around Databricks platform strengths. | Supports Databricks by Design.               |
| Business-value alignment       | Architecture decisions should connect to business outcomes.                        | Supports Business Value Before Technology.   |
| Governed data foundation       | Governance, access, lineage, and controls should be designed into the platform.    | Supports trust and enterprise readiness.     |
| Reusable patterns              | Common workload patterns should be standardized where practical.                   | Supports industrialized delivery.            |
| Validation-ready design        | Architecture should support reconciliation, comparison, and acceptance evidence.   | Supports Trust Is Earned Through Validation. |
| AI-ready foundation            | Architecture should enable future AI, analytics, and data product use cases.       | Supports AI Enablement.                      |
| Operable platform              | Architecture should support monitoring, ownership, support, and optimization.      | Supports Platform Value Is the Destination.  |

Add, remove, or refine principles as needed for the engagement.

---

# 8. Target-State Architecture View

## 8.1 Architecture Diagram Placeholder

Insert or link the target-state architecture diagram here.

```text
[Insert target-state architecture diagram]
```

Recommended diagram layers:

1. Source systems
2. Ingestion layer
3. Storage layer
4. Transformation and processing layer
5. Governance and security layer
6. Serving and consumption layer
7. Orchestration and operations layer
8. AI and advanced analytics layer
9. Monitoring, FinOps, and platform operations

## 8.2 Architecture Layer Summary

| Architecture Layer | Target-State Design | Databricks / Platform Capabilities                                 | Notes |
| ------------------ | ------------------- | ------------------------------------------------------------------ | ----- |
| Source systems     |                     |                                                                    |       |
| Ingestion          |                     |                                                                    |       |
| Storage            |                     | Delta Lake / Cloud Object Storage                                  |       |
| Transformation     |                     | Databricks Jobs / Workflows / Spark / SQL                          |       |
| Governance         |                     | Unity Catalog / Access Controls / Lineage                          |       |
| Serving            |                     | Databricks SQL / APIs / Data Products / BI Tools                   |       |
| Orchestration      |                     | Databricks Workflows / Existing Enterprise Scheduler / ADF / Other |       |
| AI / ML            |                     | MLflow / Feature Store / Vector Search / Model Serving / Other     |       |
| Monitoring         |                     | Platform logs / job monitoring / operational dashboards            |       |
| FinOps             |                     | Cost monitoring / usage reporting / optimization practices         |       |

---

# 9. Databricks Capability Alignment

## 9.1 Capability Mapping

| Modernization Need         | Databricks Capability                       | Architecture Role                         | Notes |
| -------------------------- | ------------------------------------------- | ----------------------------------------- | ----- |
| Governed data access       | Unity Catalog                               | Central governance and access control     |       |
| Reliable lakehouse storage | Delta Lake                                  | ACID storage and time travel              |       |
| Scalable data engineering  | Databricks Workflows / Spark                | Pipeline orchestration and transformation |       |
| SQL analytics              | Databricks SQL                              | Serving and consumption                   |       |
| AI readiness               | MLflow / Feature Store / Vector Search      | AI and ML enablement                      |       |
| Data sharing               | Delta Sharing                               | Governed sharing patterns                 |       |
| Operational visibility     | Job monitoring / system tables / dashboards | Platform operations                       |       |

## 9.2 Platform Fit Summary

| Area              | Fit Assessment              | Notes |
| ----------------- | --------------------------- | ----- |
| Data engineering  | Strong / Moderate / Limited |       |
| Governance        | Strong / Moderate / Limited |       |
| Analytics serving | Strong / Moderate / Limited |       |
| AI readiness      | Strong / Moderate / Limited |       |
| Integration       | Strong / Moderate / Limited |       |
| Operations        | Strong / Moderate / Limited |       |
| Cost transparency | Strong / Moderate / Limited |       |

---

# 10. Data Architecture

## 10.1 Data Flow Summary

Describe the target-state data flow.

```text
Data will flow from source systems into the target platform through...
```

## 10.2 Data Zones / Layers

| Data Zone / Layer | Purpose                                                     | Example Content | Governance Notes |
| ----------------- | ----------------------------------------------------------- | --------------- | ---------------- |
| Landing / Raw     | Capture source-aligned data with minimal transformation.    |                 |                  |
| Bronze            | Standardized raw ingestion layer.                           |                 |                  |
| Silver            | Cleansed, conformed, validated data.                        |                 |                  |
| Gold              | Curated business-ready data products.                       |                 |                  |
| Serving           | Data exposed for analytics, reporting, applications, or AI. |                 |                  |

## 10.3 Data Product Considerations

| Data Product / Subject Area | Consumers | Target Layer | Notes |
| --------------------------- | --------- | ------------ | ----- |
|                             |           |              |       |
|                             |           |              |       |

---

# 11. Integration Architecture

## 11.1 Upstream Integration

| Source System | Integration Pattern                  | Frequency / Latency | Notes |
| ------------- | ------------------------------------ | ------------------- | ----- |
|               | Batch / Streaming / API / File / CDC |                     |       |
|               | Batch / Streaming / API / File / CDC |                     |       |

## 11.2 Downstream Integration

| Downstream Consumer | Consumption Pattern                         | Output Type | Notes |
| ------------------- | ------------------------------------------- | ----------- | ----- |
|                     | SQL / File / API / Dashboard / Data Product |             |       |
|                     | SQL / File / API / Dashboard / Data Product |             |       |

## 11.3 Orchestration

| Orchestration Area             | Target Approach | Notes |
| ------------------------------ | --------------- | ----- |
| Pipeline scheduling            |                 |       |
| Job dependencies               |                 |       |
| Error handling                 |                 |       |
| Restart / recovery             |                 |       |
| Existing scheduler coexistence |                 |       |

---

# 12. Governance and Security Architecture

## 12.1 Governance Model

| Governance Area               | Target-State Approach | Notes |
| ----------------------------- | --------------------- | ----- |
| Catalog / schema organization |                       |       |
| Access control                |                       |       |
| Data classification           |                       |       |
| Lineage                       |                       |       |
| Auditability                  |                       |       |
| Policy enforcement            |                       |       |
| Environment separation        |                       |       |

## 12.2 Security Considerations

| Security Concern                  | Target-State Response | Open Questions |
| --------------------------------- | --------------------- | -------------- |
| Identity and access management    |                       |                |
| Secrets management                |                       |                |
| Network access                    |                       |                |
| Encryption                        |                       |                |
| Data masking / row-level security |                       |                |
| Privileged access                 |                       |                |

---

# 13. Coexistence and Transitional Architecture

## 13.1 Coexistence Need

Describe whether legacy and modern platforms must operate together during transition.

```text
Coexistence is required because...
```

## 13.2 Transitional Architecture States

| Transition State | Description | Duration / Trigger | Risks |
| ---------------- | ----------- | ------------------ | ----- |
| State 1          |             |                    |       |
| State 2          |             |                    |       |
| State 3          |             |                    |       |

## 13.3 Parallel Run and Validation Implications

| Validation Need                 | Architecture Implication | Notes |
| ------------------------------- | ------------------------ | ----- |
| Record count comparison         |                          |       |
| Hash / control total comparison |                          |       |
| Business rule validation        |                          |       |
| Downstream output comparison    |                          |       |
| Exception handling              |                          |       |

---

# 14. Migration Architecture Implications

## 14.1 Migration Pattern Considerations

| Workload / Candidate Type | Recommended Pattern             | Rationale |
| ------------------------- | ------------------------------- | --------- |
| Legacy ETL workflow       | Rebuild / Refactor / Replatform |           |
| Batch file integration    | Rebuild / Replatform            |           |
| Mainframe extract         | Replatform / Refactor / Hybrid  |           |
| Reporting table           | Rebuild / Refactor              |           |
| Data warehouse workload   | Rebuild / Replatform / Hybrid   |           |

## 14.2 Migration Factory Inputs

| Input Needed by Migration Factory | Architecture Source | Status                               |
| --------------------------------- | ------------------- | ------------------------------------ |
| Candidate grouping                |                     | Not Started / In Progress / Complete |
| Target pattern                    |                     | Not Started / In Progress / Complete |
| Complexity assumptions            |                     | Not Started / In Progress / Complete |
| Dependency constraints            |                     | Not Started / In Progress / Complete |
| Validation requirements           |                     | Not Started / In Progress / Complete |
| Environment requirements          |                     | Not Started / In Progress / Complete |

---

# 15. Operations and Adoption Considerations

## 15.1 Operating Model Implications

| Operating Area         | Architecture Implication | Owner / Role |
| ---------------------- | ------------------------ | ------------ |
| Platform ownership     |                          |              |
| Job monitoring         |                          |              |
| Incident response      |                          |              |
| Release management     |                          |              |
| Access management      |                          |              |
| Cost management        |                          |              |
| Data product ownership |                          |              |

## 15.2 FinOps Considerations

| Cost Driver               | Architecture Consideration | Notes |
| ------------------------- | -------------------------- | ----- |
| Compute                   |                            |       |
| Storage                   |                            |       |
| Job frequency             |                            |       |
| Environment duplication   |                            |       |
| Data movement             |                            |       |
| Premium platform features |                            |       |

## 15.3 Adoption Considerations

| Stakeholder Group   | Adoption Need | Enablement Consideration |
| ------------------- | ------------- | ------------------------ |
| Data engineers      |               |                          |
| Analysts            |               |                          |
| Business users      |               |                          |
| Platform operations |               |                          |
| Governance team     |               |                          |

---

# 16. Architecture Decisions

Use this section to capture major architecture decisions or link to Architecture Decision Records.

| Decision ID | Decision | Rationale | Status                         | Owner |
| ----------- | -------- | --------- | ------------------------------ | ----- |
| ADR-001     |          |           | Proposed / Approved / Deferred |       |
| ADR-002     |          |           | Proposed / Approved / Deferred |       |

---

# 17. Risks, Assumptions, Issues, and Dependencies

## 17.1 Risks

| Risk | Impact | Mitigation | Owner |
| ---- | ------ | ---------- | ----- |
|      |        |            |       |

## 17.2 Assumptions

| Assumption | Validation Needed | Owner |
| ---------- | ----------------- | ----- |
|            |                   |       |

## 17.3 Issues

| Issue | Impact | Resolution Path | Owner |
| ----- | ------ | --------------- | ----- |
|       |        |                 |       |

## 17.4 Dependencies

| Dependency | Related Area | Status | Owner |
| ---------- | ------------ | ------ | ----- |
|            |              |        |       |

---

# 18. Architecture Review Checklist

| Review Item                                                 | Complete |
| ----------------------------------------------------------- | -------- |
| Business outcomes are reflected in architecture             |          |
| Current-state constraints are documented                    |          |
| Databricks capabilities are mapped to modernization needs   |          |
| Target-state architecture diagram is included or referenced |          |
| Data architecture layers are described                      |          |
| Governance and security model is addressed                  |          |
| Integration architecture is addressed                       |          |
| Coexistence and transition states are addressed             |          |
| Validation implications are identified                      |          |
| Migration Factory inputs are identified                     |          |
| Operating model implications are identified                 |          |
| FinOps considerations are documented                        |          |
| Architecture decisions are captured                         |          |
| Risks, assumptions, issues, and dependencies are documented |          |

---

# 19. Workbench Potential

This asset may eventually support the following Modernization Intelligence Workbench capabilities:

* target-state architecture draft generation;
* Databricks capability mapping;
* architecture gap detection;
* diagram generation support;
* architecture decision extraction;
* reference architecture recommendation;
* governance and security checklist generation;
* migration factory input extraction.

---

# 20. Status

This Target-State Architecture Template is currently in Draft v0.1.0 status.

It is the fourth reusable asset created in Sprint 5.
