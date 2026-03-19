# AWS 3-Tier Scalable Inventory Management System using ALB, Auto Scaling & RDS

## Project Overview
This project demonstrates a highly available AWS 3-tier architecture used to deploy a scalable web application.

The architecture separates the application into three layers:

1. Presentation Layer
2. Application Layer
3. Database Layer

This design improves scalability, security and reliability.

---

## Architecture

User
↓
Application Load Balancer
↓
EC2 Instances (Auto Scaling)
↓
RDS MySQL Database

---

## AWS Services Used

- VPC
- Public Subnets
- Private Subnets
- Internet Gateway
- NAT Gateway
- Application Load Balancer
- EC2
- Auto Scaling
- RDS MySQL

---

## Project Goal

The goal of this project is to simulate a production-grade infrastructure setup where a web application can handle traffic reliably using load balancing and auto scaling.

---

## Future Improvements

- CI/CD pipeline integration
- Docker containerization
- Monitoring with Prometheus and Grafana
