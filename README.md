# AWS EC2 Static Website Project

## Overview
This is a beginner-level AWS project where I deployed a static website on an Amazon EC2 instance using Apache Web Server.

## Architecture
User → EC2 (Apache Web Server)  
Static assets → Amazon S3  
Storage → Amazon EBS

## AWS Services Used
- Amazon EC2 – Virtual server to host the website
- Amazon EBS – Block storage attached to EC2
- Amazon S3 – Object storage for static files
- Security Groups – Firewall to control traffic

## Instance Details
- AMI: Amazon Linux 2023
- Instance Type: t3.micro
- Web Server: Apache (httpd)

## What I Learned
- How to launch and configure an EC2 instance
- Difference between block storage (EBS) and object storage (S3)
- How security groups control inbound traffic
- Basics of Infrastructure as a Service (IaaS)

## Live Demo
Website hosted using EC2 public IP address.

## Python + AWS Integration
A Python script running on an EC2 instance uses the boto3 SDK to securely access Amazon S3 and list stored objects. Access is granted using an IAM role attached to the EC2 instance, following AWS security best practices.

