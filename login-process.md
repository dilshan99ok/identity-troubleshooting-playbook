# Microsoft 365 Login Process (Support View)

When a user attempts to log in, the following checks occur behind the scenes:

- User enters email and password
- Request is sent to Microsoft Entra ID
- Account existence is verified
- Password is validated
- Multi-Factor Authentication (if required) is triggered
- Conditional Access policies are evaluated
- License assignment is checked
- Access token is issued to the requested service (Teams, Outlook, SharePoint)

---

## Common Failure Points

Login can fail if:

- Account is disabled or blocked
- Password is incorrect or expired
- MFA is not configured or device changed
- Conditional Access policy blocks access
- Account is deleted
- Sign-in risk detected

---

## Initial Support Checklist

If a user cannot log in, check:

- Is the account active?
- Is sign-in blocked?
- Is the password recently changed?
- Is MFA registered correctly?
- Are there Conditional Access restrictions?
