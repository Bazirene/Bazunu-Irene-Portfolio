# 👋 Hi, I'm Bazunu Ovierheya Omonefe Irene

## Cybersecurity | Ethical Hacking | Security Engineering | Digital Forensic and Incident Response (DFIR) | SIEM | Container Security | Application Security

Welcome to my GitHub portfolio.

I am an aspiring cybersecurity professional building practical experience through hands-on projects in **cybersecurity, ethical hacking, network security, digital forensics and Incident response incident response (DFIR), SIEM, container security, application security, and web development**.

This repository serves as a central portfolio for selected projects that demonstrate my technical knowledge, practical skills, problem-solving, and continuous development.

---

# 🧑‍💻 About Me

I'm **Bazunu Ovierheya Omonefe Irene**, an aspiring cybersecurity professional with a strong interest in understanding how systems work, identifying security weaknesses, preserve evidence, building secure solutions, and responding to security threats.

My areas of interest include:

* 🔐 Cybersecurity
* 🛡️ Defensive Security
* ⚔️ Ethical Hacking
* Digital Forensic and Incidence Response (DFIR)
* 🌐 Network Security
* 🚨 Incident Response
* 📊 SIEM & Security Monitoring
* 🐳 Container Security
* 🔎 Reconnaissance & Vulnerability Assessment
* 💻 Web Development
* 🔧 Application Security
* 🔒 Secure Software Development

I believe in learning through practice by **building, testing, documenting, securing, and improving systems**.

---

# 🚀 Featured Projects

## 1. 🐳 Docker Weekend Recon

### Container Security & Vulnerability Assessment

This project focuses on container security and vulnerability assessment using Docker and Trivy.

The project demonstrates practical security activities including:

* Docker container security
* Vulnerability scanning
* Trivy security scanning
* CVE identification
* Base image security
* Container hardening
* Non-root container execution
* Vulnerability remediation

The project demonstrates how container vulnerabilities can be identified, analyzed, and addressed as part of a secure development workflow.

### 🔗 Repository

[**View Docker Weekend Recon →**](https://github.com/Bazirene/docker-weekend-recon)

---

# 2. 🔐 TechCrush Cybersecurity Projects

### Cybersecurity Capstone Projects

This repository contains my **TechCrush Cybersecurity Capstone Projects**, covering practical cybersecurity exercises across network security, incident response, and SIEM/Wazuh.

The project is organized into three major areas:

### Network Security

Projects include:

* VLAN network design
* Virtual machine security
* Network reconnaissance
* Packet analysis with Wireshark
* Data encryption and hashing
* Secure file transfer
* Secure traffic monitoring

### Incident Response

Projects include:

* Phishing and social engineering
* Ransomware response
* DDoS response
* Incident response roles
* Incident response metrics
* Post-incident review

### SIEM & Wazuh

Projects include:

* Wazuh SIEM deployment
* Kali Linux agent integration
* Windows agent integration
* Log ingestion
* MITRE ATT&CK mapping
* SSH brute-force detection
* Linux privilege escalation detection
* Credential dumping detection
* Windows Event Log erasure detection

These projects demonstrate hands-on experience with **security monitoring, network analysis, incident response, endpoint security, threat detection, and SIEM operations**.

### 🔗 Repository

[**View TechCrush Cybersecurity Projects →**](https://github.com/Bazirene/techcrush-cybersecurity-projects)

---

# 3. 🌐 Semantics Frontend Website

### Frontend Web Development

This project demonstrates my frontend development skills through the development of a website interface.

The project focuses on:

* Frontend development
* Website structure
* User interface design
* HTML
* CSS
* JavaScript
* Responsive web development

This project represents the web-development side of my technical portfolio and complements my cybersecurity work by demonstrating my understanding of how modern web applications are structured.

### 🔗 Repository

[**View Semantics Frontend Website →**](https://github.com/Bazirene/semantics-frontend-website)

### 🌍 Live Website

[**Visit the Live Website →**](https://bazirene.github.io/semantics-frontend-website/)

---

# 4. 🛡️ Operation Secure Core - Week 2

### Secure Backend & Application Security

This project focuses on secure backend development, API testing, automation, and security-focused engineering.

The project demonstrates work involving:

* Backend development
* API probing
* API testing
* Bash automation
* Security testing
* Secrets management
* Environment variables
* Secure development practices
* AI-assisted engineering documentation

The project demonstrates how security considerations can be incorporated into the development and testing of backend applications.

### 🔗 Repository

[**View Operation Secure Core - Week 2 →**](https://github.com/Bazirene/operation-secure-core-week2)

---
## 5. 🔐 OAuth 2.0 Authorization Server - Week 3

### Secure Backend & Application Security

A lightweight, production-focused OAuth 2.0 Authorization Server built using Node.js, Express, and `@node-oauth/express-oauth-server`. This project implements the secure `authorization_code` grant flow alongside an isolated multi-tier Docker infrastructure featuring Python, PostgreSQL (with SCRAM-SHA-256 encryption), and Redis caching.

The project demonstrates advanced security engineering work including:
- Decoupling API routing boundaries from data validation models
- In-memory cryptographic tracking for authorization codes, access tokens, and refresh tokens
- Implementation of standardized bearer-token authorization layers (`Authorization: Bearer <token>`)
- Multi-network infrastructure containment using Docker volumes and unique service endpoints
- PostgreSQL initialization configuration using hardened SCRAM-SHA-256 authentication

### 🔗 Repository

**[View OAuth 2.0 Authorization Server →](https://github.com/Bazirene/oauth-authorization-server)**

---
## 6. 🔐 Broken-Oauth-Server
### Application Security & Cryptographic Remediation

A comprehensive security audit, vulnerability analysis, and patching repository focused on identifying and addressing broken authentication mechanisms in an Express-based OAuth/JWT service. This workspace walks through standard reverse engineering practices, threat assessment indexing, and defensive software remediation workflows.

The project demonstrates advanced security engineering work including:
- Performing source code reviews to identify hidden token logic bypass flows
- Mapping authentication vulnerabilities to structural CWE and MITRE risk indexes
- Neutralizing cryptographic signature forge risks by eliminating weak hardcoded secrets
- Implementing strict token lifecycle boundaries via cryptographic expiry configurations (`exp`)
- Binding API validation logic safely to decoded payloads rather than unauthenticated payload bodies

### 🧰 Tools & Technologies Used
*   **Audit Engine & Analysis:** Node.js, Express, JavaScript (ES Modules framework)
*   **Cryptographic Libraries:** `jsonwebtoken` (JWT tracking), `crypto` module entropy generators
*   **Defensive Engineering Rules:** Defensive validation pattern patches, payload binding verification
*   **Validation Core Tooling:** Linux Curl Client environment, Bash environment scripting, JSON variables

### 🔗 Repository

**[View Week3-Broken-Auth-Audit →](https://github.com/Bazirene/week3-broken-auth-audit)**

## 7. 🔐 Password Strength & Breach Checker with Watchdog Log Anonymization

### Credential Security & Privacy-Preserving Breach Detection

A Python-based credential security auditing tool developed on Kali Linux that evaluates password strength, checks exposure against known data breaches, and monitors credential logs in real time. Built with Streamlit, SQLite, Python Watchdog, and the Have I Been Pwned (HIBP) API, the project combines password complexity analysis with automated log sanitization to reduce the risk of plaintext credential exposure.

The project demonstrates practical security engineering work including:

- Privacy-preserving breach verification using the HIBP k-anonymity model and SHA-1 hash-prefix matching
- Password complexity scoring and crack-time estimation using the `zxcvbn` engine
- Real-time filesystem monitoring to detect new credential entries in `passwords.log`
- Automated log sanitization to replace plaintext credentials with SHA-1 hashes
- Structured security audit logging using SQLite, including timestamps, severity classifications, and event sources
- Interactive Streamlit dashboard featuring password analysis, secure passphrase generation, email exposure checking, and historical audit records
- Verification testing for breached credentials, high-entropy passwords, and automated file sanitization

### 🔗 Repository

**[View Week3-Broken-Auth-Audit →](https://github.com/Bazirene/ProStackHub_Password_Strength-Breach_Checker.git)**

## 8. 🛡️ Host-Based Intrusion Detection (HIDS) + SOC AI Log Chatbox

### Threat Detection, Security Operations & AI-Assisted Incident Response

A Python-based Host-Based Intrusion Detection System (HIDS) developed on Kali Linux to monitor authentication logs, identify suspicious activity, and support security incident investigation. Using Python Watchdog, regular-expression-based detection, SQLite, Streamlit, and the Groq API, the project combines automated threat monitoring with an AI-powered security copilot that summarizes alerts and recommends defensive response actions.

The project demonstrates practical security engineering work including:

- Continuous monitoring of Linux authentication logs to identify suspicious security events- 
- Detection and classification of SSH brute-force attempts, failed authentication, and privilege-escalation activity
- Automated security event ingestion and structured storage in an indexed SQLite database
- Real-time SOC dashboard displaying alert metrics, severity levels, source IP addresses, and event history
- AI-assisted incident triage using recent security logs to generate threat summaries and remediation recommendations
- Controlled attack simulation using THC-Hydra to validate SSH brute-force detection and alert generation
- Verification of privilege-escalation detection and integration of AI-generated defensive firewall recommendations
- Secure API-key management practices using environment variables and .gitignore to protect sensitive credentials

🔗 Repository

**[View Week3-Broken-Auth-Audit →](https://github.com/Bazirene/ProStackHub_Host-Based-Intrusion-Detection-System-HBID-AI-Log-Chatbox.git)**

## 🔎 Network Vulnerability Scanner

### Network Security Assessment & Automated CVE Detection

A Python-based, full-stack network vulnerability scanner developed on Kali Linux to identify open ports, detect running services and software versions, and investigate known security vulnerabilities. Built using Flask, Nmap, the NIST National Vulnerability Database (NVD) REST API, and ReportLab, the application provides a web-based dashboard for viewing scan results and generating downloadable PDF vulnerability assessment reports.

The project demonstrates practical security engineering work including:

- Network reconnaissance and open-port discovery using Nmap and python-nmap
- Service and software version detection to support vulnerability assessment
- Integration with the NVD API to retrieve known Common Vulnerabilities and Exposures (CVEs) and CVSS severity scores
- Automated vulnerability lookup based on detected software names and versions
- Flask-based web dashboard for entering target details and displaying scan findings
- PDF report generation using ReportLab, with structured vulnerability findings and target information
- Python virtual environment isolation and modular application development across scanning, CVE lookup, reporting, and web interface components
- Security assessment of authorized test systems to identify potential weaknesses and support remediation planning

🔗 Repository

**[View Week3-Broken-Auth-Audit →](https://github.com/Bazirene/ProStackHub_Network-Vulnerability-Scanner.git)**

# 🧰 Tools & Technologies

## Cybersecurity

* Kali Linux
* Nmap
* Wireshark
* Wazuh
* MITRE ATT&CK
* OpenSSL
* GnuPG
* SSH
* SCP

## Networking

* Cisco Packet Tracer
* VLANs
* IP addressing
* Network reconnaissance
* Packet analysis
* Network monitoring

## Operating Systems

* Linux
* Windows
* VirtualBox
* PowerShell
* Bash

## DevSecOps & Container Security

* Docker
* Docker Compose
* Trivy
* Container vulnerability scanning
* Container hardening

## Web Development

* HTML
* CSS
* JavaScript
* Frontend development

## Backend & API Security

* Medusa
* REST APIs
* API testing
* Bash scripting
* Environment variables
* Secrets management

---

# 📚 Skills Demonstrated

Through these projects, I am developing practical skills in:

* Network security
* Network reconnaissance
* Vulnerability assessment
* Packet analysis
* Encryption and hashing
* Secure file transfer
* Incident response
* Security monitoring
* SIEM
* Wazuh
* Endpoint monitoring
* Threat detection
* MITRE ATT&CK
* Container security
* Vulnerability remediation
* API security testing
* Secure backend development
* Frontend development
* Technical documentation
* Security automation

---

# 📂 Project Portfolio

| Project                                                                                          | Area                 | Main Focus                                       |
| ------------------------------------------------------------------------------------------------ | -------------------- | ------------------------------------------------ |
| [Docker Weekend Recon](https://github.com/Bazirene/docker-weekend-recon)                         | Container Security   | Docker, Trivy, CVE analysis, container hardening |
| [TechCrush Cybersecurity Projects](https://github.com/Bazirene/techcrush-cybersecurity-projects) | Cybersecurity        | Network Security, Incident Response, Wazuh       |
| [Semantics Frontend Website](https://github.com/Bazirene/semantics-frontend-website)             | Web Development      | Frontend development and website design          |
| [Operation Secure Core - Week 2](https://github.com/Bazirene/operation-secure-core-week2)        | Application Security | Backend security, API testing, automation        |

---

# 🎯 My Cybersecurity Journey

My cybersecurity journey is focused on developing practical skills through continuous learning and hands-on projects.

I am interested in the complete security lifecycle:

```text
Build
  ↓
Test
  ↓
Identify Risks
  ↓
Detect Threats
  |
Preserve Evidence 
  ↓
Respond
  ↓
Investigate
  ↓
Improve Security
```

My projects allow me to explore both **offensive and defensive security concepts**, while also developing the technical skills required to build and secure applications and infrastructure.

---

# 🌱 Currently Learning

I am continuously developing my knowledge and practical skills in:

* Ethical hacking
* Defensive security
* Security operations
* Threat detection
* SIEM
* Digital Forensic and Incident Response (DFIR)
* Incident response
* Network security
* Container security
* Application security
* Secure software development
* Security automation
* AI-assisted security engineering

---

# 🤝 Collaboration

I am interested in collaborating on projects related to:

* Cybersecurity
* Ethical hacking
* Defensive security
* Security automation
* Threat detection
* Digital Forensic and Incident Response (DFIR)
* Application security
* Secure software development
* Container security
* Open-source security projects

I am always open to learning from other developers, cybersecurity professionals, and security enthusiasts.

---

# 📫 Contact

* **GitHub:** [@Bazirene](https://github.com/Bazirene)
* **Email:** [bazunoic@gmail.com](mailto:bazunoic@gmail.com)

---

# ⚠️ Security Disclaimer

Security testing, reconnaissance, vulnerability assessment, attack simulations, and other offensive-security activities documented in my projects should only be performed against systems and networks where proper authorization has been obtained.

The cybersecurity projects in this portfolio are intended for **education, authorized laboratory practice, security research, and professional skill development**.

---

# ⭐ Thanks for Visiting

Thank you for taking the time to explore my portfolio.

I am continuously learning, building, testing, and improving my technical and cybersecurity skills.

> **Learn. Build. Test. Identity and Protect. Detect. Respond. Investigate. Recover and Improve.**

Feel free to explore the repositories above to learn more about my projects and practical work.
