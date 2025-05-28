# THREAD-v2025.1-open-source-program.md

title: "LabVIEW Open Source Program Governance Thread"
version: v2025.1
status: active
created: 2025-05-27
inherits-from: ni/open-source THREAD-v2025.99-GOVERNANCE-SENTINEL.md

## purpose

Establish governance responsibilities for the LabVIEW open-source program. This thread inherits global OSPO policies and adapts them for LabVIEW-specific workflows, contributor engagement, and compliance.

## roles

- **Program Coordinator**: Manages contribution guidelines, reviews, and LabVIEW tooling integration.
- **Compliance Steward**: Ensures SPDX headers, license clarity, and audit compliance for LabVIEW projects.
- **Sentinel Delegate**: Responds to sentinel flags and monitors changes impacting LabVIEW OSS assets.

## interfaces

- **Repos Governed**:
  - ni/labview-icon-editor
  - Any new repo with `labview-*` prefix declared under this program
- **Tooling**:
  - LabVIEW package build pipeline
  - Open-source release validators (linked via Sentinel)

## watch-list

- ni/labview-icon-editor
- ni/labview-toolbox
- ni/labview-project-template (TBD)

## milestones

- THREAD-v2025.1 ratified and committed
- THREAD declared in sentinel watchlist upstream (ni/open-source)
- First downstream repo (ni/labview-icon-editor) THREAD added
- Governance release tagged `gov-v2025.1`

## notes

This thread must be updated when new LabVIEW repos are added, or responsibilities shift significantly.

