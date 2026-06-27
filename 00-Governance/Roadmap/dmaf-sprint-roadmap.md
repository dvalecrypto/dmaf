**DMAF Sprint Roadmap & Delivery Plan**

It should live in your repo under:

```text
00-Governance/Roadmap/dmaf-sprint-roadmap.md
```

Recommended sprint structure:

| Sprint    | Focus                            | Primary Outcome                                               |
| --------- | -------------------------------- | ------------------------------------------------------------- |
| Sprint 0  | Environment & Repo Setup         | Completed — GitHub repo initialized                           |
| Sprint 1  | Foundation Architecture          | Completed - DMAF constitutional document                                  |
| Sprint 2  | Framework Core                   | Completed - Charter, principles, domains, lifecycle, taxonomy             |
| Sprint 3  | Capability Model                 | Completed - Practice domains, capabilities, maturity model                |
| Sprint 4  | Asset Architecture               | Asset catalog and metadata standards                          |
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

**Status:** In Progress
**Release:** Release 1.5 Practice Architecture
**Primary Folder:** `01-Framework/Capability-Model/`
**Start Date:** 2026-06-26

### Objective

Create the first detailed Practice Capability Catalogue for DMAF.

The purpose of this sprint is to define the reusable capabilities within each approved practice domain and establish the structure for future methods, assets, KPIs, maturity assessment, ownership, and Workbench automation.

### Planned Outputs

* Practice Capability Catalogue
* Capability definition template refinement
* Capability-to-domain mapping
* Capability-to-lifecycle mapping
* Initial capability maturity targets
* Capability ownership model refinement
* Capability-to-asset planning structure
* Capability-to-Workbench automation potential

### Acceptance Criteria

Sprint 3 may be considered complete when:

1. Each of the nine practice domains has an initial set of defined capabilities.
2. Each capability has a clear business objective.
3. Each capability is mapped to a practice domain.
4. Each capability is mapped to relevant lifecycle stages.
5. Initial owners are identified.
6. Initial maturity targets are documented.
7. Future methods and assets can be derived from the catalogue.
8. Workbench automation potential is identified where relevant.
9. Terminology remains consistent with the DMAF Taxonomy and Glossary.
10. All Sprint 3 files are committed and pushed to GitHub.

### Sprint 3 Outcome

**In Progress — Practice Capability Catalogue development started.**

---


**In Progress — Framework Core extraction underway.**

---

