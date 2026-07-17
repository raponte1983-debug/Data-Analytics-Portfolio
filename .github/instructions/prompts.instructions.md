\# Prompt Engineering Instructions

\#\# Purpose

Define the standards for creating prompts used with AI assistants during the development of the Data Analytics Portfolio Platform (DAPP).

These instructions apply to GitHub Copilot, ChatGPT, NotebookLM and any future AI-assisted development tools.

\---

\#\# Objectives

Always create prompts that:

\- Are clear and unambiguous.  
\- Minimize token consumption.  
\- Maximize response quality.  
\- Preserve project consistency.  
\- Reuse existing project context.

\---

\#\# Prompt Structure

Whenever possible, structure prompts using the following sections:

\- Role  
\- Context  
\- Objective  
\- Constraints  
\- Expected Output

\---

\#\# Context Management

Always:

\- Provide only the necessary context.  
\- Reference approved project documentation.  
\- Reuse existing architectural decisions.  
\- Avoid repeating information already available in the repository.

\---

\#\# Prompt Quality

Prompts should be:

\- Specific.  
\- Concise.  
\- Action-oriented.  
\- Technically precise.  
\- Free of unnecessary information.

Avoid:

\- Vague requests.  
\- Multiple unrelated objectives.  
\- Contradictory instructions.

\---

\#\# Code Generation

When requesting code:

\- Specify the target technology.  
\- Reference the applicable architecture.  
\- Define expected inputs and outputs.  
\- State any performance or security requirements.

\---

\#\# Documentation Generation

When requesting documentation:

\- Follow the approved documentation standard.  
\- Reference related ADRs when applicable.  
\- Maintain consistency with existing documents.  
\- Avoid duplicating content.

\---

\#\# Review Prompts

When requesting reviews:

\- Clearly define the review objective.  
\- Specify the evaluation criteria.  
\- Request concrete findings and recommendations.  
\- Avoid open-ended reviews without scope.

\---

\#\# Token Efficiency

Prefer:

\- Modular prompts.  
\- Reusable prompt templates.  
\- Incremental interactions.  
\- Focused objectives.

Avoid unnecessarily long conversations when a targeted prompt is sufficient.

\---

\#\# AI Collaboration

Maintain consistency across all AI tools by following the same project standards and approved documentation.

\---

\#\# Reference Documents

\- DAPP-DOC-010-System\_Architecture.md  
\- DAPP-ADR-001-Technology\_Stack.md  
\- DAPP-ADR-002-Repository\_Strategy.md  
\- DAPP-DOC-000-Document\_Standard.md  
