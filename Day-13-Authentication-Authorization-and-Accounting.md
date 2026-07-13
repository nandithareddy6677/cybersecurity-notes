# Day 13: Authentication, Authorization & Accounting (AAA)

> Understanding the AAA Security Framework, authentication methods, authorization models, accounting, access control mechanisms, and their importance in cybersecurity.

---

# 🎯 Learning Objectives

- Understand the AAA Framework.
- Learn Authentication.
- Learn Authorization.
- Understand Accounting.
- Explore Authentication Methods.
- Learn Multi-Factor Authentication (MFA).
- Understand Access Control Models.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Whenever you log into Gmail, AWS, your college portal, or your bank account, the system performs three important security checks:

- Who are you?
- What are you allowed to do?
- What actions did you perform?

These three questions are answered by the **AAA Framework**.

AAA is one of the most fundamental concepts in cybersecurity and is widely used in enterprise networks, cloud computing, operating systems, and identity management systems.

---

# 🔐 What is AAA?

AAA stands for:

- Authentication
- Authorization
- Accounting

It provides secure access to systems and resources.

```
User

↓

Authentication

↓

Authorization

↓

Accounting
```

---

# Authentication

Authentication answers:

**"Who are you?"**

It verifies the identity of a user before granting access.

Examples:

- Username & Password
- Fingerprint
- Face Recognition
- OTP
- Smart Card

Without authentication, anyone could access the system.

---

# Authentication Factors

Authentication is based on one or more factors.

## Something You Know

Examples:

- Password
- PIN
- Security Questions

---

## Something You Have

Examples:

- Mobile Phone
- Smart Card
- Hardware Token
- OTP Generator

---

## Something You Are

Examples:

- Fingerprint
- Face Recognition
- Retina Scan
- Voice Recognition

---

# Multi-Factor Authentication (MFA)

Multi-Factor Authentication uses two or more authentication factors.

Example:

```
Username + Password

↓

OTP

↓

Access Granted
```

Benefits:

- Stronger Security
- Prevents Unauthorized Access
- Reduces Password-Based Attacks

---

# Authorization

Authorization answers:

**"What are you allowed to do?"**

After a user is authenticated, the system determines which resources the user can access.

Example:

A Student can:

- View Marks
- Download Assignments

A Professor can:

- Upload Marks
- Edit Student Records

Both users are authenticated, but their permissions are different.

---

# Access Control

Authorization is implemented using Access Control.

Access Control determines:

- Read Permission
- Write Permission
- Execute Permission
- Delete Permission

---

# Access Control Models

## DAC (Discretionary Access Control)

The owner decides who can access resources.

Example:

Sharing a Google Drive file.

---

## MAC (Mandatory Access Control)

Access is controlled by security policies.

Commonly used in:

- Military
- Government

---

## RBAC (Role-Based Access Control)

Permissions are assigned based on user roles.

Example:

| Role | Permission |
|------|------------|
| Student | View Results |
| Faculty | Upload Marks |
| Admin | Full Access |

RBAC is widely used in companies.

---

## ABAC (Attribute-Based Access Control)

Access depends on user attributes.

Examples:

- Department
- Location
- Time
- Device

Example:

Employees may access payroll only from the office network during working hours.

---

# Accounting

Accounting answers:

**"What did the user do?"**

It records user activities after login.

Examples:

- Login Time
- Logout Time
- Files Accessed
- Commands Executed
- Failed Login Attempts

Accounting helps organizations monitor and audit user activities.

---

# Importance of Accounting

Accounting helps in:

- Security Audits
- Incident Investigation
- Compliance
- User Monitoring
- Forensics

---

# AAA in Enterprise Networks

Organizations commonly use:

- RADIUS
- TACACS+

for centralized authentication and authorization.

---

# RADIUS

Remote Authentication Dial-In User Service

Used for:

- Wi-Fi Authentication
- VPN Authentication
- Enterprise Networks

---

# TACACS+

Terminal Access Controller Access-Control System Plus

Used mainly for:

- Network Device Administration
- Cisco Routers
- Cisco Switches

Provides more granular control than RADIUS.

---

# AAA in Cloud Computing

Cloud providers use AAA extensively.

AWS:

- IAM Users
- IAM Roles
- IAM Policies

Azure:

- Azure Active Directory

Google Cloud:

- Cloud IAM

These services control authentication and authorization for cloud resources.

---

# 🌍 Real-Life Example

Suppose an employee logs into the company's AWS Management Console.

1. Authentication verifies the employee's username and password.

2. MFA requests an OTP from the employee's phone.

3. Authorization checks whether the employee has permission to manage EC2 instances.

4. Accounting records every action performed by the employee for future auditing.

---

# 💡 Best Practices

- Enable Multi-Factor Authentication.
- Use strong passwords.
- Apply the Principle of Least Privilege.
- Review permissions regularly.
- Monitor login activity.
- Disable inactive accounts.

---

# 📌 Key Takeaways

- Authentication verifies identity.
- Authorization determines permissions.
- Accounting records user activities.
- MFA improves security.
- RBAC is widely used in organizations.
- RADIUS and TACACS+ support enterprise authentication.
- Cloud platforms implement AAA using IAM services.

---

# ❓ Interview Questions

### 1. What does AAA stand for?

Authentication, Authorization, and Accounting.

---

### 2. What is Authentication?

Authentication verifies the identity of a user before granting access.

---

### 3. What is Authorization?

Authorization determines what resources an authenticated user is allowed to access.

---

### 4. What is Accounting?

Accounting records user activities for monitoring, auditing, and investigation.

---

### 5. What is Multi-Factor Authentication (MFA)?

MFA requires two or more authentication factors to verify a user's identity.

---

### 6. What is RBAC?

Role-Based Access Control assigns permissions based on user roles.

---

### 7. What is the Principle of Least Privilege?

Users should receive only the permissions necessary to perform their tasks.

---

### 8. Name two enterprise authentication protocols.

- RADIUS
- TACACS+

---

# 📝 Summary

Today I learned about the AAA Framework, which consists of Authentication, Authorization, and Accounting. I explored authentication methods, Multi-Factor Authentication, access control models such as DAC, MAC, RBAC, and ABAC, and enterprise protocols like RADIUS and TACACS+. I also learned how cloud platforms such as AWS, Azure, and Google Cloud implement AAA using Identity and Access Management (IAM) services. Understanding AAA is essential for securing systems, controlling access, and auditing user activities in modern organizations.
