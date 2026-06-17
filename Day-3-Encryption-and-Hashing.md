# Day 3 - Encryption and Hashing

## What is Encryption?

Encryption is the process of converting readable data into unreadable data.

The purpose is to protect information from unauthorized access.

Only authorized users can convert the encrypted data back into its original form.

---

## Example

Original Message:

Hello Nanditha

Encrypted Message:

X7#A9!P@2

The encrypted text is called Ciphertext.

The original readable text is called Plaintext.

---

## Why Encryption is Important

Encryption protects:

- Passwords
- Banking information
- Personal messages
- Company data
- Government data

Without encryption, attackers could read sensitive information.

---

## Key Terms

### Plaintext

Original readable information.

Example:

Hello World

---

### Ciphertext

Encrypted unreadable information.

Example:

J7#P@X9L

---

### Encryption Key

A secret value used to encrypt and decrypt data.

Think of it as a special key for a lock.

---

## Types of Encryption

### 1. Symmetric Encryption

Uses the SAME key for:

- Encryption
- Decryption

Example:

Key = ABC123

Sender uses ABC123 to encrypt.

Receiver uses ABC123 to decrypt.

---

### Advantages

- Fast
- Efficient

### Disadvantages

- Sharing the key securely can be difficult

---

## 2. Asymmetric Encryption

Uses TWO keys:

### Public Key

Used for encryption.

Can be shared with everyone.

---

### Private Key

Used for decryption.

Must be kept secret.

---

## Example

You lock a box using a public key.

Only the private key can unlock it.

---

### Advantages

- More secure key management

### Disadvantages

- Slower than symmetric encryption

---

## Real-Life Example

HTTPS websites use encryption.

When you open:

https://www.google.com

Your communication is encrypted.

This prevents attackers from reading your data.

---

# What is Hashing?

Hashing is different from encryption.

Hashing converts data into a fixed-length value.

Hashing is a one-way process.

You cannot easily convert it back.

---

## Example

Password:

Nanditha123

Hash Value:

5f4dcc3b5aa765d61d8327deb882cf99

The hash looks completely different.

---

## Why Hashing is Used

Hashing is commonly used for:

- Password storage
- Data verification
- Digital signatures

---

## Password Example

When you create a Gmail password:

The password itself is usually not stored directly.

Instead, the hash value is stored.

If a hacker steals the database,
they will see hashes instead of actual passwords.

---

## Difference Between Encryption and Hashing

Encryption:
- Can be decrypted
- Protects data during communication

Hashing:
- One-way process
- Used for verification and password storage

---

## Digital Signatures

Digital signatures help verify:

- Identity
- Authenticity
- Integrity

They prove that data was not modified.

---

## Real-World Uses of Encryption

- WhatsApp Messages
- Online Banking
- Gmail
- E-Commerce Websites
- Cloud Storage

---

## Key Points

- Encryption protects data from unauthorized access.
- Plaintext is readable data.
- Ciphertext is encrypted data.
- Symmetric encryption uses one key.
- Asymmetric encryption uses two keys.
- Hashing is a one-way process.
- Passwords are usually stored as hashes.
- HTTPS uses encryption.
