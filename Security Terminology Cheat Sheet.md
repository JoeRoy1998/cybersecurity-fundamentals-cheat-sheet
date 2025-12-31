# Security Fundamentals Overview

## Malware Types

### Virus
**Definition:**  
A type of malware that installs itself on your computer and can corrupt various parts of the system, including files, documents, or applications.

### Worm
**Definition:**  
A self-replicating malware that does not require human interaction to infect the original host machine and can spread to other computers or networks automatically.

### Trojan Horse (Trojan)
**Definition:**  
A type of malware that disguises itself as legitimate software or files to avoid detection. Once activated, it executes malicious code. Trojans are **not** self-replicating.

### Ransomware
**Definition:**  
Malware that locks or encrypts a device or data until a ransom is paid. If the demand is not met, attackers may delete data or keep it permanently inaccessible.

### Spyware
**Definition:**  
Malware installed on an end device that monitors and records user activity for later use or analysis.

### Adware
**Definition:**  
A type of malware that displays unwanted advertisements, often impacting system performance and user experience.

### Rootkit
**Definition:**  
Malware that grants attackers root or administrative access while hiding itself, making detection extremely difficult.

### Keylogger
**Definition:**  
Malware that records keystrokes on a device, allowing attackers to review sensitive input such as passwords or messages.

### Botnet Malware
**Definition:**  
Malware that infects many computers and allows them to be controlled simultaneously by attackers, commonly used in DoS or DDoS attacks.

### Fileless Malware
**Definition:**  
Malware that does not rely on stored files, often running in memory (RAM) or abusing legitimate system tools, making detection more challenging.

---

## Authentication Methods

### Password-Based Authentication
Requires a user to enter a known password to gain access to a system or device.

### Multi-Factor Authentication (MFA)
Requires two or more authentication factors, such as:
- Something you know (password)
- Something you are (fingerprint, retina scan)
- Something you have (phone, badge, token)

### Biometric Authentication
Uses unique physical characteristics (e.g., fingerprints or retina scans) to verify identity.

### Single-Factor Authentication
Uses only one authentication method to verify identity.

### Two-Factor Authentication (2FA)
Requires **exactly two** different authentication methods.

### Token-Based Authentication
Uses a physical or digital token, such as a hardware key or one-time password (OTP).

### Certificate-Based Authentication
Uses a digital certificate issued by a trusted Certificate Authority (CA) to verify a user or device.

---

## CIA Triad

The CIA Triad is a foundational security model used to guide security policies and decisions.

### Confidentiality
Ensures data remains private and accessible only to authorized users.

### Integrity
Ensures data remains accurate, complete, and unaltered by unauthorized users or processes.

### Availability
Ensures systems, services, and data remain accessible when needed.

---

## Common Attacks

### Phishing
An attack that tricks users into revealing credentials or sensitive data through fake emails or messages that appear legitimate.

### Brute Force Attack
Attempts to gain access by trying many password combinations until successful or blocked.

### Denial-of-Service (DoS) Attack
Overwhelms a system or server with traffic to cause it to crash or become unavailable.

### Distributed Denial-of-Service (DDoS) Attack
A large-scale DoS attack using many compromised machines simultaneously.

### Man-in-the-Middle (MitM) Attack
Occurs when an attacker intercepts or alters communication between a user and a system, potentially capturing credentials or PII.

### Password Spraying
Uses a small number of common passwords across many accounts to find weak credentials.

### Malware Infection
Occurs when malicious software is installed, impacting confidentiality, integrity, or availability.

### Social Engineering
Manipulates users into giving access or information through deception, such as phishing, vishing, tailgating, or piggybacking.

---

## Basic Network Security Concepts

### Firewall
A device or software that controls incoming and outgoing network traffic based on predefined rules.

### Virtual Private Network (VPN)
Creates an encrypted tunnel that allows secure remote access to a private network.

### Encryption
Protects data by converting it into an unreadable format using:
- Symmetric encryption (same key)
- Asymmetric encryption (public/private key pair)

### Network Segmentation
Divides a network into smaller segments to limit access and reduce lateral movement.

### Intrusion Detection System (IDS)
Monitors network traffic and generates alerts for suspicious activity.

### Intrusion Prevention System (IPS)
Monitors and actively blocks malicious traffic while generating alerts.

### Least Privilege
Ensures users only have the minimum access necessary to perform their tasks.

### Secure Protocols (HTTPS, SSH)
Encrypted versions of older protocols (HTTP, Telnet, FTP) that protect data in transit.

---

## Defensive Security Concepts

Defensive security focuses on preventing attacks and minimizing damage.

### Access Control
Defines and enforces who can access resources and services within an organization.

### Security Awareness Training
Educates users on recognizing attacks and responding properly to security incidents.

### Patch Management
Ensures systems and applications are updated to remediate known vulnerabilities.

### Antivirus / Anti-Malware
Protects systems from malicious software installation and execution.

### Logging and Monitoring
Records system and network activity for investigation and incident response.

### Backups and Recovery
Creates copies of data and systems to allow restoration after incidents.

### Incident Response
A documented process for investigating, containing, recovering from, and reviewing security incidents.

---

## Threat vs Vulnerability vs Risk

These concepts help assess and manage security concerns.

### Threat
A potential cause of harm, such as attackers, malware, or natural disasters.

### Vulnerability
A weakness that can be exploited by a threat.

### Risk
The likelihood of a threat exploiting a vulnerability and the potential impact.

### Examples

**Example 1:**
- Threat: Someone attempting to harm you  
- Vulnerability: Being unprepared or out of shape  
- Risk: The possibility of being injured  

**Example 2:**
- Threat: A hacker attempting to break into a system  
- Vulnerability: Weak or reused passwords  
- Risk: Account compromise and data theft  
