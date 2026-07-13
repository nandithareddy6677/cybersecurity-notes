# Day 11: Cryptography Fundamentals

> Understanding the fundamentals of Cryptography, encryption techniques, hashing, digital signatures, certificates, and their role in protecting modern computer systems and networks.

---

# 🎯 Learning Objectives

- Understand Cryptography.
- Learn Encryption and Decryption.
- Differentiate Symmetric and Asymmetric Encryption.
- Understand Hashing.
- Learn Digital Signatures.
- Understand Digital Certificates.
- Explore real-world cybersecurity applications.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Imagine sending your bank password over the Internet as plain text.

Anyone intercepting the communication could read your password instantly.

Cryptography prevents this by converting readable information into an unreadable format.

Only authorized users possessing the correct key can recover the original information.

Today, almost every secure website, banking application, cloud platform, messaging application, and VPN depends on cryptography.

---

# 🔐 What is Cryptography?

Cryptography is the science of protecting information by converting readable data into an unreadable format.

Its objectives are:

- Confidentiality
- Integrity
- Authentication
- Non-Repudiation

These four principles form the foundation of secure communication.

---

# Important Terminology

## Plaintext

Original readable information.

Example

```
Password123
```

---

## Ciphertext

Encrypted unreadable information.

Example

```
7FkA@9#LmQ2%
```

---

## Encryption

The process of converting Plaintext into Ciphertext.

```
Plaintext

↓

Encryption Algorithm

↓

Ciphertext
```

---

## Decryption

The process of converting Ciphertext back into Plaintext.

```
Ciphertext

↓

Decryption Key

↓

Plaintext
```

---

# Why is Cryptography Important?

Cryptography protects:

- Online Banking
- UPI Transactions
- Passwords
- Email Communication
- Cloud Storage
- VPN Connections
- Government Systems
- Military Communication

Without cryptography, secure communication on the Internet would not exist.

---

# Types of Cryptography

There are two major encryption methods.

- Symmetric Encryption
- Asymmetric Encryption

---

# Symmetric Encryption

Symmetric Encryption uses the **same key** for both encryption and decryption.

```
Plaintext

↓

Encryption Key

↓

Ciphertext

↓

Same Key

↓

Plaintext
```

### Advantages

- Fast
- Efficient
- Suitable for large files

### Disadvantages

- Secure key sharing is difficult.

### Examples

- AES
- DES
- 3DES

AES is currently the industry standard.

---

# Asymmetric Encryption

Asymmetric Encryption uses **two keys**.

- Public Key
- Private Key

```
Public Key

↓

Encrypt

↓

Ciphertext

↓

Private Key

↓

Decrypt
```

### Advantages

- Secure key exchange
- Digital Signatures
- Authentication

### Disadvantages

- Slower than symmetric encryption

### Examples

- RSA
- ECC

---

# Symmetric vs Asymmetric Encryption

| Symmetric | Asymmetric |
|------------|------------|
| One Key | Two Keys |
| Faster | Slower |
| Used for bulk data | Used for secure key exchange |
| AES | RSA |

---

# What is Hashing?

Hashing converts data into a fixed-length value called a Hash.

Unlike encryption, hashing **cannot be reversed**.

Example

```
Password123

↓

SHA-256

↓

8d969eef6ecad3c29...
```

---

# Characteristics of Hash Functions

- One-way process
- Fixed output length
- Fast computation
- Detects data modification
- Cannot be decrypted

---

# Popular Hash Algorithms

- MD5 (Outdated)
- SHA-1 (Deprecated)
- SHA-256
- SHA-512

SHA-256 is widely used today.

---

# Why Hashing is Used

- Password Storage
- File Integrity
- Blockchain
- Digital Signatures
- Data Verification

---

# Digital Signature

A Digital Signature verifies:

- Identity
- Authenticity
- Integrity

```
Sender

↓

Private Key

↓

Digital Signature

↓

Receiver

↓

Public Key

↓

Verification
```

---

# Digital Certificate

A Digital Certificate proves that a website or organization is genuine.

Certificates are issued by:

- Certificate Authorities (CA)

Examples

- DigiCert
- Let's Encrypt
- GlobalSign

---

# HTTPS

HTTPS combines:

- HTTP
- SSL/TLS Encryption

This protects communication between users and websites.

Example

```
https://
```

The padlock icon in browsers indicates encrypted communication.

---

# Real-World Example

When you log into your online banking account:

- HTTPS encrypts communication.
- RSA securely exchanges keys.
- AES encrypts session data.
- SHA-256 verifies integrity.
- Digital Certificates verify the website.

All these cryptographic technologies work together behind the scenes.

---

# Cryptography in Cloud Computing

Cloud providers use cryptography for:

- Data at Rest Encryption
- Data in Transit Encryption
- AWS KMS
- Azure Key Vault
- Google Cloud KMS
- IAM Authentication

---

# Cryptography in Cybersecurity

Used for:

- VPN
- Secure Email
- Authentication
- SSL/TLS
- Password Storage
- Malware Detection
- Digital Forensics

---

# 💡 Best Practices

- Use strong encryption algorithms.
- Never store passwords in plain text.
- Use SHA-256 or stronger hashing algorithms.
- Use HTTPS for websites.
- Protect private keys carefully.
- Regularly update cryptographic protocols.

---

# 📌 Key Takeaways

- Cryptography protects information.
- Encryption converts plaintext into ciphertext.
- Decryption restores original data.
- Symmetric encryption uses one key.
- Asymmetric encryption uses two keys.
- Hashing is irreversible.
- Digital Signatures verify authenticity.
- Digital Certificates establish trust.

---

# ❓ Interview Questions

### 1. What is Cryptography?

Cryptography is the science of protecting information through encryption and other security techniques.

---

### 2. What is the difference between Encryption and Hashing?

Encryption is reversible using a key, whereas hashing is a one-way process that cannot be reversed.

---

### 3. What is Symmetric Encryption?

Symmetric Encryption uses the same key for encryption and decryption.

---

### 4. What is Asymmetric Encryption?

Asymmetric Encryption uses a public key for encryption and a private key for decryption.

---

### 5. Which algorithm is commonly used for symmetric encryption?

AES.

---

### 6. Which algorithm is commonly used for asymmetric encryption?

RSA.

---

### 7. Why are passwords hashed instead of encrypted?

Hashing is irreversible, making stored passwords more secure.

---

### 8. What is a Digital Signature?

A Digital Signature verifies the authenticity and integrity of digital information.

---

# 📝 Summary

Today I learned the fundamentals of Cryptography, one of the most important concepts in cybersecurity. I explored encryption, decryption, symmetric and asymmetric encryption, hashing, digital signatures, digital certificates, and HTTPS. These technologies protect online communication, banking systems, cloud services, and sensitive information by ensuring confidentiality, integrity, authentication, and non-repudiation.
