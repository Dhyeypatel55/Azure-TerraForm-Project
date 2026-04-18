~🏗️ Final Architecture (High Level)

~ We will automatically create this in Azure using  Terraform:

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

# Azure Terraform Web App 🚀

## 📌 Project Overview
This project deploys a web server on Microsoft Azure using Terraform.

## 🧰 Technologies Used
- Terraform
- Microsoft Azure
- Linux VM

## ⚙️ Resources Created
- Resource Group

- Virtual Network
- Subnet
- Network Security Group
- Public IP
- Virtual Machine

## 🚀 How to Run
```bash
terraform init
terraform plan
terraform apply
