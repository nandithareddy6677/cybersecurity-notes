# Day 2 - Multi-Factor Authentication (MFA) and Access Control

## What is Authentication?

Authentication means verifying the identity of a user.

It answers the question:

"Who are you?"

Examples:
- Password
- PIN
- Fingerprint
- Face ID
- OTP

---

## Problem with Passwords

Passwords can be:
- guessed
- stolen
- leaked
- reused

If a hacker gets your password, they may access your account.

---

## What is MFA?

MFA stands for Multi-Factor Authentication.

It requires more than one method of verification before granting access.

Example:

Step 1:
Password

Step 2:
OTP sent to your phone

Only after both are correct can you log in.

---

## Three Authentication Factors

### 1. Something You Know

Examples:
- Password
- PIN

### 2. Something You Have

Examples:
- Mobile phone
- OTP
- Security token

### 3. Something You Are

Examples:
- Fingerprint
- Face recognition
- Retina scan

---

## Why MFA is Important

Benefits:

- Stronger security
- Protects stolen passwords
- Reduces phishing impact
- Prevents unauthorized access

Example:

Even if a hacker knows your Gmail password,
they cannot log in without your OTP.

---

## What is Access Control?

Access Control determines:

"What can a user access?"

Not every user should have the same permissions.

Example:

Student:
- View marks

Teacher:
- Enter marks

Principal:
- Manage all records

Different users have different access levels.

---

## Principle of Least Privilege (PoLP)

Definition:

Users should receive only the permissions they need to perform their job.

Nothing more.

---

## Example

HR Employee:

Allowed:
- Employee records

Not Allowed:
- Server configuration

This follows the Principle of Least Privilege.

---

## Why Least Privilege is Important

Benefits:

- Reduces damage if an account is hacked
- Improves security
- Limits unauthorized actions

Example:

A normal employee account is hacked.

Because it has limited permissions,
the attacker cannot control the entire company system.

---

## Key Points

- Authentication = Who are you?
- Authorization = What can you access?
- MFA = Multiple verification methods
- Access Control = Controls permissions
- Least Privilege = Minimum permissions required
