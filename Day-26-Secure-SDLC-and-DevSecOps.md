**# Day 26: Secure SDLC & DevSecOps

> Understanding the Secure Software Development Life Cycle (Secure SDLC), DevSecOps, secure coding practices, vulnerability scanning, and integrating security throughout software development.

---

# 🎯 Learning Objectives

- Understand SDLC.
- Learn Secure SDLC.
- Understand DevSecOps.
- Learn Secure Coding.
- Explore Security Testing.
- Prepare for cybersecurity interviews.

---

# 📖 Introduction

Building secure software requires more than testing at the end of development.

Security should be integrated into every stage of the Software Development Life Cycle (SDLC).

This approach is known as **Secure SDLC**, and when combined with DevOps, it becomes **DevSecOps**.

---

# 💻 What is SDLC?

The Software Development Life Cycle (SDLC) is a structured process used to develop software.

Typical phases:

- Planning
- Requirements
- Design
- Development
- Testing
- Deployment
- Maintenance

---

# What is Secure SDLC?

Secure SDLC integrates security activities into every phase of software development.

Benefits:

- Fewer vulnerabilities
- Lower remediation costs
- More secure applications

---

# Secure SDLC Phases

Planning

↓

Threat Modeling

↓

Secure Design

↓

Secure Coding

↓

Security Testing

↓

Deployment

↓

Continuous Monitoring

---

# Secure Coding

Developers should:

- Validate user input.
- Avoid hardcoded passwords.
- Handle errors securely.
- Use parameterized SQL queries.
- Store passwords using secure hashing.

---

# DevSecOps

DevSecOps integrates:

- Development
- Security
- Operations

Security becomes everyone's responsibility rather than only the security team's responsibility.

---

# Security Testing

Types:

- Static Application Security Testing (SAST)
- Dynamic Application Security Testing (DAST)
- Software Composition Analysis (SCA)
- Penetration Testing

---

# SAST

Analyzes source code without executing the application.

Finds coding vulnerabilities early.

---

# DAST

Tests running applications.

Identifies vulnerabilities during execution.

---

# Software Composition Analysis (SCA)

Scans third-party libraries and dependencies for known vulnerabilities.

---

# CI/CD Security

Continuous Integration and Continuous Deployment pipelines should include:

- Code Scanning
- Dependency Scanning
- Secret Detection
- Automated Testing

---

# Common DevSecOps Tools

- SonarQube
- Snyk
- OWASP Dependency Check
- Trivy
- GitHub Advanced Security
- Checkmarx

---

# Benefits of DevSecOps

- Early vulnerability detection.
- Faster software delivery.
- Automated security testing.
- Reduced security risks.
- Continuous compliance.

---

# 🌍 Real-Life Example

A developer accidentally includes an outdated open-source library.

During the CI/CD pipeline, SCA detects the vulnerable dependency.

The deployment is stopped until the issue is fixed.

---

# 📌 Key Takeaways

- Secure SDLC integrates security into software development.
- DevSecOps combines development, security, and operations.
- SAST analyzes source code.
- DAST analyzes running applications.
- CI/CD pipelines should include automated security testing.

---

# ❓ Interview Questions

### 1. What is Secure SDLC?

A software development process that integrates security into every phase.

---

### 2. What is DevSecOps?

The practice of integrating security into DevOps processes.

---

### 3. Difference between SAST and DAST?

SAST analyzes source code, while DAST tests running applications.

---

### 4. What is Software Composition Analysis?

Scanning third-party dependencies for known vulnerabilities.

---

### 5. Name three DevSecOps tools.

- SonarQube
- Snyk
- Trivy

---

# 📝 Summary

Today I learned about Secure SDLC and DevSecOps. I explored secure coding practices, security testing methods such as SAST, DAST, and SCA, CI/CD security, and DevSecOps tools. Integrating security into every stage of software development helps organizations build secure, reliable, and resilient applications.**
