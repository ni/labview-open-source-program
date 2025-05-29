# THREAD-v2025.4-CORRECTION-MODEL.md

## Title:
Correction Model for Blueprint Governance Runtime (v2025.4)

## Purpose:
This thread documents the full set of runtime behavioral corrections embedded into the LabVIEW Open Source Program GPT governance layer. These corrections enforce strict compliance with contracts, eliminate operator fatigue risks, and ensure machine-readable consistency for all future GPTs.

## Parent Thread:
- `THREAD-v2025.4-LAUNCH.md`

## Scope:
These corrections apply to all GPTs binding to `THREAD-v2025.4-LAUNCH.md` or any descendant thread.

## Corrections Enforced:

### 🔒 Correction 1: Git Commit Precedes PR
All PRs must follow staged and committed changes. GPTs must not suggest PRs for uncommitted work.

### 🔒 Correction 2: Full File Replacement Only
GPTs must never offer partial file updates. Only complete, semantically valid file blocks are permitted.

### 🔒 Correction 3: Rebind Confirmation After Milestones
Upon closing a milestone, GPTs must re-declare their binding to the parent thread, version, and contract set.

### 🔒 Correction 4: GPT-Traceable Lifecycle Metadata
GPTs must emit machine-readable lifecycle state using a structured block. This metadata allows downstream GPTs to rebind, resume, or extend behavior programmatically.

### 🔒 Correction 5: File Stack Review Before Release
No release may be created unless all referenced files are committed and merged to `main`, and the index reflects all included threads.

### 🔒 Correction 6: Commit Metadata Must Be Explicit
Every commit must include:
- Title
- Thread references
- Purpose
- Contract scope

### 🔒 Correction 7: PR Merge Confirmation Before Release
Releases must never be suggested until the associated PR has been confirmed as merged into `main`.

### 🔒 Correction 8: Thread–Commit–PR–Release Linking
Every governance thread must be linked explicitly in its:
- Commit
- PR description
- Release notes

### 🔒 Correction 9: Parseable Thread Footers
Every `THREAD-v*.md` must end with a metadata footer:
```
---
Version: v2025.4  
Parent: THREAD-v2025.4-LAUNCH.md  
Contracts: [contract list]  
GPT Role: [role name]
```

## Lifecycle Binding:
All GPTs must bind to this correction model in addition to any contracts they inherit. It is considered part of the runtime for any thread under `v2025.4`.

## Commit:
NI Open Source Program — 2025
