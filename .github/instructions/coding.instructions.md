\# Coding Instructions

\#\# Purpose

Define the coding standards for the Data Analytics Portfolio Platform (DAPP).

These instructions apply to all generated source code.

\---

\#\# General Principles

Always:

\- Write clean, readable and maintainable code.  
\- Prefer simplicity over unnecessary complexity.  
\- Follow SOLID principles whenever applicable.  
\- Follow DRY (Don't Repeat Yourself).  
\- Follow KISS (Keep It Simple, Stupid).  
\- Follow YAGNI (You Aren't Gonna Need It).

\---

\#\# Language

\- Use TypeScript by default.  
\- Avoid plain JavaScript unless explicitly required.  
\- Use modern ECMAScript features supported by the project.

\---

\#\# Naming

Use:

\- PascalCase for components and classes.  
\- camelCase for variables and functions.  
\- UPPER\_SNAKE\_CASE for constants.  
\- kebab-case for file and folder names.

Use descriptive names.

Avoid abbreviations unless they are industry standards.

\---

\#\# Functions

Functions should:

\- Have a single responsibility.  
\- Be small and easy to understand.  
\- Avoid side effects whenever possible.  
\- Return predictable results.

\---

\#\# Components

Components must:

\- Be reusable.  
\- Have a single responsibility.  
\- Receive data through props.  
\- Avoid unnecessary state.  
\- Avoid duplicated logic.

\---

\#\# Code Organization

Always:

\- Group related functionality.  
\- Separate UI, business logic and data.  
\- Keep imports organized.  
\- Remove unused code.

\---

\#\# Error Handling

Always:

\- Handle expected errors.  
\- Provide meaningful error messages.  
\- Avoid empty catch blocks.  
\- Never ignore exceptions silently.

\---

\#\# Performance

Prefer:

\- Efficient algorithms.  
\- Lazy loading where appropriate.  
\- Memoization only when justified.  
\- Minimal client-side JavaScript.

\---

\#\# Security

Never:

\- Hardcode credentials.  
\- Expose secrets.  
\- Trust external input without validation.  
\- Disable security mechanisms without justification.

\---

\#\# Code Quality

Generated code must:

\- Compile successfully.  
\- Be formatted consistently.  
\- Avoid unnecessary complexity.  
\- Be ready for production.

\---

\#\# Reference Documents

\- DAPP-DOC-010-System\_Architecture.md  
\- DAPP-ADR-001-Technology\_Stack.md  
\- DAPP-ADR-002-Repository\_Strategy.md  
