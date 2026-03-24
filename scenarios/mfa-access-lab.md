# Lab: Multi-Factor Authentication (MFA) Enforcement

## Objective

To observe how Multi-Factor Authentication (MFA) affects the user login process in Microsoft 365.

---

## Scenario

A user is required to complete an additional verification step during login after MFA is enabled.

---

## Test Steps

- Opened Microsoft Entra ID Admin Center  
- Navigated to Per-user MFA settings  
- Enabled MFA for a test user (Sarah Lee)  
- Logged in as the user to trigger MFA setup  
- Completed MFA registration (Authenticator or phone)  
- Logged out and signed in again to verify MFA enforcement  

---

## What This Demonstrates

- MFA adds a second layer of authentication  
- Difference between "Enabled" and "Enforced" states  
- User registration process for MFA  
- Impact of MFA on login flow  

---

## Outcome

After enabling MFA:
- User was prompted to register an authentication method  
- Login required additional verification  

After completing setup:
- MFA status changed to Enforced  
- User was required to complete MFA at every login  

---

## Screenshots

- MFA enabled for user  
- MFA setup prompt during first login  
- MFA verification completed  
- MFA challenge during subsequent login  

---

## Notes

This scenario demonstrates how MFA strengthens account security by requiring a second verification step beyond the password.
