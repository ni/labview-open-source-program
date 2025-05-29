# Governance Snapshot – v2025.5-runtime

This file summarizes the locked runtime governance version `v2025.5-runtime`.

---

## 🏷️ Tag Binding

- Version: `v2025.5`
- Runtime Tag: `v2025.5-runtime`
- Branch: `main`
- Declared On: 2025-05-29

---

## 📁 Governance Structure

### `threads/`
All THREAD-v2025.5-*.md files defining roles, lifecycle, and enforcement behavior.

### `contracts/`
All CONTRACT-v2025.1-*.md files defining structural and GPT behavior constraints.

### `runtime/`
Contains:
- `governance-manifest.json`
- `GPT-TEST-RESULTS-v2025.5.md`
- `GPT-TEST-LOG-v2025.5.md`

### `interface/`
Contains:
- Contributor README
- GPT integration guides

### `release/`
Contains:
- `RELEASE-NOTES-v2025.5.md`
- `FINALIZATION-LOG.md`
- This `SNAPSHOT.md`

---

## 🤖 GPTs

Declared under `/docs/gpts/`

- **Evaluator GPT**: `/gpts/evaluator/v2025.5/GPT-INSTRUCTIONS.md`
- **Test Harness GPT**: `/gpts/test-harness/v2025.5/GPT-INSTRUCTIONS.md`

Each GPT is locked to this runtime version via instruction blocks.

---

## 🧪 Test Infrastructure

- `gpt-validation-tests.json` — JSON test suite
- `GPT-TEST-RESULTS-v2025.5.md` — Result log
- `GPT-TEST-LOG-v2025.5.md` — Manual trace log

---

## 🧠 Governance Status

This snapshot is frozen under `v2025.5-runtime`.  
All contributions must target a future version (e.g., `v2025.6`).
