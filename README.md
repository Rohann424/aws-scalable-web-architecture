# aws-scalable-web-architecture

This project demonstrates a **highly available** and scalable **web application** architecture using AWS services including **Application Load Balancer (ALB), EC2, Auto Scaling Group, and CloudWatch**.

**📌 Features:**

-**Load balancing using ALB**
-Auto Scaling based on CPU utilization
-Multi-instance deployment across availability zones
-Real-time monitoring with CloudWatch
-SNS notifications for alerts**


**Step 1 :**
Created a **Virtual Private Cloud (VPC)** with **CIDR block 10.0.0.0/16** to establish an isolated and secure networking environment in AWS. 

This VPC acts as the foundational layer where all cloud resources such as EC2 instances, load balancers, and auto scaling groups are deployed.

![Project Screenshot](Screenshots/02-versioning-enabled.png)
