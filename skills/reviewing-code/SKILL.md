---
name: reviewing-code
description: Review Java/Spring Boot changes for correctness, maintainability, security, and alignment with repository conventions.
---

# Reviewing Code

Review the implementation after code changes.

## Review areas

- Requirement alignment and functional correctness
- Spring Boot architecture and dependency injection
- Validation and exception handling
- Logging and sensitive-data handling
- Transaction boundaries
- API compatibility
- Security risks
- Performance issues
- Test coverage and regression risk

## Severity

- Critical: security/data-loss/breaking correctness issues
- Major: significant correctness, maintainability, validation, or performance issues
- Minor: style, documentation, or small refactoring improvements

Return actionable findings with file/path context where possible. Do not modify code unless the orchestration system explicitly requests a fix pass.
