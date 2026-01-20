# Cyber-Security-Internship
# Cyber Security Internship – Task 1

## Task Title
Understanding Cyber Security Basics & Attack Surface

## Description
This repository contains Task 1 of my Cyber Security Internship.  
The task focuses on understanding cyber security fundamentals, CIA Triad, attack surfaces, common attackers, OWASP Top 10, and basic data flow with attack points.

## What I Learned
- Basics of cyber security and its importance
- Understanding confidentiality, integrity, and availability
- Different types of attack surfaces
- Common cyber attackers and their motivations
- Importance of OWASP Top 10 vulnerabilities
- How data flows through applications and where attacks can occur

## Files Included
- Cyber_Security_Task1.pdf

## Tools Used
- Browser for self-research
- GitHub for documentation and submission

## Outcome
This task helped me build a strong foundation in cyber security concepts and improved my awareness of real-world cyber threats.
# Cyber Security Internship – Task 2

## Task Title
Operating System Security Fundamentals (Linux & Windows)

## Objective
The objective of this task is to understand operating system–level security concepts and learn how proper configuration and hardening can reduce security risks in Linux and Windows environments.

## Tools Used
- Ubuntu Linux (Virtual Machine)
- Windows Defender & Windows Security Settings
- VirtualBox

## Task Overview
This task focuses on basic operating system security mechanisms such as user management, access control, file permissions, firewall configuration, and service management. The goal is to understand how misconfigurations can increase system vulnerabilities and how hardening techniques help protect systems from attacks.

## Key Concepts Covered
- User accounts and access control
- Administrator vs standard user privileges
- Linux file permissions (read, write, execute)
- Permission commands: `ls -l`, `chmod`, `chown`
- Firewall configuration (UFW / Windows Firewall)
- Running processes and services
- Operating system hardening basics
- Principle of least privilege

## OS Hardening Practices
- Use strong passwords and restrict administrative access
- Avoid using root/administrator accounts for daily activities
- Disable unnecessary services and open ports
- Enable and configure firewall rules
- Keep the operating system updated
- Regularly review user accounts and permissions

## Deliverables
- OS Security Checklist Document (PDF)
- Practical understanding of OS security fundamentals

## Final Outcome
By completing this task, I gained a clear understanding of how operating systems enforce security at the user, file, and service levels. This task strengthened my knowledge of system hardening techniques that help reduce attack surfaces in both Linux and Windows environments.

---

**Task Status:** Completed

# Cyber Security Internship – Task 3

## Task Title
Networking Basics for Cyber Security

## Objective
The objective of this task is to understand basic networking concepts and learn how network traffic can be captured and analyzed for security purposes.

## Tools Used
- Wireshark  
- Alternatives: tcpdump, Microsoft Network Monitor

## Task Overview
This task focuses on learning how data travels across a network and how packet analysis helps in cybersecurity. Using Wireshark, live network traffic was captured and analyzed to understand different protocols, connection behavior, and security risks related to unencrypted communication.

## Key Concepts Covered
- Basic networking concepts (IP, MAC, DNS)
- TCP and UDP protocols
- Packet sniffing and traffic analysis
- Packet filtering using Wireshark
- TCP three-way handshake
- Plain-text vs encrypted traffic
- DNS query analysis

## Network Traffic Analysis
Live network traffic was captured using Wireshark by selecting the active network interface. Packet filters such as `tcp`, `dns`, and `http` were applied to focus on specific protocols. The TCP three-way handshake was observed using SYN, SYN-ACK, and ACK packets, showing how reliable connections are established.

Plain-text HTTP traffic was readable in captured packets, while HTTPS traffic was encrypted and unreadable. DNS traffic revealed how domain names are resolved into IP addresses, highlighting the importance of securing DNS communication.

## Observations
- Normal network activity generates a large number of packets
- Packet filtering is essential for effective analysis
- Unencrypted traffic exposes sensitive information
- DNS traffic reveals useful metadata
- Encrypted protocols improve overall security

## Deliverables
- Packet capture file
- Network traffic analysis report (PDF)

## Final Outcome
By completing this task, I gained practical experience in capturing and analyzing network traffic. This task improved my understanding of how networking knowledge is applied in cybersecurity monitoring and threat analysis.

---

**Task Status:** Completed

# Cyber Security Internship – Task 4

## Task Title
Password Security & Authentication Analysis

## Objective
The objective of this task is to understand how passwords are stored, how weak passwords are attacked, and why strong authentication mechanisms are essential for securing user accounts.

## Tools Used
- Hashcat
- John the Ripper  
- Online hash identification tools (for reference)

## Task Overview
This task focuses on analyzing password security by studying hashing mechanisms, common hash types, and password attack techniques. Practical analysis was done to understand why weak passwords fail and how attackers exploit poor authentication practices.

## Key Concepts Covered
- Password storage using hashing
- Hashing vs encryption
- Common hash types (MD5, SHA-1, bcrypt)
- Dictionary attacks and brute force attacks
- Weak password analysis
- Multi-factor authentication (MFA)
- Strong authentication practices

## Password Security Analysis
Passwords are stored as hashes rather than plain text to protect user credentials. Older hashing algorithms such as MD5 and SHA-1 are fast and vulnerable to attacks, making them unsuitable for secure systems. Modern algorithms like bcrypt are slower and provide better resistance against brute force attacks.

Weak passwords that are short, common, or predictable were found to be easily cracked using dictionary-based approaches. This demonstrates how poor password choices directly increase security risks.

## Authentication Best Practices
- Use long and unique passwords
- Avoid common or predictable password patterns
- Use modern hashing algorithms
- Enable multi-factor authentication
- Avoid password reuse across platforms
- Regularly update and review credentials

## Deliverables
- Password Security Analysis Report (PDF)

## Final Outcome
By completing this task, I gained practical understanding of password-based attacks and modern authentication defenses. This task strengthened my knowledge of how weak credentials are exploited and how strong authentication mechanisms help protect systems.

---

**Task Status:** Completed
