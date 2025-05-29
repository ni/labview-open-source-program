# LabVIEW Open Source Program

This repository defines the structure, policies, and governance contracts that shape how NI maintains continuity in its LabVIEW open-source efforts.

---

## Version
Current runtime governance version: v2025.5

Declared runtime thread: `THREAD-v2025.5-LAUNCH.md`

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

## Contracts

This runtime inherits the following contracts:
- `CONTRACT-v2025.1-FILE-INSTRUCTION.md`
- `CONTRACT-v2025.1-PR-CREATION.md`
- `CONTRACT-v2025.1-GITHUB-RELEASE.md`
- `CONTRACT-v2025.1-DISCUSSION-PROPOSAL.md`
- `CONTRACT-v2025.1-README-DOCS.md`
- `CONTRACT-v2025.1-AGENT-INHERITANCE.md`
- `THREAD-v2025.4-CORRECTION-MODEL.md`
- `THREAD-v2025.4-INTERACTION-MODEL.md`

---

## Superseded

This version supersedes:
- `THREAD-v2025.4-LAUNCH.md`

Archived governance thread declarations can be found in [`docs/THREAD-INDEX.md`](./docs/THREAD-INDEX.md)

---

Generated and maintained for GPT-parsable mesh governance. Runtime role defined in `THREAD-v2025.5-LAUNCH.md`
