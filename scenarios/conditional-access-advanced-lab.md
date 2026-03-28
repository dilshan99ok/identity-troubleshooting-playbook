# Conditional Access – Advanced Lab (Location-Based MFA)

## Objective
Implement a Conditional Access policy to require MFA only when users sign in from outside a trusted location.

---

## Configuration

### Named Location
- Created trusted location: Australia
- Based on country/IP detection

### Policy
- Users: All users
- Applications: All cloud apps
- Condition: Exclude trusted location (Australia)
- Control: Require MFA

---

## Testing

### Inside Australia
- Login successful
- MFA not required
- Conditional Access: Not applied

### Outside Australia (VPN)
- MFA required
- Conditional Access: Applied

---

## Issues Encountered

### 1. MFA always required
- Cause: Global Conditional Access policy enforcing MFA
- Fix: Disabled conflicting policy

### 2. VPN test not working
- Cause: Phone hotspot did not route traffic through VPN
- Fix: Installed VPN on PC

### 3. Logs delay
- Observation: Sign-in logs took several minutes to appear

---

## Key Learning

Conditional Access allows context-based security decisions.  
Unlike per-user MFA, it enables dynamic enforcement based on conditions such as location.

---

## Conclusion

This lab demonstrates how Conditional Access improves security while maintaining usability by applying controls only when necessary.
