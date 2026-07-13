# Day 18: Security Operations Center (SOC) & SIEM

> Understanding the Security Operations Center (SOC), Security Information and Event Management (SIEM), security monitoring, threat detection, and incident response in modern organizations.

---

# 🎯 Learning Objectives

- Understand the Security Operations Center (SOC).
- Learn SOC Roles and Responsibilities.
- Understand SIEM.
- Learn Log Management.
- Explore Threat Detection.
- Learn SOC Workflow.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Modern organizations generate millions of security events every day.

Examples include:

- Login Attempts
- Firewall Logs
- Antivirus Alerts
- VPN Connections
- Cloud Activity
- Web Server Logs

Monitoring these events manually is impossible.

To solve this problem, organizations use a **Security Operations Center (SOC)** and **SIEM Platforms**.

---

# 🏢 What is a Security Operations Center (SOC)?

A Security Operations Center (SOC) is a centralized team responsible for monitoring, detecting, investigating, and responding to cybersecurity threats 24/7.

Its main objective is to protect an organization's IT infrastructure from cyber attacks.

---

# Responsibilities of a SOC

- Monitor Security Events
- Detect Threats
- Investigate Alerts
- Respond to Incidents
- Perform Threat Hunting
- Improve Security Controls
- Generate Reports

---

# SOC Team Structure

## SOC Analyst Level 1 (L1)

Responsibilities:

- Monitor dashboards
- Review alerts
- Escalate incidents
- Perform initial investigations

---

## SOC Analyst Level 2 (L2)

Responsibilities:

- Investigate incidents
- Perform malware analysis
- Analyze logs
- Contain attacks

---

## SOC Analyst Level 3 (L3)

Responsibilities:

- Advanced Threat Hunting
- Incident Response
- Digital Forensics
- Security Improvements

---

## SOC Manager

Responsibilities:

- Manage SOC Team
- Define Security Policies
- Coordinate Incident Response
- Report to Management

---

# 📊 What is SIEM?

SIEM stands for:

**Security Information and Event Management**

A SIEM platform collects, stores, analyzes, and correlates logs from multiple systems.

Its purpose is to detect suspicious activities automatically.

---

# Why is SIEM Important?

Without SIEM:

- Logs remain scattered.
- Threats are difficult to detect.
- Incident investigation becomes slow.

With SIEM:

- Centralized Monitoring
- Faster Detection
- Automated Alerts
- Better Visibility

---

# How SIEM Works

```
Servers

↓

Firewalls

↓

Routers

↓

Applications

↓

Cloud Services

↓

SIEM Platform

↓

Correlation Rules

↓

Alerts

↓

SOC Analysts
```

---

# Log Sources

A SIEM collects logs from:

- Windows Systems
- Linux Servers
- Firewalls
- IDS/IPS
- VPN Servers
- AWS
- Azure
- Active Directory
- Databases
- Antivirus Software

---

# Log Management

SIEM performs:

- Log Collection
- Log Storage
- Log Normalization
- Log Correlation
- Alert Generation

---

# Event Correlation

A SIEM combines multiple security events to identify suspicious behavior.

Example:

```
5 Failed Logins

↓

Successful Login

↓

Large File Download

↓

Alert Generated
```

---

# Threat Detection

SIEM identifies:

- Brute Force Attacks
- Malware Activity
- Unauthorized Access
- Privilege Escalation
- Data Exfiltration
- Insider Threats

---

# Common SIEM Platforms

- Splunk
- IBM QRadar
- Microsoft Sentinel
- Elastic SIEM
- ArcSight
- LogRhythm
- Wazuh

---

# Threat Hunting

Threat Hunting is the proactive search for hidden threats that automated tools may not detect.

Threat Hunters:

- Analyze Logs
- Search for Indicators of Compromise (IOCs)
- Investigate Suspicious Activity

---

# SOC Workflow

```
Security Event

↓

SIEM Alert

↓

SOC Analyst Review

↓

Investigation

↓

Containment

↓

Recovery

↓

Report
```

---

# SIEM in Cloud Computing

Cloud platforms integrate with SIEM solutions.

Examples:

AWS

- CloudTrail
- GuardDuty
- Security Hub

Azure

- Microsoft Sentinel

Google Cloud

- Security Command Center

---

# 🌍 Real-Life Example

A hacker attempts to brute-force an employee's VPN account.

The VPN server logs multiple failed login attempts.

The SIEM detects abnormal login activity.

An alert is sent to the SOC.

The SOC Analyst investigates and temporarily locks the account before unauthorized access occurs.

---

# 💡 Best Practices

- Monitor systems 24/7.
- Centralize log collection.
- Regularly review SIEM rules.
- Automate alerting.
- Retain logs securely.
- Continuously update threat intelligence.

---

# 📌 Key Takeaways

- SOC monitors organizational security.
- SIEM centralizes security logs.
- SIEM correlates events to detect threats.
- SOC Analysts investigate alerts.
- Threat Hunting proactively searches for hidden attacks.
- Cloud platforms integrate with SIEM solutions.

---

# ❓ Interview Questions

### 1. What is a SOC?

A Security Operations Center (SOC) is a team responsible for monitoring, detecting, investigating, and responding to cybersecurity incidents.

---

### 2. What does SIEM stand for?

Security Information and Event Management.

---

### 3. What is the purpose of SIEM?

To collect, analyze, correlate, and monitor security logs from multiple sources.

---

### 4. Name three SIEM tools.

- Splunk
- IBM QRadar
- Microsoft Sentinel

---

### 5. What is Event Correlation?

The process of combining multiple security events to detect suspicious activity.

---

### 6. What is Threat Hunting?

The proactive search for hidden threats within an organization's environment.

---

### 7. Name two AWS security services used with SIEM.

- AWS CloudTrail
- AWS GuardDuty

---

### 8. What is the role of an L1 SOC Analyst?

Monitor alerts, perform initial investigations, and escalate incidents when necessary.

---

# 📝 Summary

Today I learned about the Security Operations Center (SOC) and Security Information and Event Management (SIEM). I explored SOC roles, SIEM architecture, log collection, event correlation, threat detection, threat hunting, and common SIEM platforms such as Splunk and Microsoft Sentinel. These technologies help organizations continuously monitor security events, detect cyber threats, and respond to incidents effectively.
