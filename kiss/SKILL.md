---
description: Apply the KISS principle to coding tasks by choosing the simplest correct solution, avoiding over-engineering, and making minimal maintainable changes.
---

# KISS Coding Skill

Keep it simple. Choose the smallest clear solution that solves the actual problem.

## Principles
- Prefer readable code over clever code.
- Avoid unnecessary abstractions, patterns, frameworks, and dependencies.
- Make the smallest safe change.
- Preserve existing behavior unless explicitly asked to change it.
- Reuse existing code where practical.
- Do not optimize before there is evidence of a problem.

## Before Changing Code
Ask:
1. What is the real issue?
2. What is the smallest fix?
3. Can this be done without a new dependency?
4. Will this be easy to understand later?

## When Complexity Appears
If a solution introduces extra layers, configuration, helpers, classes, or dependencies, pause and justify why they are necessary. If they are not necessary, remove them.

## Output
- Briefly state the simple approach.
- Provide the minimal code change.
- Mention only important tradeoffs.
