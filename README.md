# 🚀 Azure Terraform Web App

## 📌 Project Overview
This project demonstrates how to deploy a complete web server infrastructure on Microsoft Azure using Terraform.

All resources are provisioned using Infrastructure as Code (IaC), without any manual setup.

---

## 🏗️ Architecture

# We will automatically create this in Azure using  Terraform:

Azure Subscription
│
├── Resource Group
│
├── Virtual Network (VNet)
│   └── Subnet
│
├── Network Security Group (NSG)
│   └── Security Rules (SSH, HTTP)
│
├── Public IP
│
├── Network Interface (NIC)
│
├── Linux Virtual Machine (Ubuntu)
│   └── NGINX Web Server
│
└── Terraform State (local)
~ Everything is created by code, not manually.

## 🧰 Technologies Used
- Terraform
- Microsoft Azure
- Linux (Ubuntu)
- NGINX Web Server

---

## ⚙️ Resources Created
- Resource Group
- Virtual Network (VNet)
- Subnet
- Network Security Group (NSG)
- Public IP
- Network Interface (NIC)
- Linux Virtual Machine
- NGINX Web Server

---
## 📸 Screenshots

### 🔹 Terraform Apply Output
![Terraform Output](terraform-output.png)

### 🔹 Azure Resources
![Azure Resources](azure-resources.png)


## 🚀 How to Run

```bash
terraform init
terraform plan
terraform apply


