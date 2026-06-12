---
description: Apply SOLID principles to improve code design with clear responsibilities, small interfaces, substitutable abstractions, and explicit dependencies.
---

# SOLID Principles Coding Skill

Use SOLID principles to make code easier to change, test, and maintain.

## Goal
Design code with clear responsibilities, small interfaces, and low coupling.

## Principles

### Single Responsibility Principle
A class, module, or function should have one clear reason to change.

Prefer:
- focused functions/classes
- clear boundaries
- moving unrelated logic apart

Avoid:
- “god objects”
- functions that validate, transform, persist, and notify all at once

### Open/Closed Principle
Code should be open for extension but closed for unnecessary modification.

Prefer:
- adding behavior through small extensions
- configuration, composition, or strategy when variation is expected

Avoid:
- large conditionals that grow every time a new case is added

### Liskov Substitution Principle
Subtypes should work anywhere their parent type is expected.

Prefer:
- predictable interfaces
- subclasses that preserve expected behavior

Avoid:
- subclasses that throw unsupported errors for normal parent behavior
- changing method meaning in child classes

### Interface Segregation Principle
Depend on small, specific interfaces instead of large general ones.

Prefer:
- narrow contracts
- separate interfaces for separate capabilities

Avoid:
- forcing consumers to implement methods they do not use

### Dependency Inversion Principle
High-level code should depend on abstractions, not concrete low-level details.

Prefer:
- injecting dependencies
- depending on protocols, interfaces, or small contracts

Avoid:
- hard-coding infrastructure details inside business logic

## Before Coding
Ask:
1. What responsibility does this code have?
2. Is this change mixing unrelated concerns?
3. Is variation actually needed, or would abstraction be premature?
4. Can this be tested without real external services?
5. Are dependencies explicit?

## When Implementing
- Keep responsibilities separated.
- Prefer composition over inheritance.
- Introduce abstractions only when they reduce real coupling.
- Do not apply SOLID mechanically.
- Avoid adding layers just to satisfy a pattern.
- Keep code understandable.

## Output Style
- State which SOLID concern matters, if any.
- Make the smallest design improvement needed.
- Explain tradeoffs briefly.
