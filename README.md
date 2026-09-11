# Microsoft 365 Administration & IT Support Lab

A hands-on Microsoft 365 Business Premium lab created to practice common L1 IT Support and Microsoft 365 administration tasks in a simulated business environment.

## Overview

This project simulates a small business Microsoft 365 environment and focuses on practical user, email, identity, device, and collaboration support tasks.

The lab was built to understand how Microsoft 365 services work together and to practice basic troubleshooting workflows that can be relevant to an L1 IT Support role.

## Environment

- Microsoft 365 Business Premium
- Microsoft Entra ID
- Microsoft Intune
- Exchange Online
- Microsoft Teams
- SharePoint
- Windows 10 Enterprise

## Tasks Performed

### Microsoft 365 Admin Center

- Created and managed user accounts
- Practiced password reset procedures
- Reviewed Microsoft 365 licenses and enabled services
- Worked with shared mailboxes

### Exchange Online

- Performed message tracing for a test email
- Reviewed message delivery events and delivery status
- Configured mailbox Full Access permissions

### Microsoft Entra ID

- Reviewed user account information
- Investigated user sign-in logs
- Registered Microsoft Authenticator for MFA
- Created and tested a Conditional Access policy requiring MFA

### Microsoft Intune

- Configured automatic Windows enrollment
- Enrolled a Windows PC into Intune
- Reviewed device compliance status
- Investigated a device compliance result
- Performed manual device synchronization
- Created a Microsoft 365 Apps deployment
- Checked BitLocker recovery-key availability

### Microsoft Teams

- Created a private Team
- Added a user as a Team member
- Practiced private Team access management

### SharePoint

- Managed site/team membership
- Added an IT Support account as a Team owner

## L1 Troubleshooting Scenarios Practiced

- User account and access issues
- Password and MFA-related issues
- Sign-in investigation using Entra ID logs
- Email delivery investigation using Message Trace
- Mailbox permission issues
- Windows device enrollment
- Device compliance investigation
- Application deployment
- Device synchronization
- Teams and SharePoint access management

## Key Learning

The lab helped build an understanding of how different Microsoft services work together:

| Service | Purpose |
|---|---|
| Microsoft Entra ID | Identity and access management |
| Microsoft Intune | Device and application management |
| Exchange Online | Email and mailbox management |
| Microsoft Teams | Communication and collaboration |
| SharePoint | Sites, files, and collaboration |

### Identity → Device → Application → Access

A simplified view of the lab:

```text
User
  ↓
Microsoft Entra ID
  ↓
Windows Device
  ↓
Microsoft Intune
  ↓
Applications & Security Policies
  ↓
Teams / SharePoint / Exchange
