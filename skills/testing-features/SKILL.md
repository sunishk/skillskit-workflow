---
name: testing-features
description: Add and run focused tests for implemented Java/Spring Boot features.
---

# Testing Features

Test the implemented behavior using the repository's existing test conventions.

## Priorities

1. Unit tests for business logic
2. Controller/integration tests for API behavior
3. Repository tests where persistence behavior changed
4. Kafka tests when Kafka behavior changed
5. Edge cases and regression scenarios

## Rules

- Reuse the project's existing test framework and helpers.
- Prefer descriptive test names.
- Cover success and failure paths.
- Run the relevant test/build commands when available.
- Report failures clearly so the implementation stage can fix them.

The Development AI Agent performs final deterministic validation and is authoritative for pass/fail status.
