# Test Case Inventory

The following 14 test cases are recorded in Jira under the **User Registration** epic. Titles and intent are based on their Jira records. These are **test case summaries**, not a substitute for detailed Xray Action / Data / Expected Result steps.

## Story 1 — Enter Phone Number ([PROJ-3](https://asafaviv0312.atlassian.net/browse/PROJ-3))

| ID | Scenario | Type |
|---|---|---|
| [PROJ-10](https://asafaviv0312.atlassian.net/browse/PROJ-10) | Enter valid phone number | Positive |
| [PROJ-11](https://asafaviv0312.atlassian.net/browse/PROJ-11) | Enter invalid phone number | Negative |
| [PROJ-12](https://asafaviv0312.atlassian.net/browse/PROJ-12) | Verify valid phone number format | Positive |
| [PROJ-13](https://asafaviv0312.atlassian.net/browse/PROJ-13) | Verify invalid phone number format | Negative |
| [PROJ-14](https://asafaviv0312.atlassian.net/browse/PROJ-14) | Continue button enabled after valid phone number | Positive |
| [PROJ-15](https://asafaviv0312.atlassian.net/browse/PROJ-15) | Error message displayed for invalid phone number | Negative |

## Story 2 — Receive Verification Code ([PROJ-5](https://asafaviv0312.atlassian.net/browse/PROJ-5))

| ID | Scenario | Type |
|---|---|---|
| [PROJ-35](https://asafaviv0312.atlassian.net/browse/PROJ-35) | Receive verification code | Positive |
| [PROJ-36](https://asafaviv0312.atlassian.net/browse/PROJ-36) | Request code with invalid phone number | Negative |
| [PROJ-38](https://asafaviv0312.atlassian.net/browse/PROJ-38) | Request new verification code | Positive |
| [PROJ-39](https://asafaviv0312.atlassian.net/browse/PROJ-39) | Request new code without internet | Negative |

## Story 3 — Verify Phone Number ([PROJ-6](https://asafaviv0312.atlassian.net/browse/PROJ-6))

| ID | Scenario | Type |
|---|---|---|
| [PROJ-48](https://asafaviv0312.atlassian.net/browse/PROJ-48) | Verify with valid code | Positive |
| [PROJ-50](https://asafaviv0312.atlassian.net/browse/PROJ-50) | Verify with invalid code | Negative |
| [PROJ-52](https://asafaviv0312.atlassian.net/browse/PROJ-52) | Verify with empty code | Negative |
| [PROJ-60](https://asafaviv0312.atlassian.net/browse/PROJ-60) | Verify with partial code | Negative |

## Preconditions

- [PROJ-7](https://asafaviv0312.atlassian.net/browse/PROJ-7) — User Registration Environment Ready: application installed, device online, registration screen available, SMS available, phone number not already registered.
- [PROJ-8](https://asafaviv0312.atlassian.net/browse/PROJ-8) — Verification Process Ready. Jira description provides only the title; detailed setup conditions were not confirmed.

## Evidence limitations

Jira issue descriptions establish test intent, but the connector did not expose detailed Xray test steps or run-level pass/fail results. Do not present these cases as independently verified successful executions without exporting that evidence.
