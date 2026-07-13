# Day 28: Threat Intelligence, IOC, IOA, STIX & TAXII

> Understanding Cyber Threat Intelligence, Indicators of Compromise (IOC), Indicators of Attack (IOA), STIX, TAXII, threat feeds, and proactive cyber defense.

---

# 🎯 Learning Objectives

- Understand Threat Intelligence.
- Learn IOC and IOA.
- Explore Threat Intelligence Lifecycle.
- Understand STIX and TAXII.
- Learn Threat Hunting.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Cyber attacks evolve every day.

Organizations must stay informed about:

- New Malware
- Emerging Threats
- Attacker Techniques
- Vulnerabilities

Threat Intelligence helps organizations prepare for attacks before they occur.

---

# 🛡️ What is Threat Intelligence?

Threat Intelligence is the collection, analysis, and sharing of information about cyber threats.

Objectives:

- Detect threats early.
- Improve defenses.
- Reduce attack impact.

---

# Threat Intelligence Lifecycle

```
Planning

↓

Collection

↓

Processing

↓

Analysis

↓

Dissemination

↓

Feedback
```

---

# Types of Threat Intelligence

## Strategic Intelligence

Focuses on business risks and long-term trends.

Audience:

- Executives
- Management

---

## Tactical Intelligence

Focuses on attacker techniques and tactics.

Audience:

- SOC Teams
- Security Analysts

---

## Operational Intelligence

Provides information about ongoing attacks.

Audience:

- Incident Response Teams

---

## Technical Intelligence

Includes:

- Malicious IP Addresses
- Domains
- File Hashes
- URLs

---

# IOC (Indicator of Compromise)

An IOC is evidence that a system may already be compromised.

Examples:

- Malicious IP Address
- File Hash
- Suspicious Domain
- Registry Changes
- Unusual Network Traffic

---

# IOA (Indicator of Attack)

An IOA identifies attacker behavior before an attack is completed.

Examples:

- Privilege Escalation
- Credential Dumping
- Lateral Movement
- Suspicious PowerShell Execution

---

# IOC vs IOA

| IOC | IOA |
|------|------|
| Evidence after compromise | Detects attacker behavior |
| Reactive | Proactive |
| File Hashes | Suspicious Activities |
| IP Addresses | Attack Techniques |

---

# Threat Hunting

Threat Hunting is the proactive search for hidden threats that automated tools may miss.

Threat Hunters use:

- SIEM
- EDR
- Threat Intelligence
- MITRE ATT&CK

---

# STIX

STIX stands for:

Structured Threat Information Expression.

It is a standardized format for sharing cyber threat intelligence.

---

# TAXII

TAXII stands for:

Trusted Automated Exchange of Intelligence Information.

It enables organizations to automatically exchange threat intelligence.

---

# MITRE ATT&CK

Threat Intelligence often uses the MITRE ATT&CK framework to map attacker tactics and techniques.

Examples:

- Initial Access
- Persistence
- Credential Access
- Lateral Movement
- Exfiltration

---

# Threat Intelligence Sources

- VirusTotal
- AlienVault OTX
- MISP
- CISA Advisories
- Microsoft Threat Intelligence
- Cisco Talos

---

# 🌍 Real-Life Example

A Threat Intelligence feed reports a malicious IP address used in ransomware attacks.

The organization's firewall blocks the IP.

The SIEM searches logs for previous communication with that IP.

The SOC investigates affected systems before damage occurs.

---

# 💡 Best Practices

- Use trusted threat feeds.
- Automate IOC ingestion.
- Perform regular threat hunting.
- Correlate intelligence with SIEM alerts.
- Update detection rules frequently.

---

# 📌 Key Takeaways

- Threat Intelligence improves proactive defense.
- IOC indicates compromise.
- IOA indicates attacker behavior.
- STIX standardizes intelligence sharing.
- TAXII automates intelligence exchange.
- Threat Hunting searches for hidden threats.

---

# ❓ Interview Questions

### 1. What is Threat Intelligence?

Threat Intelligence is information about cyber threats used to improve security.

---

### 2. What is an IOC?

Evidence indicating that a system may have been compromised.

---

### 3. What is an IOA?

Evidence of attacker behavior before compromise is completed.

---

### 4. Difference between IOC and IOA?

IOC identifies compromise after an attack, while IOA detects attacker behavior during an attack.

---

### 5. What is STIX?

A standardized language for sharing cyber threat intelligence.

---

### 6. What is TAXII?

A protocol for automatically exchanging cyber threat intelligence.

---

### 7. What is Threat Hunting?

The proactive search for hidden threats within an organization's environment.

---

### 8. Name three Threat Intelligence sources.

- VirusTotal
- AlienVault OTX
- CISA Advisories

---

# 📝 Summary

Today I learned about Threat Intelligence and how organizations use threat data to improve security. I explored the Threat Intelligence Lifecycle, Indicators of Compromise (IOC), Indicators of Attack (IOA), STIX, TAXII, MITRE ATT&CK, and Threat Hunting. These concepts help organizations detect attacks earlier, respond more effectively, and strengthen their overall cybersecurity posture.
