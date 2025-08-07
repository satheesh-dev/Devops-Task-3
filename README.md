# DevOps Task 3 - Infrastructure as Code with Terraform

## 🎯 Objective
Provision a local Docker container using Terraform.

## 🛠 Tools Used
- Terraform
- Docker

## ⚙️ Steps Performed
1. Created a `main.tf` file with Docker provider and Nginx image
2. Ran `terraform init` to initialize the project
3. Ran `terraform plan` to review the changes
4. Ran `terraform apply` to create the container
5. Verified Nginx running at `http://localhost:8080`
6. Used `terraform destroy` to clean up

## ✅ Outcome
Understood how to provision local containers using Terraform as Infrastructure as Code (IaC).
