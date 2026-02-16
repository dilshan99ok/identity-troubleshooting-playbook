# Authentication vs Authorization

Understanding the difference between authentication and authorization helps isolate where an issue is occurring.

## Authentication

Authentication answers:
Who are you?

It verifies identity using:

- Username or email
- Password
- Multi-Factor Authentication (MFA)

If authentication fails:
- The user cannot log in at all
- An error appears during sign-in

---

## Authorization

Authorization answers:
What are you allowed to access?

It determines access based on:

- License assignment
- Group membership
- Role-based access control (RBAC)
- SharePoint or Teams permissions

If authorization fails:
- Login may succeed
- Access to a specific service or resource is denied

---

## Support Thinking

If login fails → check authentication layer.

If login succeeds but access fails → check authorization layer.
