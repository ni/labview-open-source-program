# GPT Integrations — NI Governance v2025.6

This directory contains version-scoped GPT instruction files for test coordination, runtime evaluation, and enforcement logic.

Each GPT has a defined role under `v2025.6` and may only operate within the declared runtime or staging boundary.

---

## 🤖 GPT Roles

| GPT | Path | Purpose |
|-----|------|---------|
| 🧪 Test Harness GPT | `test-harness/GPT-INSTRUCTIONS.md` | Executes governance tests and classifies results |
| 🧠 Evaluator GPT | `evaluator/GPT-INSTRUCTIONS.md` | Orchestrates test queries and receives result blocks |
| 🔄 Coordinator GPT | `coordinator/GPT-INSTRUCTIONS.md` | Maps test results to governance sections, logs failures, and suggests changes (under human approval only) |

---

## 🧠 Runtime Enforcement

Each GPT must declare its:
- Bound governance version (`v2025.6`)
- Active tag or branch (e.g., `develop`, `v2025.6-runtime`)
- Interpretation limits (no undeclared files, no simulation of roles)

GPTs must not create governance changes.  
Only the human operator or authorized maintainers may approve or apply governance edits.

---

## 🔐 Note

This folder supports GPT deployment only.  
It is not a source of governance truth—it reflects enforcement tooling only.

