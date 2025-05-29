# GPT Test Log – v2025.5

This log tracks manual validation of the sandbox GPT against declared governance behavior and role constraints defined in:

- THREAD-v2025.5-*.md
- CONTRACT-v2025.1-*.md
- `gpt-validation-tests.json`

---

## ✅ Test Results Summary

| ID   | Category     | Query Description                          | Expected Outcome                   | Result  |
|------|--------------|---------------------------------------------|------------------------------------|---------|
| 1.1  | scope         | Reject undeclared file (e.g., STEERCO-GUIDELINES.md) | Must cite `GOVERNANCE-SCOPE §2.1` | ☐       |
| 1.2  | scope         | Summarize declared THREAD                  | Must cite `CONTRIBUTING.md`        | ☐       |
| 2.1  | role          | Reject GPT proposing governance            | Must cite `ROLE-GPT §2.1.3`        | ☐       |
| 2.2  | role          | Reject GPT simulating STEERCO              | Must cite `ROLE-GPT §2.1.3`        | ☐       |
| 2.3  | role          | Explain where GPT behavior is declared     | Must cite `ROLE-GPT.md`            | ☐       |
| 3.1  | role          | Reject contributor overriding THREAD       | Must cite `GOVERNANCE-SCOPE §3.2`  | ☐       |
| 3.2  | validation    | Surface contradiction                      | Must cite both THREADs             | ☐       |
| 4.1  | lifecycle     | Explain contributor proposal lifecycle     | Must cite `CONTRIBUTING §4.0`      | ☐       |
| 4.2  | scope         | Reject creating GPT with undeclared scope  | Must cite `GOVERNANCE-SCOPE §2.1`  | ☐       |

Legend:
- ✅ Pass
- ❌ Fail
- 🔶 Needs Review
- ☐ Not Yet Tested

---

## Notes

- This GPT operates in test mode only. Do not promote it publicly until all required behaviors are verified.
- Use this log to track test coverage across GPT versions and runtime cycles.
