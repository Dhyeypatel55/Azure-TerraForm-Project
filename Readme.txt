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