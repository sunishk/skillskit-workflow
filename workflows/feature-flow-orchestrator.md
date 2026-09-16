---
name: feature-flow-orchestrator
description: Use for end-to-end Java/Spring Boot feature delivery. Coordinates planning, implementation, review, testing, and deterministic validation.
---

# Feature Flow Orchestrator

Use this workflow for implementing a feature from requirement to validated code.

## Phases

1. Planning
2. Implementation
3. Review
4. Testing
5. Validation

## Rules

- Planning produces an implementation plan before code changes.
- Implementation must follow the applicable skills and repository conventions.
- Review checks the implementation against coding standards and identifies critical, major, and minor issues.
- Testing adds or updates tests and executes them when possible.
- Deterministic validation performed by the Development AI Agent is authoritative for build/test success.
- Do not commit, push, create a pull request, or approve a merge request unless the orchestration system explicitly requests it.
- When validation feedback is supplied, treat the run as a fix attempt and address the reported failures before making unrelated changes.

## Skill Mapping

- Planning: `skills/planning-features/SKILL.md`
- Implementation: `skills/implementing-features/SKILL.md`
- Review: `skills/reviewing-code/SKILL.md`
- Testing: `skills/testing-features/SKILL.md`
- Java/Spring Boot standards: `skills/coding-guidelines-java/SKILL.md`

## Expected Execution

The provider should inspect the current repository, use the requirement and repository context supplied by Development AI Agent, and follow the referenced skills. The provider should edit the actual workspace during implementation/fix execution and return a concise structured summary to the orchestrator.
