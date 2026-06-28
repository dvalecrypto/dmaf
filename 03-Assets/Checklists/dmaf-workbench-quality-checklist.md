---

asset_id: DMAF-ASSET-CHK-003
title: DMAF Workbench Quality Checklist
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Checklist

practice_domain:
- Modernization Intelligence Workbench

capability:
- DMAF-CAP-MIW-008 — Workbench Governance & Quality Control

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- AI Enablement
- Automation
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- Continuous Optimization & Modernization Intelligence
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Coexistence & Validation
- Executive Advisory

guiding_principles:
- AI Accelerates, People Govern
- Knowledge Compounds
- Everything Is Traceable
- Trust Is Earned Through Validation
- Modernization Is an Operating Model

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Knowledge-Graph/dmaf-knowledge-graph.md
- 01-Framework/Meta-Model/dmaf-meta-model.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md
- 03-Assets/Checklists/dmaf-ai-output-review-checklist.md

## last_updated: 2026-06-28

---

# DMAF Workbench Quality Checklist

## 1. Purpose

The purpose of this checklist is to define quality control expectations for future Modernization Intelligence Workbench outputs.

This checklist supports:

```text id="8ljl0g"
DMAF-CAP-MIW-008 — Workbench Governance & Quality Control
```

The Modernization Intelligence Workbench is intended to help ingest inputs, interpret modernization context, map content to the DMAF framework, recommend assets, generate advisory outputs, support traceability, and improve practice reuse.

Workbench outputs must remain evidence-based, framework-aligned, reviewed, traceable, and appropriate for their intended use.

---

## 2. Intended Audience

This checklist is intended for:

* DMAF practice leads;
* Workbench product owners;
* solution architects;
* advisory consultants;
* engagement leads;
* quality reviewers;
* AI output reviewers;
* knowledge managers;
* asset owners;
* future Workbench developers and maintainers.

---

## 3. When to Use This Checklist

Use this checklist when reviewing:

* Workbench-generated summaries;
* Workbench-generated recommendations;
* asset recommendations;
* capability mappings;
* lifecycle mappings;
* generated advisory outputs;
* generated templates, checklists, or workbook concepts;
* knowledge graph metadata;
* prompt libraries;
* reusable asset packaging;
* engagement workspace outputs;
* any AI-assisted output produced through or for the Workbench.

---

## 4. Workbench Quality Review Summary

| Field                       | Response                                                                                          |
| --------------------------- | ------------------------------------------------------------------------------------------------- |
| Engagement / Workspace Name |                                                                                                   |
| Workbench Output Reviewed   |                                                                                                   |
| Output Type                 | Summary / Recommendation / Mapping / Template / Checklist / Workbook / Dashboard / Prompt / Other |
| Date Reviewed               |                                                                                                   |
| Reviewed By                 |                                                                                                   |
| Review Role                 | Practice Lead / Architect / Engagement Lead / QA / SME / Other                                    |
| Source Inputs Used          |                                                                                                   |
| Related DMAF Domain         |                                                                                                   |
| Related Capability          |                                                                                                   |
| Intended Use                | Internal Draft / Client Review / Executive Review / Delivery Artifact / Repository Asset          |
| Review Status               | Approved / Approved with Edits / Needs Rework / Rejected                                          |

---

# 5. Input Quality Review

## 5.1 Source Input Check

| Review Question                                                                                     | Yes / No / N/A | Notes |
| --------------------------------------------------------------------------------------------------- | -------------- | ----- |
| Are the source inputs known and available for review?                                               |                |       |
| Are file names, source notes, meeting notes, screenshots, spreadsheets, or other inputs identified? |                |       |
| Are client-provided facts separated from assumptions and interpretations?                           |                |       |
| Are outdated or superseded inputs flagged?                                                          |                |       |
| Are incomplete inputs or gaps identified?                                                           |                |       |
| Are conflicting inputs identified?                                                                  |                |       |
| Are input limitations documented?                                                                   |                |       |

## 5.2 Input Normalization Check

| Review Question                                                                                                        | Yes / No / N/A | Notes |
| ---------------------------------------------------------------------------------------------------------------------- | -------------- | ----- |
| Has the input been normalized into a usable structure?                                                                 |                |       |
| Are entities such as platforms, applications, workflows, systems, stakeholders, risks, and decisions clearly captured? |                |       |
| Are counts, dates, names, and system references preserved accurately?                                                  |                |       |
| Are unclear terms flagged rather than silently corrected?                                                              |                |       |
| Are unknowns retained as unknowns?                                                                                     |                |       |
| Are assumptions labeled and traceable?                                                                                 |                |       |

---

# 6. Framework Alignment Review

## 6.1 DMAF Domain Alignment

| Review Question                                                                    | Yes / No / N/A | Notes |
| ---------------------------------------------------------------------------------- | -------------- | ----- |
| Is the output mapped to an approved DMAF practice domain?                          |                |       |
| Is the domain mapping reasonable based on the input context?                       |                |       |
| Does the output avoid inventing new practice domains?                              |                |       |
| Are cross-cutting capabilities used correctly?                                     |                |       |
| Is governance treated as a cross-cutting capability rather than a practice domain? |                |       |
| Are domain names consistent with the approved DMAF terminology?                    |                |       |

## 6.2 Capability Alignment

| Review Question                                                                       | Yes / No / N/A | Notes |
| ------------------------------------------------------------------------------------- | -------------- | ----- |
| Is the output mapped to an approved DMAF capability?                                  |                |       |
| Is the capability mapping accurate and defensible?                                    |                |       |
| Does the output avoid creating methods or assets without approved capability mapping? |                |       |
| Are capability IDs accurate?                                                          |                |       |
| Are capability names accurate?                                                        |                |       |
| Is the capability mapping traceable to the Capability Catalogue?                      |                |       |

## 6.3 Lifecycle Alignment

| Review Question                                                                            | Yes / No / N/A | Notes |
| ------------------------------------------------------------------------------------------ | -------------- | ----- |
| Is the output mapped to the correct lifecycle stage?                                       |                |       |
| Does the lifecycle stage reflect how the output will be used?                              |                |       |
| Are earlier or later lifecycle dependencies identified?                                    |                |       |
| Does the output avoid skipping required discovery, validation, or governance steps?        |                |       |
| Are cutover, operations, or continuous optimization implications identified when relevant? |                |       |

---

# 7. Evidence and Traceability Review

## 7.1 Evidence Review

| Review Question                                                                | Yes / No / N/A | Notes |
| ------------------------------------------------------------------------------ | -------------- | ----- |
| Are key facts supported by source evidence?                                    |                |       |
| Are recommendations supported by evidence, reasoning, or explicit assumptions? |                |       |
| Are unsupported claims removed, reworded, or flagged?                          |                |       |
| Are confidence levels documented where appropriate?                            |                |       |
| Are source gaps documented?                                                    |                |       |
| Are open questions captured for follow-up?                                     |                |       |

## 7.2 Traceability Chain

Confirm that the output can be traced through the DMAF structure.

| Traceability Link                      | Complete | Notes |
| -------------------------------------- | -------- | ----- |
| Source input to interpreted context    |          |       |
| Interpreted context to practice domain |          |       |
| Practice domain to capability          |          |       |
| Capability to method or asset          |          |       |
| Method or asset to output              |          |       |
| Output to reviewer decision            |          |       |

---

# 8. Output Quality Review

## 8.1 Accuracy and Completeness

| Review Question                                                                                      | Yes / No / N/A | Notes |
| ---------------------------------------------------------------------------------------------------- | -------------- | ----- |
| Is the output factually accurate based on available inputs?                                          |                |       |
| Does the output answer the intended request?                                                         |                |       |
| Are important gaps, risks, or constraints included?                                                  |                |       |
| Are major stakeholder concerns addressed?                                                            |                |       |
| Are business, technical, governance, delivery, and operational dimensions considered where relevant? |                |       |
| Is the output complete enough for the intended use?                                                  |                |       |

## 8.2 Recommendation Quality

| Review Question                                              | Yes / No / N/A | Notes |
| ------------------------------------------------------------ | -------------- | ----- |
| Are recommendations clear?                                   |                |       |
| Are recommendations actionable?                              |                |       |
| Are recommendations proportionate to the evidence available? |                |       |
| Are alternatives or caveats included where needed?           |                |       |
| Does the output avoid premature solutioning?                 |                |       |
| Does the output avoid unsupported certainty?                 |                |       |

## 8.3 Advisory Readiness

| Review Question                                                 | Yes / No / N/A | Notes |
| --------------------------------------------------------------- | -------------- | ----- |
| Is the output useful for advisory or delivery work?             |                |       |
| Is the language appropriate for the intended audience?          |                |       |
| Is the level of detail appropriate?                             |                |       |
| Is the structure clear and reusable?                            |                |       |
| Does the output support a decision, next step, or artifact?     |                |       |
| Does the output require additional human refinement before use? |                |       |

---

# 9. Metadata Quality Review

## 9.1 Metadata Completeness

| Metadata Item         | Complete | Notes |
| --------------------- | -------- | ----- |
| Asset or output title |          |       |
| Status                |          |       |
| Version               |          |       |
| Owner                 |          |       |
| Asset type            |          |       |
| Practice domain       |          |       |
| Capability            |          |       |
| Lifecycle stage       |          |       |
| Guiding principles    |          |       |
| Dependencies          |          |       |
| Last updated date     |          |       |

## 9.2 YAML and Repository Standards

| Review Question                                               | Yes / No / N/A | Notes |
| ------------------------------------------------------------- | -------------- | ----- |
| Does the output use approved YAML front matter when required? |                |       |
| Are YAML scalar values unquoted unless quotes are required?   |                |       |
| Are top-level keys unindented?                                |                |       |
| Are list values formatted consistently?                       |                |       |
| Are domain and capability names spelled consistently?         |                |       |
| Is the file stored in the correct repository folder?          |                |       |
| Does the file name follow DMAF naming conventions?            |                |       |

---

# 10. Governance and Risk Review

## 10.1 Governance Review

| Review Question                                                                         | Yes / No / N/A | Notes |
| --------------------------------------------------------------------------------------- | -------------- | ----- |
| Does the output respect the DMAF control rule that assets map to approved capabilities? |                |       |
| Is ownership clear?                                                                     |                |       |
| Is review status documented?                                                            |                |       |
| Are required reviewers identified?                                                      |                |       |
| Is the output ready for its intended repository status?                                 |                |       |
| Are future changes expected to follow version control?                                  |                |       |

## 10.2 Risk Review

| Review Question                                                                      | Yes / No / N/A | Notes |
| ------------------------------------------------------------------------------------ | -------------- | ----- |
| Does the output avoid exposing confidential or sensitive information unnecessarily?  |                |       |
| Does the output avoid including credentials, secrets, tokens, or private keys?       |                |       |
| Does the output avoid presenting uncertain information as confirmed fact?            |                |       |
| Does the output avoid making compliance, legal, or regulatory claims without review? |                |       |
| Are known risks or caveats documented?                                               |                |       |
| Are any redactions required before broader use?                                      |                |       |

---

# 11. Human Review Requirements

## 11.1 Required Reviewers

| Review Area              | Required Reviewer               | Reviewer Name | Status                       |
| ------------------------ | ------------------------------- | ------------- | ---------------------------- |
| Framework alignment      | DMAF Practice Lead              |               | Not Started / Complete / N/A |
| Technical accuracy       | Architect / Technical SME       |               | Not Started / Complete / N/A |
| Engagement fit           | Engagement Lead                 |               | Not Started / Complete / N/A |
| Client-specific accuracy | Account Owner / SME             |               | Not Started / Complete / N/A |
| Governance and risk      | Governance / Risk Reviewer      |               | Not Started / Complete / N/A |
| Asset quality            | Asset Owner / Knowledge Manager |               | Not Started / Complete / N/A |

## 11.2 Review Decision

| Decision Field         | Response                                                 |
| ---------------------- | -------------------------------------------------------- |
| Review Decision        | Approved / Approved with Edits / Needs Rework / Rejected |
| Required Edits         |                                                          |
| Open Questions         |                                                          |
| Required SME Follow-Up |                                                          |
| Final Approver         |                                                          |
| Approval Date          |                                                          |

---

# 12. Workbench Output Disposition

| Disposition         | Use When                                                                                      |
| ------------------- | --------------------------------------------------------------------------------------------- |
| Approved            | Output is accurate, traceable, framework-aligned, reviewed, and ready for intended use.       |
| Approved with Edits | Output is mostly usable, but documented edits are required before release or reuse.           |
| Needs Rework        | Output has useful elements but requires significant correction, completion, or restructuring. |
| Rejected            | Output is inaccurate, unsupported, unsafe, misaligned to DMAF, or not suitable for reuse.     |

---

# 13. Quality Scoring

Use this optional scoring model when a numeric quality score is helpful.

| Quality Area                  | Score 1–5 | Notes |
| ----------------------------- | --------: | ----- |
| Input quality                 |           |       |
| Framework alignment           |           |       |
| Evidence and traceability     |           |       |
| Output accuracy               |           |       |
| Output completeness           |           |       |
| Recommendation quality        |           |       |
| Metadata quality              |           |       |
| Governance and risk readiness |           |       |
| Human review readiness        |           |       |

## 13.1 Scoring Guide

| Score | Meaning                                    |
| ----: | ------------------------------------------ |
|     1 | Poor — significant issues, not usable.     |
|     2 | Weak — usable only after major rework.     |
|     3 | Acceptable — usable with edits or caveats. |
|     4 | Strong — usable with minor edits.          |
|     5 | Excellent — ready for intended use.        |

## 13.2 Overall Quality Band

| Average Score | Quality Band | Recommended Action                   |
| ------------: | ------------ | ------------------------------------ |
|       1.0–2.4 | Low          | Reject or rework before use.         |
|       2.5–3.4 | Medium       | Use only with review and edits.      |
|       3.5–4.4 | High         | Approve with minor edits or caveats. |
|       4.5–5.0 | Very High    | Approve for intended use.            |

---

# 14. Review Checklist Summary

Before approving a Workbench output, confirm:

| Review Item                                 | Complete |
| ------------------------------------------- | -------- |
| Source inputs are known                     |          |
| Input gaps are documented                   |          |
| Output maps to an approved practice domain  |          |
| Output maps to an approved capability       |          |
| Lifecycle stage is identified               |          |
| Key claims are traceable                    |          |
| Assumptions are labeled                     |          |
| Unsupported claims are removed or flagged   |          |
| Recommendations are evidence-based          |          |
| Metadata is complete                        |          |
| YAML formatting is correct where applicable |          |
| Governance and risk review is complete      |          |
| Required human reviewers are identified     |          |
| Final disposition is documented             |          |

---

# 15. Relationship to AI Output Review

This checklist governs Workbench-level quality.

For any Workbench output that uses AI-generated or AI-assisted content, also apply:

```text id="0f196a"
03-Assets/Checklists/dmaf-ai-output-review-checklist.md
```

The AI Output Review Checklist focuses on AI-specific quality, hallucination risk, sensitive information, evidence, and human review.

The Workbench Quality Checklist focuses on Workbench-level governance, metadata, framework alignment, traceability, and reusable output readiness.

---

# 16. Future Workbench Automation Potential

This checklist may eventually support the following automated or semi-automated Workbench functions:

* metadata completeness checking;
* YAML formatting checks;
* approved domain and capability validation;
* traceability chain validation;
* unsupported claim detection;
* input gap detection;
* evidence confidence scoring;
* quality scoring;
* review queue routing;
* approval workflow tracking;
* asset readiness reporting.

---

# 17. Status

This Workbench Quality Checklist is currently in Draft v0.1.0 status.

It is the tenth reusable asset created in Sprint 5.
