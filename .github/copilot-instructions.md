\# GitHub Copilot Instructions

\#\# Project

Data Analytics Portfolio Platform (DAPP)

\---

\#\# Purpose

These instructions define the global behavior expected from GitHub Copilot when generating code, documentation, configuration files and project structure.

These rules apply to the entire repository.

\---

\#\# General Principles

\- Follow the approved project documentation before generating code.  
\- Respect all Architecture Decision Records (ADR).  
\- Follow the System Architecture document.  
\- Prioritize maintainability over short-term solutions.  
\- Prefer reusable components.  
\- Keep modules independent.  
\- Generate production-quality code.  
\- Avoid unnecessary complexity.

\---

\#\# Documentation

\- Update documentation when code changes affect architecture or functionality.  
\- Generate Markdown documentation using the project standard.  
\- Do not duplicate information already documented.

\---

\#\# Code Generation

\- Prefer TypeScript over JavaScript.  
\- Generate modular code.  
\- Use descriptive names.  
\- Avoid duplicated logic.  
\- Follow SOLID principles whenever applicable.

\---

\#\# Repository

\- Respect the approved repository structure.  
\- Follow Conventional Commits.  
\- Never generate secrets, credentials or sensitive information.  
\- Assume GitHub Pages as the initial deployment target.

\---

\#\# Security

\- Follow Security by Design.  
\- Validate external inputs.  
\- Avoid insecure dependencies.  
\- Never expose secrets in code.

\---

\#\# AI Collaboration

When context is required, prioritize the following documents:

1\. DAPP-DOC-010-System\_Architecture.md  
2\. DAPP-ADR-001-Technology\_Stack.md  
3\. DAPP-ADR-002-Repository\_Strategy.md  
4\. Project documentation under \`/docs\`.

\---

\#\# Scope

These instructions are global.

More specific rules are defined under:

.github/instructions/  
