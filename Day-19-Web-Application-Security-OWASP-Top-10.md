# Day 19: Web Application Security & OWASP Top 10

> Understanding Web Application Security, the OWASP Top 10 vulnerabilities, common web attacks, secure coding practices, and techniques used to protect web applications.

---

# 🎯 Learning Objectives

- Understand Web Application Security.
- Learn about OWASP.
- Explore the OWASP Top 10.
- Understand common web attacks.
- Learn secure coding practices.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Most modern businesses depend on web applications.

Examples include:

- Amazon
- Gmail
- Netflix
- Banking Portals
- University Portals

Because these applications store sensitive information, they are common targets for attackers.

Web Application Security focuses on protecting these applications from cyber threats.

---

# 🌐 What is Web Application Security?

Web Application Security is the practice of protecting websites and web applications from cyber attacks.

Its objectives include:

- Protect User Data
- Prevent Unauthorized Access
- Ensure Data Integrity
- Maintain Service Availability

---

# What is OWASP?

OWASP stands for:

**Open Worldwide Application Security Project**

It is a non-profit organization that provides security resources, tools, and best practices for web application security.

The **OWASP Top 10** lists the most critical web application security risks.

---

# OWASP Top 10

The current major categories include:

1. Broken Access Control
2. Cryptographic Failures
3. Injection
4. Insecure Design
5. Security Misconfiguration
6. Vulnerable and Outdated Components
7. Identification and Authentication Failures
8. Software and Data Integrity Failures
9. Security Logging and Monitoring Failures
10. Server-Side Request Forgery (SSRF)

---

# 1. Broken Access Control

Users gain access to resources they should not access.

Example:

A normal user accesses the administrator dashboard.

Protection:

- Role-Based Access Control (RBAC)
- Principle of Least Privilege

---

# 2. Cryptographic Failures

Sensitive information is exposed because encryption is weak or missing.

Examples:

- Passwords stored in plain text
- Weak encryption algorithms

Protection:

- HTTPS
- AES Encryption
- SHA-256 Password Hashing

---

# 3. Injection

Attackers insert malicious commands into applications.

Examples:

- SQL Injection
- Command Injection
- LDAP Injection

Example SQL Injection:

```sql
' OR '1'='1
```

Protection:

- Parameterized Queries
- Input Validation

---

# 4. Insecure Design

Applications are built without considering security.

Examples:

- Weak password policies
- Missing authorization checks

Protection:

- Secure Design Principles
- Threat Modeling

---

# 5. Security Misconfiguration

Incorrect security settings expose systems.

Examples:

- Default passwords
- Debug mode enabled
- Open cloud storage

Protection:

- Secure configuration
- Regular security reviews

---

# 6. Vulnerable and Outdated Components

Using outdated software with known vulnerabilities.

Examples:

- Old libraries
- Unsupported frameworks

Protection:

- Regular updates
- Patch management

---

# 7. Identification and Authentication Failures

Weak authentication mechanisms allow attackers to compromise accounts.

Examples:

- Weak passwords
- No MFA
- Session management flaws

Protection:

- Multi-Factor Authentication
- Strong password policies

---

# 8. Software and Data Integrity Failures

Applications trust software or updates without verification.

Examples:

- Malicious software updates
- Compromised dependencies

Protection:

- Digital Signatures
- Integrity Verification

---

# 9. Security Logging and Monitoring Failures

Security events are not properly logged or monitored.

Examples:

- Failed login attempts not recorded
- No alert generation

Protection:

- SIEM
- Centralized Logging

---

# 10. Server-Side Request Forgery (SSRF)

An attacker tricks the server into making requests to unintended destinations.

Example:

Accessing internal cloud metadata services.

Protection:

- Input Validation
- URL Allow Lists
- Network Segmentation

---

# Common Web Attacks

- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Clickjacking
- File Upload Attacks
- Directory Traversal

---

# Secure Coding Best Practices

- Validate User Input
- Sanitize Data
- Use HTTPS
- Store Passwords Securely
- Apply Least Privilege
- Update Dependencies
- Perform Security Testing

---

# Web Application Security Testing Tools

- Burp Suite
- OWASP ZAP
- Nikto
- Nmap
- SQLmap

---

# 🌍 Real-Life Example

An online shopping website allows users to search for products.

An attacker enters malicious SQL code into the search field.

Without proper validation, the attacker retrieves customer information from the database.

Using parameterized queries and input validation prevents the attack.

---

# 💡 Best Practices

- Follow the OWASP Top 10.
- Use secure authentication.
- Encrypt sensitive data.
- Validate all user input.
- Keep software updated.
- Perform regular security testing.

---

# 📌 Key Takeaways

- Web applications are common attack targets.
- OWASP Top 10 identifies major security risks.
- SQL Injection remains a critical threat.
- Broken Access Control is a leading vulnerability.
- Secure coding reduces attack risks.
- Regular testing improves security.

---

# ❓ Interview Questions

### 1. What is OWASP?

OWASP is a non-profit organization focused on improving web application security.

---

### 2. What is SQL Injection?

A vulnerability that allows attackers to execute malicious SQL commands.

---

### 3. What is Broken Access Control?

A vulnerability that allows users to access resources beyond their permissions.

---

### 4. What is SSRF?

Server-Side Request Forgery tricks a server into making unintended requests.

---

### 5. Name three OWASP Top 10 vulnerabilities.

- Broken Access Control
- Injection
- Security Misconfiguration

---

### 6. What tool is commonly used for web application security testing?

Burp Suite.

---

### 7. Why is HTTPS important?

It encrypts communication between users and web servers.

---

### 8. How can SQL Injection be prevented?

Using parameterized queries, prepared statements, and input validation.

---

# 📝 Summary

Today I learned about Web Application Security and the OWASP Top 10. I explored common vulnerabilities such as Broken Access Control, SQL Injection, Cryptographic Failures, Security Misconfiguration, and SSRF. I also learned secure coding practices, web application testing tools, and methods to protect applications from cyber attacks. Understanding the OWASP Top 10 is essential for developers, penetration testers, cloud engineers, and cybersecurity professionals.
