# Terraform-for-DevOps

# AWS Infrastructure Automation with Terraform

This repository contains Terraform configurations to provision and manage a scalable AWS infrastructure across three environments: Development (Dev), Staging, and Production.

## Topics Covered

- **Introduction**: Overview of Terraform and its significance in infrastructure as code.
- **Why Learn Terraform**: Benefits of using Terraform for cloud infrastructure management.
- **Difference between Terraform and Ansible**: Comparison of capabilities and use cases for each tool.
- **How to Write HCL in Terraform**: Basics of HashiCorp Configuration Language (HCL) for defining infrastructure.
- **Connecting Terraform with AWS**: Steps to configure Terraform for AWS deployment.
- **Making a Multi-env Infrastructure on AWS**: Best practices for creating isolated environments (Dev, Staging, Production).
- **Terraform Init, Plan, Apply**: Commands for initializing, planning, and applying configurations.
- **Creating EC2 with VPC and Security Group**: Provisioning EC2 instances within a configured VPC and security group.
- **Creating DynamoDB**: Setting up DynamoDB tables as part of the infrastructure.
- **Outputs in Terraform**: Managing and displaying outputs from Terraform configurations.
- **States in Terraform**: Understanding Terraform state management for resource tracking.
- **Destroying Resources in Terraform**: Safe removal of resources created by Terraform.
- **Modules in Terraform with Project**: Creating reusable modules for better organization and maintainability.
- **Final Project Demo**: A comprehensive demonstration of the entire infrastructure setup.

## Deployment

To deploy the infrastructure, run the following commands:

1. `terraform init`
2. `terraform plan`
3. `terraform apply`

Use `terraform destroy` to remove resources, with targeted destruction options available.

## Prerequisites

- Terraform installed
- AWS account credentials configured
![Terraform](https://github.com/user-attachments/assets/82a1fc33-70cc-4388-af5d-17898cc1ee64)
