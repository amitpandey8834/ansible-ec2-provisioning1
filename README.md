# Ansible EC2 Provisioning Project

This project automates the provisioning of an AWS EC2 instance and installs Apache using Ansible. It is ideal for DevOps beginners and enthusiasts who want hands-on experience with cloud automation and infrastructure-as-code practices.

---

## 🚀 Features

- Launches an EC2 instance on AWS
- Configures security groups for SSH access
- Waits for the instance to become accessible
- Installs Apache web server
- Uses dynamic inventory to manage the new EC2 host

---

## 🛠️ Technologies Used

- **Ansible**
- **AWS EC2**
- **Boto3 (Python SDK for AWS)**
- **Dynamic Inventory Scripts**

---

## 📁 Project Structure

```bash
.
├── ansible_demo/
│   ├── launch_ec2_instance1.yml      # Main playbook to launch EC2 and install Apache
│   └── .gitignore                    # Git ignore rules
├── docker.yml                        # (Optional) Docker-related Ansible playbook
├── inventory.yml                     # Ansible inventory file
├── Awskey.pem                        # Private key (DO NOT SHARE or COMMIT this)
└── README.md                         # You're here!
