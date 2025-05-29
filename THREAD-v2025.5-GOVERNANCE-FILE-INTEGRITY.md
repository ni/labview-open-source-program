# THREAD-v2025.5-GOVERNANCE-FILE-INTEGRITY.md

## Title:
Governance File Integrity Policy (v2025.5)

## Purpose:
This thread defines the integrity enforcement model for governance-related markdown files in GPT-operational runtime.

## Covered Artifacts:
- All THREAD-v*.md and CONTRACT-v*.md files
- CONTRIBUTING.md, README.md, and policy markdowns under `/docs/governance`

## GPT Interpretation Rules:
- GPTs may not interpret any policy file not declared in a thread
- GPTs must treat deleted or renamed files as invalid unless superseded
- Thread metadata must be present for machine execution
- GPTs must reference file hashes or commit SHAs if contract-bound

## Parent:
- `THREAD-v2025.5-LAUNCH.md`

## Contracts:
- CONTRACT-v2025.1-FILE-INSTRUCTION.md
- CONTRACT-v2025.1-AGENT-INHERITANCE.md
- THREAD-v2025.4-CORRECTION-MODEL.md

## Commit:
NI Open Source Program — 2025

---
Version: v2025.5  
Contracts:
- CONTRACT-v2025.1-FILE-INSTRUCTION.md  
- CONTRACT-v2025.1-AGENT-INHERITANCE.md  
- THREAD-v2025.4-CORRECTION-MODEL.md  
GPT Role: File Integrity GPT
