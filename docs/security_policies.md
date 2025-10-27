# 🛡️ Security Policies

This document outlines the security practices implemented in the **Network-Automation-with-Ansible** project.  

---

## 1. Network Access
- Only authorized hosts are allowed to connect via SSH.
- Access control lists (ACLs) are defined for all network segments.
- Sensitive services are restricted to internal IP ranges.

---

## 2. Authentication & Keys
- SSH keys are rotated regularly using automated playbooks.
- Password authentication is disabled for all network devices.
- Users are assigned least privilege access.

---

## 3. Firewall Configuration
- Firewall rules are centralized and deployed via Ansible.
- Only necessary ports are open for services.
- All inbound traffic is logged and monitored.

---

## 4. Monitoring & Alerts
- Network devices are monitored for uptime and configuration changes.
- Automated alerts are triggered on unauthorized access attempts.
- Logs are centralized for auditing purposes.

---

## 5. Backups & Recovery
- Network configurations are backed up automatically.
- Snapshots of critical devices are stored securely.
- Recovery procedures are tested periodically.

---

## 6. Best Practices
- All changes are version-controlled using Ansible playbooks.
- Documentation is updated with each deployment.
- Regular security reviews are conducted to identify vulnerabilities.
