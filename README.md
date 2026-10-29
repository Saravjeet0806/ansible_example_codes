# Ansible Example Codes ⚙️

A collection of hands-on Ansible examples demonstrating configuration management, server automation, and infrastructure provisioning using Ansible playbooks.

## 📚 Topics Covered

- **Ansible Playbooks** — Automating system administration tasks.
- **Inventory Management** — Defining and managing target hosts.
- **Configuration Management** — Configuring remote servers.
- **Task Automation** — Automating repetitive operations.
- **Package Management** — Installing and managing software packages.
- **Service Management** — Managing system services.
- **Web Server Automation** — Automating web server installation and configuration.
- **Variables and YAML** — Using variables and YAML syntax in playbooks.
- **SSH Connectivity** — Connecting to remote hosts securely.

## 🛠️ Technologies Used

- Ansible
- YAML
- Linux
- SSH
- Ubuntu

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed or configured:

- Ansible on the control node.
- SSH access to the target machines.
- Python on the managed nodes, where required.

### Clone the Repository

```bash
git clone https://github.com/Saravjeet0806/ansible_example_codes.git
cd ansible_example_codes
```

### Verify Ansible Installation

```bash
ansible --version
ansible-playbook --version
```

### Test Connectivity

After configuring your inventory file and SSH access, test connectivity to your managed hosts:

```bash
ansible all -i inventory.ini -m ping
```

Replace `inventory.ini` with the path to your actual inventory file.

### Run a Playbook

```bash
ansible-playbook -i inventory.ini playbook.yml
```

Replace `playbook.yml` with the name of the playbook you want to execute.

**Note:** Commands, inventory paths, and playbook names may need to be adjusted to match the files in each project directory.

## 🎯 Objective

To build practical Ansible skills through hands-on exercises in configuration management, server administration, remote execution, and infrastructure automation.

## 👨‍💻 Author

**Saravjeet Singh**

GitHub: [Saravjeet0806](https://github.com/Saravjeet0806)
