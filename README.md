# AWS-Cloud-Infrastructure-Labs
Overview

This repository documents hands-on cloud engineering work completed through AWS Academy labs and independent exploration. The focus is on designing secure, scalable, and highly available cloud systems, aligned with real-world production architectures used in large-scale technology companies.

Problem Statement

Modern distributed systems must handle:
High availability across regions
Secure networking and access control
Elastic scaling under variable workloads
Cost-efficient resource utilization
Observability and fault detection
These labs and projects address these challenges using AWS-managed cloud services and industry best practices.

Solution & Implementation

I designed and deployed multiple cloud architectures using AWS core services. Each lab simulates real production scenarios such as web hosting, database deployment, serverless execution, monitoring, and scaling.
Key implementation themes:
Infrastructure isolation using VPCs and subnets
Security enforcement using IAM, NACLs, and security groups
Horizontal and vertical scaling
Event-driven and serverless architectures
Cloud monitoring and logging

AWS Services & Cloud Concepts Used

Compute & Containers

EC2: Virtual machine provisioning and lifecycle management
AWS Lambda: Event-driven serverless compute
Kubernetes (conceptual): Container orchestration fundamentals and scaling concepts

Networking & Availability

VPC: Network isolation and segmentation
Availability Zones: High availability and fault tolerance
VPC Peering & VPC Sharing: Secure cross-network communication

AWS Gateways:

Internet Gateway
NAT Gateway
Virtual Private Gateway

Storage & Databases

EBS: Persistent block storage for EC2
S3: Object storage (standard & Glacier for archival)
Amazon RDS: Managed relational database deployment

Security

IAM: Fine-grained identity and access control
NACLs & Security Groups: Network-level and instance-level security
Encryption & least-privilege access practices

Scaling & Reliability

Auto Scaling Groups
Elastic Load Balancing
Fault isolation across AZs

Monitoring & Observability

Amazon CloudWatch:
Metrics
Logs
Alarms for system health and performance

Cost & Pricing Models

On-Demand Instances
Reserved Instances
Spot Instances
Cost-aware architecture decisions

Labs Completed (Hands-On)

IAM configuration and policy enforcement
VPC design and web server deployment
EC2 provisioning and EBS attachment
Database server setup on AWS
Auto Scaling and Load Balancing
AWS Lambda fundamentals
Monitoring infrastructure using CloudWatch

📸 Screenshots of completed labs are included to demonstrate hands-on execution.

Architecture Highlights

Multi-AZ web application architecture
Secure VPC with public and private subnets
Load-balanced EC2 fleet with auto scaling
Serverless execution using Lambda
Monitored infrastructure with CloudWatch alarms

Impact & Learning Outcomes

Built production-style cloud architectures instead of toy examples
Applied security-first design principles
Learned how large-scale systems handle reliability and failures
Understood cost-performance trade-offs in cloud environments
Gained practical exposure to cloud-native design patterns

Documentation

📄 Detailed learning notes and PDFs: /docs
📸 Lab completion screenshots: /screenshots

Virtual Private Gateway

