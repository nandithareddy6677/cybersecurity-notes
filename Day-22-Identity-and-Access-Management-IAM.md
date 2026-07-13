# Day 22: Identity and Access Management (IAM)

> Understanding Identity and Access Management (IAM), authentication, authorization, users, groups, roles, policies, permissions, and security best practices in modern cloud environments.

---

# 🎯 Learning Objectives

- Understand Identity and Access Management (IAM).
- Differentiate Authentication and Authorization.
- Learn IAM Components.
- Understand Users, Groups, Roles, and Policies.
- Learn the Principle of Least Privilege.
- Explore AWS IAM Concepts.
- Prepare for cloud and cybersecurity interviews.

---

# 📖 Introduction

In every organization, not every employee should have access to every resource.

For example:

- HR employees should access payroll systems.
- Developers should deploy applications.
- Database Administrators should manage databases.
- Security Teams should monitor security logs.

Identity and Access Management (IAM) ensures that users can access only the resources they are authorized to use.

IAM is one of the most important security services in cloud computing.

---

# 🔐 What is IAM?

Identity and Access Management (IAM) is a framework that manages digital identities and controls access to resources.

IAM answers two important questions:

- Who is the user?
- What is the user allowed to do?

---

# Why is IAM Important?

IAM helps organizations:

- Secure Cloud Resources
- Prevent Unauthorized Access
- Manage User Permissions
- Implement Least Privilege
- Meet Compliance Requirements

---

# Authentication vs Authorization

## Authentication

Authentication verifies the identity of a user.

Examples:

- Username
- Password
- OTP
- Fingerprint

Question answered:

> "Who are you?"

---

## Authorization

Authorization determines what resources a user can access.

Examples:

- Read Files
- Create EC2 Instances
- Delete Databases

Question answered:

> "What are you allowed to do?"

---

# IAM Components

Identity and Access Management consists of:

- Users
- Groups
- Roles
- Policies
- Permissions

---

# IAM Users

An IAM User represents an individual person or application.

Each user has:

- Username
- Password
- Access Keys
- Permissions

Example:

```
Employee

↓

IAM User

↓

AWS Console Access
```

---

# IAM Groups

A Group is a collection of IAM Users.

Instead of assigning permissions individually, permissions are assigned to the group.

Example:

```
Developers

↓

IAM Group

↓

EC2 Access
```

Members automatically inherit the group's permissions.

---

# IAM Roles

An IAM Role provides temporary permissions.

Roles are commonly used by:

- EC2 Instances
- Lambda Functions
- Applications
- Cross-Account Access

Unlike users, roles do not have permanent passwords.

---

# IAM Policies

Policies define permissions.

Policies are written in JSON format.

Example:

```json
{
  "Effect": "Allow",
  "Action": "s3:ListBucket",
  "Resource": "*"
}
```

Policies determine what actions are allowed or denied.

---

# Principle of Least Privilege

Users should receive only the permissions required to perform their tasks.

Example:

A developer should deploy applications but should not delete production databases.

Least Privilege reduces security risks.

---

# Permission Types

Permissions include:

- Read
- Write
- Create
- Update
- Delete
- Execute

Organizations assign permissions carefully based on job responsibilities.

---

# Multi-Factor Authentication (MFA)

MFA strengthens IAM security.

Example:

```
Username

↓

Password

↓

OTP

↓

Access Granted
```

Even if a password is stolen, MFA provides an additional layer of protection.

---

# Temporary Credentials

Cloud platforms often use temporary credentials instead of long-term passwords.

Benefits:

- Reduced Risk
- Automatic Expiration
- Better Security

AWS IAM Roles use temporary credentials.

---

# IAM Best Practices

- Enable MFA.
- Use IAM Roles instead of sharing credentials.
- Apply Least Privilege.
- Rotate Access Keys regularly.
- Remove unused accounts.
- Review permissions periodically.

---

# IAM in AWS

AWS IAM provides:

- Users
- Groups
- Roles
- Policies
- MFA
- Access Analyzer

IAM is available at no additional cost.

---

# IAM in Azure

Microsoft Entra ID (formerly Azure Active Directory) provides:

- Identity Management
- Authentication
- Single Sign-On (SSO)
- Conditional Access

---

# IAM in Google Cloud

Google Cloud IAM manages:

- Users
- Service Accounts
- Roles
- Permissions

---

# 🌍 Real-Life Example

A company has three employees.

- HR Manager
- Software Developer
- Cloud Administrator

Each employee receives a different IAM Role.

The HR Manager cannot manage AWS servers.

The Developer cannot access payroll data.

The Cloud Administrator manages infrastructure but does not access confidential HR documents.

IAM ensures that everyone receives only the permissions necessary for their job.

---

# 💡 Best Practices

- Never share IAM credentials.
- Enable MFA for all privileged accounts.
- Use Roles instead of long-term access keys.
- Audit permissions regularly.
- Follow the Principle of Least Privilege.
- Remove inactive accounts immediately.

---

# 📌 Key Takeaways

- IAM manages identities and permissions.
- Authentication verifies identity.
- Authorization determines permissions.
- Users represent individuals.
- Groups simplify permission management.
- Roles provide temporary access.
- Policies define permissions.
- Least Privilege improves security.

---

# ❓ Interview Questions

### 1. What is IAM?

IAM is a framework used to manage identities and control access to resources.

---

### 2. What is the difference between Authentication and Authorization?

Authentication verifies identity, while Authorization determines permissions.

---

### 3. What is an IAM Role?

An IAM Role provides temporary permissions without permanent credentials.

---

### 4. Why are IAM Groups useful?

They simplify permission management by assigning permissions to multiple users at once.

---

### 5. What is the Principle of Least Privilege?

Users should receive only the minimum permissions required to perform their work.

---

### 6. What format are AWS IAM Policies written in?

JSON.

---

### 7. Why should Multi-Factor Authentication (MFA) be enabled?

It adds an additional layer of security beyond passwords.

---

### 8. Name three AWS IAM components.

- Users
- Groups
- Roles

---

# 📝 Summary

Today I learned about Identity and Access Management (IAM), one of the most important security concepts in cloud computing. I explored authentication, authorization, IAM users, groups, roles, policies, permissions, and the Principle of Least Privilege. I also learned how AWS, Microsoft Azure, and Google Cloud use IAM to secure cloud resources and manage user access effectively.
