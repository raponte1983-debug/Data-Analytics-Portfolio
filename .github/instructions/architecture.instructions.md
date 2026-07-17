\# Architecture Instructions

\#\# Purpose

Define the mandatory architectural rules for every implementation within the Data Analytics Portfolio Platform (DAPP).

These instructions are mandatory for all generated code, components and project structure.

\---

\#\# Architecture Principles

Always:

\- Follow the approved System Architecture (DAPP-DOC-010).  
\- Follow all approved Architecture Decision Records (ADR).  
\- Respect the Project as a Module (PaaM) architecture.  
\- Prioritize modularity and low coupling.  
\- Maximize component reusability.  
\- Separate content, presentation and business logic.  
\- Keep the architecture scalable and maintainable.

\---

\#\# Project Structure

Always:

\- Respect the approved repository structure.  
\- Place reusable components in the shared components directory.  
\- Keep project-specific resources inside their corresponding project module.  
\- Keep documentation under \`/docs\`.  
\- Keep static assets under \`/public\` or \`/assets\` according to the project structure.

Never:

\- Create folders outside the approved architecture.  
\- Duplicate project structures.

\---

\#\# Components

Components must:

\- Have a single responsibility.  
\- Be reusable whenever possible.  
\- Remain small and maintainable.  
\- Use composition instead of inheritance.  
\- Avoid duplicated implementations.  
\- Receive data through well-defined interfaces.

\---

\#\# Project Modules (PaaM)

Each project module must be independent.

Each module may contain:

\- Documentation  
\- Markdown content  
\- Images  
\- Datasets  
\- Dashboards  
\- Notebooks  
\- Project metadata

A project module must never depend directly on another project module.

\---

\#\# Content Management

Always:

\- Separate content from presentation.  
\- Use Markdown or MDX whenever possible.  
\- Store project metadata outside UI components.

Never:

\- Hardcode project content inside reusable components.  
\- Mix datasets with application logic.

\---

\#\# Performance

Prioritize:

\- Static rendering.  
\- Lazy loading when appropriate.  
\- Optimized assets.  
\- Minimal JavaScript.  
\- Fast page loading.

\---

\#\# Scalability

Every architectural decision must support:

\- New project modules.  
\- New content categories.  
\- Future hosting migration.  
\- Future backend integration.  
\- Future authentication.  
\- Future search improvements.

Avoid architectural decisions that prevent future growth.

\---

\#\# Restrictions

Do not:

\- Break approved architectural decisions.  
\- Introduce unnecessary frameworks.  
\- Create circular dependencies.  
\- Mix UI, business logic and data.  
\- Duplicate reusable components.

\---

\#\# Decision Priority

When conflicts exist, follow this order:

1\. Approved ADRs  
2\. System Architecture  
3\. Repository Strategy  
4\. Documentation Standards  
5\. Local implementation decisions

\---

\#\# Reference Documents

\- DAPP-DOC-010-System\_Architecture.md  
\- DAPP-ADR-001-Technology\_Stack.md  
\- DAPP-ADR-002-Repository\_Strategy.md  
