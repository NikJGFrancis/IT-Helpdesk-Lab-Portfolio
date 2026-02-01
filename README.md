IT Help Desk Lab Portfolio
Hands-on Azure Entra ID & Jira Ticketing Experience

About
This portfolio demonstrates practical IT Help Desk skills using:
- Azure Entra ID (Active Directory) for user management
- Jira Service Management for ticket handling
- Real-world scenarios that 90% of Help Desk technicians encounter daily

Lab 1: Azure Entra ID Administration

Company Scenario
TechFlow Solutions - IT Consulting Firm
- 10+ employees across multiple departments
- Hybrid cloud infrastructure
- Enterprise security requirements

1. Initial Setup

Azure Portal Dashboard
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/abfc2ea327caf6c8c713946a2c73bd322ba2f015/Azure%20Directory%20Entra%20ID%20Lab/Azure%20Portal%20Dashboard.png
- Successfully accessed Azure Portal

Entra ID Overview
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Entra%20ID%20Overview%20page%20showing%20tenant%20name.png
- Azure Active Directory tenant configured for TechFlow Solutions

2. User Account Management

Created 10 Employee Accounts
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/All%20Users%20List%20Showing%2010%20Users.png
- Complete user directory spanning all departments with consistent naming

Key Actions Performed:
- Created 10 user accounts with proper attributes
- Assigned job titles and departments
- Generated secure temporary passwords
- Configured account settings

3. Security Group Organization

All Security Groups
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Groups%20Overview%20showing%20all%204%20groups%20created.png
- 4 security groups created for department and role-based access control

IT Department Members
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/IT%20Department%20Showing%20Members.png
- IT-Department group members

Sales Team Members
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Sales_Team%20Showing%20Members.png
- Sales-Team group members

Key Actions Performed:
- Created 4 security groups
- Assigned users to appropriate groups
- Verified group membership
- Tested group-based access

4. Password Reset

Scenario: User Sarah Johnson unable to access email - forgot password

Password Reset Process
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Password%20Reset%20Confirmation%20with%20new%20password%20visible.png
- Generated temporary password via Azure Entra ID admin center

Resolution Steps:
1. Verified user identity via security questions
2. Located user account in Entra ID
3. Clicked "Reset Password"
4. Generated temporary password
5. Contacted user via phone with new credentials
6. Confirmed user regained access

5. Account Disable/Enable

Account Disabled - Employee Termination
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Michael%20Chen's%20Account%20Disabled.png
- Michael Chen account disabled immediately upon termination notice

Account Re-enabled - False Alarm
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Michael%20Chen's%20Profile%20Showing%20%22Account%20enabled%3A%20Yes%22.png
- Account restored after termination was cancelled by HR

Key Actions Performed:
- Immediate account lockout for security
- Removed from all security groups
- Documented changes in audit log
- Re-enabled with proper authorization

6. Delete and Restore Users

Deleted User
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Delete%20Confirmation%20Dialog.png
- Robert Taylor moved to deleted users - 30-day retention period active

Deleted Users List
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Deleted%20Users%20list%20showing%20Robert%20Taylor.png
- Robert Taylor no longer appears in active directory

User Restored
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/All%20Users%20list%20showing%20Robert%20Taylor%20Restored.png
- Robert Taylor successfully restored after accidental deletion

Key Learning:
- Deleted users retained for 30 days
- Can be restored with all properties intact
- Permanent deletion requires explicit action

7. Bulk Operations

Bulk User Creation Results
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Azure%20Active%20Directory%20Entra%20ID/Bulk%20Operation%20Results.png
- Successfully created 3 users simultaneously via CSV import

Use Case: Onboarding multiple new hires efficiently

8. Intentional Break & Fix Exercise
Removed Manager from Department Group
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Azure%20Active%20Directory%20Entra%20ID/IT-Department%20without%20manager.png
- IT-Department group missing manager John Davis - intentional misconfiguration

Manager Restored
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Azure%20Active%20Directory%20Entra%20ID/John%20Davis%20Restored%20to%20group.png
- John Davis re-added to IT-Department - access restored

Purpose: Practice identifying and correcting access issues

9. Audit Trail Review

Audit Logs
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/a6e30846a016dce249b00cce461dbd4c5ffdcc8b/Azure%20Directory%20Entra%20ID%20Lab/Audit%20logs%20showing%20activities.png
- Complete audit trail in the last 24 hours

Compliance Value:
- Every action timestamped
- User who made change identified
- Before/after states captured
- Required for security audits

Lab 2: Jira Ticketing System

Workspace Setup

Jira Service Management Dashboard
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Jira%20Space%20Dashboard.png

Ticket #1: Password Reset Request

Ticket Created
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Ticket%20%231%20Created.png

Details:
- Type: Service Request
- Priority: High
- User: Robert Williams
- Issue: Forgot password, cannot access email
- Impact: Unable to access work applications

Ticket Resolved with Professional Notes
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Resolved%20Ticket%
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Resolved%20Ticket%20with%20notes%20Part%202(Password%20Reset).png20Part%201(Password%20Reset).png

Resolution Notes:
Actions Taken:
- Verified user identity via security questions
- Confirmed with manager Emily Chen
- Reset password via Azure Portal
- Generated temporary password: TempPass2026!
- Called user at ext. 4455 - provided credentials verbally
- Instructed user to change password on first login
- Confirmed user regained access

Ticket #2: New Hire Setup

Ticket Created
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Ticket%20%232%20Created.png

Details:
- Employee: Alex Rivera
- Position: Junior Help Desk Technician
- Start Date: January 27, 2026
- Department: IT

Checklist:
- Create Active Directory account
- Add to IT-Department group
- Add to IT-Helpdesk group
- Assign Office 365 license
- Setup email account
- Provision equipment
- Generate temporary password

Ticket Resolved
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/New%20Hire%20Setup%20(Part%201).png
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/New%20Hire%20Setup%20with%20Notes%20(Part%202).png

Ticket #3: Account Lockout

Ticket Created
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Ticket%20%233%20Created.png

Details:
- User: Mike Johnson
- Issue: Account locked after multiple failed login attempts
- Time: 10:15 AM - 10:18 AM
- Attempts: 6 failed logins

Ticket Resolved
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Lockout%20Ticket%20Resolved%20(Part%201).png
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Lockout%20Ticket%20Resolved%20with%20notes%20(Part%202).png

Resolution Notes:
Investigation:
- Reviewed Azure sign-in logs
- Confirmed 6 failed attempts between 10:15-10:18 AM
- Called user to verify legitimate activity

Resolution:
- Unlocked account via Azure Entra ID
- Reset password as precaution
- Recommended IT Security awareness training

Follow-up:
- Sent email with password manager guidelines
- Scheduled 15-min training session

Ticket #4: Group Access Modification

Ticket Created
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Ticket%20%234%20Created.png

Details:
- User: Sarah Martinez
- Request: Add to Managers group (promotion)
- Approval: John Davis (IT Manager)

Ticket Resolved
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Group%20Access%20Ticket%20Resolved%20(Part%201).png
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Group%20Access%20Ticket%20Resolved%20(Part%202).png

Ticket #5: Account Termination

Ticket Created
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Ticket%20%235%20Created.png

Details:
- Employee: Jennifer Garcia
- Department: Finance
- Termination Date: January 30, 2026
- Priority: CRITICAL

Immediate Actions Required:
- Disable AD account
- Disable email access
- Remove from all security groups
- Revoke licenses
- Forward email to manager
- 30-day data retention

Ticket Resolved
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Termination%20Ticket%20(Part%201).png
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Termination%20Ticket%20Resolved%20(Part%202).png

Resolution Notes:
CRITICAL - Employee Termination Process

COMPLETED IMMEDIATELY:
- Disabled Active Directory account (4:15 PM)
- Disabled Office 365 account
- Revoked all licenses
- Removed from Finance-Department group
- Blocked sign-in to all Microsoft services
- Reset password to prevent access

Email Handling:
- Configured forwarding to David Brown (HR Manager)
- Auto-reply set
- Calendar appointments transferred

Data Retention:
- OneDrive backed up to HR archive
- Mailbox retention: 30 days
- Deletion scheduled: March 1, 2026

Tools Used: Azure Entra ID, Exchange Admin Center
Status: COMPLETED

Ticket Queue Overview
Resolved Tickets
- https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio/blob/c7b812cd2fb31f05cfe595fff88e9cb70f68537d/Jira%20Ticketing%20System/Resolved%20and%20Closed%20Tickets.png

Skills Demonstrated

Technical Skills
- Active Directory user lifecycle management
- Security group administration
- Password policy configuration
- Account lockout troubleshooting
- License management
- Multi-factor authentication (MFA)
- Sign-in and audit log analysis
- Bulk user operations
- Professional ticket documentation
- Incident prioritization and categorization

Soft Skills
- Clear technical communication
- Thorough documentation
- Time management
- Customer service orientation
- Problem-solving methodology
- Security awareness
- Attention to detail

Scenarios Practiced
- Password resets
- New employee onboarding
- Account lockouts
- Group access modifications
- Employee terminations
- Account recovery
- Security incident response

Tools & Technologies

- Microsoft Azure
- Azure Entra ID
- Jira Service Management
- Office 365 Admin Center
- GitHub

Contact
Nikolas Francis
- Email: nikfrancisbrand@gmail.com
- Portfolio: https://github.com/NikJGFrancis/IT-Helpdesk-Lab-Portfolio

