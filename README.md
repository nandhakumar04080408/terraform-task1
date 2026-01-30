# Terraform EC2 with MariaDB AMI

This project creates an EC2 instance using a custom AMI
that already has MariaDB installed.

## Prerequisites
- AWS CLI configured
- Terraform installed
- Existing AMI with MariaDB
- Existing VPC, Subnet, and Security Group

## Steps to Run
```bash
terraform init
terraform plan
terraform apply
