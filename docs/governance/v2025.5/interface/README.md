# NI Runtime Governance — Version v2025.5

This directory contains the authoritative governance documents that define roles, constraints, and runtime behavior for contributors and tooling within the NI open-source program.

## 🔒 Runtime Version Declaration

- **Version:** v2025.5
- **Declared Live:** 2025-06-01
- **Status:** Active
- **Scope:** All interactions governed under `THREAD-v2025.5-*` and `CONTRACT-v2025.1-*`

## 🧭 File Structure

### THREADs

| File | Purpose |
|------|---------|
| `THREAD-v2025.5-LAUNCH.md` | Activates this governance version |
| `THREAD-v2025.5-GOVERNANCE-SCOPE.md` | Limits interpretation to declared files |
| `THREAD-v2025.5-CONTRIBUTING.md` | Defines contribution paths and constraints |
| `THREAD-v2025.5-ENGAGEMENT-GUIDE.md` | Details interaction rules and lifecycle flows |
| `THREAD-v2025.5-ROLE-CONTRIBUTORS.md` | Contributor role definitions |
| `THREAD-v2025.5-ROLE-GPT.md` | GPT role constraints |
| `THREAD-v2025.5-ROLE-STEERCO.md` | STEERCO authority and limitations |

### CONTRACTs

| File | Purpose |
|------|---------|
| `CONTRACT-v2025.1-FILE-INSTRUCTION.md` | Structural rules for file format |
| `CONTRACT-v2025.1-AGENT-INHERITANCE.md` | GPT behavior inheritance constraints |
| `CONTRACT-v2025.1-README-DOCS.md` | Human-readable README expectations (optional) |

## 👤 Human Operator Interface (Open Access)

This governance system is enforced primarily through automation (e.g. GPTs), but some responsibilities remain outside machine-enforced scope.

Any contributor or stakeholder may act as a **human operator** to:

- Post or modify governance documents
- Raise questions GPTs cannot answer
- Escalate contradictions or propose changes

See the [Governance Manifest](./governance-manifest.json) and [Validation Tests](./gpt-validation-tests.json) for structure and enforcement.

## 📬 Contributions

Changes must comply with:
- Role maps
- Declared file scope
- The proposal lifecycle in `THREAD-v2025.5-CONTRIBUTING.md`
