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

# 9. Status

This Capability Method Asset Map is currently in Draft v0.1.0 status.

The Strategy & Business Value method and asset map has been drafted.

Remaining domains are pending.
