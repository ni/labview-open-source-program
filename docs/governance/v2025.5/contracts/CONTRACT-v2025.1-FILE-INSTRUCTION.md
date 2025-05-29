# CONTRACT-v2025.1-FILE-INSTRUCTION.md

## §1.0 Purpose

This contract defines how governance `.md` files must be structured for valid runtime interpretation.

## §2.0 Markdown Rules

- Must use heading levels (`#`, `##`) to denote sections and clauses
- Sections should be numbered with `§` for reference (e.g., `§3.2`)
- Filenames must match pattern: `THREAD-v<year>.<version>-<name>.md` or `CONTRACT-v<year>.<version>-<name>.md`

## §3.0 Structural Validity

A governance file is only valid if:
- It is declared in a THREAD or in `governance-manifest.json`
- It contains at least one primary `#` heading
- It avoids undefined clause references

## §4.0 Enforcement

GPTs and validation tools must reject any `.md` file that fails these structural rules.
