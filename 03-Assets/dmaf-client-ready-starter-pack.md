---

title: DMAF Client-Ready Starter Pack
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
artifact_type: Starter Pack Definition

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
- 00-Governance/Governance/dmaf-asset-metadata-standard.md
- 00-Governance/Release-Notes/release-2.0-consulting-assets.md

## last_updated: 2026-06-29

---

# DMAF Client-Ready Starter Pack

## 1. Purpose

The purpose of this document is to define which DMAF assets should be considered candidates for controlled client-facing use.

The Client-Ready Starter Pack identifies the first reusable assets that can support client conversations, discovery workshops, architecture discussions, migration planning, validation strategy, and executive communication.

This document does not automatically approve assets for unrestricted external use. It defines the candidate pack and the review conditions required before client delivery.

---

## 2. Starter Pack Objective

The starter pack should help a delivery or advisory team quickly support a Databricks modernization conversation from early qualification through planning.

The starter pack should answer the following questions:

| Question                                                     | Supporting Asset                          |
| ------------------------------------------------------------ | ----------------------------------------- |
| Is this a real modernization opportunity?                    | Opportunity Qualification Checklist       |
| What applications, workflows, and dependencies are in scope? | Application Inventory Workbook            |
| How complex is the modernization scope?                      | Modernization Complexity Scoring Workbook |
| What is the target-state direction?                          | Target-State Architecture Template        |
| How should migration work be sequenced?                      | Migration Wave Planning Workbook          |
| How will trust and validation be established?                | Validation Strategy Template              |
| How should the story be presented to executives?             | Executive One-Page Template               |
| How will the platform be operated after delivery?            | Platform Operating Model Template         |

---

# 3. Client-Ready Candidate Assets

## 3.1 Recommended Client-Ready Starter Pack

| Priority | Asset                                     | Type      | Client-Ready Potential | Notes                                                                                          |
| -------: | ----------------------------------------- | --------- | ---------------------- | ---------------------------------------------------------------------------------------------- |
|        1 | Opportunity Qualification Checklist       | Checklist | High                   | Useful for early-stage opportunity conversations and internal pursuit alignment.               |
|        2 | Application Inventory Workbook            | Workbook  | High                   | Useful for structured discovery intake and client-provided inventory capture.                  |
|        3 | Modernization Complexity Scoring Workbook | Workbook  | High                   | Useful for prioritization, scope discussion, and migration readiness analysis.                 |
|        4 | Target-State Architecture Template        | Template  | High                   | Useful for architecture workshops and target-state recommendation development.                 |
|        5 | Migration Wave Planning Workbook          | Workbook  | High                   | Useful for sequencing, dependency-aware planning, and delivery roadmap discussion.             |
|        6 | Validation Strategy Template              | Template  | High                   | Useful for establishing trust, reconciliation, evidence, and cutover expectations.             |
|        7 | Executive One-Page Template               | Template  | High                   | Useful for executive communication and decision support.                                       |
|        8 | Platform Operating Model Template         | Template  | High                   | Useful for operating model, ownership, governance, support, and value realization discussions. |

---

## 3.2 Internal-First Assets

The following assets should remain primarily internal at this stage.

| Asset                       | Type      | Recommended Use                                   | Rationale                                                                 |
| --------------------------- | --------- | ------------------------------------------------- | ------------------------------------------------------------------------- |
| AI Output Review Checklist  | Checklist | Internal governance and quality control           | Useful for internal review of AI-assisted outputs before client use.      |
| Workbench Quality Checklist | Checklist | Internal Workbench governance and quality control | Intended for future Workbench governance, metadata, and review workflows. |

These assets may become client-facing later, but they should first mature through internal use.

---

# 4. Client-Ready Review Criteria

Before an asset is used externally, confirm the following.

| Review Area            | Requirement                                                                                  |
| ---------------------- | -------------------------------------------------------------------------------------------- |
| Branding               | Remove internal-only language or repository-specific references where inappropriate.         |
| Client confidentiality | Confirm the asset contains no confidential information from another client or engagement.    |
| Language               | Ensure language is professional, neutral, and suitable for client-facing use.                |
| Completeness           | Confirm the asset is complete enough for the intended workshop, meeting, or deliverable.     |
| Scope fit              | Tailor the asset to the client’s modernization context.                                      |
| Metadata               | Keep internal metadata where useful, but remove or simplify if it distracts from client use. |
| Assumptions            | Clearly distinguish facts, assumptions, and recommendations.                                 |
| Review                 | Obtain practice lead or engagement lead review before external use.                          |

---

# 5. Client-Ready Packaging Model

## 5.1 Suggested Packaging Tiers

| Tier                                    | Description                                                  | Assets                                                                    |
| --------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------- |
| Tier 1 — Executive Starter Pack         | Supports early executive and opportunity conversations.      | Opportunity Qualification Checklist; Executive One-Page Template          |
| Tier 2 — Discovery Starter Pack         | Supports structured discovery and assessment.                | Application Inventory Workbook; Modernization Complexity Scoring Workbook |
| Tier 3 — Architecture and Planning Pack | Supports architecture, roadmap, and migration planning.      | Target-State Architecture Template; Migration Wave Planning Workbook      |
| Tier 4 — Validation and Operations Pack | Supports production trust and post-migration sustainability. | Validation Strategy Template; Platform Operating Model Template           |

---

## 5.2 Recommended First Client-Facing Bundle

The recommended first client-facing bundle should include:

1. Executive One-Page Template;
2. Opportunity Qualification Checklist;
3. Application Inventory Workbook;
4. Modernization Complexity Scoring Workbook;
5. Target-State Architecture Template.

This bundle is suitable for early advisory, discovery, and proposal-shaping activities.

---

# 6. Asset Tailoring Guidance

## 6.1 Tailoring by Engagement Type

| Engagement Type           | Recommended Assets                                                          | Tailoring Notes                                                                     |
| ------------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Early opportunity shaping | Opportunity Qualification Checklist; Executive One-Page Template            | Keep concise and business-value oriented.                                           |
| Discovery assessment      | Application Inventory Workbook; Modernization Complexity Scoring Workbook   | Add client-specific source platforms, workloads, and complexity criteria if needed. |
| Architecture advisory     | Target-State Architecture Template; Executive One-Page Template             | Tailor architecture sections to the client’s target platform and governance needs.  |
| Migration planning        | Migration Wave Planning Workbook; Modernization Complexity Scoring Workbook | Adjust capacity, wave, dependency, and prioritization assumptions.                  |
| Validation strategy       | Validation Strategy Template                                                | Tailor comparison methods, tolerance rules, evidence, and sign-off criteria.        |
| Platform operating model  | Platform Operating Model Template                                           | Tailor roles, RACI, support, governance, FinOps, and adoption sections.             |

---

## 6.2 Tailoring by Source Platform

| Source Platform Context        | Tailoring Considerations                                                                            |
| ------------------------------ | --------------------------------------------------------------------------------------------------- |
| Informatica modernization      | Emphasize workflows, mappings, sessions, schedules, dependencies, and migration waves.              |
| Mainframe modernization        | Emphasize files, batch jobs, business rules, reconciliation, downstream extracts, and validation.   |
| SSIS / DataStage modernization | Emphasize packages, jobs, dependencies, orchestration, and transformation complexity.               |
| Hadoop modernization           | Emphasize data zones, storage formats, workload patterns, governance, and platform operating model. |
| Data warehouse modernization   | Emphasize schemas, tables, reports, performance, downstream consumers, and coexistence.             |
| Custom pipeline modernization  | Emphasize code inventory, orchestration, data lineage, business rules, and support model.           |

---

# 7. External Use Guidance

## 7.1 Appropriate External Use

The starter pack may be used externally for:

* workshop preparation;
* client discovery sessions;
* structured intake;
* architecture planning discussions;
* migration planning conversations;
* executive summary development;
* validation strategy discussions;
* operating model workshops.

## 7.2 Inappropriate External Use

The starter pack should not be used externally when:

* the asset has not been reviewed;
* the asset contains internal-only notes;
* the client context has not been tailored;
* recommendations are presented as final before discovery;
* assumptions are not labeled;
* the asset implies a commitment to scope, effort, cost, or timeline without review;
* the asset includes another client’s information.

---

# 8. Promotion Path

Assets should move through the following readiness path.

```text id="promotion-path"
Draft
  ↓
Internal Review
  ↓
Approved for Internal Reuse
  ↓
Client-Ready Candidate
  ↓
Client-Ready
  ↓
Baselined Release Asset
```

## 8.1 Promotion Criteria

| Promotion Stage             | Criteria                                                         |
| --------------------------- | ---------------------------------------------------------------- |
| Draft                       | Asset exists and maps to an approved capability.                 |
| Internal Review             | Asset has been reviewed by practice or engagement lead.          |
| Approved for Internal Reuse | Asset is suitable for repeated internal use.                     |
| Client-Ready Candidate      | Asset has strong external-use potential but requires tailoring.  |
| Client-Ready                | Asset is reviewed, polished, and safe for controlled client use. |
| Baselined Release Asset     | Asset is part of an approved DMAF release baseline.              |

---

# 9. Recommended Client-Ready Status

| Asset                                     | Current Status | Recommended Next Status     |
| ----------------------------------------- | -------------- | --------------------------- |
| Opportunity Qualification Checklist       | Draft          | Client-Ready Candidate      |
| Application Inventory Workbook            | Draft          | Client-Ready Candidate      |
| Modernization Complexity Scoring Workbook | Draft          | Client-Ready Candidate      |
| Target-State Architecture Template        | Draft          | Client-Ready Candidate      |
| Migration Wave Planning Workbook          | Draft          | Client-Ready Candidate      |
| Validation Strategy Template              | Draft          | Client-Ready Candidate      |
| Executive One-Page Template               | Draft          | Client-Ready Candidate      |
| Platform Operating Model Template         | Draft          | Client-Ready Candidate      |
| AI Output Review Checklist                | Draft          | Approved for Internal Reuse |
| Workbench Quality Checklist               | Draft          | Approved for Internal Reuse |

---

# 10. Client-Ready QA Checklist

Before marking any asset Client-Ready, confirm:

| Review Item                                                     | Complete |
| --------------------------------------------------------------- | -------- |
| Asset maps to an approved capability                            |          |
| Asset has been reviewed by the practice lead or engagement lead |          |
| Internal-only notes are removed or clearly separated            |          |
| Client-sensitive language is removed                            |          |
| Assumptions and recommendations are clearly distinguished       |          |
| Asset is understandable without excessive internal context      |          |
| Asset is reusable across more than one client scenario          |          |
| Asset has clear usage instructions                              |          |
| Asset has clear review or completion criteria                   |          |
| Asset has no unsupported claims                                 |          |
| Asset can be tailored without breaking structure                |          |
| Asset is stored in the correct repository location              |          |

---

# 11. Workbench Potential

This starter pack definition may eventually support the following Workbench capabilities:

* asset recommendation by engagement stage;
* asset recommendation by role;
* asset recommendation by source platform;
* client-ready readiness scoring;
* internal-only asset filtering;
* asset packaging automation;
* engagement bundle generation;
* Workbench-driven asset retrieval.

---

# 12. Status

This Client-Ready Starter Pack Definition is currently in Draft v0.1.0 status.

It is the fourth packaging artifact created in Sprint 6.
