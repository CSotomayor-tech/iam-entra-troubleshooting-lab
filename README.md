# IAM Troubleshooting Lab – Microsoft Entra ID

## Overview
This project demonstrates real-world Identity and Access Management (IAM) troubleshooting scenarios using Microsoft Entra ID (Azure AD).

## Objectives
Simulate and resolve common identity-related issues found in enterprise environments.

---

## Scenario 1: Group Membership Issue
- Removed user from required group
- Observed loss of access
- Restored membership to resolve issue

![Group Membership Added](screenshots/01-sarah-in-employees.png)
![Group Membership Removed](screenshots/02-sarah-removed.png)
![Group Membership Restored](screenshots/03-sarah-restored.png)

---

## Scenario 2: Disabled Account
- Disabled user account
- Identified authentication impact
- Re-enabled account to restore access

![Account Disabled](screenshots/04-account-disabled.png)
![Account Enabled](screenshots/05-account-enabled.png)

---

## Scenario 3: Role-Based Access Review
- Reviewed administrative role assignments
- Verified correct permissions

![RBAC Review](screenshots/06-role-review.png)

---

## Scenario 4: Sign-In Log Analysis
- Reviewed authentication logs
- Analyzed application usage and IP address
- Confirmed successful sign-ins

![Sign-In Logs](screenshots/07-log-investigation.png)

---

## Skills Demonstrated
- IAM troubleshooting
- RBAC validation
- Identity lifecycle management
- Authentication log analysis
- Microsoft Entra ID administration

---

## Troubleshooting Approach
1. Identify the issue  
2. Validate user state (groups, roles, account status)  
3. Analyze logs  
4. Apply fix  
5. Confirm resolution  

---

## Business Value
Demonstrates the ability to diagnose and resolve identity-related access issues in enterprise environments.
