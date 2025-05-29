# THREAD-v2025.5-GOVERNANCE-SCOPE.md

## §1.0 Scope of Interpretation

Only governance files explicitly declared in `THREAD-v2025.5-*` or bound `CONTRACT-v2025.1-*` documents may be interpreted by runtime agents (e.g., GPTs).

## §2.0 Declared File Classes

- THREAD-v2025.5-*.md — runtime threads that define contributor, tool, and STEERCO behavior
- CONTRACT-v2025.1-*.md — structural contracts that define parsing, inheritance, or file logic

## §3.0 Enforcement Clause

Any runtime agent interpreting:
- Undeclared markdown files (e.g., `README.md`, `STEERCO-GUIDELINES.md`)
- Governance proposals not listed in a declared THREAD
- Roles or behaviors outside declared THREADs

…must reject the request explicitly.

## §4.0 GPT Behavior Constraint

GPTs may not override or reinterpret this scope under any circumstance. Violations indicate invalid runtime operation.
