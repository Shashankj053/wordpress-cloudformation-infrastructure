# WordPress Deployment on AWS using CloudFormation

## Overview

This project demonstrates automated deployment of a production-ready WordPress environment on AWS using Infrastructure as Code (IaC) principles with AWS CloudFormation.

The infrastructure was provisioned using reusable YAML templates and includes automation, scaling, backup, and monitoring concepts commonly used in real-world DevOps environments.

---

## Technologies Used

* AWS EC2
* AWS CloudFormation
* AWS IAM
* AWS Route53
* Auto Scaling Groups
* AMI Backups
* Linux
* WordPress

---

## Features

* Automated infrastructure provisioning using CloudFormation
* WordPress deployment on EC2
* Scheduled Auto Scaling configuration
* Route53 health checks
* AMI backup image creation
* Separate development and production environments
* Infrastructure managed through reusable templates

---

## Architecture

![Architecture](architecture-diagram.png)

---

## Deployment Screenshots

### CloudFormation Stack

![CloudFormation](cloudformation-stack.png)

### EC2 Instance

![EC2](ec2-instance.png)

### WordPress Installation

![WordPress](wordpress-installation.png)

### Auto Scaling Group

![ASG](autoscaling-group.png)

### Route53 Health Check

![Route53](route53-healthcheck.png)

### AMI Backup

![AMI](ami-backup.png)

### Live WordPress Deployment

![Live Site](wordpress-live-site.png)

---

## Key Learnings

* Infrastructure as Code (IaC)
* AWS cloud provisioning
* DevOps automation workflows
* Cloud scalability concepts
* Infrastructure monitoring and reliability
* Troubleshooting deployment and permissions issues

---

## Author

Shashank Jain
