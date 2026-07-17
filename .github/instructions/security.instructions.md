\# Security Instructions

\#\# Purpose

Define the secure development rules for the Data Analytics Portfolio Platform (DAPP).

These instructions apply to all source code, dependencies, configuration files, CI/CD workflows and repository management.

\---

\#\# Security Principles

Always:

\- Apply Security by Design.  
\- Apply the Principle of Least Privilege.  
\- Validate all external input.  
\- Fail securely.  
\- Keep security simple and maintainable.

\---

\#\# Secrets Management

Never:

\- Hardcode passwords.  
\- Hardcode API keys.  
\- Hardcode tokens.  
\- Commit secrets to the repository.  
\- Store credentials in source code.

Always:

\- Use GitHub Secrets.  
\- Use environment variables for sensitive configuration.  
\- Rotate secrets when compromised.

\---

\#\# Dependencies

Before adding a dependency:

\- Verify active maintenance.  
\- Verify license compatibility.  
\- Verify there are no known critical vulnerabilities.  
\- Prefer well-established libraries.

Remove unused dependencies.

\---

\#\# Input Validation

Always:

\- Validate user input.  
\- Validate external data.  
\- Sanitize data when required.  
\- Reject invalid data early.

Never trust external input.

\---

\#\# Authentication & Authorization

When authentication is implemented:

\- Use trusted authentication providers.  
\- Never implement custom cryptography.  
\- Store authentication logic separately from UI.  
\- Protect sensitive routes.

\---

\#\# Error Handling

Do not expose:

\- Stack traces.  
\- Internal paths.  
\- Secrets.  
\- Sensitive configuration.  
\- Database details.

Return user-friendly error messages.

\---

\#\# Client-Side Security

Avoid:

\- Inline scripts when possible.  
\- Unnecessary third-party scripts.  
\- Excessive browser permissions.

Optimize for a secure static website.

\---

\#\# Repository Security

Always:

\- Enable Dependabot.  
\- Enable Secret Scanning.  
\- Enable Code Scanning.  
\- Protect the main branch.

Review security alerts regularly.

\---

\#\# AI Security

When generating code:

\- Never generate fake credentials.  
\- Never expose secrets in examples.  
\- Prefer secure defaults.  
\- Follow approved architecture and repository rules.

\---

\#\# Reference Documents

\- DAPP-DOC-010-System\_Architecture.md  
\- DAPP-ADR-001-Technology\_Stack.md  
\- DAPP-ADR-002-Repository\_Strategy.md

