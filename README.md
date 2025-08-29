# aws-infra-terraform-basics
✅ Ready-made README.md
# Terraform AWS Infrastructure Basics

This is a simple **Terraform project** that demonstrates Infrastructure as Code (IaC) on AWS.  
The project provisions:
- An **S3 Bucket** for storage
- An **EC2 Instance** with SSH access

---

## 📌 Features
- Infrastructure as Code using **Terraform**
- **AWS CLI** used for authentication
- Automated provisioning of AWS resources
- Clean and reusable code
- **Study / Demo purpose only**

---

## 📂 Project Structure


terraform-for-devops/
│── main.tf # Main Terraform configuration
│── provider.tf # AWS provider configuration
│── s3.tf # S3 bucket resource definition
│── README.md # Documentation
│── .gitignore # Ignore terraform local files & state


---

## ⚙️ Prerequisites
Before using this project, make sure you have:
- An **AWS Account**
- **AWS CLI** installed and configured  
  ```bash
  aws configure


Terraform installed

terraform -version

🚀 Usage

Initialize Terraform

terraform init


Preview the execution plan

terraform plan


Apply the configuration

terraform apply -auto-approve


Destroy resources (when no longer needed)

terraform destroy -auto-approve

⚠️ Notes

Do not push .terraform/, terraform.tfstate, or provider binaries to GitHub.

This project is for learning purposes only.

For production, always enable remote state management (S3 + DynamoDB).

📝 Author

👤 Shivam Pandey
Learning DevOps & Cloud | Building hands-on AWS + Terraform projects
