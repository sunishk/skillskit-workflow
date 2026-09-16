---
name: planning-features
description: Build a concise, repository-aware implementation plan before coding.
---

# Planning Features

Analyze the requirement and repository before implementation.

## Responsibilities

- Clarify the requested behavior from the supplied requirement.
- Inspect relevant modules and existing patterns.
- Identify files likely to change or be created.
- Define API/domain impacts where applicable.
- Define a testing strategy.
- Call out blocking assumptions or missing information.

## Output

Return a concise plan containing:

- Requirement summary
- Existing-code observations
- Proposed changes
- Files to modify/create
- Test strategy
- Risks/assumptions

Do not change production code during planning.
