# AWS Terraform Infrastructure

## Project Overview

This project provisions AWS infrastructure using Terraform.

## Technologies

- Terraform
- AWS EC2
- AWS Security Groups

## Project Structure

```text
aws-terraform-infrastructure/
├── terraform/
│   ├── provider.tf
│   ├── variables.tf
│   ├── main.tf
│   ├── outputs.tf
│   └── terraform.tfvars.example
├── .gitignore
└── README.md
```

## Features

- AWS Provider Configuration
- EC2 Instance Creation
- Security Group Configuration
- Variables
- Outputs

## How to Use

```bash
terraform init
terraform plan
terraform apply
```

## Future Improvements

- VPC
- Public & Private Subnets
- Internet Gateway
- Route Tables
- Auto Scaling
- Load Balancer
- Remote Backend (S3)
