---

title: DMAF Asset Metadata Standard
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
artifact_type: Standard

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

lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Coexistence & Validation
- Executive Advisory
- Platform Operations, Adoption & Value Realization
- Continuous Optimization & Modernization Intelligence

guiding_principles:
- Everything Is Traceable
- Knowledge Compounds
- Modernization Is an Operating Model
- AI Accelerates, People Govern

dependencies:
- 03-Assets/README.md
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md
- 01-Framework/Taxonomy/dmaf-taxonomy-and-glossary.md

## last_updated: 2026-06-29

---

# DMAF Asset Metadata Standard

## 1. Purpose

The purpose of this standard is to define consistent metadata expectations for reusable DMAF assets.

Consistent metadata helps DMAF assets remain:

* traceable;
* searchable;
* governable;
* reusable;
* version controlled;
* Workbench-ready.

This standard applies to reusable assets stored under:

```text id="asset-root"
03-Assets/
```

---

## 2. Metadata Control Rule

Every reusable DMAF asset should be traceable to an approved DMAF capability.

```text id="metadata-control-rule"
No reusable asset should be created, promoted, or packaged unless it maps to an approved DMAF capability.
```

This rule supports the DMAF principle:

```text id="traceability-principle"
Everything Is Traceable
```

---

## 3. Asset Metadata Scope

This standard applies to:

| Asset Type          | Metadata Approach                                     |
| ------------------- | ----------------------------------------------------- |
| Markdown templates  | YAML front matter required                            |
| Markdown checklists | YAML front matter required                            |
| Markdown guides     | YAML front matter required                            |
| Markdown standards  | YAML front matter required                            |
| Markdown playbooks  | YAML front matter required                            |
| Excel workbooks     | README sheet metadata required                        |
| PowerPoint decks    | Title slide or metadata slide required                |
| Word documents      | Cover page or metadata section required               |
| Diagrams            | Metadata block in companion Markdown file recommended |
| Prompt libraries    | YAML front matter required                            |
| Dashboards          | Metadata section or companion Markdown file required  |

---

# 4. Required Metadata Fields

## 4.1 Required Fields for Markdown Assets

Markdown assets should include the following YAML front matter fields.

| Field                      | Required    | Description                                      |
| -------------------------- | ----------- | ------------------------------------------------ |
| asset_id                   | Yes         | Unique asset identifier.                         |
| title                      | Yes         | Human-readable asset title.                      |
| status                     | Yes         | Current lifecycle status.                        |
| version                    | Yes         | Asset version.                                   |
| owner                      | Yes         | Accountable owner or role.                       |
| release                    | Yes         | Associated DMAF release.                         |
| asset_type                 | Yes         | Type of reusable asset.                          |
| practice_domain            | Yes         | Approved DMAF practice domain.                   |
| capability                 | Yes         | Approved DMAF capability.                        |
| cross_cutting_capabilities | Recommended | Relevant cross-cutting capabilities.             |
| lifecycle_stage            | Yes         | Relevant DMAF lifecycle stage.                   |
| guiding_principles         | Recommended | Relevant DMAF guiding principles.                |
| dependencies               | Recommended | Related source artifacts or required references. |
| last_updated               | Yes         | Last update date in YYYY-MM-DD format.           |

---

## 4.2 Required Fields for Workbook Assets

Workbook assets should include a `README` sheet with the following fields.

| Field               | Required    | Description                                              |
| ------------------- | ----------- | -------------------------------------------------------- |
| Asset ID            | Yes         | Unique asset identifier.                                 |
| Title               | Yes         | Human-readable asset title.                              |
| Status              | Yes         | Current lifecycle status.                                |
| Version             | Yes         | Asset version.                                           |
| Owner               | Yes         | Accountable owner or role.                               |
| Release             | Yes         | Associated DMAF release.                                 |
| Asset Type          | Yes         | Workbook, dashboard, calculator, or other workbook type. |
| Practice Domain     | Yes         | Approved DMAF practice domain.                           |
| Capability          | Yes         | Approved DMAF capability.                                |
| Lifecycle Stage     | Yes         | Relevant DMAF lifecycle stage.                           |
| Intended Audience   | Recommended | Primary users of the workbook.                           |
| Usage Guidance      | Yes         | Instructions for how to use the workbook.                |
| Workbench Potential | Recommended | Future automation or Workbench indexing potential.       |
| Last Updated        | Yes         | Last update date in YYYY-MM-DD format.                   |

---

# 5. Approved Metadata Values

## 5.1 Approved Practice Domains

Use only the following approved practice domains.

| Approved Practice Domain                          |
| ------------------------------------------------- |
| Strategy & Business Value                         |
| Discovery & Assessment                            |
| Modernization Architecture                        |
| Migration Factory                                 |
| Coexistence & Validation                          |
| AI & Automation                                   |
| Executive Advisory                                |
| Platform Operations, Adoption & Value Realization |
| Modernization Intelligence Workbench              |

Do not use `Governance` as a practice domain.

Governance is represented as a cross-cutting capability through:

```text id="governance-cross-cutting"
Governance & Security
```

---

## 5.2 Approved Cross-Cutting Capabilities

Use the following approved cross-cutting capabilities where relevant.

| Approved Cross-Cutting Capability |
| --------------------------------- |
| Governance & Security             |
| Risk & Compliance                 |
| FinOps & Cost Optimization        |
| AI Enablement                     |
| Automation                        |
| Knowledge Management              |
| Reusable Accelerators             |

---

## 5.3 Approved Lifecycle Stages

Use the following approved DMAF lifecycle stages.

| Lifecycle Stage                                      |
| ---------------------------------------------------- |
| Opportunity Qualification & Modernization Strategy   |
| Strategy & Business Value                            |
| Discovery & Assessment                               |
| Modernization Architecture                           |
| Migration Factory Planning                           |
| Reference Implementation / Pilot                     |
| Migration Factory Execution                          |
| Coexistence & Validation                             |
| Production Cutover                                   |
| Platform Operations, Adoption & Value Realization    |
| Continuous Optimization & Modernization Intelligence |

---

## 5.4 Approved Guiding Principles

Use the following approved guiding principles.

| Guiding Principle                   |
| ----------------------------------- |
| Business Value Before Technology    |
| Databricks by Design                |
| Modernization Is an Operating Model |
| Industrialize Delivery              |
| Coexistence Is Intentional          |
| Trust Is Earned Through Validation  |
| AI Accelerates, People Govern       |
| Executive Storytelling Matters      |
| Knowledge Compounds                 |
| Platform Value Is the Destination   |
| Everything Is Traceable             |

---

## 5.5 Approved Asset Types

Use the following asset types unless a new type is approved.

| Asset Type             | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| Checklist              | Structured review or decision checklist.                           |
| Template               | Structured reusable document or artifact pattern.                  |
| Workbook               | Spreadsheet-based inventory, scoring, planning, or dashboard tool. |
| Guide                  | Instructional or explanatory asset.                                |
| Standard               | Governance or formatting standard.                                 |
| Playbook               | Repeatable delivery or advisory procedure.                         |
| Dashboard              | Visual or metric-based reporting asset.                            |
| Prompt Library         | Reusable AI prompt set.                                            |
| Diagram                | Architecture, process, or conceptual visual.                       |
| Reference Architecture | Reusable architecture pattern.                                     |
| Release Notes          | Release documentation.                                             |
| QA Review              | Quality assurance review artifact.                                 |
| Asset Index            | Navigational index of reusable assets.                             |

---

# 6. YAML Formatting Standard

Markdown assets should use YAML front matter formatted as follows.

## 6.1 YAML Formatting Rules

| Rule           | Requirement                                                 |
| -------------- | ----------------------------------------------------------- |
| Scalar values  | Do not wrap scalar values in double quotes unless required. |
| Top-level keys | Keep top-level keys unindented.                             |
| Lists          | Use hyphenated list values directly under the key.          |
| Dates          | Use `YYYY-MM-DD`.                                           |
| Paths          | Use repository-relative paths.                              |
| Names          | Use approved DMAF terminology exactly.                      |

## 6.2 YAML Example

```yaml id="yaml-example"
---
asset_id: DMAF-ASSET-TPL-000
title: Example DMAF Template
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
- Knowledge Management

lifecycle_stage:
- Modernization Architecture

guiding_principles:
- Databricks by Design
- Everything Is Traceable

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md

last_updated: 2026-06-29
---
```

---

# 7. Asset ID Standard

## 7.1 Asset ID Format

Asset IDs should use the following pattern.

```text id="asset-id-pattern"
DMAF-ASSET-[TYPE]-[NUMBER]
```

Examples:

| Asset ID           | Asset Type     |
| ------------------ | -------------- |
| DMAF-ASSET-CHK-001 | Checklist      |
| DMAF-ASSET-TPL-001 | Template       |
| DMAF-ASSET-WBK-001 | Workbook       |
| DMAF-ASSET-GDE-001 | Guide          |
| DMAF-ASSET-STD-001 | Standard       |
| DMAF-ASSET-PLY-001 | Playbook       |
| DMAF-ASSET-DIA-001 | Diagram        |
| DMAF-ASSET-PMT-001 | Prompt Library |

---

## 7.2 Recommended Type Codes

| Type Code | Asset Type             |
| --------- | ---------------------- |
| CHK       | Checklist              |
| TPL       | Template               |
| WBK       | Workbook               |
| GDE       | Guide                  |
| STD       | Standard               |
| PLY       | Playbook               |
| DIA       | Diagram                |
| PMT       | Prompt Library         |
| DSH       | Dashboard              |
| REF       | Reference Architecture |

---

# 8. Asset Status Standard

Use the following asset statuses.

| Status       | Meaning                                                  |
| ------------ | -------------------------------------------------------- |
| Draft        | Asset is created but not yet validated through real use. |
| Review       | Asset is under formal review.                            |
| Approved     | Asset is approved for internal reuse.                    |
| Client-Ready | Asset is suitable for controlled client-facing use.      |
| Baselined    | Asset is part of an official DMAF release baseline.      |
| Deprecated   | Asset is no longer recommended for use.                  |
| Archived     | Asset is retained for history only.                      |

---

# 9. Versioning Standard

Use semantic-style versioning for reusable assets.

| Version | Meaning                                      |
| ------- | -------------------------------------------- |
| 0.1.0   | Initial draft.                               |
| 0.x.0   | Iterative draft updates.                     |
| 1.0.0   | First approved or baselined version.         |
| 1.x.0   | Minor enhancements.                          |
| 2.0.0   | Major restructuring or new release baseline. |

Version changes should be made intentionally and documented where meaningful.

---

# 10. Repository Placement Standard

Assets should be stored in the appropriate folder.

| Asset Type               | Recommended Folder            |
| ------------------------ | ----------------------------- |
| Checklists               | `03-Assets/Checklists/`       |
| Templates                | `03-Assets/Templates/`        |
| Workbooks                | `03-Assets/Workbooks/`        |
| Diagrams                 | `03-Assets/Diagrams/`         |
| Dashboards               | `03-Assets/Dashboards/`       |
| Prompt Libraries         | `03-Assets/Prompts/`          |
| Playbooks                | `02-Playbook/`                |
| Reference Architectures  | `04-Reference-Architectures/` |
| Workbench Specifications | `05-Workbench/`               |

---

# 11. Workbook Metadata Standard

Workbook assets should include a `README` sheet with:

1. asset purpose;
2. related DMAF capability;
3. intended audience;
4. workbook structure;
5. usage instructions;
6. version and owner;
7. update date;
8. future Workbench potential.

Workbook assets should also include, where appropriate:

* reference lists;
* data validation dropdowns;
* protected formulas where practical;
* dashboard or summary views;
* sample rows that can be removed or replaced;
* clear user-input columns;
* calculated columns clearly labeled;
* formula error checks before release.

---

# 12. Workbench Metadata Readiness

Assets should be prepared for future Workbench indexing by including:

| Metadata Item      | Workbench Use                              |
| ------------------ | ------------------------------------------ |
| asset_id           | Unique retrieval and reference key.        |
| title              | Human-readable search and display name.    |
| asset_type         | Asset filtering and recommendation.        |
| practice_domain    | Domain-based retrieval.                    |
| capability         | Capability-based retrieval.                |
| lifecycle_stage    | Stage-based recommendation.                |
| guiding_principles | Principle-based explanation and alignment. |
| dependencies       | Traceability and impact analysis.          |
| status             | Release and readiness filtering.           |
| version            | Change management.                         |
| last_updated       | Freshness and review management.           |

---

# 13. Metadata QA Checklist

Before promoting an asset beyond Draft, confirm:

| Review Item                                | Complete |
| ------------------------------------------ | -------- |
| Asset has a unique asset ID                |          |
| Asset title is clear                       |          |
| Status is current                          |          |
| Version is current                         |          |
| Owner is identified                        |          |
| Release is identified                      |          |
| Asset type is approved                     |          |
| Practice domain is approved                |          |
| Capability is approved                     |          |
| Lifecycle stage is approved                |          |
| Guiding principles are relevant            |          |
| Dependencies are repository-relative       |          |
| Last updated date is current               |          |
| YAML formatting follows DMAF standard      |          |
| Repository folder is appropriate           |          |
| Workbench metadata readiness is sufficient |          |

---

# 14. Status

This Asset Metadata Standard is currently in Draft v0.1.0 status.

It is the second packaging artifact created in Sprint 6.
