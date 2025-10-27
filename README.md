# 🔧 Network Automation with Ansible

Automated network management and configuration using **Ansible**.  
This project demonstrates how to deploy and manage network devices efficiently with playbooks, roles, and reusable automation scripts.

---

## 🧩 Project Overview
This demo shows how Ansible can simplify the configuration of routers, switches, and firewalls across multiple hosts.

The repository includes:
- Example playbooks for network setup and security.
- Reusable Ansible roles for SSH key rotation and firewall rules.
- Documentation for best practices in secure network automation.

---

## 📂 Folder Structure
```bash
Network-Automation-with-Ansible/
├── ansible/
│   ├── playbooks/
│   │   ├── firewall_config.yml
│   │   ├── ssh_key_rotation.yml
│   │   └── network_setup.yml
│   └── roles/
│       └── common_tasks/
├── docs/
│   └── security_policies.md
└── README.md


---

## 🛠 Features
- Automated SSH key rotation.
- Centralized firewall configuration.
- Consistent network setup across multiple hosts.
- Modular roles and playbooks.

---

## 🚀 How to Run
```bash
# 1. Install Ansible
sudo apt install ansible -y

# 2. Navigate to the project directory
cd ansible/playbooks

# 3. Run a sample playbook
ansible-playbook network_setup.yml -i inventory.ini
