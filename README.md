## AWS LAMP Stack Production Deployment using WordPress on AWS
## Project Overview

This project demonstrates the deployment of a production-oriented LAMP Stack architecture on AWS using Amazon Linux 2023, Apache HTTP Server, PHP, and Amazon RDS (MariaDB). The application is deployed on Amazon EC2 and integrated with AWS networking, storage, monitoring, and scalability services to simulate a real-world cloud deployment.

The architecture follows a multi-tier design where the web server and database server are separated, improving security, availability, scalability, and maintainability.

## Project Objectives
Deploy a LAMP Stack on Amazon EC2.
Configure Apache HTTP Server and PHP.
Deploy WordPress as the web application.
Use Amazon RDS (MariaDB) as the managed database.
Configure Application Load Balancer (ALB).
Implement Auto Scaling Group (ASG).
Mount Amazon EFS for shared application storage.
Monitor infrastructure using Amazon CloudWatch.
Configure networking using Amazon VPC, Public and Private Subnets.
Implement Security Groups following least privilege principles.
Demonstrate a production-style AWS deployment.

## AWS Services Used
------------------------------------------------------------------------------------------
| Service                         | Purpose                                              |
| ------------------------------- | ---------------------------------------------------- |
| Amazon EC2                      | Hosts Apache, PHP, and WordPress                     |
| Amazon Linux 2023               | Operating System                                     |
| Apache HTTP Server              | Web Server                                           |
| PHP                             | Server-side scripting language                       |
| Amazon RDS (MariaDB)            | Managed relational database                          |
| Application Load Balancer (ALB) | Distributes incoming traffic across EC2 instances    |
| Auto Scaling Group (ASG)        | Automatically scales EC2 instances                   |
| Amazon EFS                      | Shared file storage for WordPress                    |
| Amazon CloudWatch               | Monitors infrastructure and application performance  |
| Amazon VPC                      | Provides isolated cloud networking                   |
| Public Subnets                  | Host the Application Load Balancer and EC2 instances |
| Private Subnets                 | Host Amazon RDS and Amazon EFS                       |
| Security Groups                 | Control inbound and outbound network traffic         |
------------------------------------------------------------------------------------------
## Architecture Overview

```text
Internet Users
      │
      ▼
Application Load Balancer (ALB)
      │
      ▼
Auto Scaling Group (ASG)
      │
      ▼
Amazon EC2
(Amazon Linux 2023)
Apache + PHP + WordPress
      │
      ├────────► Amazon EFS
      │
      ▼
Amazon RDS (MariaDB)
      │
      ▼
Amazon CloudWatch (Monitoring & Metrics)
---

## Deployment Workflow

1. Launch Amazon Linux 2023 EC2 Instance.
2. Install Apache HTTP Server.
3. Install PHP and required modules.
4. Create Amazon RDS (MariaDB).
5. Configure the WordPress database.
6. Install and configure WordPress.
7. Configure `wp-config.php`.
8. Mount Amazon EFS.
9. Configure the Application Load Balancer.
10. Configure the Auto Scaling Group.
11. Configure Security Groups and Networking.
12. Monitor the infrastructure using Amazon CloudWatch.


## The project follows a three-tier cloud architecture.

Client
   │
   ▼
Application Load Balancer
   │
   ▼
Auto Scaling Group
   │
   ▼
Amazon EC2
(Apache + PHP + WordPress)
   │
   ├────────► Amazon EFS
   │
   ▼
Amazon RDS (MariaDB)


## Technology Stack
Layer	Technology
Operating System --> Amazon Linux 2023
Web Server	--> Apache HTTP Server
Programming Language	--> PHP
Database	--> Amazon RDS MariaDB
Web Application --> 	WordPress
Cloud Platform	--> Amazon Web Services
Monitoring	--> Amazon CloudWatch

## Project Features
Production-ready LAMP Stack deployment
Managed database using Amazon RDS
Dynamic web application using WordPress
High Availability using Application Load Balancer
Automatic Scaling using Auto Scaling Group
Shared file storage using Amazon EFS
Cloud monitoring with Amazon CloudWatch
Secure network architecture using VPC and Security Groups
Public and Private subnet implementation
Production networking architecture

## Learning Outcomes
This project demonstrates practical knowledge of:
Linux Administration
Apache Web Server
PHP Configuration
WordPress Deployment
Amazon EC2
Amazon RDS MariaDB
Amazon EFS
Amazon CloudWatch
Application Load Balancer
Auto Scaling Group
Amazon Route 53
AWS Networking
Security Groups
Production Cloud Architecture

## Conclusion
This project demonstrates the deployment of a scalable and production-oriented LAMP Stack architecture on AWS using Amazon Linux 2023, Apache HTTP Server, PHP, Amazon RDS (MariaDB), Amazon EFS, Application Load Balancer, Auto Scaling Group, CloudWatch, and Route 53. The implementation follows cloud best practices by separating the web and database tiers, using managed services, monitoring infrastructure health, and designing for scalability, security, and high availability. The project provides hands-on experience with deploying and managing modern web applications in a production-like AWS environment.


## Author
## Shivam Gaike
DevOps Engineer | Cloud Engineer | Big Data Engineer | AWS | Linux | Apache | PHP | MariaDB | WordPress | Cloud Computing | Data Engineering
