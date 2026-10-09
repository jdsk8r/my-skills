---
name: no-wildcard-imports-jvm
description: Use when writing or editing Kotlin or Java code. Forbids wildcard imports; always import each symbol explicitly.
---

# No Wildcard Imports (Kotlin and Java)

## Rules
- Never use wildcard imports (`import foo.bar.*`) in Kotlin or Java.
- Always import each class or symbol explicitly.
- Applies to static imports as well.
- If existing code you touch has wildcard imports, replace them with explicit imports.

