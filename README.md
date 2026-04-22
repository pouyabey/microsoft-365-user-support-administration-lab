# Microsoft 365 User Support & Administration Lab

## Project Overview

This project documents common Microsoft 365 help desk and system support scenarios. The lab focuses on user account setup, license assignment, password resets, MFA and authentication method support, shared mailbox access, Teams group membership, and OneDrive/SharePoint permission troubleshooting.

The goal of this project is to demonstrate practical Microsoft 365 administration and end-user support skills commonly used in IT Help Desk, IT Support Technician, and IT System Support I roles.

This lab also includes Outlook on the web validation steps to confirm mailbox access, email functionality, and shared mailbox visibility from the end-user perspective.

---

## Lab Environment

- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Microsoft 365 test tenant
- Microsoft 365 user accounts
- Microsoft 365 license assignment
- Outlook on the web
- Shared mailboxes
- Microsoft Teams / Microsoft 365 groups
- OneDrive / SharePoint permissions

---

## Project Structure

```text
Microsoft-365-User-Support-Lab/
│
├── README.md
│
├── tickets/
│   ├── ticket-01-new-user-setup.md
│   ├── ticket-02-password-reset.md
│   ├── ticket-03-license-assignment.md
│   ├── ticket-04-mfa-authentication-methods.md
│   ├── ticket-05-shared-mailbox-access.md
│   ├── ticket-06-teams-access.md
│   └── ticket-07-onedrive-sharepoint-permissions.md
│
└── screenshots/
    ├── ticket-01-create-user.png
    ├── ticket-01-user-profile.png
    ├── ticket-01-license-assigned.png
    ├── ticket-02-password-reset.png
    ├── ticket-02-signin-status.png
    ├── ticket-03-user-without-license.png
    ├── ticket-03-license-assigned.png
    ├── ticket-03-outlook-validation.png
    ├── ticket-04-authentication-methods.png
    ├── ticket-04-mfa-reset.png
    ├── ticket-05-shared-mailbox-created.png
    ├── ticket-05-mailbox-permissions.png
    ├── ticket-05-outlook-shared-mailbox.png
    ├── ticket-06-team-membership.png
    ├── ticket-06-user-added-to-team.png
    ├── ticket-07-sharepoint-permissions.png
    └── ticket-07-access-updated.png
```


 ## Tickets Documented

| Ticket | Scenario | Skills Demonstrated |
|---|---|---|
| [Ticket 01](tickets/ticket-01-new-user-setup.md) | New User Setup | User provisioning, license assignment, onboarding support |
| [Ticket 02](tickets/ticket-02-password-reset-sign-in-support.md) | Password Reset and Sign-in Support | Password reset, sign-in troubleshooting, account support |
| [Ticket 03](tickets/ticket-03-license-assignment-issue.md) | License Assignment Issue | License troubleshooting, app access, Outlook validation |
| [Ticket 04](tickets/ticket-04-mfa-authentication-methods-support.md) | MFA / Authentication Methods Support | MFA reset, authentication methods, Entra admin support |
| [Ticket 05](tickets/ticket-05-shared-mailbox-access.md) | Shared Mailbox Access | Mailbox delegation, shared mailbox access, Outlook validation |
| [Ticket 06](tickets/ticket-06-teams-access-issue.md) | Teams Access Issue | Microsoft 365 group membership, Teams access support |
| [Ticket 07](tickets/ticket-07-onedrive-sharepoint-permission-issue.md) | OneDrive / SharePoint Permission Issue | File access troubleshooting, sharing permissions |


## Summary

This project demonstrates practical Microsoft 365 support tasks used in real help desk and system support environments. Each ticket includes a user-reported issue, admin troubleshooting steps, resolution, skills demonstrated, and supporting screenshots.

نکته مهم: چون داخل README اصلی یک code block برای Project Structure داری، دقت کن که در GitHub سه تا بک‌تیک اول و آخر درست بسته شده باشد.

---



برای README اصلی، لازم نیست خیلی زیاد screenshot بگذاری. فقط ۲ یا ۳ تا کافی است:

```text
main-admin-center-dashboard.png
از صفحه اصلی Microsoft 365 Admin Center

main-active-users.png
از Users → Active users

main-entra-admin-center.png
از Microsoft Entra Admin Center

