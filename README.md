# -Linux-IAM-Hardening-mini


# Linux IAM & Hardening Mini Project (Users, Groups, Permissions)

## Objective

Design and implement a secure user/group and permission model for a small team on an Ubuntu server. Analyze a deliberately vulnerable lab VM, identify and remediate three misconfigurations, and document all findings and actions.

***

## Environment

- Ubuntu VM (lab environment)
- Kali or attacker VM for safe testing
- Sudo access to lab VM

***

## Steps

### 1. Baseline Policy

- Define which team roles require administrative (sudo) privileges.
- Specify user group roles, such as admin, developer, and auditor.
- Document folder and file access requirements for each group.

### 2. User and Group Creation

- Set up users and groups based on the baseline policy.
- Assign appropriate group memberships for secure role separation.

### 3. Sudo Privileges

- Restrict administrative access to only required users or groups.
- Implement least-privilege configurations.
- Limit sudo permissions to essential administrative tasks only.

### 4. Permissions and Access Control

- Set correct folder and file permissions for collaboration and security.
- Apply additional access control methods so only intended groups can write, while others have read-only access.
- Ensure sensitive files and directories are protected from unauthorized access.

### 5. Auditing

- Enable and configure auditing to monitor changes to critical files such as password files and sudoers configuration.
- Review collected logs regularly for unauthorized or suspicious activities.

***

## Vulnerability Assessment & Remediation

- Examine the vulnerable VM for misconfigurations such as excessive file permissions, inappropriate sudo privileges, and poorly protected sensitive files.
- Remediate identified issues following security best practices.
- Document before-and-after state for each fix and maintain evidence for the report.

***

## Deliverables

- Baseline policy document outlining the user/group/permissions model
- Written checklist of issues found, remediation actions taken, and ongoing recommendations
- Documentation showing evidence of misconfiguration discovery and successful fixes
- Audit log snippets relevant to sensitive changes
- Summary slide or document presenting outcomes and recommendations



