# LAB Objective
To simulate real IT helpdesk troubleshooting scenarios across common enterprise IT environments including Active Directory, user devices, network access, applications, and system configuration issues.

---

## Example Tickets

### Ticket 001 - Password Reset (Active Directory)
User was unable to log in after forgetting their password. Verified account status in Active Directory Users and Computers (ADUC). Password was reset and the option “User must change password at next logon” was enabled. User successfully regained access after updating credentials.

---

### Ticket 002 - Account Lockout (AD Authentication Issue)
User account became locked after multiple failed login attempts. Checked account status in Active Directory, confirmed lockout threshold was reached. Account was unlocked and login attempt history reviewed. User was advised on correct credential usage.

![unlocked account](https://github.com/masib237/IT-HELPDESK-PORTFOLIO/blob/main/ActiveDirectoryLabs/PasswordReset&Unlock%20Account.png?raw=true)


### Ticket 003 - Access Denied to Shared Folder (Permissions Issue)
User reported inability to access departmental shared folder. Verified NTFS and share permissions on the file server. User was not part of the required security group. Added user to appropriate group and applied updated permissions. Access restored after group policy refresh.

![sharedfolderaccess](https://github.com/masib237/IT-HELPDESK-PORTFOLIO/blob/main/FileSharing&Permissions/permissions.png?raw=true)

---

### Ticket 004 - Network Connectivity Issue
User unable to access internal network resources. Diagnosed issue using basic connectivity tests (ipconfig, ping). Identified incorrect DNS configuration on client machine. Corrected DNS settings to point to domain controller. Network access restored.

---

### Ticket 005 - Application Not Launching
User reported that a company-installed application would not open. Checked Task Manager for background processes and attempted restart. Verified missing dependency causing application failure. Reinstalled application and confirmed successful launch.

---

### Ticket 006 - Printer Not Responding
User unable to print documents to network printer. Checked print queue and restarted Print Spooler service on client machine. Removed and re-added network printer. Test print completed successfully.

---

### Ticket 007 - Slow Computer Performance
User reported slow system performance. Checked startup programs, disk usage, and running processes. Disabled unnecessary startup applications and cleared temporary files. Performance improved after optimization.


## Jira Ticketing System Simulation

As part of the helpdesk simulation lab, Jira was used to document and track IT support incidents in a structured ticketing workflow. Each ticket was created to reflect real-world IT service desk operations including issue logging, categorization, prioritization, assignment, and resolution tracking.

---

## Ticket Management Process Demonstrated

- **Issue Logging:** Incidents were recorded with clear problem descriptions submitted by end users.
- **Categorization:** Tickets were classified based on type such as Access Issues, Authentication Failures, Network Problems, and System/Application Errors.
- **Priority Assignment:** Each ticket was assigned a priority level (Low, Medium, High, Critical) depending on business impact and urgency.
- **Assignment:** Tickets were assigned to a support agent for resolution based on workload and skill set.
- **Investigation & Resolution:** Troubleshooting steps were documented within the ticket, including system checks, configuration changes, and user verification.
- **Closure:** Tickets were marked as resolved after confirmation that the user issue had been successfully fixed.

---

## Priority Understanding

- **Low Priority:** Minor issues not affecting business operations (e.g., UI glitches, non-urgent requests)
- **Medium Priority:** Issues affecting individual users but not blocking critical work
- **High Priority:** Issues affecting multiple users or key business functions
- **Critical Priority:** System-wide outages or security-related incidents requiring immediate attention

![JiraTickets]()

