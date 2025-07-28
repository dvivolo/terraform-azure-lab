# Terraform Azure Lab

This repository contains Infrastructure-as-Code (IaC) configurations for deploying secure Azure resources using Terraform. It serves as a learning lab for DevSecOps concepts and cloud security best practices.

## 📌 Goals
- Practice writing Terraform configurations to provision Azure resources.
- Explore secure cloud architecture and role-based access control (RBAC).
- Build reusable Terraform modules for common security configurations.

## 🛠 Tools & Technologies
- **Terraform** (Infrastructure as Code)
- **Microsoft Azure** (Cloud Provider)
- **Azure CLI** (Authentication and management)

## 📂 Repository Structure (Planned)
```
terraform-azure-lab/
├── modules/               # Reusable Terraform modules
├── environments/          # Dev / Test / Prod environments
│   └── dev/               # Example environment
│       └── main.tf        # Root configuration file
└── README.md              # Project documentation
```

## 🚀 Usage
1. Authenticate to Azure:
   ```bash
   az login
   ```
2. Initialize Terraform:
   ```bash
   terraform init
   ```
3. Plan and apply:
   ```bash
   terraform plan
   terraform apply
   ```

## 🔒 Security Considerations
- Use Azure Key Vault for storing sensitive values.
- Configure remote state backend (Azure Storage) with proper RBAC.
- Apply least privilege for Terraform service principals.

## 📅 Status
🚧 **Work in Progress** – This repository will be updated as labs are completed.
