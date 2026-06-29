---

title: DMAF Workbench Metadata Readiness Review
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
artifact_type: Readiness Review

practice_domain:
- Modernization Intelligence Workbench

lifecycle_stage:
- Continuous Optimization & Modernization Intelligence
- Discovery & Assessment
- Modernization Architecture
- Migration Factory Planning
- Coexistence & Validation
- Executive Advisory
- Platform Operations, Adoption & Value Realization

guiding_principles:
- AI Accelerates, People Govern
- Knowledge Compounds
- Everything Is Traceable
- Trust Is Earned Through Validation
- Modernization Is an Operating Model

dependencies:
- 03-Assets/README.md
- 00-Governance/Governance/dmaf-asset-metadata-standard.md
- 00-Governance/Release-Notes/release-2.0-consulting-assets.md
- 03-Assets/dmaf-client-ready-starter-pack.md
- 03-Assets/dmaf-example-scenario-pack-plan.md
- 03-Assets/Checklists/dmaf-workbench-quality-checklist.md
- 03-Assets/Checklists/dmaf-ai-output-review-checklist.md

## last_updated: 2026-06-29

---

# DMAF Workbench Metadata Readiness Review

## 1. Purpose

The purpose of this review is to assess whether the current DMAF asset library has enough metadata structure to support future Modernization Intelligence Workbench capabilities.

The Workbench is expected to help ingest inputs, interpret modernization context, recommend assets, generate advisory outputs, support traceability, and improve reuse across engagements.

This review focuses on metadata readiness, not software implementation.

---

## 2. Readiness Review Objective

The objective is to determine whether Release 2.0 consulting assets are ready for future Workbench indexing, retrieval, recommendation, governance, and quality control.

The review evaluates whether assets can be reliably searched, filtered, mapped, recommended, and governed by metadata.

---

# 3. Workbench Metadata Use Cases

Future Workbench capabilities may require metadata to support the following use cases.

| Use Case                               | Metadata Needed                              |
| -------------------------------------- | -------------------------------------------- |
| Recommend assets by engagement stage   | lifecycle_stage                              |
| Recommend assets by practice domain    | practice_domain                              |
| Recommend assets by capability         | capability                                   |
| Recommend assets by role               | intended audience or usage guidance          |
| Recommend assets by asset type         | asset_type                                   |
| Filter internal vs client-ready assets | status, client-ready status                  |
| Check asset currency                   | version, last_updated                        |
| Check governance ownership             | owner                                        |
| Trace asset lineage                    | dependencies                                 |
| Validate framework alignment           | practice_domain, capability, lifecycle_stage |
| Support quality review                 | review checklist, QA criteria                |
| Support example generation             | example scenario links                       |
| Support release packaging              | release, status, version                     |

---

# 4. Current Metadata Readiness Summary

| Readiness Area                          | Current Status  | Notes                                                                                |
| --------------------------------------- | --------------- | ------------------------------------------------------------------------------------ |
| Asset index exists                      | Ready           | `03-Assets/README.md` provides a navigable asset catalogue.                          |
| Metadata standard exists                | Ready           | `dmaf-asset-metadata-standard.md` defines required metadata expectations.            |
| Markdown YAML standard exists           | Ready           | YAML formatting rules are documented.                                                |
| Practice domain metadata exists         | Ready           | Markdown assets include approved practice domain mapping.                            |
| Capability metadata exists              | Ready           | Markdown assets map to approved capabilities.                                        |
| Lifecycle stage metadata exists         | Ready           | Markdown assets identify relevant lifecycle stages.                                  |
| Guiding principle metadata exists       | Ready           | Markdown assets identify relevant guiding principles.                                |
| Workbook metadata exists                | Partially Ready | Workbook metadata is captured in README sheets rather than companion YAML files.     |
| Client-ready metadata exists            | Partially Ready | Client-ready potential is documented in the asset index and starter pack definition. |
| Example scenario metadata exists        | Planned         | Example pack plan exists, but example assets are not yet created.                    |
| Machine-readable asset catalogue exists | Not Ready       | Asset index is human-readable Markdown, not yet structured as YAML, JSON, or CSV.    |
| Workbench ingestion schema exists       | Not Ready       | A formal Workbench asset metadata schema has not yet been created.                   |

---

# 5. Asset-Level Readiness Review

| Asset                                     | Metadata Readiness | Workbench Readiness | Notes                                                                                                |
| ----------------------------------------- | ------------------ | ------------------- | ---------------------------------------------------------------------------------------------------- |
| Opportunity Qualification Checklist       | High               | High                | Strong candidate for opportunity intake and qualification scoring.                                   |
| Application Inventory Workbook            | Medium             | High                | Strong candidate for ingestion, but workbook metadata should be mirrored in machine-readable form.   |
| Modernization Complexity Scoring Workbook | Medium             | High                | Strong candidate for scoring automation, but metadata and scoring definitions should be extractable. |
| Target-State Architecture Template        | High               | High                | Strong candidate for architecture draft generation and capability mapping.                           |
| Migration Wave Planning Workbook          | Medium             | High                | Strong candidate for wave recommendation, but workbook structure should be documented for ingestion. |
| Validation Strategy Template              | High               | High                | Strong candidate for validation rule generation and readiness scoring.                               |
| AI Output Review Checklist                | High               | High                | Strong candidate for AI output review workflow.                                                      |
| Executive One-Page Template               | High               | High                | Strong candidate for executive summary generation.                                                   |
| Platform Operating Model Template         | High               | High                | Strong candidate for operating model draft generation and readiness review.                          |
| Workbench Quality Checklist               | High               | High                | Core governance asset for Workbench quality control.                                                 |

---

# 6. Metadata Strengths

The current asset library has several strengths.

## 6.1 Strong Framework Alignment

Most assets include direct mapping to:

* approved practice domains;
* approved capabilities;
* lifecycle stages;
* guiding principles;
* dependencies;
* release;
* owner;
* status;
* version.

This supports the DMAF principle:

```text id="traceability-principle"
Everything Is Traceable
```

## 6.2 Consistent YAML Pattern for Markdown Assets

Markdown assets use a consistent YAML pattern that can support future parsing, indexing, and retrieval.

The current standard is compatible with future Workbench functions such as:

* asset search;
* domain filtering;
* capability filtering;
* release filtering;
* status filtering;
* dependency analysis.

## 6.3 Asset Index Provides Human Navigation

The asset index provides a clear human-readable catalogue of Release 2.0 assets.

This is useful as a bridge between manual consulting use and future Workbench-based asset recommendation.

## 6.4 Workbench Governance Assets Exist

The Workbench Quality Checklist and AI Output Review Checklist provide early governance controls for future AI-assisted and Workbench-generated outputs.

---

# 7. Metadata Gaps

The current asset library has the following metadata gaps.

## 7.1 Workbook Metadata Is Not Yet Fully Machine-Readable

Workbook assets include README sheets, but they do not yet have companion metadata files.

Recommended future companion files:

```text id="workbook-companion-files"
03-Assets/Workbooks/dmaf-application-inventory-workbook.metadata.yaml
03-Assets/Workbooks/dmaf-modernization-complexity-scoring-workbook.metadata.yaml
03-Assets/Workbooks/dmaf-migration-wave-planning-workbook.metadata.yaml
```

## 7.2 Asset Index Is Human-Readable Only

The current asset index is Markdown. This is useful for people, but a future Workbench will benefit from a structured asset catalogue.

Recommended future catalogue options:

| Option           | Description                                            |
| ---------------- | ------------------------------------------------------ |
| YAML catalogue   | Good for repository-based metadata management.         |
| JSON catalogue   | Good for application ingestion and API use.            |
| CSV catalogue    | Good for spreadsheet review and lightweight reporting. |
| SQLite catalogue | Good for local prototype search and filtering.         |
| Delta table      | Good for future Databricks-based metadata management.  |

## 7.3 Client-Ready Status Is Not Yet a Formal Metadata Field

Client-ready potential is documented, but assets do not yet include a dedicated metadata field such as:

```text id="client-ready-field"
client_ready_status: Candidate
```

Recommended values:

| Value         | Meaning                                                         |
| ------------- | --------------------------------------------------------------- |
| Internal Only | Asset is not intended for client-facing use.                    |
| Candidate     | Asset has client-ready potential but needs review or tailoring. |
| Client-Ready  | Asset is approved for controlled client-facing use.             |
| Baselined     | Asset is approved as part of a release baseline.                |

## 7.4 Intended Audience Is Not Yet Consistently Metadata

Most assets include intended audience sections, but this is not always represented as structured metadata.

A future Workbench should support role-based asset recommendation using a field such as:

```text id="intended-audience-field"
intended_audience:
- Account Executive
- Engagement Lead
- Solution Architect
```

## 7.5 Source Platform Fit Is Not Yet Structured

The client-ready starter pack includes source-platform tailoring guidance, but assets do not yet include structured source-platform metadata.

Potential future field:

```text id="source-platform-field"
source_platform_fit:
- Informatica
- Mainframe
- SSIS
- DataStage
- Hadoop
- Teradata
- Oracle ETL
- Custom Pipelines
```

---

# 8. Recommended Workbench Metadata Fields

Future Workbench-ready assets should support the following metadata fields.

| Field                      | Purpose                                                 |
| -------------------------- | ------------------------------------------------------- |
| asset_id                   | Unique asset identity.                                  |
| title                      | Display name and search result title.                   |
| status                     | Governance and release readiness.                       |
| version                    | Version control and freshness.                          |
| owner                      | Ownership and stewardship.                              |
| release                    | Release filtering.                                      |
| asset_type                 | Asset filtering.                                        |
| practice_domain            | Domain-based retrieval.                                 |
| capability                 | Capability-based retrieval.                             |
| lifecycle_stage            | Engagement-stage recommendation.                        |
| guiding_principles         | Alignment explanation.                                  |
| cross_cutting_capabilities | Governance, AI, FinOps, automation, and risk filtering. |
| dependencies               | Traceability and impact analysis.                       |
| intended_audience          | Role-based recommendation.                              |
| client_ready_status        | Internal vs external-use filtering.                     |
| source_platform_fit        | Source-platform recommendation.                         |
| workbench_use_cases        | Workbench function mapping.                             |
| example_assets             | Link to example-filled versions.                        |
| last_updated               | Freshness and review management.                        |

---

# 9. Proposed Workbench Metadata Schema

The following draft schema should be considered for future Workbench indexing.

```yaml id="draft-workbench-metadata-schema"
asset_id: DMAF-ASSET-TPL-001
title: DMAF Target-State Architecture Template
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-2.0
asset_type: Template
client_ready_status: Candidate

practice_domain:
- Modernization Architecture

capability:
- DMAF-CAP-MAR-001 — Target-State Architecture Design

cross_cutting_capabilities:
- Governance & Security
- Risk & Compliance
- AI Enablement

lifecycle_stage:
- Modernization Architecture
- Reference Implementation / Pilot

guiding_principles:
- Databricks by Design
- Everything Is Traceable

intended_audience:
- Solution Architect
- Enterprise Architect
- Data Architect
- Engagement Lead

source_platform_fit:
- Informatica
- Mainframe
- SSIS
- DataStage
- Hadoop
- Teradata
- Oracle ETL
- Custom Pipelines

workbench_use_cases:
- Asset recommendation
- Architecture draft generation
- Capability mapping
- Governance checklist generation

dependencies:
- 01-Framework/Capability-Model/dmaf-practice-capability-catalogue.md
- 01-Framework/Capability-Model/dmaf-capability-method-asset-map.md

example_assets:
- 03-Assets/Examples/Regional-Financial-Services-Modernization/dmaf-example-target-state-architecture.md

last_updated: 2026-06-29
```

---

# 10. Workbench Readiness Recommendations

## 10.1 Near-Term Recommendations

| Priority | Recommendation                                     | Rationale                                                    |
| -------: | -------------------------------------------------- | ------------------------------------------------------------ |
|        1 | Add companion metadata files for workbook assets   | Makes workbook assets indexable without parsing Excel files. |
|        2 | Add `client_ready_status` to future asset metadata | Enables internal vs external-use filtering.                  |
|        3 | Add `intended_audience` to future asset metadata   | Enables role-based asset recommendation.                     |
|        4 | Add `source_platform_fit` to future asset metadata | Enables source-platform-aware asset recommendation.          |
|        5 | Create a machine-readable asset catalogue          | Supports future Workbench search and retrieval.              |

## 10.2 Medium-Term Recommendations

| Priority | Recommendation                              | Rationale                                                 |
| -------: | ------------------------------------------- | --------------------------------------------------------- |
|        1 | Create Workbench asset metadata schema      | Defines the metadata contract for indexing.               |
|        2 | Create Workbench ingestion rules            | Defines how assets are read, validated, and indexed.      |
|        3 | Create Workbench asset recommendation rules | Defines how assets are recommended based on context.      |
|        4 | Create Workbench review workflow            | Defines human review, approval, and rejection steps.      |
|        5 | Create example-filled assets                | Supports testing, demonstration, and prompt benchmarking. |

---

# 11. Readiness Score

| Readiness Category             | Score 1–5 | Notes                                                                  |
| ------------------------------ | --------: | ---------------------------------------------------------------------- |
| Human navigability             |         5 | Asset index provides strong human navigation.                          |
| Framework traceability         |         5 | Assets map to approved domains and capabilities.                       |
| YAML consistency               |         4 | Markdown assets are consistent; workbook metadata differs.             |
| Machine readability            |         2 | No structured catalogue or metadata schema yet.                        |
| Workbook readiness             |         3 | Workbooks are usable, but companion metadata is needed.                |
| Client-ready filtering         |         3 | Client-ready potential exists but is not yet structured metadata.      |
| Role-based recommendation      |         3 | Role guidance exists but is not yet structured metadata.               |
| Source-platform recommendation |         2 | Source-platform guidance exists only in starter pack narrative.        |
| Workbench governance           |         4 | Workbench and AI quality checklists exist.                             |
| Overall Workbench readiness    |         3 | Strong foundation, but metadata needs to become more machine-readable. |

## 11.1 Overall Readiness Band

```text id="overall-readiness-band"
Medium — Strong human-readable foundation; machine-readable metadata layer still required.
```

---

# 12. Recommended Next Workbench Artifacts

Future Workbench-focused artifacts should include:

| Priority | Artifact                             | Repository Path                                             |
| -------: | ------------------------------------ | ----------------------------------------------------------- |
|        1 | Workbench Asset Metadata Schema      | `05-Workbench/dmaf-workbench-asset-metadata-schema.md`      |
|        2 | Workbench Ingestion Rules            | `05-Workbench/dmaf-workbench-ingestion-rules.md`            |
|        3 | Workbench Asset Recommendation Rules | `05-Workbench/dmaf-workbench-asset-recommendation-rules.md` |
|        4 | Workbook Companion Metadata Files    | `03-Assets/Workbooks/*.metadata.yaml`                       |
|        5 | Machine-Readable Asset Catalogue     | `03-Assets/dmaf-asset-catalogue.yaml`                       |

---

# 13. QA Checklist

| Review Item                                 | Complete |
| ------------------------------------------- | -------- |
| Asset index exists                          | Complete |
| Metadata standard exists                    | Complete |
| Release notes exist                         | Complete |
| Client-ready starter pack definition exists | Complete |
| Example scenario pack plan exists           | Complete |
| Workbench quality checklist exists          | Complete |
| AI output review checklist exists           | Complete |
| Metadata strengths are documented           | Complete |
| Metadata gaps are documented                | Complete |
| Recommended metadata fields are documented  | Complete |
| Future Workbench artifacts are identified   | Complete |

---

# 14. Status

This Workbench Metadata Readiness Review is currently in Draft v0.1.0 status.

It is the sixth packaging artifact created in Sprint 6.
