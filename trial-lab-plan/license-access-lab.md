# Lab Plan: License-Based Access Issue

## Objective

To observe how Microsoft 365 services behave when a required license or service is not assigned or is disabled.

This lab focuses on authorization and service access control.

---

## Scenario

User reports:

"I can log into Microsoft 365, but Outlook and Teams are not working."

---

## Planned Test Steps (During Trial)

1. Create a new test user account.
2. Assign a Microsoft 365 license.
3. Confirm all services work normally.
4. Disable Exchange Online service inside the license.
5. Attempt to access Outlook.
6. Re-enable Exchange Online.
7. Confirm Outlook access is restored.

---

## Expected Observations

When Exchange Online is disabled:

- User can still log into Microsoft 365.
- Outlook access fails.
- Mailbox becomes inaccessible.

After re-enabling:

- Mailbox access is restored.
- Outlook works normally.

---

## What This Lab Demonstrates

- Difference between authentication and authorization
- Role of licenses in service access
- Exchange Online dependency for mailbox functionality
- Structured troubleshooting approach for access issues
