# Lab Plan: Simulating Login Failure

## Objective

To observe how Microsoft 365 behaves when a user cannot log in due to account-level restrictions.

---

## Scenario

User reports:  
"I cannot sign in to my Microsoft 365 account."

---

## Test Steps

- Created a test user account  
- Logged in successfully to confirm normal access  
- Blocked sign-in for the user from the Admin Center  
- Attempted login again  
- Observed the error message  
- Re-enabled sign-in  
- Logged in again to confirm the issue was resolved  

---

## What This Demonstrates

- How account status affects login access  
- The difference between active and blocked users  
- What the user sees when access is restricted  
- Basic admin troubleshooting steps  

---

## Outcome

When sign-in was blocked:
- Login failed immediately  
- An error message indicated that access was restricted  

After re-enabling sign-in:
- The user was able to log in successfully  

---

## Screenshots

- Successful login  
- Login failure (blocked account)  
- Admin setting (block sign-in)  
- Login success after fix  

---

## Notes

This scenario reflects a common IT support issue where a user cannot access their account due to account restrictions. The issue was identified and resolved through the Microsoft 365 Admin Center.
