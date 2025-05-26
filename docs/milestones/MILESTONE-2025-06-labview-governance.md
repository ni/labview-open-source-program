# MILESTONE: Launch of LabVIEW Governance Layer

📅 Finalized: 2025-06

---

## 🎯 Objective

Establish a domain-specific governance layer for LabVIEW repositories under the  
[NI Open-Source Program](https://github.com/ni/open-source) — enabling long-term contributor trust, certification scoring, and traceable role boundaries.

This milestone formalizes the inheritance path from:

- Canonical governance core: `ni/open-source`
- LabVIEW-specific governance: `ni/labview-open-source`
- Governed implementations: `labview-icon-editor`, `actor-framework`, `labview-open-source-framework`

---

## 🧱 Governance Architecture

- `ni/open-source`  
  ↳ **Canonical governance system**: role definitions, scoring, badges, override rules

  - `ni/labview-open-source`  
    ↳ **LabVIEW governance layer**: contributor templates, certification logic, repo registry

    - `ni/labview-icon-editor`  
      ↳ ✅ First governed LabVIEW implementation

    - `ni/actor-framework`  
      ↳ Governed legacy codebase with modern participation support

    - `ni/labview-open-source-framework`  
      ↳ Foundational module built under governance for reuse and scaling

---

## 📌 What This Unlocks

- LabVIEW certification scoring linked to open-source contributions  
- Public, opt-in badge eligibility for LabVIEW-based repositories  
- Manual test templates for `.vi`, `.gvi`, `.vim` artifacts  
- Contributor onboarding decoupled from any single codebase  
- Platform roadmap anchored in SteerCo-visible GitHub activity  
- Future forks remain governed under traceable
