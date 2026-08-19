# Dmitry Nesmachny

**Enterprise & Solution Architect**

[Architecture portfolio](https://nesmachnydn.github.io/) · [LinkedIn](https://www.linkedin.com/in/dmitry-nesmachniy/)

I design enterprise and solution architectures for complex corporate systems, with a focus on architecture transformation, integration, content and document platforms, secure exchange, architecture repositories, engineering enablement, and technology decision governance.

My work combines architecture governance with hands-on technical design: from motivation, capabilities and application landscapes to integration boundaries, deployment constraints, data flows, security concerns, technology selection, migration planning, and implementation-ready architectural decisions.

## Architecture focus

- Enterprise Architecture — TOGAF, ArchiMate, capability-based planning, baseline/target architecture and migration roadmaps
- Solution Architecture — service decomposition, integration boundaries, quality attributes and deployment design
- Enterprise Integration — APIs, messaging, filesystem exchange, store-and-forward patterns, transition architectures and legacy modernization
- Security Architecture — IAM/IdM integration, RBAC boundaries, access governance, Segregation of Duties and reconciliation
- Architecture Governance — ADRs, traceability, technology standards, architecture reviews, solution selection, trade studies and implementation review
- AI-Assisted Engineering — repository-governed context, bounded PRs, versioned prompts, independent review and explicit quality gates
- Architecture Tooling — repository automation, developer tooling and repeatable engineering environments

## Enterprise architecture & transformation cases

| Project | Architecture focus |
|---|---|
| **[Cloud Development Platform Architecture](https://github.com/NesmachnyDN/cloud-development-platform-architecture)** | End-to-end enterprise architecture transformation case developed with TOGAF 10 concepts and ArchiMate. Covers stakeholders and motivation, capability planning, AS-IS/TO-BE value streams, baseline/target architecture, ABB/SBB decomposition, GAP analysis, organization design, risk/readiness assessment and migration roadmap. The original model contains 487 elements, 847 relationships and 20 ArchiMate views. |
| **[Enterprise Integration Modernization](https://github.com/NesmachnyDN/enterprise-integration-migration-case)** | Legacy integration modernization case focused on the migration stream: AS-IS, transition and target architectures, controlled coexistence, migration archetypes, readiness gates, wave planning, pilot-first validation, cutover/rollback governance and a repeatable migration factory. |

## Security architecture & access governance

| Project | Architecture focus |
|---|---|
| **[Centralized IAM Integration for an Enterprise Platform](https://github.com/NesmachnyDN/enterprise-platform-iam-integration-case)** | Centralized access-management architecture separating IAM control plane from application runtime. Demonstrates directory-group-to-RBAC mapping, workflow-governed provisioning/deprovisioning, TEST/PROD entitlement separation, Segregation of Duties, reconciliation and controlled IAM failure behavior. |

## Architecture review, governance & technology decisions

| Project | Architecture focus |
|---|---|
| **[Federated Platform Architecture Review](https://github.com/NesmachnyDN/federated-platform-architecture-review)** | Architecture review case for a distributed enterprise platform. Demonstrates separation of control and execution planes, governed node profiles, lifecycle/version management, bounded autonomy, synchronization and reconciliation semantics, operations responsibility boundaries and failure containment. |
| **[IT Solution Selection Framework](https://github.com/NesmachnyDN/it-solution-selection-framework)** | Vendor-neutral architecture trade-study framework for selecting enterprise IT solutions. Demonstrates non-compensatory mandatory gates, evidence-backed weighted evaluation, common-horizon TCO, initial/residual risk assessment, sensitivity analysis and an explicit recommendation with trade-offs and decision conditions. Includes a reusable Excel template and a fully synthetic worked example. |

## Solution architecture & integration cases

| Project | Architecture focus |
|---|---|
| **[Portable Secure Exchange Client](https://github.com/NesmachnyDN/portable-secure-exchange-client)** | Cross-platform local client for controlled file exchange. Demonstrates filesystem-based integration boundaries, file-integrity verification, detached-signature abstraction, local audit, embedded persistence and self-contained Windows/Linux packaging. |
| **[Offline Worklog Bridge](https://github.com/NesmachnyDN/offline-worklog-bridge)** | Offline-first integration bridge for systems available only from mutually exclusive network contexts. Demonstrates store-and-forward synchronization, canonical data modeling, anti-corruption layers, reconciliation, proportional allocation, traceability and idempotent publishing. |

## Architecture & engineering tooling

| Project | Engineering focus |
|---|---|
| **[AI-Assisted Engineering Template](https://github.com/NesmachnyDN/ai-assisted-engineering-template)** | Reusable architecture-governed workflow for software development with AI coding agents. Turns project context, architecture constraints, roadmaps, bounded PRs, versioned prompts, validation evidence, independent review and remediation into explicit repository artifacts instead of transient chat context. |
| **[SILA Union Development Toolkit](https://github.com/NesmachnyDN/sila-union-development-toolkit)** | Vendor-neutral Java toolkit illustrating architecture-repository automation, glossary import, synthetic repository stubs and architecture reporting. |
| **[Local Microservice Dev Stack](https://github.com/NesmachnyDN/local-microservice-dev-stack)** | Reproducible local infrastructure bootstrap for microservice development with PostgreSQL, Kafka and Apache Artemis while application services run and debug from the IDE. |

## How I approach architecture

I treat architecture as an engineering discipline rather than a diagramming activity. A useful architecture should make boundaries explicit, explain trade-offs, preserve traceability to business drivers and requirements, constrain implementation where necessary, and provide a realistic path from baseline to target state.

The repositories above are curated public portfolio artifacts. Depending on the case, they use generalized/synthetic data or sanitized independently authored architecture material. They are structured to demonstrate architecture decisions and engineering practices without exposing proprietary source code, credentials, internal endpoints, or organization-specific confidential data.

---

**Core areas:** Enterprise Architecture · Solution Architecture · TOGAF · ArchiMate · Capability-Based Planning · Integration Architecture · Security Architecture · IAM / IdM · RBAC · Legacy Modernization · Transition Architecture · Architecture Governance · Architecture Review · Decision Analysis · Technology Selection · AI-Assisted Engineering · DDD · Java · Spring Boot · Architecture Automation