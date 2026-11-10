# MZ-UCA Terraform VPC Project
## Purpose
Creates an AWS network using Terraform.
## Resources
- One VPC and two subnets
- Internet Gateway and public route table
- Public route table association
- HTTPS security group
## CIDR plan
- VPC: 10.20.0.0/16
- Public: 10.20.1.0/24
- Private: 10.20.11.0/24
## Deployment
terraform init
terraform fmt -recursive
terraform validate
terraform plan
terraform apply
## Security
Never commit credentials or state files.
## Cleanup
terraform destroy