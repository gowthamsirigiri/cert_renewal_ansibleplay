SSL Certificate Renewal Playbook
This repository contains a lightweight Ansible playbook designed to automate the renewal of SSL certificates across multiple remote hosts.

🚀 Overview
The script streamlines the certificate lifecycle by connecting to target servers via SSH (Port 22) and executing renewal commands, ensuring your services remain secure without manual intervention.

🛠 Features
Automated Renewal: Handles the end-to-end process of updating expiring certificates.

Multi-Host Support: Scale the renewal process across different environments (Dev, Staging, Production) simultaneously.

Secure Connection: Utilizes standard SSH protocols for secure communication.

📋 Prerequisites
Before running the playbook, ensure you have:

Ansible installed on your control node.

SSH access to the target hosts (Public Key Authentication recommended).

Appropriate permissions (sudo) on remote hosts to modify certificate files.

📖 Quick Start
To run the playbook, use the following command:

Bash
ansible-playbook -i inventory.yml playbook.yml
