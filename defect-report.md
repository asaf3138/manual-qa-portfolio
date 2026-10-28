# Defect Case Study — Partial Verification Code Accepted

**Educational QA case study.** This document summarizes the issue as recorded in Jira; it does not independently verify a defect in the official Signal application.

| Field | Jira evidence |
|---|---|
| Defect | [PROJ-68 — System Accepts Partial Verification Code](https://asafaviv0312.atlassian.net/browse/PROJ-68) |
| Related test | [PROJ-60 — Verify Phone Number With Partial Verification Code](https://asafaviv0312.atlassian.net/browse/PROJ-60) |
| Related execution | [PROJ-66 — User Registration Story 3](https://asafaviv0312.atlassian.net/browse/PROJ-66) |
| User story | [PROJ-6 — Verify Phone Number](https://asafaviv0312.atlassian.net/browse/PROJ-6) |
| Jira issue status | To Do (not a test-run result) |

## Reported behavior

According to the Jira defect description, the system accepts a partially entered verification code and allows verification to continue.

## Expected behavior

The verification process must reject incomplete codes; the phone number must remain unverified, and the user must remain on the verification screen. This is consistent with the negative BDD scenario recorded in PROJ-6.

## Reproduction outline

1. Reach the verification screen in the educational registration scenario.
2. Enter only part of the required verification code.
3. Attempt verification.
4. Compare the actual response with the expected rejection.

**Evidence limitation:** Jira's defect description does not specify a device/build, exact test data, the number of required digits, screenshots, or a confirmed actual execution log. These should be added only if real evidence is available, not invented.

## Why this example matters

It illustrates how a negative test scenario can be connected to a documented defect and a test execution item. It also demonstrates the distinction between expected results, reported actual behavior, and independently verified execution evidence.
