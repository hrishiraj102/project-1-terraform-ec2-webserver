
# Project 1: Deploy Linux EC2 Web Server using Terraform

## Objective
Deploy a Linux web server on AWS using Infrastructure as Code.

## Technologies
- AWS EC2
- Terraform
- VPC
- Security Groups
- Linux
- Apache HTTP Server
- Bash scripting

## Infrastructure Created
1. AWS VPC
2. Public Subnet
3. Internet Gateway
4. Route Table
5. Security Group
6. EC2 Instance

## Deployment Steps

Initialize Terraform:
terraform init

Validate:
terraform validate

Preview:
terraform plan

Deploy:
terraform apply

Get website URL:
terraform output website_url

## Testing
Open the generated website URL in a browser.

## Cleanup
terraform destroy

## Expected Result
A working Apache web server hosted on an AWS EC2 instance.
