# Day 21: Cloud Security Fundamentals

> Understanding Cloud Security, the Shared Responsibility Model, cloud security challenges, identity management, encryption, and best practices used to secure modern cloud environments.

---

# 🎯 Learning Objectives

- Understand Cloud Security.
- Learn the Shared Responsibility Model.
- Explore Cloud Security Challenges.
- Understand IAM.
- Learn Data Protection.
- Explore Cloud Security Services.
- Prepare for cloud and cybersecurity interviews.

---

# 📖 Introduction

Cloud Computing has transformed how organizations store data, deploy applications, and manage infrastructure.

However, moving workloads to the cloud introduces new security challenges.

Cloud Security focuses on protecting:

- Cloud Infrastructure
- Applications
- User Identities
- Data
- Networks

Cloud providers such as AWS, Microsoft Azure, and Google Cloud offer built-in security services, but customers are also responsible for securing their own cloud environments.

---

# ☁️ What is Cloud Security?

Cloud Security is the collection of technologies, policies, controls, and best practices used to protect cloud-based systems, applications, and data.

Cloud Security ensures:

- Confidentiality
- Integrity
- Availability

---

# Why Cloud Security is Important

Organizations use cloud services for:

- Web Applications
- Databases
- Storage
- Virtual Machines
- AI Services
- Enterprise Applications

Without proper security:

- Data Breaches
- Misconfigurations
- Account Compromise
- Ransomware
- Insider Threats

can occur.

---

# Cloud Service Models

Cloud services are commonly divided into:

## Infrastructure as a Service (IaaS)

Examples:

- Amazon EC2
- Azure Virtual Machines
- Google Compute Engine

Customer manages:

- Operating System
- Applications
- Security Configuration

---

## Platform as a Service (PaaS)

Examples:

- Azure App Service
- Google App Engine

Cloud provider manages:

- Infrastructure
- Operating System

Customer manages:

- Applications
- Data

---

## Software as a Service (SaaS)

Examples:

- Gmail
- Microsoft 365
- Salesforce

Cloud provider manages almost everything.

Users simply use the application.

---

# Shared Responsibility Model

Cloud Security is a shared responsibility.

```
Cloud Provider

↓

Physical Security

Infrastructure

Networking

Hardware

↓

Customer

Operating System

Applications

Data

IAM

Configuration
```

Example (AWS)

AWS secures:

- Data Centers
- Servers
- Storage Hardware
- Networking Infrastructure

Customers secure:

- User Accounts
- IAM Policies
- Security Groups
- Stored Data
- Applications

---

# Common Cloud Security Challenges

- Misconfigured Storage Buckets
- Weak IAM Policies
- Exposed APIs
- Data Leakage
- Insider Threats
- Unpatched Virtual Machines
- Credential Theft

---

# Identity and Access Management (IAM)

IAM controls:

- Who can access cloud resources.
- What actions users can perform.

IAM includes:

- Users
- Groups
- Roles
- Policies

Following the Principle of Least Privilege is essential.

---

# Data Protection

Cloud data should always be protected.

Techniques include:

- Encryption at Rest
- Encryption in Transit
- Backups
- Key Management
- Access Control

---

# Encryption

Cloud providers encrypt data:

## At Rest

Stored data is encrypted.

Example:

Amazon S3 Encryption.

---

## In Transit

Data is encrypted while moving across networks.

Example:

HTTPS using TLS.

---

# Multi-Factor Authentication (MFA)

MFA adds an additional layer of protection.

Example:

```
Username

↓

Password

↓

OTP

↓

Cloud Console Access
```

---

# Security Monitoring

Cloud environments continuously monitor security using:

AWS:

- CloudTrail
- CloudWatch
- GuardDuty
- Security Hub

Azure:

- Microsoft Defender for Cloud
- Azure Monitor

Google Cloud:

- Security Command Center

---

# Cloud Security Best Practices

- Enable MFA.
- Use strong IAM policies.
- Encrypt sensitive data.
- Enable logging.
- Monitor cloud resources.
- Patch virtual machines regularly.
- Review permissions periodically.

---

# Real-World Example

A company stores customer data in Amazon S3.

Initially, the storage bucket is configured as public.

Anyone on the Internet can access sensitive files.

The security team:

- Makes the bucket private.
- Enables encryption.
- Restricts access using IAM.
- Enables logging.
- Monitors activity using AWS CloudTrail.

The data is now protected.

---

# Cloud Security in AWS

Common AWS Security Services:

- IAM
- KMS
- CloudTrail
- GuardDuty
- Security Hub
- AWS WAF
- AWS Shield

---

# 💡 Best Practices

- Follow the Shared Responsibility Model.
- Apply Least Privilege.
- Enable logging.
- Encrypt sensitive information.
- Regularly audit cloud resources.
- Monitor suspicious activities.

---

# 📌 Key Takeaways

- Cloud Security protects cloud environments.
- Security is shared between provider and customer.
- IAM controls user access.
- Encryption protects cloud data.
- Monitoring detects security threats.
- Cloud providers offer built-in security services.

---

# ❓ Interview Questions

### 1. What is Cloud Security?

Cloud Security is the practice of protecting cloud systems, applications, and data.

---

### 2. What is the Shared Responsibility Model?

A security model where the cloud provider secures the infrastructure while customers secure their data, applications, and configurations.

---

### 3. What are the three cloud service models?

- IaaS
- PaaS
- SaaS

---

### 4. What is IAM?

Identity and Access Management controls authentication and authorization within cloud environments.

---

### 5. Name three AWS security services.

- IAM
- GuardDuty
- CloudTrail

---

### 6. Why is MFA important?

It adds an extra layer of authentication beyond passwords.

---

### 7. What is encryption at rest?

Encrypting stored data to protect it from unauthorized access.

---

### 8. Why is CloudTrail important?

It records AWS account activity for auditing, monitoring, and incident investigation.

---

# 📝 Summary

Today I learned about Cloud Security Fundamentals and how organizations protect cloud infrastructure, applications, and data. I explored cloud service models, the Shared Responsibility Model, IAM, encryption, MFA, monitoring services, and AWS security tools. Cloud Security is a critical area because modern organizations increasingly rely on cloud platforms to host applications and store sensitive information.
