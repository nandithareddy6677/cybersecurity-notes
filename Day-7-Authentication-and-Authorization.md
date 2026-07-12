# Day 7: Authentication and Authorization

> Understanding how users are identified, verified, and granted access to resources in modern computer systems.

---

# 🎯 Learning Objectives

- Understand Authentication and Authorization.
- Learn the difference between Authentication and Authorization.
- Explore different authentication methods.
- Understand Multi-Factor Authentication (MFA).
- Learn about Biometrics.
- Explore Role-Based Access Control (RBAC).
- Understand Attribute-Based Access Control (ABAC).
- Learn OAuth and OpenID Connect.
- Understand Single Sign-On (SSO).
- Learn security best practices.

---

# 📖 Introduction

Whenever we log into Gmail, Instagram, our bank account, or any online application, the system first verifies who we are and then decides what we are allowed to do.

This process involves two important security concepts:

- Authentication
- Authorization

These concepts are fundamental to cybersecurity and are used in almost every modern application.

---

# 🔐 What is Authentication?

Authentication is the process of verifying the identity of a user, device, or application.

In simple words,

Authentication answers the question:

**"Who are you?"**

Example:

You enter your username and password to log into Gmail.

If the credentials are correct,

Google confirms your identity.

This is Authentication.

---

# Common Authentication Methods

## 1. Password-Based Authentication

The most common method.

The user enters:

- Username
- Password

Advantages

- Easy to use
- Widely supported

Disadvantages

- Weak passwords
- Password reuse
- Phishing attacks

---

## 2. Multi-Factor Authentication (MFA)

MFA requires more than one method to verify identity.

Usually combines two or more of the following:

### Something You Know

- Password
- PIN

### Something You Have

- Mobile Phone
- OTP
- Security Token

### Something You Are

- Fingerprint
- Face Recognition
- Iris Scan

Example

Password

+

OTP sent to your phone

---

Advantages

- Stronger security
- Prevents unauthorized access

---

## 3. Biometric Authentication

Uses unique biological characteristics.

Examples

- Fingerprint
- Face Recognition
- Retina Scan
- Iris Scan
- Voice Recognition

Advantages

- Difficult to copy
- Fast authentication

Limitations

- Privacy concerns
- Hardware requirements

---

# 🔓 What is Authorization?

Authorization determines what an authenticated user is allowed to access.

It answers the question:

**"What are you allowed to do?"**

Example

After logging into Gmail,

You can access

- Your emails

But

You cannot access someone else's inbox.

That is Authorization.

---

# Authentication vs Authorization

| Authentication | Authorization |
|----------------|---------------|
| Verifies identity | Determines permissions |
| Happens first | Happens after authentication |
| "Who are you?" | "What can you do?" |
| Username & Password | User Permissions |

---

# Access Control

Access Control determines who can access specific resources.

It ensures that users only access information they are authorized to use.

---

# Types of Access Control

## 1. Role-Based Access Control (RBAC)

Permissions are assigned based on a user's role.

Example

Administrator

↓

Full Access

Manager

↓

Department Access

Employee

↓

Limited Access

Advantages

- Easy to manage
- Common in organizations

---

## 2. Attribute-Based Access Control (ABAC)

Permissions are granted based on attributes such as:

- Department
- Location
- Time
- Device
- Job Title

Example

Employees can access company files

Only

From office computers

Between

9 AM and 6 PM.

---

# Single Sign-On (SSO)

SSO allows users to log in once and access multiple applications without logging in again.

Example

Logging into your Google account allows access to:

- Gmail
- Google Drive
- YouTube
- Google Docs

Advantages

- Convenience
- Better user experience
- Fewer passwords

---

# OAuth

OAuth is an authorization framework.

It allows applications to access user data without sharing passwords.

Example

"Continue with Google"

The application never receives your Google password.

Instead,

Google provides an access token.

---

# OpenID Connect (OIDC)

OpenID Connect is built on top of OAuth 2.0.

Purpose

Authentication

OAuth

Authorization

OpenID Connect

Authentication + User Identity

Example

Signing into Spotify using your Google account.

---

# JWT (JSON Web Token)

JWT is a secure method of transmitting user information between systems.

It is commonly used for:

- Authentication
- Authorization
- API Security

A JWT contains:

- Header
- Payload
- Signature

---

# Password Security Best Practices

- Use strong passwords.
- Use Multi-Factor Authentication.
- Never reuse passwords.
- Store passwords using hashing.
- Change compromised passwords immediately.
- Use a Password Manager.

---

# 🌍 Real-Life Example

A company's HR portal allows:

Employees

- View salary
- Update profile

Managers

- View department records
- Approve leave requests

Administrators

- Manage all employee accounts
- Change permissions

All users authenticate using MFA before authorization determines what they can access.

---

# 📌 Key Takeaways

- Authentication verifies identity.
- Authorization determines permissions.
- Authentication happens before Authorization.
- MFA improves account security.
- RBAC assigns permissions based on roles.
- ABAC uses user attributes for access decisions.
- OAuth enables secure authorization.
- OpenID Connect provides authentication.
- JWT securely transfers authentication information.

---

# ❓ Interview Questions

### 1. What is Authentication?

Authentication is the process of verifying the identity of a user or system.

---

### 2. What is Authorization?

Authorization determines what an authenticated user is allowed to access.

---

### 3. Difference between Authentication and Authorization?

Authentication verifies identity.

Authorization grants permissions after identity verification.

---

### 4. What is Multi-Factor Authentication?

MFA uses two or more verification methods to authenticate a user.

---

### 5. What is RBAC?

Role-Based Access Control grants permissions based on user roles.

---

### 6. What is ABAC?

Attribute-Based Access Control grants permissions based on attributes like department, location, or time.

---

### 7. What is OAuth?

OAuth is an authorization framework that allows applications to access user data without sharing passwords.

---

### 8. What is OpenID Connect?

OpenID Connect is an authentication layer built on top of OAuth 2.0.

---

### 9. What is JWT?

JSON Web Token is a secure token used for authentication and authorization.

---

### 10. Why is MFA important?

MFA adds an extra layer of security by requiring multiple forms of verification, reducing the risk of unauthorized access.

---

# 📝 Summary

Today I learned about Authentication and Authorization, two fundamental concepts in cybersecurity. Authentication verifies the identity of users, while Authorization determines their access permissions. I also explored Multi-Factor Authentication, Biometrics, RBAC, ABAC, OAuth, OpenID Connect, JWT, and security best practices that help protect modern applications and user accounts.
