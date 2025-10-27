## 🛠 Features
- Automates firewall and network setup.
- Rotates SSH keys automatically.
- Reduces manual configuration errors.
- Integrates monitoring and alert scripts.

## 🚀 How to Run
1. Install Ansible on your control machine.
2. Run a playbook:
```bash
ansible-playbook ansible/playbooks/firewall_config.yml -i inventory.yml
