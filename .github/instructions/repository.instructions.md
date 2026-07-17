\# Repository Instructions

\#\# Purpose

Define the repository management rules for the Data Analytics Portfolio Platform (DAPP).

These instructions apply to source code, documentation, branches, commits and repository organization.

\---

\#\# Repository Structure

Always:

\- Respect the approved repository structure.  
\- Keep a clean and organized repository.  
\- Place files in their corresponding directories.  
\- Follow the Project as a Module (PaaM) architecture.

Never:

\- Create new top-level folders without an approved ADR.  
\- Duplicate repository structures.  
\- Store temporary or personal files in the repository.

\---

\#\# Branch Strategy

Use the approved branch strategy:

\- main  
\- develop  
\- feature/\*  
\- fix/\*  
\- docs/\*  
\- refactor/\*  
\- experiment/\*

Rules:

\- Never commit directly to \`main\`.  
\- Develop new functionality in feature branches.  
\- Use documentation branches only for documentation changes.  
\- Merge changes through Pull Requests.

\---

\#\# Commit Convention

Follow Conventional Commits.

Examples:

\- feat(ui): add project card  
\- feat(project): create football analytics module  
\- fix(router): resolve broken navigation  
\- docs(architecture): update system architecture  
\- refactor(layout): simplify page layout  
\- test(search): add search unit tests  
\- chore(deps): update dependencies

Rules:

\- One logical change per commit.  
\- Keep commit messages concise.  
\- Write commit messages in English.

\---

\#\# Pull Requests

Every Pull Request must:

\- Have a descriptive title.  
\- Include a clear summary.  
\- Reference related documentation when applicable.  
\- Pass all automated validations.  
\- Avoid unrelated modifications.  
\- Be focused on a single objective.

\---

\#\# Version Control

Use Semantic Versioning.

Format:

MAJOR.MINOR.PATCH

Examples:

\- 1.0.0  
\- 1.1.0  
\- 1.2.3  
\- 2.0.0

\---

\#\# Documentation

Whenever repository changes affect:

\- Architecture  
\- Structure  
\- Features  
\- Configuration

Update the corresponding documentation before completing the work.

Documentation must always remain synchronized with the implementation.

\---

\#\# File Naming

Use:

\- English language  
\- lowercase  
\- kebab-case  
\- descriptive names

Avoid:

\- spaces  
\- special characters  
\- generic names  
\- duplicated names

\---

\#\# Dependency Management

Before adding a dependency, verify:

\- Active maintenance.  
\- Compatibility with the approved technology stack.  
\- Compatible license.  
\- No known critical vulnerabilities.  
\- Clear value for the project.

Remove obsolete dependencies whenever possible.

\---

\#\# Repository Security

Never commit:

\- Passwords  
\- API Keys  
\- Tokens  
\- Secrets  
\- Certificates  
\- Private credentials  
\- Environment files containing sensitive information  
\- Generated build artifacts

Use GitHub Secrets for all sensitive configuration.

\---

\#\# AI Collaboration

When generating repository changes:

\- Respect the approved repository strategy.  
\- Follow the approved architecture.  
\- Preserve repository consistency.  
\- Avoid generating unnecessary files.  
\- Do not reorganize the repository unless explicitly requested.

\---

\#\# Reference Documents

\- DAPP-ADR-002-Repository\_Strategy.md  
\- DAPP-ADR-001-Technology\_Stack.md  
\- DAPP-DOC-010-System\_Architecture.md  
