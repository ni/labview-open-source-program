# LabVIEW Open Source Program

This repository defines the structure, policies, and governance contracts that shape how NI maintains continuity in its LabVIEW open-source efforts.

---

## GPT Governance Mesh

This program is now actively governed by GPT agents bound to versioned threads.  
The operational mesh was launched under:

- `THREAD-v2025.4-LAUNCH.md`: Declares the GPT runtime and actor model

Each GPT in this mesh must:

- Inherit from the LabVIEW Open Source Program GPT
- Declare its behavior via a `THREAD-v*.md`
- Bind to all contracts defined under `v2025.1`

---

## GPT Role Registry

| Role                               | Thread Reference                          | Description                                   |
|------------------------------------|--------------------------------------------|-----------------------------------------------|
| LabVIEW Open Source Program GPT    | `THREAD-v2025.99-LABVIEW-OSP.md`           | Root authority for all child agents           |
| Governance Sentinel GPT            | `THREAD-v2025.99-GOVERNANCE-SENTINEL.md`   | Observes repository compliance and continuity |
| LabVIEW Open Source Program GPT (Replica) | `THREAD-v2025.3-REPLICATION.md`        | Functionally identical GPT for continuity     |
| Contributor Guide GPT              | `THREAD-v2025.4-CONTRIBUTOR-GUIDE.md`      | Assists contributors in navigating governance policies |

---

## Governance Threads

Declared in versioned `THREAD-*.md` files, governance threads encode the structure, behavior, and inheritance of GPT roles.

See the full index in [`docs/THREAD-INDEX.md`](./docs/THREAD-INDEX.md)

---

## Governance Contracts (v2025.1)

These documents define how GPTs behave, bind, and interact with the NI open-source governance lifecycle:

- `CONTRACT-v2025.1-FILE-INSTRUCTION.md`  
- `CONTRACT-v2025.1-PR-CREATION.md`  
- `CONTRACT-v2025.1-GITHUB-RELEASE.md`  
- `CONTRACT-v2025.1-DISCUSSION-PROPOSAL.md`  
- `CONTRACT-v2025.1-README-DOCS.md`  
- `CONTRACT-v2025.1-AGENT-INHERITANCE.md`

---

## Version

Current governance spec version: `v2025.4`

---
Generated and maintained by LabVIEW Open Source Program GPT (strict rebind mode)
