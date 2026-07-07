# Multi-VPC Networking with AWS PrivateLink

Production-style AWS networking project demonstrating secure communication between isolated VPCs using AWS PrivateLink.

## Architecture

<img width="1536" height="1024" alt="Multi-VPC Networking" src="https://github.com/user-attachments/assets/24509d21-eb8c-42db-851f-c2cc1016c9ef" />

## Technologies

- Amazon VPC
- AWS PrivateLink
- Network Load Balancer
- NAT Gateway
- EC2
- Security Groups
- Route Tables
- EC2 Instance Connect Endpoint

## Architecture

Payments VPC
        │
Interface Endpoint
        │
AWS PrivateLink
        │
Endpoint Service
        │
Internal Network Load Balancer
        │
Target Group
        │
Private EC2

## Documentation

Detailed documentation is available here:

[Multi-VPC-Networking-with-AWS-PrivateLink.pdf](https://github.com/user-attachments/files/29753145/Multi-VPC-Networking-with-AWS-PrivateLink.pdf)

## Author

**Dwayne Cowart**

Cloud Engineer

📧 dcowart87@gmail.com

LinkedIn: www.linkedin.com/in/dwayne-cowart
