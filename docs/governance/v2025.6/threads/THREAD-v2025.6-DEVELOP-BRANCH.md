# THREAD-v2025.6-DEVELOP-BRANCH.md

## 🧭 Proposal

Establish a default governance development branch (e.g., `develop`) for all pre-declared governance work, prior to sealing it under a versioned declaration (e.g., `v2025.6-declared`).

## 🔍 Rationale

- Enables contributors and GPT authors to work against an active staging area
- Prevents confusion between live governance and proposals in flight
- Aligns governance iterations with common development branching models

## 📐 Scope

This THREAD affects:

- ✅ Contributor workflows
- ✅ Proposal lifecycle
- ✅ Governance repository structure

## ✨ Expected Outcome

- New governance threads targeting `v2025.6` should branch from `develop`
- Proposals can be batched and reviewed in staging before being tagged into `main`
- Clarity between declared (`main`, `*-runtime`) and proposed (`develop`) governance states

## 📄 Supporting Context

- `v2025.5-runtime` was sealed and frozen on 2025-05-29
- All governance commits in `main` are now locked

## 🛑 Lifecycle Notes

This thread defines a transient development branch (`develop`) used to integrate governance proposals targeting `v2025.6`.

This thread and branch are intended to be discarded once `v2025.6` is declared and sealed under a runtime tag.

Tools, GPTs, or validators **must not bind to `develop`**, but may use it for pre-release validation.
