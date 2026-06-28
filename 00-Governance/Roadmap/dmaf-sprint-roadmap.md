**DMAF Sprint Roadmap & Delivery Plan**

It should live in your repo under:

```text
00-Governance/Roadmap/dmaf-sprint-roadmap.md
```

Recommended sprint structure:

| Sprint    | Focus                            | Primary Outcome                                               |
| --------- | -------------------------------- | ------------------------------------------------------------- |
| Sprint 0  | Environment & Repo Setup         | Completed - GitHub repo initialized                           |
| Sprint 1  | Foundation Architecture          | Completed - DMAF constitutional document                                  |
| Sprint 2  | Framework Core                   | Completed - Charter, principles, domains, lifecycle, taxonomy             |
| Sprint 3  | Capability Model                 | Completed - Practice domains, capabilities, maturity model                |
| Sprint 4  | Asset Architecture               | Completed - Asset catalog and metadata standards                          |
| Sprint 5  | Migration Factory Toolkit        | Scoring, waves, factory model                                 |
| Sprint 6  | Coexistence & Validation Toolkit | Validation and cutover framework                              |
| Sprint 7  | Architecture Library             | Databricks reference architectures                            |
| Sprint 8  | Executive Advisory Toolkit       | Discovery findings, proposals, exec narratives                |
| Sprint 9  | Industry Pack — Banking          | TD/CIBC/BMO-style prospect and play materials                 |
| Sprint 10 | Workbench Blueprint              | Product architecture for Modernization Intelligence Workbench |
| Sprint 11 | Release 1.0 Packaging            | Baseline review and release notes                             |

---
## Sprint 0 — Repository Foundation

**Status:** Complete  
**Outcome:** DMAF GitHub repository initialized with baseline folder structure, governance folders, framework folders, asset library, Workbench structure, GitHub templates, metadata template, and initial repository documentation.

**Completion Notes:**
- Repository structure generated using `bootstrap_dmaf.py`
- Initial structure committed and pushed to GitHub
- DMAF is now ready for Foundation Architecture development

---

## Sprint 1 — Foundation Architecture

**Status:** Complete
**Release:** Release 1.0 Foundation
**Primary Artifact:** `00-Governance/Charter/dmaf-foundation-architecture-v1.md`
**Completion Date:** 2026-06-26

### Objective

Create the foundational architecture document for the Databricks Modernization Advisory Framework.

The purpose of this sprint was to establish DMAF as a coherent, governed, Databricks-first modernization framework with clear principles, domains, lifecycle stages, governance rules, release structure, and baseline criteria.

### Completed Outputs

* DMAF Foundation Architecture v1.0 drafted
* Guiding principles documented
* Practice domains documented
* Cross-cutting capabilities documented
* DMAF lifecycle documented
* DMAF meta model documented
* DMAF knowledge graph documented
* DMAF capability model documented
* DMAF governance model documented
* Product roadmap alignment documented
* Repository and asset governance documented
* Release 1.0 baseline criteria documented
* QA review completed
* Baseline register created
* Release 1.0 release notes created

### Completion Notes

Sprint 1 establishes the constitutional foundation for DMAF.

Future DMAF assets, playbooks, reference architectures, industry packs, Workbench modules, consulting templates, and delivery accelerators should align to the Foundation Architecture unless a governed change is approved.

### Sprint 1 Outcome

**Complete — Ready for Release 1.0 baseline.**

---

## Sprint 2 — Framework Core

**Status:** Complete
**Release:** Release 1.0 Foundation / Release 1.5 Practice Architecture
**Primary Folder:** `01-Framework/`
**Completion Date:** 2026-06-26

### Objective

Extract the approved concepts from the DMAF Foundation Architecture into modular framework artifacts under `01-Framework/`.

The purpose of this sprint was to make the framework easier to maintain, reference, extend, and reuse. The Foundation Architecture remains the constitutional source of truth, while Sprint 2 created focused framework files for day-to-day practice use.

### Completed Outputs

* Framework Core README updated
* DMAF Taxonomy and Glossary created
* Practice Domain Model created
* Lifecycle Model created
* Cross-Cutting Capabilities Model created
* Meta Model created
* Knowledge Graph created
* Capability Model created
* Sprint 2 QA cleanup completed
* Metadata taxonomy correction applied
* Governance / practice domain distinction clarified

### Completion Notes

Sprint 2 successfully modularized the Foundation Architecture into reusable framework components.

The Framework Core now provides standalone reference files that support future playbook development, asset governance, capability catalogue development, Workbench design, and practice onboarding.

### Sprint 2 Outcome

**Complete — Framework Core extraction completed and pushed to GitHub.**

---

## Sprint 3 — Practice Capability Catalogue

**Status:** Complete
**Release:** Release 1.5 Practice Architecture
**Primary Folder:** `01-Framework/Capability-Model/`
**Completion Date:** 2026-06-27

### Objective

Create the first detailed Practice Capability Catalogue for DMAF.

The purpose of this sprint was to define the reusable capabilities within each approved practice domain and establish the structure for future methods, assets, KPIs, maturity assessment, ownership, and Workbench automation.

### Completed Outputs

* Practice Capability Catalogue created
* Capability definition template established
* Capability ID convention established
* Capability-to-domain mapping completed
* Capability-to-lifecycle mapping completed
* Initial capability maturity targets documented
* Capability ownership model applied
* Workbench automation potential identified
* Sprint 3 QA review completed

### Capability Catalogue Summary

| Practice Domain                                   | Capability Count | Status      |
| ------------------------------------------------- | ---------------: | ----------- |
| Strategy & Business Value                         |                7 | Drafted     |
| Discovery & Assessment                            |                8 | Drafted     |
| Modernization Architecture                        |                8 | Drafted     |
| Migration Factory                                 |                8 | Drafted     |
| Coexistence & Validation                          |                8 | Drafted     |
| AI & Automation                                   |                8 | Drafted     |
| Executive Advisory                                |                8 | Drafted     |
| Platform Operations, Adoption & Value Realization |                8 | Drafted     |
| Modernization Intelligence Workbench              |                8 | Drafted     |
| **Total**                                         |           **71** | **Drafted** |

### Completion Notes

Sprint 3 moved DMAF from framework architecture into practice architecture.

The Practice Capability Catalogue now defines the initial reusable capability model for all nine approved practice domains. It provides the organizing structure for future methods, reusable assets, maturity assessment, KPIs, ownership, and Workbench automation.

### Sprint 3 Outcome

**Complete — Initial Practice Capability Catalogue drafted and QA reviewed.**

---

## Sprint 4 — Methods and Asset Mapping

**Status:** Complete
**Release:** Release 1.5 Practice Architecture
**Primary Folder:** `01-Framework/Capability-Model/`
**Completion Date:** 2026-06-28

### Objective

Map approved DMAF capabilities to candidate methods and reusable assets.

The purpose of this sprint was to ensure that future templates, workbooks, diagrams, prompts, checklists, decks, dashboards, and Workbench specifications are created from approved capabilities rather than added randomly.

### Completed Outputs

* DMAF Capability Method Asset Map created
* All nine practice domains mapped
* Capabilities mapped to candidate methods
* Capabilities mapped to candidate reusable assets
* Asset types classified
* Priority levels assigned
* Workbench potential identified
* Initial priority build list created
* Sprint 4 QA review completed

### Method and Asset Mapping Summary

| Practice Domain                                   | Mapping Rows | Status     |
| ------------------------------------------------- | -----------: | ---------- |
| Strategy & Business Value                         |           14 | Mapped     |
| Discovery & Assessment                            |           16 | Mapped     |
| Modernization Architecture                        |           16 | Mapped     |
| Migration Factory                                 |           16 | Mapped     |
| Coexistence & Validation                          |           16 | Mapped     |
| AI & Automation                                   |           16 | Mapped     |
| Executive Advisory                                |           16 | Mapped     |
| Platform Operations, Adoption & Value Realization |           16 | Mapped     |
| Modernization Intelligence Workbench              |           16 | Mapped     |
| **Total**                                         |      **142** | **Mapped** |

### Completion Notes

Sprint 4 extended DMAF traceability from framework concepts to capabilities, methods, and candidate reusable assets.

The key control rule established in Sprint 4 is:

```text
No method or asset should be created unless it maps to an approved capability.
```

This prevents uncontrolled content expansion and prepares DMAF for focused priority asset development.

### Sprint 4 Outcome

**Complete — Capability-to-method and capability-to-asset mapping completed and QA reviewed.**

---

## Sprint 5 — Priority Asset Build Pack

**Status:** Complete
**Release:** Release 2.0 Consulting Assets
**Primary Folder:** `03-Assets/`
**Start Date:** 2026-06-28
**Completion Date:** 2026-06-28

### Objective

Build the first reusable DMAF assets from the approved capability-to-method and capability-to-asset map.

The purpose of this sprint was to move from framework and mapping into practical consulting assets that can be reused in advisory, discovery, architecture, migration planning, validation, executive communication, platform operations, and future Workbench scenarios.

### Sprint 5 Control Rule

No asset should be created unless it maps to an approved DMAF capability.

Each Sprint 5 asset was required to include or support:

* approved metadata;
* related practice domain;
* related capability;
* related lifecycle stage;
* related guiding principles;
* intended audience;
* asset type;
* usage guidance;
* review checklist or review criteria;
* future Workbench potential.

### Completed Assets

| Priority | Asset                                     | Asset Type | Related Domain                                    | Related Capability                                           | Status   |
| -------: | ----------------------------------------- | ---------- | ------------------------------------------------- | ------------------------------------------------------------ | -------- |
|        1 | Opportunity Qualification Checklist       | Checklist  | Strategy & Business Value                         | DMAF-CAP-SBV-001 — Modernization Opportunity Qualification   | Complete |
|        2 | Application Inventory Workbook            | Workbook   | Discovery & Assessment                            | DMAF-CAP-DAS-002 — Application & Workflow Inventory Analysis | Complete |
|        3 | Modernization Complexity Scoring Workbook | Workbook   | Discovery & Assessment                            | DMAF-CAP-DAS-005 — Modernization Complexity Scoring          | Complete |
|        4 | Target-State Architecture Template        | Template   | Modernization Architecture                        | DMAF-CAP-MAR-001 — Target-State Architecture Design          | Complete |
|        5 | Migration Wave Planning Workbook          | Workbook   | Migration Factory                                 | DMAF-CAP-MGF-001 — Migration Wave Planning                   | Complete |
|        6 | Validation Strategy Template              | Template   | Coexistence & Validation                          | DMAF-CAP-COV-004 — Validation Strategy Design                | Complete |
|        7 | AI Output Review Checklist                | Checklist  | AI & Automation                                   | DMAF-CAP-AIA-008 — AI Governance & Human Review Model        | Complete |
|        8 | Executive One-Page Template               | Template   | Executive Advisory                                | DMAF-CAP-EXA-006 — Executive Visual Design                   | Complete |
|        9 | Platform Operating Model Template         | Template   | Platform Operations, Adoption & Value Realization | DMAF-CAP-POV-001 — Platform Operating Model Design           | Complete |
|       10 | Workbench Quality Checklist               | Checklist  | Modernization Intelligence Workbench              | DMAF-CAP-MIW-008 — Workbench Governance & Quality Control    | Complete |

### Repository Outputs

| Asset                                     | Repository Path                                                                 |
| ----------------------------------------- | ------------------------------------------------------------------------------- |
| Opportunity Qualification Checklist       | `03-Assets/Checklists/dmaf-opportunity-qualification-checklist.md`              |
| Application Inventory Workbook            | `03-Assets/Workbooks/dmaf-application-inventory-workbook.xlsx`                  |
| Modernization Complexity Scoring Workbook | `03-Assets/Workbooks/dmaf-modernization-complexity-scoring-workbook.xlsx`       |
| Target-State Architecture Template        | `03-Assets/Templates/dmaf-target-state-architecture-template.md`                |
| Migration Wave Planning Workbook          | `03-Assets/Workbooks/dmaf-migration-wave-planning-workbook.xlsx`                |
| Validation Strategy Template              | `03-Assets/Templates/dmaf-validation-strategy-template.md`                      |
| AI Output Review Checklist                | `03-Assets/Checklists/dmaf-ai-output-review-checklist.md`                       |
| Executive One-Page Template               | `03-Assets/Templates/dmaf-executive-one-page-template.md`                       |
| Platform Operating Model Template         | `03-Assets/Templates/dmaf-platform-operating-model-template.md`                 |
| Workbench Quality Checklist               | `03-Assets/Checklists/dmaf-workbench-quality-checklist.md`                      |
| Sprint 5 QA Review                        | `00-Governance/Governance/dmaf-sprint-5-priority-asset-build-pack-qa-review.md` |

### Acceptance Criteria Review

| Acceptance Criterion                                             | Status   |
| ---------------------------------------------------------------- | -------- |
| At least five priority assets are created                        | Complete |
| Each asset maps to an approved capability                        | Complete |
| Each asset uses approved DMAF metadata or workbook documentation | Complete |
| Each asset includes usage guidance                               | Complete |
| Each asset includes review criteria                              | Complete |
| Each asset identifies future Workbench potential                 | Complete |
| Sprint 5 QA review is completed                                  | Complete |
| Sprint 5 files are committed and pushed to GitHub                | Complete |

### Completion Notes

Sprint 5 moved DMAF from framework architecture into reusable consulting asset development.

The sprint produced the first practical DMAF asset pack across all nine approved practice domains. The assets support early opportunity qualification, discovery intake, complexity scoring, target-state architecture, migration wave planning, validation strategy, AI governance, executive communication, platform operating model definition, and future Workbench quality control.

Sprint 5 also confirmed the DMAF traceability chain:

```text id="3qogm0"
Foundation Architecture
        ↓
Framework Core
        ↓
Practice Capability Catalogue
        ↓
Capability Method Asset Map
        ↓
Priority Asset Build Pack
        ↓
Reusable Consulting Assets
        ↓
Future Workbench Enablement
```

### Sprint 5 Outcome

**Complete — Priority Asset Build Pack created and QA reviewed.**

---


