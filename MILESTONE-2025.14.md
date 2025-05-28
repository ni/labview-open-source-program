# 🏁 Milestone v2025.14 – Certification Scoring Activation

**Release Date:** 2025-05-28  
**Scope Owner:** NI Open Source Program Manager  
**Governance Layer:** LabVIEW Domain Tier  
**Milestone Type:** Contributor Recognition / Certification Alignment

---

## 🎯 Purpose

To activate certification point scoring logic for LabVIEW-governed repositories that meet the following criteria:
- CLA opt-in support via `CONTRIBUTOR-LICENSE-MODE.md`
- Participation in test milestones or PRs with traceable metadata
- Downstream inheritance from `ni/labview-open-source-program`

This milestone marks the first active scoring cycle under governance version `v2025.99`.

---

## 🗂️ Governed Targets

| Repository | Scoring Status | Notes |
|------------|----------------|-------|
| `ni/labview-icon-editor` | ✅ Enabled | CLA and test metadata enabled |
| `ni/actor-framework` | 🔜 Pending | Requires governance drop + CLA metadata |

---

## 📌 Rules for Recognition

Points may be awarded for:
- Executing manual test reports
- Contributing code merged via CLA-validated PR
- Participating in milestone discussions or architecture reviews

Each eligible action must be:
- Bound to a GitHub Issue or PR
- Tracked in the governance milestone layer
- Exportable as contributor metadata

---

## 🤖 GPT Execution Role

Automated threads executing under this milestone:
- May emit certification point summaries in markdown
- Must follow logic from `GPT-ROLE-CONTRACT.md`
- Must retire using `THREAD-RETIREMENT.md` once export is complete

---

## ✅ Completion Criteria

This milestone is complete when:
- At least one certification point export is successfully emitted
- Contributor eligibility is traceable via public artifacts
- At least one downstream repo publicly recognizes participant contributions
