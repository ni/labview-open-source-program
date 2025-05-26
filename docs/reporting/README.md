# 📊 Reporting Layer Overview

> Milestone: `v2025.14 – Unified Reporting Layer`

---

## 🎯 Purpose

This folder provides machine- and human-readable views of:

- All governance milestone execution
- Contributor badge visibility (opt-in only)
- GPT thread roles and handoffs
- Export readiness for program audit or publication

---

## 📦 Included

- `unified-status.md`: Human-readable milestone index + thread registry
- `unified-status.yml`: Same data in YAML
- `recognition-feed.md` (pending): Recognition events + contributor metadata
- `recognition-feed.yml`: Machine-parsable event map
- `status-schema.json`: Optional — defines feed structure for bots/dashboards

---

## 🔒 Trust Model

All data is:
- Opt-in only (per `CONTRIBUTOR-RECOGNITION.md`)
- Milestone-locked and changelog-backed
- Traceable to GPT threads with declared roles

Maintained by: System Coordinator GPT  
Authorized by: @svelderrainruiz
