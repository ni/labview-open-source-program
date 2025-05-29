# NI Runtime Governance v2025.5 — Structure Index

This directory contains the authoritative governance framework, declarations, automation logic, and contributor-facing documentation for NI Governance v2025.5.

---

## 📌 Runtime Tag

This structure is bound to runtime version:

```
Tag: v2025.5-runtime
Branch: main
```

All tooling, GPTs, and contributors must interpret governance behavior strictly as declared in this versioned snapshot.

---

## 📁 Folder Overview

### `threads/`
All declared `THREAD-v2025.5-*.md` governance files defining roles, lifecycle, and behavioral boundaries.

### `contracts/`
All `CONTRACT-v2025.1-*.md` files defining structural constraints and runtime interpretation models.

### `runtime/`
Operational artifacts:
- `governance-manifest.json`
- `GPT-TEST-RESULTS-v2025.5.md`
- `GPT-TEST-LOG-v2025.5.md`

### `release/`
- `RELEASE-NOTES-v2025.5.md`
- `GOVERNANCE-CHANGELOG.md`
- `FINALIZATION-LOG.md`

### `interface/`
Human-facing documentation:
- This `README.md`
- GPT integration guides
- Contributor onboarding docs

---

## 🧠 Version Scope

This version is runtime-locked under tag `v2025.5-runtime`.  
Any changes beyond this point must be introduced under a future governance cycle (e.g., `v2025.6`).
