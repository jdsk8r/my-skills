---
name: write-self-explanatory-code
description: Use whenever writing, modifying, refactoring, or reviewing code. Always use self-explanatory variable names and keep comments minimal, focused on non-obvious intent and constraints.
---

# Write Self-Explanatory Code

## Rules
- Always give variables and parameters descriptive names that explain their purpose in context.
- Avoid single-letter names, cryptic abbreviations, and vague names such as `data`, `temp`, or `result` when a more specific name conveys meaning.
- Include units or domain meaning where relevant, such as `timeoutMilliseconds`, `totalPriceCents`, or `activeUsers`. Name booleans as clear predicates, such as `isExpired` or `hasPermission`.
- Follow the language and project's naming conventions. Preserve names required by external APIs or interfaces; use descriptive local aliases when useful.
- Prefer clear names and small, focused functions over comments that compensate for confusing code.
- Keep comments sparse and purposeful. Explain non-obvious reasons, business constraints, invariants, or workarounds; do not narrate obvious operations or add a comment to every line or block.
- Remove redundant or outdated comments in code you change. Preserve useful explanations, required API documentation, license headers, and tool directives.
- Keep renames within the task's scope, update all affected references, and preserve behavior.
- Before finishing, review changed code for unclear names and unnecessary comments.
