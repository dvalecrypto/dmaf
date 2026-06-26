---

asset_id: DMAF-FWK-002
title: DMAF Taxonomy and Glossary
status: Draft
version: 0.1.0
owner: DMAF Practice Lead
release: Release-1.0

practice_domain:
- Governance
- Executive Advisory
- Modernization Architecture

lifecycle_stage:
- Opportunity Qualification & Modernization Strategy
- Strategy & Business Value

guiding_principles:
- Everything Is Traceable
- Executive Storytelling Matters
- Knowledge Compounds

dependencies:
- 00-Governance/Charter/dmaf-foundation-architecture-v1.md

last_updated: 2026-06-26

---

# DMAF Taxonomy and Glossary

## 1. Purpose

The purpose of this document is to define the approved terminology, conceptual distinctions, and naming conventions used by the Databricks Modernization Advisory Framework, referred to as DMAF.

This taxonomy ensures that DMAF content remains consistent as the framework expands into playbooks, assets, reference architectures, industry packs, Workbench modules, AI prompts, and delivery accelerators.

The taxonomy supports:

* consistent language;
* executive clarity;
* practitioner alignment;
* asset traceability;
* Workbench indexing;
* governance review;
* future automation.

This document should be used whenever new DMAF artifacts are created or existing artifacts are revised.

---

## 2. Source of Truth

The source of truth for this taxonomy is:

```text
00-Governance/Charter/dmaf-foundation-architecture-v1.md
```

This taxonomy does not replace the Foundation Architecture.

It extracts, organizes, and clarifies terminology from the Foundation Architecture so that practitioners can apply DMAF language consistently.

---

## 3. Taxonomy Rules

DMAF terminology should follow these rules:

1. Use approved terms consistently.
2. Avoid inventing new names for existing concepts.
3. Do not rename practice domains without governance approval.
4. Do not confuse lifecycle stages with practice domains.
5. Do not confuse assets with methods.
6. Do not confuse the Workbench with the Asset Library.
7. Do not treat reference architectures as the full methodology.
8. Use Databricks-first language without making DMAF source-platform limited.
9. Mark future-state concepts clearly when they are not yet implemented.
10. Ensure major artifacts can be traced to principles, domains, capabilities, lifecycle stages, and release versions.

---

## 3.1 Metadata Usage Rule

DMAF metadata must use approved taxonomy values consistently.

The `practice_domain` field should contain only approved DMAF practice domains.

The approved practice domains are:

1. Strategy & Business Value
2. Discovery & Assessment
3. Modernization Architecture
4. Migration Factory
5. Coexistence & Validation
6. AI & Automation
7. Executive Advisory
8. Platform Operations, Adoption & Value Realization
9. Modernization Intelligence Workbench

The term `Governance` should not be used as a practice domain unless a future governed change explicitly adds it as one.

Governance-related assets should instead use one or more of the following approaches:

* place the asset in the appropriate governance repository folder;
* map the asset to a relevant approved practice domain;
* use `Governance & Security` under `cross_cutting_capabilities`;
* identify governance relevance in the asset purpose or review criteria.

Similarly, the following are cross-cutting capabilities, not practice domains:

* Governance & Security
* Risk & Compliance
* FinOps & Cost Optimization
* AI Enablement
* Automation
* Knowledge Management
* Reusable Accelerators

Repository areas, folder names, and cross-cutting capabilities should not be confused with practice domains.

---
## 4. Approved Framework Name

| Term                                        | Definition                                                               | Status   |
| ------------------------------------------- | ------------------------------------------------------------------------ | -------- |
| Databricks Modernization Advisory Framework | The full official name of the framework.                                 | Approved |
| DMAF                                        | The official short name for Databricks Modernization Advisory Framework. | Approved |

Do not use alternate names for the framework unless explicitly approved through governance.

---

## 5. Core DMAF Terms

| Term                     | Definition                                                                                                                                                                                      |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DMAF                     | A Databricks-first advisory and delivery framework for helping organizations plan, govern, and execute modernization from legacy data platforms to Databricks-centered lakehouse architectures. |
| Foundation Architecture  | The constitutional reference document that defines DMAF purpose, principles, domains, lifecycle, meta model, knowledge graph, capability model, and governance model.                           |
| Practice Domain          | A major area of advisory, architecture, delivery, or enablement capability required to plan and execute Databricks-led modernization.                                                           |
| Capability               | A reusable practice competency within a practice domain. A capability defines what DMAF must be able to do.                                                                                     |
| Method                   | A repeatable approach, process, workshop, assessment model, decision tree, or delivery pattern used to execute a capability.                                                                    |
| Asset                    | A reusable work product such as a template, diagram, workbook, checklist, deck, script, prompt, or reference artifact.                                                                          |
| Platform Service         | A software-enabled or AI-assisted capability that operationalizes DMAF through the Modernization Intelligence Workbench or related tooling.                                                     |
| Lifecycle Stage          | A phase in the DMAF modernization lifecycle describing when work occurs.                                                                                                                        |
| Cross-Cutting Capability | A shared concern that applies across multiple practice domains and lifecycle stages.                                                                                                            |
| Baseline                 | An approved release-level version of a DMAF artifact or decision.                                                                                                                               |
| Baseline Register        | The formal record of approved DMAF decisions, artifacts, gates, and release baselines.                                                                                                          |
| Release Notes            | A summary of what is included, excluded, changed, and still open in a DMAF release.                                                                                                             |
| Workbench                | The future software-enabled environment for applying, scaling, and automating DMAF.                                                                                                             |
| Asset Library            | The curated collection of reusable DMAF intellectual property.                                                                                                                                  |

---

## 6. Approved Practice Domains

DMAF contains nine approved practice domains.

| # | Practice Domain                                   | Definition                                                                                                    |
| - | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| 1 | Strategy & Business Value                         | Defines the business rationale, executive alignment, investment logic, and measurable value of modernization. |
| 2 | Discovery & Assessment                            | Defines how DMAF gathers, normalizes, interprets, and scores current-state modernization evidence.            |
| 3 | Modernization Architecture                        | Defines target-state and transitional Databricks-centered architecture models.                                |
| 4 | Migration Factory                                 | Defines how modernization is planned, sequenced, industrialized, executed, and measured at scale.             |
| 5 | Coexistence & Validation                          | Defines how legacy and modern platforms coexist during transition and how modernization outcomes are proven.  |
| 6 | AI & Automation                                   | Defines how automation and AI-assisted techniques accelerate modernization while preserving human governance. |
| 7 | Executive Advisory                                | Defines how modernization is communicated, positioned, and governed with senior stakeholders.                 |
| 8 | Platform Operations, Adoption & Value Realization | Defines how the modernized platform is adopted, governed, operated, optimized, and measured after migration.  |
| 9 | Modernization Intelligence Workbench              | Defines the future software-enabled layer that operationalizes DMAF.                                          |

---

## 7. Approved Cross-Cutting Capabilities

DMAF contains seven approved cross-cutting capabilities.

| # | Cross-Cutting Capability   | Definition                                                                                                                         |
| - | -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 1 | Governance & Security      | Defines how data, access, policies, standards, controls, and security expectations are managed across modernization.               |
| 2 | Risk & Compliance          | Defines how modernization risk is identified, assessed, communicated, mitigated, and governed.                                     |
| 3 | FinOps & Cost Optimization | Defines how modernization addresses cost transparency, platform efficiency, consumption management, and financial sustainability.  |
| 4 | AI Enablement              | Defines how modernization prepares the client for AI adoption and how AI can accelerate modernization work.                        |
| 5 | Automation                 | Defines how repeatable modernization activities can be standardized, scripted, templated, or productized.                          |
| 6 | Knowledge Management       | Defines how engagement learning, patterns, decisions, assumptions, risks, and assets are captured and reused.                      |
| 7 | Reusable Accelerators      | Defines the tools, templates, scripts, calculators, diagrams, prompts, and workbooks that improve modernization speed and quality. |

---

## 8. Approved Lifecycle Stages

DMAF contains eleven lifecycle stages, beginning with Stage 0.

| Stage | Lifecycle Stage                                      | Definition                                                                                               |
| ----- | ---------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| 0     | Opportunity Qualification & Modernization Strategy   | Determines whether a modernization opportunity is real, valuable, actionable, and strategically aligned. |
| 1     | Strategy & Business Value                            | Defines the business rationale, outcomes, sponsorship, and value logic for modernization.                |
| 2     | Discovery & Assessment                               | Establishes the evidence base for modernization decisions.                                               |
| 3     | Modernization Architecture                           | Defines the target-state and transitional architecture direction.                                        |
| 4     | Migration Factory Planning                           | Turns modernization strategy and architecture into an executable migration factory model.                |
| 5     | Reference Implementation / Pilot                     | Validates the modernization approach through a controlled implementation.                                |
| 6     | Migration Factory Execution                          | Executes modernization at scale using repeatable factory practices.                                      |
| 7     | Coexistence & Validation                             | Ensures legacy and modern platforms can coexist and that modernized outcomes are trusted.                |
| 8     | Production Cutover                                   | Transitions modernized workloads into production use.                                                    |
| 9     | Platform Operations, Adoption & Value Realization    | Ensures the client can operate, adopt, govern, optimize, and derive value from the modernized platform.  |
| 10    | Continuous Optimization & Modernization Intelligence | Converts modernization learning into ongoing optimization and reusable intelligence.                     |

---

## 9. Approved Guiding Principles

DMAF contains eleven guiding principles.

| #  | Guiding Principle                   | Short Definition                                                                                                                                |
| -- | ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | Business Value Before Technology    | Modernization must begin with business value, not technology replacement.                                                                       |
| 2  | Databricks by Design                | DMAF is Databricks-first and evaluates modernization through a Databricks-centered target-state lens.                                           |
| 3  | Modernization Is an Operating Model | Modernization is not only a migration project; it creates a new way to assess, migrate, validate, govern, operate, and optimize data platforms. |
| 4  | Industrialize Delivery              | DMAF favors repeatable, factory-oriented delivery over ad hoc migration.                                                                        |
| 5  | Coexistence Is Intentional          | Coexistence between legacy and modern platforms must be deliberately designed, governed, and validated.                                         |
| 6  | Trust Is Earned Through Validation  | Modernization outcomes must be proven through validation, reconciliation, and business acceptance.                                              |
| 7  | AI Accelerates, People Govern       | AI may accelerate modernization, but accountable practitioners govern decisions and outputs.                                                    |
| 8  | Executive Storytelling Matters      | Modernization must be understandable to both executives and delivery teams.                                                                     |
| 9  | Knowledge Compounds                 | Every engagement should strengthen DMAF through reusable learning and assets.                                                                   |
| 10 | Platform Value Is the Destination   | Migration is successful only when the modernized platform becomes a trusted foundation for future value.                                        |
| 11 | Everything Is Traceable             | Every major recommendation, method, asset, and Workbench capability should trace back to the framework.                                         |

---

## 10. Conceptual Distinctions

This section defines distinctions that must remain consistent across DMAF.

---

### 10.1 Framework vs. Methodology

| Concept     | Meaning                                                                                                                  |
| ----------- | ------------------------------------------------------------------------------------------------------------------------ |
| Framework   | The organizing structure of DMAF, including principles, domains, lifecycle, meta model, knowledge graph, and governance. |
| Methodology | The repeatable approach for applying DMAF in modernization engagements.                                                  |

Use **framework** when referring to how DMAF is organized.

Use **methodology** when referring to how DMAF is applied.

---

### 10.2 Framework vs. Playbook

| Concept   | Meaning                                           |
| --------- | ------------------------------------------------- |
| Framework | What DMAF is and how it is organized.             |
| Playbook  | How practitioners apply DMAF in real engagements. |

The framework should remain relatively stable.

The playbook may evolve more frequently as delivery practices, lessons learned, client needs, and Databricks capabilities change.

---

### 10.3 Practice Domain vs. Capability

| Concept         | Meaning                                                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------------------- |
| Practice Domain | A major area of practice capability, such as Migration Factory or Coexistence & Validation.                    |
| Capability      | A specific reusable competency within a domain, such as Migration Wave Planning or Validation Strategy Design. |

A domain contains capabilities.

A capability should belong primarily to one domain but may support multiple lifecycle stages.

---

### 10.4 Capability vs. Method

| Concept    | Meaning                           |
| ---------- | --------------------------------- |
| Capability | What DMAF must be able to do.     |
| Method     | How that capability is performed. |

Example:

```text
Capability: Migration Wave Planning
Method: Complexity-Based Wave Sequencing
```

---

### 10.5 Method vs. Process

| Concept | Meaning                                                                         |
| ------- | ------------------------------------------------------------------------------- |
| Method  | A reusable approach that may include steps, decisions, templates, and judgment. |
| Process | A defined sequence of activities or workflow steps.                             |

A method may contain one or more processes.

DMAF should use **method** when practitioner judgment and adaptation are required.

---

### 10.6 Asset vs. Deliverable

| Concept     | Meaning                                                             |
| ----------- | ------------------------------------------------------------------- |
| Asset       | A reusable DMAF work product that can support multiple engagements. |
| Deliverable | A client-specific output produced for a specific engagement.        |

A deliverable may be created using a reusable asset.

Before adding a deliverable to the core DMAF repository, it should be sanitized, generalized, and converted into reusable asset form.

---

### 10.7 Reference Architecture vs. Target Architecture

| Concept                | Meaning                                                                           |
| ---------------------- | --------------------------------------------------------------------------------- |
| Reference Architecture | A reusable Databricks-centered architecture pattern for a modernization scenario. |
| Target Architecture    | A client-specific architecture design for a specific modernization engagement.    |

A target architecture may be based on one or more reference architectures.

Reference architectures belong in:

```text
04-Reference-Architectures/
```

Client-specific target architectures should not be stored in the core DMAF repository unless sanitized and generalized.

---

### 10.8 Pattern vs. Accelerator

| Concept     | Meaning                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------ |
| Pattern     | A reusable solution approach or design structure.                                          |
| Accelerator | A reusable tool, template, script, workbook, prompt, or artifact that speeds up execution. |

Example:

```text
Pattern: Complexity-Based Wave Planning
Accelerator: Migration Factory Planning Workbook
```

---

### 10.9 Operating Model vs. Lifecycle

| Concept         | Meaning                                                                            |
| --------------- | ---------------------------------------------------------------------------------- |
| Operating Model | Who does the work, how responsibilities are assigned, and how governance operates. |
| Lifecycle       | When work occurs across modernization stages.                                      |

The lifecycle describes progression.

The operating model describes roles, responsibilities, and governance routines.

---

### 10.10 Asset Library vs. Workbench

| Concept       | Meaning                                                                                                                |
| ------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Asset Library | The curated collection of reusable DMAF intellectual property.                                                         |
| Workbench     | The software-enabled environment that helps practitioners apply, search, generate, interpret, and improve DMAF assets. |

The Workbench should operationalize the Asset Library, not replace it.

---

### 10.11 Governance vs. Delivery

| Concept    | Meaning                                                                                |
| ---------- | -------------------------------------------------------------------------------------- |
| Governance | Defines how DMAF decisions, assets, releases, quality, and change control are managed. |
| Delivery   | Defines how modernization work is executed in a client engagement.                     |

Governance protects consistency.

Delivery produces outcomes.

---

## 11. Knowledge Graph Taxonomy

The approved DMAF Knowledge Graph relationship chain is:

```text
Guiding Principles
        ↓
Practice Domains
        ↓
Capabilities
        ↓
Methods
        ↓
Assets
        ↓
Platform Services
```

Each major DMAF artifact should be traceable through this chain where practical.

---

## 12. Asset Status Terms

DMAF uses the following approved asset statuses.

| Status     | Definition                                         |
| ---------- | -------------------------------------------------- |
| Proposed   | Idea identified, not yet approved for development. |
| Draft      | Content is being created or revised.               |
| Review     | Content is ready for structured review.            |
| Approved   | Content is approved for use.                       |
| Baselined  | Content is part of an official DMAF release.       |
| Deprecated | Content should no longer be used for new work.     |
| Archived   | Content retained for history only.                 |

---

## 13. Release Terms

| Term                              | Definition                                                                                                                                                |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Release                           | A governed version of DMAF or a DMAF asset set.                                                                                                           |
| Release 1.0 Foundation            | The first official DMAF foundation release.                                                                                                               |
| Release 1.5 Practice Architecture | Planned release focused on capability catalogue, operating model, maturity, ownership, and KPIs.                                                          |
| Release 2.0 Consulting Assets     | Planned release focused on reusable consulting assets, playbooks, discovery kits, architecture assets, migration factory toolkit, and validation toolkit. |
| Release Notes                     | Documentation summarizing included items, exclusions, known limitations, acceptance criteria, and next release focus.                                     |
| Baseline                          | A formally accepted version of a DMAF artifact or release.                                                                                                |

---

## 14. Repository Terms

| Term                          | Definition                                                                                        |
| ----------------------------- | ------------------------------------------------------------------------------------------------- |
| `00-Governance/`              | Repository area for charter, roadmap, release notes, baseline register, and governance standards. |
| `01-Framework/`               | Repository area for modular framework components.                                                 |
| `02-Playbook/`                | Repository area for practitioner guidance on applying DMAF.                                       |
| `03-Assets/`                  | Repository area for reusable templates, workbooks, diagrams, workshops, and accelerators.         |
| `04-Reference-Architectures/` | Repository area for Databricks-centered architecture patterns.                                    |
| `05-Workbench/`               | Repository area for future software, prompts, agents, specifications, and knowledge assets.       |
| `06-Research/`                | Repository area for Databricks, Azure, AI, competitor, and industry research.                     |
| `07-Releases/`                | Repository area for release packages, snapshots, and release documentation.                       |
| `99-Archive/`                 | Repository area for retired, deprecated, or historical materials.                                 |

---

## 15. Naming Standards

DMAF file names should follow these standards:

* use lowercase;
* use hyphens instead of spaces;
* be descriptive;
* avoid vague names such as `final`, `latest`, `new`, or `copy`;
* avoid client names in reusable framework assets;
* include version numbers only when useful;
* use `.md` for framework documents.

Examples:

```text
dmaf-foundation-architecture-v1.md
dmaf-taxonomy-and-glossary.md
dmaf-practice-domain-model.md
dmaf-lifecycle-model.md
dmaf-meta-model.md
dmaf-knowledge-graph.md
migration-factory-planning-workbook.md
coexistence-validation-checklist.md
```

---

## 16. Approved Acronyms

| Acronym | Meaning                                                   |
| ------- | --------------------------------------------------------- |
| DMAF    | Databricks Modernization Advisory Framework               |
| AI      | Artificial Intelligence                                   |
| KPI     | Key Performance Indicator                                 |
| RACI    | Responsible, Accountable, Consulted, Informed             |
| FinOps  | Cloud financial operations and cost management discipline |
| ADR     | Architecture Decision Record                              |

Additional acronyms may be added as DMAF expands, but should be defined before use.

---

## 17. Terms to Avoid or Use Carefully

| Term                         | Guidance                                                                                                 |
| ---------------------------- | -------------------------------------------------------------------------------------------------------- |
| Final                        | Avoid. Use a version and status instead.                                                                 |
| Latest                       | Avoid. Use a version and status instead.                                                                 |
| Tool Replacement             | Use carefully. DMAF positions modernization as broader than tool replacement.                            |
| Code Converter               | Avoid describing DMAF this way. DMAF is not a code conversion utility.                                   |
| Generic Cloud Migration      | Avoid describing DMAF this way. DMAF is Databricks-first.                                                |
| One-Time Project             | Avoid. DMAF is a long-lived productized practice capability.                                             |
| Workbench as Source of Truth | Avoid. The Workbench operationalizes DMAF but does not replace the governed framework and asset library. |

---

## 18. Taxonomy Governance

This taxonomy should be updated when:

* a new approved term is introduced;
* a term is renamed;
* a conceptual distinction needs clarification;
* a new practice domain is approved;
* a lifecycle stage is changed;
* a new asset type is introduced;
* a new Workbench object type is defined;
* terminology drift is detected.

Changes to approved core terms should be reflected in:

```text
00-Governance/Baseline-Register/
00-Governance/Release-Notes/
```

---

## 19. Review Checklist

Before approving new DMAF content, reviewers should ask:

1. Does the content use approved DMAF terms?
2. Does it introduce any new terms?
3. Are new terms defined?
4. Does it confuse domains with lifecycle stages?
5. Does it confuse assets with deliverables?
6. Does it confuse framework with playbook?
7. Does it confuse methodology with reference architecture?
8. Does it confuse asset library with Workbench?
9. Does it avoid vague terms such as final or latest?
10. Can the content be traced to DMAF principles, domains, capabilities, lifecycle stages, and release version?

---

## 20. Status

This taxonomy is currently in **Draft v0.1.0** status.

It is the first substantive framework artifact created in Sprint 2.
