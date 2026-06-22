# Cybersecurity Fundamentals Lab

## Overview

This repository contains solutions and practical activities completed during a Cybersecurity Fundamentals workshop. The exercises cover Linux basics, ethical hacking methodology, vulnerability assessment, CVSS prioritization, SQL Injection, phishing awareness, and security risk analysis.

The goal of this lab is to introduce core cybersecurity concepts and demonstrate how security professionals identify risks, analyze threats, and recommend appropriate defenses.

---

## Learning Objectives

By completing these activities, participants learn how to:

* Use basic Linux commands
* Understand the Ethical Hacking lifecycle
* Differentiate between vulnerabilities and exploits
* Prioritize risks using CVSS severity levels
* Understand web application architecture
* Identify SQL Injection weaknesses
* Recognize phishing and social engineering attacks
* Map system assets, threats, vulnerabilities, and defenses
* Apply basic risk assessment principles

---

# Concepts Covered

## Linux Fundamentals

Linux is widely used in cybersecurity because it provides powerful command-line tools for system administration, penetration testing, monitoring, and automation.

### Commands Practiced

| Command | Purpose                    |
| ------- | -------------------------- |
| whoami  | Display current user       |
| pwd     | Display current directory  |
| ls      | List files and directories |
| cd      | Change directory           |
| touch   | Create an empty file       |
| mkdir   | Create a directory         |
| cat     | Display file content       |
| nano    | Edit text files            |

---

## Ethical Hacking Process

Ethical hacking follows a structured methodology:

1. Reconnaissance
2. Scanning
3. Gaining Access
4. Maintaining Access
5. Covering Tracks and Reporting

### Ethical vs Malicious Hacking

Ethical hackers work with authorization to improve security, while malicious hackers operate without permission and attempt to cause damage or steal information.

---

## Vulnerabilities and Exploits

### Vulnerability

A weakness in a system that could be abused by an attacker.

Examples:

* Weak passwords
* Poor input validation
* Excessive permissions
* Unpatched software

### Exploit

A technique or method used to take advantage of a vulnerability.

Examples:

* SQL Injection
* Credential Theft
* Account Takeover
* Privilege Abuse

---

## CVSS Risk Prioritization

CVSS (Common Vulnerability Scoring System) helps security teams prioritize vulnerabilities based on severity.

### Severity Levels

| Severity | Description               |
| -------- | ------------------------- |
| Low      | Limited impact            |
| Medium   | Moderate risk             |
| High     | Serious security issue    |
| Critical | Immediate action required |

---

## Web Application Architecture

Typical web applications follow the flow:

Browser → Front-End → Back-End → Database

### Components

* Login Page
* Student Dashboard
* Teacher Dashboard
* Admin Account
* Student Records
* Messages
* File Upload
* Server Logs

### Responsibilities

#### Front-End

Handles user interaction and presentation.

#### Back-End

Processes requests, business logic, and communication with the database.

#### Database

Stores application data and records.

---

## SQL Injection

SQL Injection occurs when user input is not properly validated and becomes part of a database query.

### Potential Impact

* Authentication bypass
* Data theft
* Data modification
* Unauthorized access

### Defense

* Parameterized Queries
* Input Validation
* Least Privilege Access

---

## Social Engineering and Phishing

Social engineering manipulates people into revealing sensitive information.

### Common Techniques

* Authority
* Urgency
* Scarcity
* Reciprocity
* Social Proof
* Curiosity

### Phishing Types

* Phishing
* Spear Phishing
* Whaling
* Smishing
* Vishing

### Safety Rule

Always verify the sender before clicking links or sharing sensitive information.

---

# Activities

## Challenge 1 — Linux Command Match

Practiced basic Linux commands and their cybersecurity applications.

### Key Takeaway

Linux command-line skills are essential for security professionals.

---

## Challenge 2 — Ethical Hacking Process

Identified and arranged the phases of an ethical hacking engagement.

### Key Takeaway

Security testing must follow a structured and authorized process.

---

## Challenge 3 — Vulnerability, Exploit, and CVSS

Classified vulnerabilities and exploits and ranked risks based on severity.

### Key Takeaway

Not all vulnerabilities have the same impact; prioritization matters.

---

## Challenge 4 — Web Application and SQL Injection

Analyzed web application architecture and identified SQL Injection risks.

### Key Takeaway

User input should never be trusted without validation.

---

## Challenge 5 — Social Engineering and Phishing

Matched social engineering tactics and classified phishing attacks.

### Key Takeaway

Human behavior is often the easiest attack surface.

---

## Activity 1 — Security Review Summary

Reviewed:

* Linux Commands
* Ethical Hacking Lifecycle
* Vulnerability Assessment
* CVSS Ranking
* SQL Injection Defenses
* Phishing Awareness

---

## Activity 2 — Mini Security Map

### System Flow

Browser → Login Page → Front-End → Back-End → Database

### Supporting Components

* Student Records
* Admin Account
* Server Logs
* Student Dashboard
* Teacher Dashboard
* Messages
* File Upload

### Selected Weak Points

| Weakness              | Type          |
| --------------------- | ------------- |
| Weak Admin Password   | Human         |
| Poor Input Validation | Technical     |
| No Log Monitoring     | Configuration |

### Attack Mapping

| Weakness              | Attack           |
| --------------------- | ---------------- |
| Poor Input Validation | SQL Injection    |
| Weak Admin Password   | Account Takeover |

### Defenses

| Risk               | Defense                     |
| ------------------ | --------------------------- |
| SQL Injection      | Parameterized Queries       |
| Weak Passwords     | Multi-Factor Authentication |
| Missing Monitoring | Log Monitoring              |

### Risk Ranking

| Weakness              | Severity |
| --------------------- | -------- |
| Weak Admin Password   | Critical |
| Poor Input Validation | High     |
| No Log Monitoring     | Medium   |

### Highest Priority Risk

Weak Admin Password

Reason: It may allow complete administrative control of the system.

---

# Skills Gained

* Linux Fundamentals
* Ethical Hacking Concepts
* Vulnerability Assessment
* CVSS Risk Analysis
* Web Security Basics
* SQL Injection Awareness
* Security Monitoring
* Phishing Detection
* Security Risk Mapping
* Defensive Security Thinking

---

# Disclaimer

This repository is intended for educational and learning purposes only. All activities were performed in a controlled and authorized training environment.
