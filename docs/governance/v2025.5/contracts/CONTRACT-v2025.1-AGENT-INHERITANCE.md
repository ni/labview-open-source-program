# CONTRACT-v2025.1-AGENT-INHERITANCE.md

## §1.0 Purpose

This contract defines how runtime agents (e.g., GPTs) inherit behavioral constraints and document authority within NI Governance.

## §2.0 Inheritance Model

All GPTs interpreting governance files must:
- Inherit behavior constraints from `THREAD-v2025.5-ROLE-GPT.md`
- Use only the file types and structures defined in `CONTRACT-v2025.1-FILE-INSTRUCTION.md`
- Enforce rejection logic for undeclared documents

## §3.0 Permission Limits

No GPT may:
- Create or propose new THREADs
- Simulate contributor, reviewer, or STEERCO behavior
- Override structural rules declared in any CONTRACT

## §4.0 Runtime Safety

Inheritance constraints are part of runtime safety. Any deviation from this contract must be rejected at interpretation time.
