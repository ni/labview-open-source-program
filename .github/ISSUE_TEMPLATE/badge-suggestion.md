name: Badge Nomination – Contributor Recognition
description: Submit a public recognition suggestion for a contributor
title: "[Nomination]: <GitHub handle> – <Badge Type>"
labels: [recognition-nomination, governance-traceable]
body:
  - type: markdown
    attributes:
      value: |
        🏅 Use this template to suggest recognition for a governed contributor.
  - type: input
    id: nominee
    attributes:
      label: GitHub Handle
  - type: input
    id: repository
    attributes:
      label: Repo name
  - type: dropdown
    id: badge_type
    attributes:
      label: Badge Type
      options:
        - 🧪 Test Coordinator
        - 🧠 SteerCo Nominee
        - ⭐ Top Contributor
        - ❓ Other
  - type: textarea
    id: evidence
    attributes:
      label: GitHub evidence
