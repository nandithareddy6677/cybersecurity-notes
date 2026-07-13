# Day 25: Email Security, SPF, DKIM & DMARC

> Understanding Email Security, common email-based attacks, authentication protocols (SPF, DKIM, DMARC), phishing prevention, and email protection techniques.

---

# 🎯 Learning Objectives

- Understand Email Security.
- Learn Email Threats.
- Understand SPF.
- Learn DKIM.
- Explore DMARC.
- Learn Secure Email Practices.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Email is one of the most widely used communication methods in organizations.

Unfortunately, it is also one of the most common attack vectors.

Cybercriminals use email to:

- Steal Credentials
- Spread Malware
- Deliver Ransomware
- Perform Business Email Compromise (BEC)
- Launch Phishing Attacks

Email Security protects users and organizations from these threats.

---

# 📧 What is Email Security?

Email Security protects email systems from unauthorized access, phishing, spam, malware, and spoofing attacks.

Objectives:

- Protect Confidential Information
- Prevent Email Spoofing
- Block Malware
- Detect Phishing

---

# Common Email Threats

- Spam
- Phishing
- Spear Phishing
- Whaling
- Malware Attachments
- Business Email Compromise (BEC)
- Email Spoofing

---

# Spam

Unwanted emails sent in bulk.

Examples:

- Advertisements
- Fake Offers
- Scams

---

# Phishing

Fake emails designed to steal sensitive information.

Example:

An attacker sends an email pretending to be your bank asking you to reset your password.

---

# Spear Phishing

Targeted phishing attacks aimed at a specific individual or organization.

---

# Whaling

Highly targeted phishing attacks against senior executives or high-profile individuals.

---

# Email Spoofing

The attacker forges the sender's email address to appear as a trusted source.

---

# SPF (Sender Policy Framework)

SPF verifies that an email is sent from an authorized mail server.

Benefits:

- Prevents sender spoofing.
- Improves email authenticity.

---

# DKIM (DomainKeys Identified Mail)

DKIM digitally signs outgoing emails.

The receiving server verifies that the message has not been modified.

Benefits:

- Ensures email integrity.
- Confirms authenticity.

---

# DMARC (Domain-based Message Authentication, Reporting & Conformance)

DMARC works with SPF and DKIM.

Functions:

- Verifies sender identity.
- Rejects suspicious emails.
- Generates authentication reports.

---

# Email Security Best Practices

- Enable SPF, DKIM, and DMARC.
- Use secure email gateways.
- Scan attachments.
- Train employees about phishing.
- Enable MFA.
- Avoid clicking suspicious links.

---

# Common Email Security Tools

- Microsoft Defender for Office 365
- Proofpoint
- Mimecast
- Cisco Secure Email
- Google Workspace Security

---

# 🌍 Real-Life Example

An attacker sends a fake email pretending to be Microsoft asking employees to verify their Office 365 password.

Because SPF, DKIM, and DMARC are properly configured, the receiving mail server rejects the spoofed email before it reaches users.

---

# 📌 Key Takeaways

- Email is one of the biggest attack vectors.
- SPF verifies sending servers.
- DKIM digitally signs emails.
- DMARC works with SPF and DKIM.
- Phishing remains the most common email attack.

---

# ❓ Interview Questions

### 1. What is SPF?

Sender Policy Framework verifies authorized email servers.

---

### 2. What is DKIM?

A protocol that digitally signs emails to verify integrity.

---

### 3. What is DMARC?

A protocol that works with SPF and DKIM to protect against email spoofing.

---

### 4. Difference between Phishing and Spear Phishing?

Phishing targets many users, while Spear Phishing targets specific individuals.

---

### 5. Name three common email attacks.

- Phishing
- Spam
- Email Spoofing

---

# 📝 Summary

Today I learned about Email Security, phishing attacks, spam, spoofing, and the authentication protocols SPF, DKIM, and DMARC. These technologies help organizations verify email authenticity, reduce phishing attacks, and improve email security.
