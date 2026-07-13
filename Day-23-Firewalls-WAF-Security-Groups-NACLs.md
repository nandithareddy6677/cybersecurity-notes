# Day 23: Firewalls, WAF, Security Groups & Network ACLs

> Understanding Firewalls, Web Application Firewalls (WAF), Network Firewalls, AWS Security Groups, Network ACLs, and how they protect cloud infrastructure.

---

# 🎯 Learning Objectives

- Understand Firewalls.
- Learn Packet Filtering.
- Understand Stateful vs Stateless Firewalls.
- Learn Web Application Firewall (WAF).
- Understand AWS Security Groups.
- Learn Network ACLs.
- Prepare for cloud interviews.

---

# 📖 Introduction

Every organization connected to the Internet needs protection from unauthorized access.

Firewalls act as the first line of defense by inspecting and filtering network traffic.

Cloud providers also provide virtual firewalls to secure cloud resources.

---

# 🔥 What is a Firewall?

A Firewall is a security device or software that monitors and controls incoming and outgoing network traffic based on predefined security rules.

Its primary purpose is to:

- Allow legitimate traffic
- Block malicious traffic
- Protect systems from unauthorized access

---

# Types of Firewalls

- Packet Filtering Firewall
- Stateful Firewall
- Proxy Firewall
- Next Generation Firewall (NGFW)
- Web Application Firewall (WAF)

---

# Packet Filtering Firewall

Filters traffic using:

- Source IP
- Destination IP
- Port Number
- Protocol

Fast but limited.

---

# Stateful Firewall

Tracks active network connections.

Advantages:

- Better security
- Intelligent filtering
- Understands connection state

---

# Next Generation Firewall (NGFW)

Provides advanced protection.

Features:

- Deep Packet Inspection
- Intrusion Prevention (IPS)
- Malware Detection
- Application Control
- SSL Inspection

Examples:

- Palo Alto
- Fortinet
- Cisco Firepower

---

# Web Application Firewall (WAF)

Protects web applications from HTTP/HTTPS attacks.

Common attacks blocked:

- SQL Injection
- Cross-Site Scripting (XSS)
- File Inclusion
- Cross-Site Request Forgery (CSRF)

Example:

AWS WAF

---

# AWS Security Groups

Security Groups act as virtual firewalls for EC2 instances.

Characteristics:

- Stateful
- Instance Level
- Allow Rules Only
- Default: Deny All Inbound

Example:

```
Inbound

HTTPS 443 → Allow

SSH 22 → Allow

Everything Else → Block
```

---

# Network ACL (NACL)

Network ACL protects an entire subnet.

Characteristics:

- Stateless
- Allow & Deny Rules
- Subnet Level

---

# Security Group vs NACL

| Security Group | Network ACL |
|---------------|-------------|
| Stateful | Stateless |
| Instance Level | Subnet Level |
| Allow Rules Only | Allow & Deny Rules |
| More Secure | Extra Network Layer |

---

# Firewall Rules

Common Rules:

- Allow HTTP (80)
- Allow HTTPS (443)
- Allow SSH (22)
- Block Telnet (23)

---

# Defense in Depth

Organizations use multiple layers:

Internet

↓

Firewall

↓

WAF

↓

IDS/IPS

↓

Application

↓

Database

---

# Cloud Firewall Best Practices

- Allow only required ports.
- Block unused services.
- Restrict SSH access.
- Use WAF for websites.
- Monitor firewall logs.
- Review firewall rules regularly.

---

# 🌍 Real-Life Example

An e-commerce website is hosted on AWS.

Security Group:

- Allows HTTP and HTTPS.
- Blocks all unnecessary ports.

AWS WAF:

- Blocks SQL Injection.
- Blocks XSS attacks.

Network ACL:

- Restricts suspicious IP addresses.

Together they provide multiple layers of security.

---

# 📌 Key Takeaways

- Firewalls filter network traffic.
- WAF protects web applications.
- Security Groups are stateful.
- NACLs are stateless.
- Firewalls are essential for cloud security.

---

# ❓ Interview Questions

### 1. What is a Firewall?

A Firewall monitors and filters network traffic based on security rules.

---

### 2. What is WAF?

A Web Application Firewall protects web applications from HTTP attacks.

---

### 3. Difference between Security Groups and NACL?

Security Groups are stateful and instance-level, while NACLs are stateless and subnet-level.

---

### 4. Which AWS service protects web applications?

AWS WAF.

---

### 5. What is an NGFW?

A Next Generation Firewall provides advanced inspection and threat prevention.

---

# 📝 Summary

Today I learned about Firewalls, WAF, Security Groups, and Network ACLs. These technologies protect cloud infrastructure by filtering network traffic, securing applications, and preventing unauthorized access. Understanding these concepts is essential for cloud engineers and cybersecurity professionals.
