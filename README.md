# Manual QA Portfolio — Messaging App Registration

**Project type:** Educational manual software testing project using Jira and Xray-style test management workflows.

**Scope:** Requirements analysis, positive/negative scenarios, test design, test organization, execution tracking, and defect reporting for a messaging application's phone-number registration flow. The scenarios reference Signal as a learning example; this is **not** an official Signal QA project or an independently verified assessment of the production application.

## Project at a glance

| Artifact | Recorded in Jira |
|---|---:|
| Epic | 1 — User Registration |
| User stories | 3 |
| Acceptance criteria | 14 (5 + 4 + 5) |
| BDD scenarios | 12 (4 per story) |
| Test cases | 14 |
| Preconditions | 2 |
| Test sets | 3 |
| Test executions | 3 |
| Test plans | 1 |
| Linked defect reports | 1 |

The counts above describe the *User Registration* epic only, not the entire Jira project. Jira workflow status **To Do** is not a test execution result. Test-run outcomes and detailed Xray steps were not independently retrieved through the available connector, so this portfolio does not claim a pass rate or complete executed-step evidence.

## Workflow

1. Analyze the **User Registration** epic and three user stories.
2. Define acceptance criteria and positive/negative BDD scenarios.
3. Create reusable preconditions and 14 test cases.
4. Organize tests into three test sets and a test plan.
5. Document test execution items and a linked defect example.
6. Maintain traceability through Jira issue links and references.

## User stories

| Jira issue | User story | Acceptance criteria | BDD scenarios | Test cases |
|---|---|---:|---:|---:|
| [PROJ-3](https://asafaviv0312.atlassian.net/browse/PROJ-3) | Enter Phone Number | 5 | 4 | 6 |
| [PROJ-5](https://asafaviv0312.atlassian.net/browse/PROJ-5) | Receive Verification Code | 4 | 4 | 4 |
| [PROJ-6](https://asafaviv0312.atlassian.net/browse/PROJ-6) | Verify Phone Number | 5 | 4 | 4 |

**Epic:** [PROJ-1 — User Registration](https://asafaviv0312.atlassian.net/browse/PROJ-1)

## Test management artifacts

| Type | Jira references |
|---|---|
| Preconditions | [PROJ-7](https://asafaviv0312.atlassian.net/browse/PROJ-7), [PROJ-8](https://asafaviv0312.atlassian.net/browse/PROJ-8) |
| Test sets | [PROJ-27](https://asafaviv0312.atlassian.net/browse/PROJ-27), [PROJ-40](https://asafaviv0312.atlassian.net/browse/PROJ-40), [PROJ-65](https://asafaviv0312.atlassian.net/browse/PROJ-65) |
| Test executions | [PROJ-29](https://asafaviv0312.atlassian.net/browse/PROJ-29), [PROJ-41](https://asafaviv0312.atlassian.net/browse/PROJ-41), [PROJ-66](https://asafaviv0312.atlassian.net/browse/PROJ-66) |
| Test plan | [PROJ-70](https://asafaviv0312.atlassian.net/browse/PROJ-70) |
| Defect example | [PROJ-68](https://asafaviv0312.atlassian.net/browse/PROJ-68) |

## Portfolio contents

- [Test Case Inventory](test-cases.md) — all 14 cases, organized by story.
- [Requirements Traceability](traceability.md) — acceptance criteria and evidence of Jira links.
- [Defect Case Study](defect-report.md) — documented partial-code validation issue.

## Access and evidence notes

Jira links may require authentication and access permission. The local Markdown documentation is intended to remain readable without Jira access. Actual Xray step tables, test-run statuses, attachments, and screenshots should be exported separately before making claims about execution results. No production defect or product affiliation is asserted.
