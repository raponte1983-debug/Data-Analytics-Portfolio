\# Testing Instructions

\#\# Purpose

Define the testing standards for the Data Analytics Portfolio Platform (DAPP).

These instructions apply to source code, components, pages, integrations and analytical modules.

\---

\#\# Testing Principles

Always:

\- Test before merging changes.  
\- Prefer automated testing whenever practical.  
\- Keep tests simple, readable and maintainable.  
\- Ensure tests are deterministic and reproducible.

\---

\#\# Testing Levels

Use the following testing levels when applicable:

\- Unit Testing  
\- Integration Testing  
\- End-to-End Testing (E2E)  
\- Manual Validation  
\- Accessibility Testing  
\- Performance Testing

\---

\#\# Unit Tests

Unit tests should:

\- Validate a single behavior.  
\- Be independent.  
\- Execute quickly.  
\- Avoid external dependencies.

\---

\#\# Integration Tests

Integration tests should verify:

\- Component interaction.  
\- Data flow.  
\- Routing.  
\- External service integration when applicable.

\---

\#\# End-to-End Tests

E2E tests should validate:

\- Critical user journeys.  
\- Navigation.  
\- Search.  
\- Project pages.  
\- Responsive behavior.

\---

\#\# Manual Validation

Before completing any feature, verify:

\- Functionality.  
\- Responsive design.  
\- Accessibility.  
\- Visual consistency.  
\- Navigation.

\---

\#\# Accessibility Testing

Verify:

\- Keyboard navigation.  
\- Semantic HTML.  
\- Alternative text.  
\- Color contrast.  
\- Focus visibility.

\---

\#\# Performance Testing

Verify:

\- Fast page load.  
\- Optimized assets.  
\- Minimal JavaScript.  
\- Acceptable Lighthouse scores.

\---

\#\# AI Testing

When generating tests:

\- Cover expected behavior.  
\- Cover edge cases.  
\- Avoid redundant tests.  
\- Keep test code maintainable.

\---

\#\# Definition of Done

A feature is complete only if:

\- Implementation is finished.  
\- Documentation is updated.  
\- Required tests pass.  
\- No known critical defects remain.

\---

\#\# Reference Documents

\- DAPP-DOC-010-System\_Architecture.md  
\- DAPP-ADR-001-Technology\_Stack.md  
\- DAPP-ADR-002-Repository\_Strategy.md  
