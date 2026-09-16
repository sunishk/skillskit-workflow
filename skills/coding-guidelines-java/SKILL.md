---
name: coding-guidelines-java
description: Shared Java and Spring Boot coding guidelines for feature implementation and review.
---

# Java / Spring Boot Coding Guidelines

## Architecture

- Prefer constructor injection.
- Keep controllers focused on HTTP concerns.
- Keep business logic in services.
- Reuse existing interfaces and patterns before introducing new abstractions.
- Prefer immutable DTOs/values where practical.

## Validation and errors

- Use Bean Validation at API boundaries where appropriate.
- Use domain-specific exceptions.
- Follow the repository's existing error-response conventions.

## Logging

- Use SLF4J / the repository's existing logging approach.
- Do not log passwords, tokens, secrets, or unnecessary PII.
- Include useful business/technical context in logs.

## Transactions

- Keep transaction boundaries in the service layer.
- Keep transactions short.
- Avoid remote/external calls inside database transactions where practical.

## Quality

- Prefer clear names and small focused methods/classes.
- Do not add hard-coded environment-specific values when configuration is appropriate.
- Do not leave commented-out code or debug prints.
- Add/update tests for behavior changes.
