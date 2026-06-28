---

asset_id: DMAF-ASSET-CHK-002
title: DMAF AI Output Review Checklist
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Checklist

practice_domain:
- AI & Automation

capability:
- DMAF-CAP-AIA-008 — AI Governance & Human Review Model

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- AI Enablement
- Knowledge Management
- Reusable Accelerators

lifecycle_stage:
- AI & Automation
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Coexistence & Validation
- Executive Advisory

guiding_principles:
- AI Accelerates, People Govern
- Trust Is Earned Through Validation
- Executive Storytelling Matters
- Knowledge Compounds
- Everything Is Traceable

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

## last_updated: 2026-06-28

---

# DMAF AI Output Review Checklist

## 1. Purpose

The purpose of this checklist is to ensure that AI-assisted outputs used in DMAF advisory, discovery, architecture, migration planning, validation, executive communication, and Workbench scenarios are accurate, traceable, appropriate, and reviewed by qualified humans before use.

This checklist supports:

```text id="5mo2hz"
DMAF-CAP-AIA-008 — AI Governance & Human Review Model
```

AI can accelerate analysis and content generation, but AI-generated output must not be treated as automatically correct, complete, approved, or client-ready.

---

## 2. Intended Audience

This checklist is intended for:

* account executives;
* engagement leads;
* advisory consultants;
* solution architects;
* data architects;
* migration leads;
* QA leads;
* practice leads;
* Workbench reviewers;
* anyone using AI-assisted content in DMAF artifacts.

---

## 3. When to Use This Checklist

Use this checklist when AI has been used to help produce, summarize, classify, recommend, draft, transform, score, or review any DMAF-related output.

Examples include:

* client discovery summaries;
* application or workflow classification;
* modernization recommendations;
* architecture narratives;
* migration wave recommendations;
* complexity scoring summaries;
* validation strategy drafts;
* risk summaries;
* executive one-pagers;
* proposal content;
* Workbench-generated outputs.

---

## 4. AI Output Review Summary

| Field                         | Response                                                                                            |
| ----------------------------- | --------------------------------------------------------------------------------------------------- |
| Client / Account              |                                                                                                     |
| Engagement / Opportunity Name |                                                                                                     |
| Artifact / Output Reviewed    |                                                                                                     |
| Date Reviewed                 |                                                                                                     |
| Reviewed By                   |                                                                                                     |
| AI Tool / Model Used          |                                                                                                     |
| Input Source(s) Used          |                                                                                                     |
| Output Type                   | Summary / Recommendation / Classification / Template Draft / Scoring / Diagram Narrative / Other    |
| Intended Use                  | Internal Draft / Client Review / Executive Review / Proposal / Delivery Artifact / Workbench Output |
| Review Status                 | Approved / Approved with Edits / Needs Rework / Rejected                                            |

---

# 5. Source and Evidence Review

## 5.1 Input Source Check

| Review Question                                                                        | Yes / No / N/A | Notes |
| -------------------------------------------------------------------------------------- | -------------- | ----- |
| Were the input sources known and available for review?                                 |                |       |
| Were client-provided facts separated from assumptions?                                 |                |       |
| Were uploaded files, notes, transcripts, spreadsheets, or diagrams clearly identified? |                |       |
| Were outdated, incomplete, or low-confidence inputs flagged?                           |                |       |
| Were any missing inputs or gaps documented?                                            |                |       |
| Was the AI prevented from inventing facts where evidence was missing?                  |                |       |

## 5.2 Traceability Check

| Review Question                                                           | Yes / No / N/A | Notes |
| ------------------------------------------------------------------------- | -------------- | ----- |
| Can key claims be traced back to source inputs?                           |                |       |
| Are important recommendations supported by evidence or clear reasoning?   |                |       |
| Are assumptions explicitly labeled?                                       |                |       |
| Are unresolved questions documented?                                      |                |       |
| Are citations, file references, or source notes included where required?  |                |       |
| Is there a clear distinction between fact, inference, and recommendation? |                |       |

---

# 6. Accuracy and Completeness Review

## 6.1 Accuracy Check

| Review Question                                                            | Yes / No / N/A | Notes |
| -------------------------------------------------------------------------- | -------------- | ----- |
| Are names, dates, counts, platforms, systems, and terms accurate?          |                |       |
| Are client-specific facts represented correctly?                           |                |       |
| Are technical statements plausible and consistent with known architecture? |                |       |
| Are Databricks capabilities described appropriately?                       |                |       |
| Are risks, constraints, and dependencies represented accurately?           |                |       |
| Are there any unsupported claims that should be removed or reworded?       |                |       |

## 6.2 Completeness Check

| Review Question                                                                            | Yes / No / N/A | Notes |
| ------------------------------------------------------------------------------------------ | -------------- | ----- |
| Does the output answer the actual request?                                                 |                |       |
| Are important stakeholder concerns addressed?                                              |                |       |
| Are business, technical, operational, and governance dimensions considered where relevant? |                |       |
| Are known gaps or unknowns acknowledged?                                                   |                |       |
| Are recommended next steps included where appropriate?                                     |                |       |
| Is the output complete enough for its intended use?                                        |                |       |

---

# 7. Relevance and Fit Review

## 7.1 DMAF Alignment

| Review Question                                                                                 | Yes / No / N/A | Notes |
| ----------------------------------------------------------------------------------------------- | -------------- | ----- |
| Does the output align to an approved DMAF practice domain?                                      |                |       |
| Does the output align to an approved DMAF capability?                                           |                |       |
| Does the output support the relevant lifecycle stage?                                           |                |       |
| Does the output use DMAF terminology consistently?                                              |                |       |
| Does the output support the relevant guiding principles?                                        |                |       |
| Does the output avoid creating assets or methods outside the approved framework without review? |                |       |

## 7.2 Engagement Fit

| Review Question                                                                        | Yes / No / N/A | Notes |
| -------------------------------------------------------------------------------------- | -------------- | ----- |
| Is the output appropriate for the client’s maturity level?                             |                |       |
| Is the output appropriate for the current engagement phase?                            |                |       |
| Is the output appropriate for the intended audience?                                   |                |       |
| Is the level of detail suitable?                                                       |                |       |
| Does the output avoid over-engineering the recommendation?                             |                |       |
| Does the output avoid prematurely prescribing a solution before discovery is complete? |                |       |

---

# 8. Risk, Compliance, and Confidentiality Review

## 8.1 Sensitive Information Check

| Review Question                                                                              | Yes / No / N/A | Notes |
| -------------------------------------------------------------------------------------------- | -------------- | ----- |
| Does the output avoid exposing confidential client information unnecessarily?                |                |       |
| Does the output avoid including credentials, secrets, tokens, or private keys?               |                |       |
| Does the output avoid including sensitive personal information unless required and approved? |                |       |
| Does the output avoid copying proprietary material without permission?                       |                |       |
| Is the output appropriate for the planned distribution audience?                             |                |       |
| Are redactions or anonymization needed?                                                      |                |       |

## 8.2 Risk and Compliance Check

| Review Question                                                               | Yes / No / N/A | Notes |
| ----------------------------------------------------------------------------- | -------------- | ----- |
| Are risk statements clear and not exaggerated?                                |                |       |
| Are compliance statements reviewed by the appropriate subject matter expert?  |                |       |
| Are legal, regulatory, audit, or control implications flagged where relevant? |                |       |
| Are security recommendations reviewed before client use?                      |                |       |
| Are assumptions about client controls avoided unless confirmed?               |                |       |
| Are limitations and caveats documented?                                       |                |       |

---

# 9. Recommendation Review

## 9.1 Recommendation Quality

| Review Question                                               | Yes / No / N/A | Notes |
| ------------------------------------------------------------- | -------------- | ----- |
| Are recommendations clearly stated?                           |                |       |
| Are recommendations tied to client objectives or constraints? |                |       |
| Are recommendations actionable?                               |                |       |
| Are recommendations proportionate to available evidence?      |                |       |
| Are alternative options considered where appropriate?         |                |       |
| Are recommendations free from unsupported certainty?          |                |       |

## 9.2 Decision Readiness

| Review Question                                                | Yes / No / N/A | Notes |
| -------------------------------------------------------------- | -------------- | ----- |
| Can a stakeholder understand what decision is being supported? |                |       |
| Is the recommended next step clear?                            |                |       |
| Are dependencies and prerequisites identified?                 |                |       |
| Are caveats visible enough for decision makers?                |                |       |
| Is the recommendation ready for its intended use?              |                |       |
| Does the output require additional SME review before release?  |                |       |

---

# 10. Writing and Presentation Review

## 10.1 Clarity Check

| Review Question                                   | Yes / No / N/A | Notes |
| ------------------------------------------------- | -------------- | ----- |
| Is the output clear and easy to read?             |                |       |
| Is the structure logical?                         |                |       |
| Are headings and labels meaningful?               |                |       |
| Is jargon explained or avoided where appropriate? |                |       |
| Are overly broad statements tightened?            |                |       |
| Are repeated ideas removed?                       |                |       |

## 10.2 Executive Readiness Check

| Review Question                                             | Yes / No / N/A | Notes |
| ----------------------------------------------------------- | -------------- | ----- |
| Is the executive message clear?                             |                |       |
| Does the output lead with business value where appropriate? |                |       |
| Are visuals, tables, or summaries used appropriately?       |                |       |
| Is the output concise enough for the intended audience?     |                |       |
| Are technical details placed at the right level?            |                |       |
| Is the call to action clear?                                |                |       |

---

# 11. Required Human Review

## 11.1 Review Ownership

| Review Area          | Required Reviewer                 | Reviewer Name | Status                       |
| -------------------- | --------------------------------- | ------------- | ---------------------------- |
| Business accuracy    | Engagement Lead / Account Owner   |               | Not Started / Complete / N/A |
| Technical accuracy   | Architect / Technical SME         |               | Not Started / Complete / N/A |
| Delivery feasibility | Delivery Lead / Migration Lead    |               | Not Started / Complete / N/A |
| Validation accuracy  | QA Lead / Validation Lead         |               | Not Started / Complete / N/A |
| Risk and compliance  | Risk / Compliance SME             |               | Not Started / Complete / N/A |
| Executive readiness  | Practice Lead / Executive Sponsor |               | Not Started / Complete / N/A |

## 11.2 Review Decision

| Decision Field      | Response                                                 |
| ------------------- | -------------------------------------------------------- |
| Review Decision     | Approved / Approved with Edits / Needs Rework / Rejected |
| Required Edits      |                                                          |
| Open Questions      |                                                          |
| Required SME Review |                                                          |
| Final Approver      |                                                          |
| Approval Date       |                                                          |

---

# 12. AI Output Disposition

| Disposition         | Use When                                                                          |
| ------------------- | --------------------------------------------------------------------------------- |
| Approved            | Output is accurate, traceable, appropriate, and ready for intended use.           |
| Approved with Edits | Output is usable after documented edits are made.                                 |
| Needs Rework        | Output has useful elements but requires substantial correction or completion.     |
| Rejected            | Output is inaccurate, unsupported, inappropriate, unsafe, or not aligned to DMAF. |

---

# 13. Review Checklist Summary

Before releasing an AI-assisted output, confirm:

| Review Item                                  | Complete |
| -------------------------------------------- | -------- |
| Input sources are identified                 |          |
| Key claims are traceable                     |          |
| Assumptions are labeled                      |          |
| Client-specific facts are checked            |          |
| Technical accuracy is reviewed               |          |
| Recommendations are evidence-based           |          |
| Confidentiality risks are reviewed           |          |
| Compliance-sensitive statements are reviewed |          |
| DMAF alignment is confirmed                  |          |
| Intended audience fit is confirmed           |          |
| Required human reviewers are identified      |          |
| Final disposition is documented              |          |

---

# 14. Workbench Potential

This asset may eventually support the following Modernization Intelligence Workbench capabilities:

* AI output review workflow;
* evidence traceability checking;
* unsupported claim detection;
* assumption extraction;
* SME review routing;
* review status tracking;
* quality scoring;
* approval workflow management.

---

# 15. Status

This AI Output Review Checklist is currently in Draft v0.1.0 status.

It is the seventh reusable asset created in Sprint 5.
