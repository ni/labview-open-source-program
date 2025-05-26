# FORMS-METADATA-MAP.md

> Maps fields from Microsoft Forms → GitHub recognition and governance logic  
> Milestone: `v2025.06.2-forms`  
> Maintainer: @svelderrainruiz  
> Framework: v2025.05-governance-hardened

---

## 🔍 Field Mapping Table

| Form Field                                     | GitHub Target                | Governance Mapping                                |
|------------------------------------------------|-------------------------------|---------------------------------------------------|
| GitHub Handle                                  | Contributor ID               | Recognition + badge linkage via PR/issues         |
| "What type of issue or friction?"              | Proposed GitHub label        | `recognition-missing`, `policy-unclear`, etc.     |
| Link to relevant GitHub activity               | Issue/PR metadata            | Manual triage or signal extraction                |
| Summary of the situation                       | Issue body content           | `test-coordinator` or `contributor-support` tag   |
| Confidence scale (1–5)                         | Signal strength indicator     | Optional for prioritization                       |
| Proposed resolution                            | Optional contributor feedback | Used in `dashboard-metadata.yml` or profiles      |
| Public display consent                         | Recognition opt-in            | Required per `CONTRIBUTOR-RECOGNITION.md`         |
| Contact permission                             | Triage escalation route       | Certification layer may surface flagged entries   |

---

## 📂 Governance Files Used

- `RECOGNITION-TAG-MAP.md` → maps GitHub labels + templates to badge types  
- `CONTRIBUTOR-RECOGNITION.md` → enforces opt-in, visibility, and badge issuance rules
