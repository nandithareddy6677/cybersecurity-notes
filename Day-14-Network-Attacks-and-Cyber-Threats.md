# Day 14: Network Attacks & Common Cyber Threats

> Understanding common cyber attacks, how attackers exploit networks, and the techniques organizations use to defend against them.

---

# 🎯 Learning Objectives

- Understand Network Attacks.
- Learn DoS and DDoS.
- Understand Man-in-the-Middle (MITM).
- Learn Spoofing.
- Understand Sniffing.
- Learn Session Hijacking.
- Understand Replay Attacks.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Every computer connected to the Internet faces potential cyber attacks.

Attackers constantly search for vulnerabilities to steal data, interrupt services, or gain unauthorized access.

Understanding these attacks is the first step toward defending against them.

---

# What is a Cyber Attack?

A Cyber Attack is an attempt to gain unauthorized access, disrupt services, steal information, or damage systems.

Common goals include:

- Data Theft
- Financial Gain
- Espionage
- Service Disruption

---

# DoS (Denial of Service)

A DoS attack overwhelms a target using a single attacking system.

Goal:

- Make the service unavailable.

Example:

One attacker sends millions of requests to a web server.

---

# DDoS (Distributed Denial of Service)

A DDoS attack uses thousands of compromised devices (Botnet) to attack one target.

Characteristics:

- Massive traffic
- Difficult to block
- Can take websites offline

---

# Botnet

A Botnet is a collection of infected computers controlled by an attacker.

Examples:

- Mirai
- Emotet

---

# Man-in-the-Middle (MITM)

An attacker secretly intercepts communication between two parties.

Example:

```
User

↓

Attacker

↓

Bank Server
```

The attacker can read or modify data.

---

# IP Spoofing

An attacker changes the source IP address to impersonate another device.

Used in:

- DDoS
- Bypassing filters

---

# MAC Spoofing

Changing the MAC address of a device.

Often used to bypass network restrictions.

---

# DNS Spoofing

Attackers redirect users to fake websites by manipulating DNS responses.

Example:

Typing:

```
www.bank.com
```

Opens a fake banking website.

---

# ARP Spoofing

The attacker sends fake ARP messages to redirect network traffic.

Often used for MITM attacks.

---

# Packet Sniffing

Packet Sniffing captures network traffic.

Tools:

- Wireshark
- tcpdump

Attackers may steal:

- Passwords
- Cookies
- Emails

---

# Session Hijacking

Attackers steal an active user session after login.

This allows them to access accounts without knowing the password.

---

# Replay Attack

An attacker captures valid network traffic and retransmits it later to gain unauthorized access.

---

# Password Attacks

Common types:

- Brute Force
- Dictionary Attack
- Credential Stuffing
- Password Spraying

---

# Social Engineering

Manipulating people instead of computers.

Examples:

- Phishing
- Vishing
- Smishing
- Pretexting
- Baiting

---

# Malware-Based Attacks

Examples:

- Virus
- Worm
- Trojan
- Spyware
- Ransomware
- Rootkit

---

# How Organizations Defend Against These Attacks

- Firewalls
- IDS/IPS
- VPN
- MFA
- Network Segmentation
- Antivirus
- Security Awareness Training

---

# 🌍 Real-Life Example

An attacker sends a phishing email that tricks an employee into entering credentials on a fake login page.

The attacker logs into the company VPN and steals confidential files.

This attack combines:

- Social Engineering
- Phishing
- Credential Theft

---

# 💡 Best Practices

- Use HTTPS.
- Enable MFA.
- Update systems regularly.
- Train employees.
- Monitor network traffic.
- Use strong passwords.

---

# 📌 Key Takeaways

- DoS uses one attacker.
- DDoS uses many compromised devices.
- MITM intercepts communication.
- Spoofing impersonates trusted devices.
- Sniffing captures network traffic.
- Session Hijacking steals active sessions.
- Phishing targets users rather than systems.

---

# ❓ Interview Questions

### 1. What is the difference between DoS and DDoS?

DoS uses one attacking system, while DDoS uses multiple compromised systems.

---

### 2. What is MITM?

A Man-in-the-Middle attack intercepts communication between two parties.

---

### 3. What is Packet Sniffing?

Capturing network traffic for analysis or malicious purposes.

---

### 4. What is ARP Spoofing?

Sending fake ARP messages to redirect network traffic.

---

### 5. What is Session Hijacking?

Taking control of an authenticated user session.

---

### 6. What is DNS Spoofing?

Redirecting users to fake websites by manipulating DNS responses.

---

### 7. What is a Botnet?

A network of infected devices controlled by an attacker.

---

### 8. Name three password attacks.

- Brute Force
- Dictionary Attack
- Credential Stuffing

---

# 📝 Summary

Today I learned about common cyber attacks including DoS, DDoS, MITM, spoofing, sniffing, session hijacking, replay attacks, password attacks, and social engineering. I also explored how organizations defend against these threats using firewalls, IDS/IPS, VPNs, MFA, and security awareness programs.
