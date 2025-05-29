# LabVIEW Open Source Program

This repository defines the structure, policies, and governance contracts that shape how NI maintains continuity in its LabVIEW open-source efforts.

---

## GPT Governance Mesh

This program is governed by GPT agents declared under `THREAD-v*.md` threads.  
The current runtime version is defined by:

- `THREAD-v2025.4-LAUNCH.md`: Mesh origin
- `THREAD-v2025.4-CORRECTION-MODEL.md`: Runtime enforcement model
- `THREAD-v2025.4-INTERACTION-MODEL.md`: GPT-to-operator interaction model

---

## GPT Role Registry

| Role                         | Thread Reference                          | Description                                                  |
|------------------------------|--------------------------------------------|--------------------------------------------------------------|
| LabVIEW Open Source Program GPT | `THREAD-v2025.99-LABVIEW-OSP.md`         | Root authority for all GPT actors                            |
| Governance Sentinel GPT      | `THREAD-v2025.99-GOVERNANCE-SENTINEL.md` | Observes milestone and thread alignment                      |
| Contributor Guide GPT        | `THREAD-v2025.4.2-CONTRIBUTOR-GUIDE.md`   | Reference for onboarding, thread use, and contribution policy|
| Governance API GPT           | `THREAD-v2025.4.2-GOVERNANCE-API.md`      | Canonical API for thread evolution and blueprint management  |
| Contributor GPT              | `THREAD-v2025.4.3-CONTRIBUTOR-GPT.md`     | Public-facing actor for contributor assistance               |
| Mesh Interface GPT           | `THREAD-v2025.4.3-MESH-INTERFACE.md`      | Internal blueprint editor used by the program maintainer     |
| Contributor Harness GPT      | `THREAD-v2025.4.3-HARNESS.md`             | Runtime validator and prompt-based test harness              |

---

## Governance Contracts

Declared in versioned `CONTRACT-v*.md` files.  
Full index available in [`docs/THREAD-INDEX.md`](./docs/THREAD-INDEX.md)

---

## Version

Current runtime governance version: `v2025.4.3`

---
Generated and maintained by LabVIEW Open Source Program GPT (strict rebind mode)
