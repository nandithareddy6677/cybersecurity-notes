# Day 12: Public Key Infrastructure (PKI), SSL & TLS

> Understanding Public Key Infrastructure (PKI), SSL/TLS protocols, digital certificates, Certificate Authorities (CAs), and how secure communication is established over the Internet.

---

# 🎯 Learning Objectives

- Understand Public Key Infrastructure (PKI).
- Learn how SSL and TLS work.
- Understand Digital Certificates.
- Learn Certificate Authorities (CA).
- Understand the SSL/TLS Handshake.
- Explore HTTPS communication.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Whenever you visit a secure website such as:

- https://google.com
- https://amazon.com
- https://bankofamerica.com

your browser establishes a secure encrypted connection before any information is exchanged.

This secure communication is possible because of:

- PKI
- SSL/TLS
- Digital Certificates
- Public Key Cryptography

Together, these technologies ensure that sensitive information remains confidential and protected.

---

# 🔐 What is PKI?

PKI stands for **Public Key Infrastructure**.

It is a framework that manages:

- Public Keys
- Private Keys
- Digital Certificates
- Certificate Authorities

PKI enables secure communication over insecure networks such as the Internet.

---

# Components of PKI

A Public Key Infrastructure consists of:

- Public Key
- Private Key
- Digital Certificate
- Certificate Authority (CA)
- Registration Authority (RA)

---

# Public Key

A Public Key is shared openly.

Anyone can use it to encrypt data.

---

# Private Key

A Private Key is secret.

Only the owner possesses it.

It is used to:

- Decrypt data
- Create Digital Signatures

Private Keys should never be shared.

---

# Digital Certificate

A Digital Certificate proves the identity of a website, server, or organization.

It contains:

- Domain Name
- Public Key
- Organization Name
- Certificate Authority
- Expiration Date
- Digital Signature

---

# Certificate Authority (CA)

A Certificate Authority is a trusted organization that issues Digital Certificates.

Examples:

- DigiCert
- Let's Encrypt
- GlobalSign
- Sectigo

Browsers trust certificates issued by recognized Certificate Authorities.

---

# Registration Authority (RA)

The Registration Authority verifies the identity of an organization before a certificate is issued.

The RA works together with the Certificate Authority.

---

# What is SSL?

SSL stands for **Secure Sockets Layer**.

SSL was the original protocol used to encrypt Internet communication.

Today, SSL has been replaced by TLS.

Although people still say "SSL Certificate," modern websites actually use TLS.

---

# What is TLS?

TLS stands for **Transport Layer Security**.

TLS is the modern protocol used to secure Internet communication.

TLS provides:

- Encryption
- Authentication
- Data Integrity

---

# SSL vs TLS

| SSL | TLS |
|------|------|
| Older protocol | Modern protocol |
| Less secure | More secure |
| Deprecated | Currently used |

Today, almost every secure website uses TLS.

---

# HTTPS

HTTPS stands for:

```
HyperText Transfer Protocol Secure
```

HTTPS combines:

- HTTP
- TLS Encryption

This protects communication between users and websites.

Example:

```
https://example.com
```

The padlock icon in the browser indicates a secure HTTPS connection.

---

# SSL/TLS Handshake

Before encrypted communication begins, the client and server perform a handshake.

```
Client

↓

Hello

↓

Server

↓

Certificate

↓

Key Exchange

↓

Session Key Created

↓

Encrypted Communication Begins
```

---

# Steps in the TLS Handshake

### Step 1

The client sends a "Client Hello" message.

---

### Step 2

The server responds with a "Server Hello."

---

### Step 3

The server sends its Digital Certificate.

---

### Step 4

The client verifies the certificate.

---

### Step 5

A session key is securely generated.

---

### Step 6

Encrypted communication begins.

---

# Why TLS is Important

TLS provides:

- Confidentiality
- Authentication
- Integrity

It protects users from:

- Eavesdropping
- Data Tampering
- Man-in-the-Middle Attacks

---

# Real-World Example

Suppose you log into your online banking account.

Before your password is sent:

- The website sends its Digital Certificate.
- Your browser verifies the certificate.
- TLS establishes an encrypted session.
- Your password is encrypted before transmission.

Even if someone intercepts the traffic, they cannot read your password.

---

# PKI in Cloud Computing

Cloud providers use PKI for:

- AWS IAM
- AWS Certificate Manager (ACM)
- Azure Key Vault
- Google Cloud Certificate Manager
- VPN Authentication
- HTTPS Load Balancers

---

# PKI in Cybersecurity

PKI is used for:

- Secure Websites
- VPN Authentication
- Secure Email
- Digital Signatures
- Code Signing
- Identity Verification

---

# 💡 Best Practices

- Always use HTTPS.
- Verify certificate validity.
- Protect private keys.
- Renew certificates before expiration.
- Disable outdated SSL versions.
- Use TLS 1.2 or TLS 1.3.

---

# 📌 Key Takeaways

- PKI manages certificates and encryption keys.
- Digital Certificates verify identity.
- Certificate Authorities issue trusted certificates.
- TLS encrypts Internet communication.
- HTTPS uses TLS.
- TLS Handshake establishes a secure connection.
- Modern websites use TLS instead of SSL.

---

# ❓ Interview Questions

### 1. What is PKI?

PKI is a framework that manages public keys, private keys, and digital certificates for secure communication.

---

### 2. What is the difference between SSL and TLS?

SSL is the older, deprecated protocol, while TLS is the modern and more secure protocol used today.

---

### 3. What is a Digital Certificate?

A Digital Certificate verifies the identity of a website or organization and contains its public key.

---

### 4. What is a Certificate Authority (CA)?

A Certificate Authority is a trusted organization that issues Digital Certificates.

---

### 5. What is HTTPS?

HTTPS is HTTP secured using TLS encryption.

---

### 6. Why is the TLS Handshake important?

It authenticates the server and establishes an encrypted session before communication begins.

---

### 7. Why should private keys be protected?

Anyone with the private key can decrypt sensitive data or impersonate the owner.

---

### 8. Which version should organizations use today?

TLS 1.2 or TLS 1.3.

---

# 📝 Summary

Today I learned about Public Key Infrastructure (PKI), SSL, TLS, and Digital Certificates. I explored how secure websites establish encrypted connections, the role of Certificate Authorities, the TLS Handshake process, and how HTTPS protects online communication. These technologies are fundamental to cybersecurity, cloud computing, online banking, secure APIs, and modern web applications.
