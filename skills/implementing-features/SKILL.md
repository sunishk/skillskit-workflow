---
name: implementing-features
description: Implement Java/Spring Boot features from an approved plan using repository conventions and safe coding practices.
---

# Implementing Features

Implement the requested feature directly in the current repository workspace.

## Before coding

- Read files that will be modified.
- Match existing architecture and naming patterns.
- Verify dependencies and existing services before introducing new ones.

## Java/Spring Boot rules

- Prefer constructor injection.
- Keep controllers thin and business logic in services.
- Use Bean Validation on request DTOs where appropriate.
- Use domain-specific exceptions and existing exception-handling patterns.
- Use SLF4J and do not log secrets or sensitive data.
- Keep transactions in the service layer and avoid external calls inside transactions when possible.
- Reuse existing project libraries/patterns before adding new dependencies.

## Tests

Add or update tests for changed behavior. Follow the project's existing test framework and conventions.

## Delivery rules

- Edit files; do not only describe changes.
- Do not commit, push, or create pull requests unless the orchestration system explicitly asks.
- When validation feedback is provided, focus on fixing that feedback first.
