# Day 6: Web Security

> Understanding how websites are secured against cyber attacks and learning common web vulnerabilities.

---

# 🎯 Learning Objectives

- Understand Web Security.
- Learn the difference between HTTP and HTTPS.
- Understand SSL/TLS.
- Learn about Cookies and Sessions.
- Understand Same-Origin Policy.
- Learn common web attacks.
- Explore OWASP Top 10.
- Learn secure coding practices.

---

# 📖 Introduction

Almost everything we do today happens through web applications, including online banking, shopping, social media, healthcare, and education.

Since millions of users access websites every day, web applications are one of the biggest targets for cyber attackers.

Web Security focuses on protecting websites, web applications, users, and data from cyber threats.

---

# 🌐 What is Web Security?

Web Security is the practice of protecting websites, web applications, servers, and users from cyber attacks.

Its primary goals are:

- Protect user data
- Prevent unauthorized access
- Ensure secure communication
- Maintain availability of web services

---

# HTTP vs HTTPS

## HTTP (HyperText Transfer Protocol)

HTTP is the protocol used for communication between a web browser and a web server.

Characteristics:

- Data is transmitted in plain text.
- No encryption.
- Vulnerable to interception.

Example:

http://example.com

---

## HTTPS (HyperText Transfer Protocol Secure)

HTTPS is the secure version of HTTP.

It uses SSL/TLS encryption to protect communication.

Characteristics:

- Encrypted communication
- Protects sensitive information
- Prevents data interception

Example:

https://example.com

---

# SSL/TLS

SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are security protocols used to encrypt communication between a client and a server.

Today, TLS has replaced SSL and is the standard protocol.

Benefits:

- Data Encryption
- Authentication
- Data Integrity

When you see the padlock icon in a browser, it indicates that the website is using HTTPS with SSL/TLS.

---

# Cookies

Cookies are small pieces of data stored by a website in the user's browser.

Purpose:

- Remember login information
- Store user preferences
- Maintain shopping carts
- Track user sessions

Example:

When you log into Gmail, a cookie keeps you logged in.

---

# Sessions

A Session stores user information on the server while the user is actively connected.

Unlike cookies, session data is not stored on the user's device.

Purpose:

- User authentication
- Session management
- Temporary data storage

---

# Cookies vs Sessions

| Cookies | Sessions |
|----------|----------|
| Stored on browser | Stored on server |
| Less secure | More secure |
| Can remain after browser closes | Usually ends when user logs out or session expires |

---

# Same-Origin Policy (SOP)

Same-Origin Policy is a browser security mechanism that prevents one website from accessing data belonging to another website.

Example:

A malicious website cannot directly access your Gmail data because of the Same-Origin Policy.

Purpose:

- Protect user information
- Prevent unauthorized access
- Reduce cross-site attacks

---

# Common Web Attacks

## 1. SQL Injection (SQLi)

An attacker inserts malicious SQL queries into application input fields.

Example:

Instead of entering a username, the attacker enters SQL commands to access the database.

Impact:

- Data theft
- Data modification
- Complete database compromise

Prevention:

- Prepared Statements
- Parameterized Queries
- Input Validation

---

## 2. Cross-Site Scripting (XSS)

XSS occurs when attackers inject malicious JavaScript into a website.

Types:

- Stored XSS
- Reflected XSS
- DOM-based XSS

Impact:

- Cookie theft
- Session hijacking
- Website defacement

Prevention:

- Input validation
- Output encoding
- Content Security Policy (CSP)

---

## 3. Cross-Site Request Forgery (CSRF)

CSRF tricks an authenticated user into performing actions without their knowledge.

Example:

A logged-in user unknowingly transfers money by clicking a malicious link.

Prevention:

- CSRF Tokens
- SameSite Cookies
- User Authentication

---

## 4. Clickjacking

An attacker hides malicious buttons beneath legitimate web pages.

Users unknowingly click on hidden elements.

Prevention:

- X-Frame-Options
- Content Security Policy

---

## 5. Broken Authentication

Occurs when authentication mechanisms are improperly implemented.

Examples:

- Weak passwords
- Predictable session IDs
- Poor session management

Prevention:

- Strong passwords
- MFA
- Secure session handling

---

# OWASP Top 10

OWASP (Open Worldwide Application Security Project) publishes the most critical web application security risks.

Some important risks include:

- Broken Access Control
- Cryptographic Failures
- Injection
- Insecure Design
- Security Misconfiguration
- Vulnerable Components
- Identification & Authentication Failures
- Software & Data Integrity Failures
- Logging & Monitoring Failures
- Server-Side Request Forgery (SSRF)

OWASP Top 10 is considered one of the most important references for web security professionals.

---

# Secure Coding Best Practices

- Validate all user input.
- Sanitize user data.
- Use HTTPS everywhere.
- Store passwords using secure hashing algorithms.
- Implement Multi-Factor Authentication.
- Keep software updated.
- Follow the Principle of Least Privilege.
- Perform regular security testing.

---

# 🌍 Real-Life Example

An online shopping website uses HTTPS, secure authentication, session management, and Web Application Firewalls (WAFs) to protect customer information.

Developers regularly test the application using OWASP Top 10 guidelines to identify and fix vulnerabilities before attackers can exploit them.

---

# 📌 Key Takeaways

- Web Security protects websites and web applications.
- HTTPS encrypts communication using TLS.
- Cookies store information in browsers.
- Sessions store user information on servers.
- SQL Injection targets databases.
- XSS injects malicious scripts.
- CSRF tricks users into performing unwanted actions.
- OWASP Top 10 provides the most common web security risks.

---

# ❓ Interview Questions

### 1. What is Web Security?

Web Security is the practice of protecting websites, web applications, users, and servers from cyber attacks.

---

### 2. Difference between HTTP and HTTPS?

HTTP sends data in plain text, while HTTPS encrypts communication using TLS.

---

### 3. What is SQL Injection?

SQL Injection is an attack where malicious SQL queries are inserted into application inputs to manipulate databases.

---

### 4. What is XSS?

Cross-Site Scripting is an attack where attackers inject malicious JavaScript into web pages.

---

### 5. What is CSRF?

Cross-Site Request Forgery tricks authenticated users into performing unwanted actions.

---

### 6. What is OWASP Top 10?

OWASP Top 10 is a list of the most critical web application security risks published by the Open Worldwide Application Security Project.

---

### 7. Difference between Cookies and Sessions?

Cookies are stored in the user's browser, while Sessions are stored on the server.

---

# 📝 Summary

Today I learned the fundamentals of Web Security, including HTTP vs HTTPS, SSL/TLS, Cookies, Sessions, Same-Origin Policy, common web attacks such as SQL Injection, XSS, and CSRF, and the OWASP Top 10 security risks. I also learned secure coding practices that help developers build secure web applications.
