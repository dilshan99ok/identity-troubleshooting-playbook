# Lab: License-Based Access Issue (Exchange Online)

## Objective

To observe how Microsoft 365 behaves when a required service (Exchange Online) is disabled.

---

## Scenario

User reports:  
"I can log into Microsoft 365, but Outlook is not working."

---

## Test Steps

- Logged in as the test user (Sarah Lee)  
- Confirmed that Outlook was working normally  
- Disabled Exchange Online from the user’s license in the Admin Center  
- Attempted to access Outlook  
- Observed the error message  
- Re-enabled Exchange Online  
- Waited for changes to apply and tested again  

---

## What This Demonstrates

- Users can log in even if a service is unavailable  
- Exchange Online is required for mailbox access  
- Service-level license changes directly affect user experience  
- Basic troubleshooting for service-related issues  

---

## Outcome

When Exchange Online was disabled:
- User was able to log in  
- Outlook failed to load  
- Error displayed indicating mailbox was unavailable  
- Error included: `UserHasNoMailboxAndNoLicenseAssignedException`

After re-enabling Exchange Online:
- Mailbox was provisioned  
- Outlook access was restored after a short delay  

---

## Screenshots

- Exchange Online disabled  
- Outlook error (mailbox unavailable)  
- Exchange Online re-enabled  
- Outlook working after fix  

---

## Notes

This scenario reflects a common IT support issue where a user can authenticate successfully but cannot access specific services due to licensing configuration. The issue was identified and resolved using the Microsoft 365 Admin Center.
