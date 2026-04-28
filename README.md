# AWS 3-Tier Scalable Inventory Management System

## 📌 Project Overview

This project demonstrates a **production-like 3-tier architecture on AWS** to deploy a scalable and highly available web application.

The application is designed to handle traffic efficiently using **Application Load Balancer and Auto Scaling**, while securely storing data in **Amazon RDS**.

---

## 🏗️ Architecture

User
↓
Application Load Balancer (ALB)
↓
EC2 Instances (Auto Scaling Group)
↓
Amazon RDS (MySQL Database)

---

## ⚙️ AWS Services Used

* Amazon EC2
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* Amazon RDS (MySQL)
* VPC (Public & Private Subnets)
* Internet Gateway & Security Groups

---

## 🚀 How It Works

1. User sends request via browser
2. ALB receives traffic and distributes it across EC2 instances
3. EC2 instances run the inventory application
4. Application interacts with RDS database for data storage
5. Auto Scaling automatically increases/decreases instances based on load

---

## 🛠️ Deployment Steps (High-Level)

1. Launch EC2 instance and deploy application
2. Configure security groups and networking
3. Create RDS MySQL database
4. Setup Application Load Balancer
5. Create Target Group and register instances
6. Configure Auto Scaling Group using Launch Template

---

## 📸 Screenshots

Refer to the `/screenshots` folder for:

* EC2 instance running
* ALB configuration
* Target group health checks
* Auto Scaling setup
* RDS database
* Application working in browser

---

## ⚠️ Challenges Faced

* Target group showing unhealthy due to DB connection issues
* Fixed by ensuring RDS was running and accessible
* Managed IAM permission issues during Elastic IP operations

---

## 📈 Future Improvements

* CI/CD pipeline using GitHub Actions
* Docker containerization
* Kubernetes deployment
* Monitoring using CloudWatch / Prometheus / Grafana

---

## 🎯 Key Learnings

* Real-world 3-tier architecture design
* Load balancing and high availability concepts
* Auto Scaling implementation
* Debugging production-like issues

---

## 💡 Conclusion

This project simulates a **real-world scalable cloud architecture**, making it a strong foundation for DevOps and Cloud roles.

