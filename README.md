# LabVIEW Governance Layer — NI Open-Source Program

> 🧭 This repository defines the LabVIEW-specific governance layer  
> for all open-source LabVIEW modules governed under the  
> [NI Open-Source Program](https://github.com/ni/open-source).

It provides contributor templates, certification alignment, and roadmap context  
for projects that adopt the centralized rules defined in `ni/open-source`.

---

## 🎯 Purpose

This repo exists to:

- Serve as a **single entry point** for contributors to governed LabVIEW repos
- Define LabVIEW-specific expectations (test formats, PR structure)
- Track certification scoring and public badge eligibility
- Maintain a registry of officially governed LabVIEW repositories
- Ensure governance inheritance remains traceable, portable, and auditable

---

## 🧱 Governance Structure

- [`ni/open-source`](https://github.com/ni/open-source)  
  ↳ Canonical governance system (roles, scoring, override logic)

  - [`ni/labview-open-source`](https://github.com/ni/labview-open-source)  
    ↳ LabVIEW-specific governance: templates, cert rules, roadmap registry

    - [`labview-icon-editor`](https://github.com/ni/labview-icon-editor)  
      ↳ ✅ First governed LabVIEW implementation

    - [`actor-framework`](https://github.com/ni/actor-framework)  
      ↳ Governed legacy framework with contributor scoring

    - [`labview-open-source-framework`](https://github.com/ni/labview-open-source-framework)  
      ↳ Governed foundation module designed for reuse and scaling

---

## 📄 Governance Milestone

This layer was formalized in:

- [`MILESTONE-2025-06-labview-governance.md`](https://github.com/ni/labview-open-source/blob/main/docs/milestones/MILESTONE-2025-06-labview-governance.md)
- Pull Request: [#1](https://github.com/ni/labview-open-source/pull/1)
- Public record: [GitHub Discussion #2](https://github.com/ni/labview-open-source/discussions/2)

Framework version: `v2025.05-governance-hardened`  
Maintained by: [@svelderrainruiz](https://github.com/svelderrainruiz) (Program Manager & Architect)

---

## ✅ Governed LabVIEW Repos

| Repo | Status |
|------|--------|
| [`labview-icon-editor`](https://github.com/ni/labview-icon-editor) | ✅ First governed LabVIEW repo |
| [`actor-framework`](https://github.com/ni/actor-framework) | ✅ Governed with traceable participation |
| [`labview-open-source-framework`](https://github.com/ni/labview-open-source-framework) | ✅ Governed foundation module |

Propose additions via:  
[`registry/governed-repos.md`](https://github.com/ni/labview-open-source/blob/main/registry/governed-repos.md)

---

## 🧠 Strategic Intent

This repo does not replace core governance.  
It **extends it**, with a focus on:

- Language-specific contributor experience (LabVIEW)
- Certification integration for LabVIEW engineers
- Template enforcement across visual workflows (`.vi`, `.vim`, `.gvi`)
- Future roadmap tracking for governed tooling

---

## 🚀 Contributor Entry Points

- [Manual Test Template (LabVIEW)](./templates/manual-test-report-lv.md)
- [Certification Scoring Criteria](./CERTIFICATION-LABVIEW.md)
- [Governed Repo Registry](./registry/governed-repos.md)
- [Join a SteerCo](https://github.com/ni/open-source/discussions/22)

---

[![](https://img.shields.io/badge/Governed%20By-NI%20Open--Source-blue)](https://github.com/ni/open-source)
[![](https://img.shields.io/badge/Milestone-v2025.06--labview--governance-green)](https://github.com/ni/labview-open-source/blob/main/docs/milestones/MILESTONE-2025-06-labview-governance.md)
[![](https://img.shields.io/badge/Recognition-Eligible-brightgreen)](https://github.com/ni/open-source/blob/main/docs/governance/CONTRIBUTOR-RECOGNITION.md)
