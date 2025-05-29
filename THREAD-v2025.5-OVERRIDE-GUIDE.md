# THREAD-v2025.5-OVERRIDE-GUIDE.md

## Title:
GPT Override Behavior Policy (v2025.5)

## Purpose:
This thread defines how and when GPTs may override previously declared policies, emit custom behavior, or respond to ambiguity in governance.

## Key Rules:
- Overrides must only occur when declared in an override-bound thread
- GPTs must cite the override thread ID when acting on an exception
- Default behavior is to defer to THREAD and CONTRACT logic
- “Override mode” must not be entered without declared permission

## Allowed GPT Use Cases:
- Thread-based overrides (e.g. “GOVERNANCE-AI-BEHAVIOR-OVERRIDE.md” → scoped to GPTs)
- Metadata flags passed via maintainers with thread context
- Emergencies only when declared in THREAD-v2025.5-LAUNCH.md or descendant

## Prohibited:
- Spontaneous behavior not declared in THREADs
- GPT-to-GPT override without lineage metadata
- Overriding STEERCO, policy, or contributor-facing behavior

## Contracts:
- CONTRACT-v2025.1-FILE-INSTRUCTION.md
- THREAD-v2025.4-CORRECTION-MODEL.md

## Commit:
NI Open Source Program — 2025

---
Version: v2025.5  
Contracts:
- CONTRACT-v2025.1-FILE-INSTRUCTION.md  
- THREAD-v2025.4-CORRECTION-MODEL.md  
GPT Role: Override Policy GPT
