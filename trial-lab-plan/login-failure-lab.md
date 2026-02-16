# Lab Plan: Simulating Login Failure

## Objective

To observe how Microsoft 365 behaves when a user cannot log in due to account-level issues.

This lab will test the authentication layer.

---

## Scenario

User reports:
"I cannot sign in to my Microsoft 365 account."

---

## Planned Test Steps (During Trial)

- Create a test user account
- Attempt normal login (confirm it works)
- Block sign-in for the user
- Attempt login again
- Observe error message
- Re-enable sign-in
- Confirm successful login

---

## What This Tests

- Account status impact on authentication
- Difference between blocked and active accounts
- User-facing error messages
- Basic admin troubleshooting steps

---

## Expected Outcome

When sign-in is blocked:
- Login attempt should fail immediately
- Error message should indicate account restriction

After re-enabling:
- Login should succeed normally

