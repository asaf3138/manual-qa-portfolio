# Requirements Traceability — User Registration

This is a **requirements-to-test inventory**, based on Jira story acceptance criteria, test titles and issue links. The rows below are not a claim that Xray's complete coverage calculation was verified.

## Story 1 — Enter Phone Number

Source: [PROJ-3](https://asafaviv0312.atlassian.net/browse/PROJ-3)

| Criterion | Requirement (condensed from Jira) | Relevant test cases |
|---|---|---|
| AC-1 | Phone number can be entered | [PROJ-10](https://asafaviv0312.atlassian.net/browse/PROJ-10) |
| AC-2 | Only valid phone number formats accepted | [PROJ-12](https://asafaviv0312.atlassian.net/browse/PROJ-12), [PROJ-13](https://asafaviv0312.atlassian.net/browse/PROJ-13) |
| AC-3 | Continue enabled for valid number | [PROJ-14](https://asafaviv0312.atlassian.net/browse/PROJ-14) |
| AC-4 | Continue disabled for invalid number | [PROJ-11](https://asafaviv0312.atlassian.net/browse/PROJ-11), [PROJ-13](https://asafaviv0312.atlassian.net/browse/PROJ-13) |
| AC-5 | Error shown for invalid number | [PROJ-15](https://asafaviv0312.atlassian.net/browse/PROJ-15) |

The six test issues above have explicit **Test** issue links to PROJ-3 in Jira.

## Story 2 — Receive Verification Code

Source: [PROJ-5](https://asafaviv0312.atlassian.net/browse/PROJ-5)

| Criterion | Requirement (condensed from Jira) | Relevant test cases |
|---|---|---|
| AC-1 | Code sent to entered phone number | [PROJ-35](https://asafaviv0312.atlassian.net/browse/PROJ-35), [PROJ-36](https://asafaviv0312.atlassian.net/browse/PROJ-36) |
| AC-2 | Code delivered successfully | [PROJ-35](https://asafaviv0312.atlassian.net/browse/PROJ-35) |
| AC-3 | Verification screen displayed | [PROJ-35](https://asafaviv0312.atlassian.net/browse/PROJ-35) — scenario-level expectation; step-level evidence not retrieved |
| AC-4 | User can request new code | [PROJ-38](https://asafaviv0312.atlassian.net/browse/PROJ-38), [PROJ-39](https://asafaviv0312.atlassian.net/browse/PROJ-39) |

These four test issues have explicit **Test** links to PROJ-5 in Jira.

## Story 3 — Verify Phone Number

Source: [PROJ-6](https://asafaviv0312.atlassian.net/browse/PROJ-6)

| Criterion | Requirement (condensed from Jira) | Relevant test cases |
|---|---|---|
| AC-1 | User can enter verification code | [PROJ-48](https://asafaviv0312.atlassian.net/browse/PROJ-48), [PROJ-52](https://asafaviv0312.atlassian.net/browse/PROJ-52), [PROJ-60](https://asafaviv0312.atlassian.net/browse/PROJ-60) |
| AC-2 | System validates code | [PROJ-48](https://asafaviv0312.atlassian.net/browse/PROJ-48), [PROJ-50](https://asafaviv0312.atlassian.net/browse/PROJ-50), [PROJ-60](https://asafaviv0312.atlassian.net/browse/PROJ-60) |
| AC-3 | Correct code verifies phone number | [PROJ-48](https://asafaviv0312.atlassian.net/browse/PROJ-48) |
| AC-4 | Successful verification permits continuing | [PROJ-48](https://asafaviv0312.atlassian.net/browse/PROJ-48) — scenario-level expectation |
| AC-5 | Incorrect code produces error | [PROJ-50](https://asafaviv0312.atlassian.net/browse/PROJ-50) |

**Important:** Unlike the first two stories, PROJ-6 did not expose explicit direct Test links for these four test issues in the Jira issue-link field. Their association is supported by the shared epic, titles, and the Story 3 test set [PROJ-65](https://asafaviv0312.atlassian.net/browse/PROJ-65), but complete native Xray membership/coverage was not independently checked.

## Defect traceability example

[PROJ-60 — Partial verification code](https://asafaviv0312.atlassian.net/browse/PROJ-60) → [PROJ-68 — System accepts partial code](https://asafaviv0312.atlassian.net/browse/PROJ-68). The defect also has a Jira link to [PROJ-66 — Story 3 execution](https://asafaviv0312.atlassian.net/browse/PROJ-66).

## Interpretation

The mappings above are an analyst-prepared traceability overview based on the educational project's Jira records. They should not be represented as a formal Xray coverage report or as evidence that the production application was tested.
