---
name: always-add-unit-tests
description: Use whenever creating or modifying code. Requires adding unit tests for all new code, covering important logic without needing every combination.
---

# Always Add Unit Tests

## Rules
- Every piece of code you create must ship with unit tests.
- Cover important logic: core behavior, branching, edge cases, error handling.
- Exhaustive combinations are not required; prioritize meaningful coverage.
- Use the testing framework already present in the project; if none exists, pick a stable, actively maintained one.
- Run the tests and make sure they pass before finishing.
- Keep tests clean, deterministic, and independent of each other.

