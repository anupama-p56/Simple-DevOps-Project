## This project demonstrates a secure and production-ready AWS network architecture provisioned entirely using Terraform. The infrastructure follows AWS best practices, including network isolation, controlled access, and high availability.

### Architecture
- Custom AWS VPC with defined CIDR ranges
- Public and private subnets
- Internet Gateway and NAT Gateway
- Bastion host in public subnet for secure SSH access
- Private EC2 instance with no direct internet exposure
- Strict security group rules for controlled traffic flow

### Tech Stack

- Terraform (v1.x)
- AWS EC2
- VPC, Subnets, Route Tables
- Internet Gateway & NAT Gateway
- Security Groups
- Amazon Linux 2