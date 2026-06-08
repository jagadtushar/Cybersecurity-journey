# Notes 1 — IBM: Cybersecurity and Data
> **Platform:** IBM SkillsBuild  
> **Learing plan:** Getting Started in Cybersecurity  
> **course:** 1 of 3  
> **Status:** ✅ Completed

---

## 📋 Table of Contents
- [Module 1: Introduction to Cybersecurity](#module-1-introduction-to-cybersecurity)
- [Module 2: Data Privacy](#module-2-data-privacy)
- [Module 3: Data Security](#module-3-data-security)

---

## Module 1: Introduction to Cybersecurity

### 1.1 Why is Cybersecurity Important?

Cybersecurity is a critical need for every organization, business, and individual — not optional.

> The potential cost of a data breach far outweighs the cost of investing in good cybersecurity.

**What a data breach costs an organization:**

| Impact | Description |
|--------|-------------|
| 💰 **Financial** | Fines, lawsuits, recovery costs |
| 🏢 **Operational** | Systems go offline, work stops |
| 📉 **Reputational** | Customers lose trust, business suffers |
| ⚖️ **Legal** | Regulatory penalties (GDPR, HIPAA, etc.) |

**Why the threat keeps growing:**
- More devices connected to the internet (IoT explosion)
- More sensitive data stored digitally every day
- Attackers are increasingly organized and sophisticated
- Remote work has expanded the attack surface massively

> 💡 **Key Insight:** Cybersecurity is not just an IT problem — it affects every department and every person in an organization.

---

### 1.2 Cybersecurity Threats

**Common Threats:**

| Threat | Description |
|--------|-------------|
| **Malware** | Malicious software that damages or gains unauthorized access |
| **Phishing** | Fake emails tricking users into revealing sensitive info |
| **Ransomware** | Encrypts data and demands payment to restore access |
| **Insider Threats** | Employees or ex-employees misusing their access |
| **Social Engineering** | Psychologically manipulating people to bypass security |
| **DDoS Attacks** | Flooding systems with traffic to make them unavailable |
| **Data Breaches** | Unauthorized access to confidential data |

**Who is behind these threats?**
- Cybercriminals — financial motivation
- Nation-state actors — espionage and cyberwarfare
- Hacktivists — political or social causes
- Insider threats — disgruntled or negligent employees
- Script kiddies — unskilled attackers using existing tools

---

### 1.3 Key Elements of Cybersecurity

IBM defines **three key elements** that every organization must address:

```
┌──────────────────────────────────────────────┐
│                                              │
│    PEOPLE  +  PROCESSES  +  TECHNOLOGY       │
│                                              │
│    All three must work together.             │
│    A weakness in any one = a security gap.   │
│                                              │
└──────────────────────────────────────────────┘
```

**🧑 People**
- Humans are the #1 target of social engineering attacks
- Security awareness training significantly reduces human error
- Every person in an organization is part of its security posture
- A security-conscious culture must be built from the top down

**⚙️ Processes**
- Defined processes ensure consistent, repeatable security practices
- Incident response plans prepare teams before attacks happen
- Regular audits identify gaps before attackers find them
- Compliance frameworks (NIST, ISO 27001) guide best practices

**💻 Technology**

| Technology | Purpose |
|------------|---------|
| Firewall | Filters and controls network traffic |
| Antivirus / EDR | Detects and removes malware on devices |
| SIEM | Centralized security monitoring and alerting |
| IDS / IPS | Detects and/or blocks intrusions |
| Encryption | Protects data if stolen |
| MFA | Adds extra layer beyond passwords |
| VPN | Secures remote connections |
| DLP | Prevents sensitive data from leaving the organization |

> 💡 Technology alone is never enough. A firewall cannot stop an employee tricked into giving away their password.

---

### 1.4 Applying the Key Elements

**Real example — Phishing attack scenario:**
```
WITHOUT all 3 elements:
  ❌ Employee clicks malicious link       (people failed)
  ❌ No incident response plan exists    (process failed)
  ❌ No email filtering tool in place    (technology failed)
  Result → Full data breach

WITH all 3 elements:
  ✅ Employee trained to spot phishing   (people)
  ✅ Incident reported per policy        (process)
  ✅ Email filter blocks attempts        (technology)
  Result → Threat detected and contained
```

These three elements also apply to your **personal** digital life:
- Strong passwords = technology + personal habit
- Not clicking suspicious links = awareness (people)
- Regular backups = process
- Antivirus on personal devices = technology

---

### 1.5 Career Highlight: Cybersecurity Career Path

**Why the field is in demand:**
- Global shortage of cybersecurity professionals
- Every industry needs security — healthcare, finance, government, tech
- Salaries are above average compared to most IT roles

**Entry-level roles:**

| Role | What They Do |
|------|-------------|
| SOC Analyst (L1) | Monitor alerts, triage incidents |
| IT Security Analyst | Implement and manage security tools |
| Junior Penetration Tester | Assist in testing systems for vulnerabilities |
| GRC Analyst | Ensure compliance with policies and regulations |

**Career progression:**
```
Entry Level         →   Intermediate          →   Senior
────────────────────────────────────────────────────────
SOC Analyst L1      →   SOC Analyst L2/L3     →   SOC Manager
IT Security         →   Security Engineer     →   Security Architect
Junior Pen Tester   →   Penetration Tester    →   Red Team Lead
GRC Analyst         →   Risk Manager          →   CISO
```

---

## Module 2: Data Privacy

### 2.1 What is Data?

Data is any information stored, processed, or transmitted digitally. It is one of the most valuable assets an organization holds — and one of the most targeted.

**Data exists in three states:**

| State | Description | Protection Method |
|-------|-------------|-------------------|
| **Data at Rest** | Stored on a device or server | Encryption, access controls |
| **Data in Transit** | Being sent over a network | HTTPS, TLS, VPN |
| **Data in Use** | Being actively processed | Secure memory, access controls |

---

### 2.2 Types of Data

Not all data carries the same sensitivity or risk. Organizations classify data to apply the right level of protection.

**Data Classification Levels:**

| Level | Description | Examples |
|-------|-------------|---------|
| **Confidential** | Highest sensitivity, strictest protection | Passwords, financial records, trade secrets |
| **Private** | Internal use only | Employee salaries, HR records |
| **Sensitive** | Requires careful handling | Medical records, personal data |
| **Public** | Can be shared freely | Press releases, public website content |

**Types of sensitive data organizations must protect:**
- **PII (Personally Identifiable Information)** — Name, address, date of birth, national ID
- **PHI (Protected Health Information)** — Medical history, prescriptions, health records
- **Financial Data** — Bank account numbers, credit card details, transaction records
- **Intellectual Property** — Trade secrets, patents, proprietary source code
- **Employee Data** — HR records, payroll, performance reviews
- **Customer Data** — Purchase history, preferences, contact information

---

### 2.3 Data Protection

Organizations use a combination of technical and policy-based controls to protect data.

**Key Data Protection Methods:**

| Method | Description |
|--------|-------------|
| **Encryption** | Converts data into unreadable format without the correct key |
| **Access Controls** | Limits who can view or modify data (role-based access) |
| **Data Masking** | Hides sensitive parts of data (e.g. showing only last 4 digits of card) |
| **Tokenization** | Replaces sensitive data with non-sensitive placeholder tokens |
| **Backups** | Copies of data stored separately in case of loss or attack |
| **Audit Logs** | Records of who accessed or modified data and when |

---

### 2.4 Why Data Privacy Matters

Data privacy is about giving individuals **control over their own personal information** and ensuring organizations handle that data responsibly.

**Impact of poor data privacy:**
- Identity theft and financial fraud for individuals
- Massive fines for organizations (GDPR fines can reach €20 million)
- Loss of customer trust and brand reputation
- Legal action and regulatory investigations

**Key Data Privacy Regulations:**

| Regulation | Region | What it Covers |
|------------|--------|----------------|
| **GDPR** | European Union | Personal data of EU citizens |
| **HIPAA** | United States | Health and medical data |
| **CCPA** | California, USA | Consumer privacy rights |
| **IT Act 2000** | India | Cybercrime and data protection |

**Individual rights under privacy laws:**
- Right to access your own data
- Right to correct inaccurate data
- Right to delete your data ("right to be forgotten")
- Right to know how your data is being used
- Right to opt out of data selling

---

### 2.5 Privacy Best Practices

**For organizations:**
- Collect only the data that is absolutely necessary (data minimization)
- Store data only as long as needed (data retention policies)
- Encrypt sensitive data at rest and in transit
- Train employees on data privacy responsibilities
- Have a clear, honest, and accessible privacy policy

**For individuals:**
- Read privacy policies before agreeing to them
- Use strong, unique passwords + a password manager
- Enable Two-Factor Authentication (2FA) on all accounts
- Regularly review what permissions apps have on your phone
- Be mindful of what personal information you share online

> 💡 **Remember:** If a service is free, your data is often the product being sold.

---

### 2.6 GAPP — Generally Accepted Privacy Principles

GAPP is a privacy framework that organizations use as a standard for managing personal data responsibly.

**The 10 GAPP Principles:**

| # | Principle | Meaning |
|---|-----------|---------|
| 1 | **Management** | Org has privacy policies and accountability |
| 2 | **Notice** | Individuals are told how their data is used |
| 3 | **Choice & Consent** | Individuals can choose how their data is used |
| 4 | **Collection** | Only necessary data is collected |
| 5 | **Use & Retention** | Data is used only for stated purposes |
| 6 | **Access** | Individuals can view and correct their data |
| 7 | **Disclosure** | Data is only shared with authorized parties |
| 8 | **Security** | Data is protected from unauthorized access |
| 9 | **Quality** | Data is accurate and complete |
| 10 | **Monitoring** | Compliance with privacy policies is enforced |

---

### 2.7 Career Highlight: Data Privacy Career Paths

**Roles in data privacy:**

| Role | Focus |
|------|-------|
| **Data Privacy Analyst** | Ensure compliance with privacy regulations |
| **Privacy Officer (DPO)** | Oversees organization's entire privacy program |
| **Compliance Analyst** | Audit and enforce internal privacy policies |
| **GRC Analyst** | Governance, Risk, and Compliance across the organization |

---

## Module 3: Data Security

### 3.1 The CIA Triad

The CIA Triad is the **most fundamental model in cybersecurity**. It defines the three core objectives that all security measures must protect.

```
        ┌─────────────────────┐
        │   C — Confidentiality│  Only authorized people can access data
        ├─────────────────────┤
        │   I — Integrity      │  Data is accurate and has not been altered
        ├─────────────────────┤
        │   A — Availability   │  Data and systems are accessible when needed
        └─────────────────────┘
```

**Confidentiality:**
- Ensures data is only seen by those who are authorized
- Achieved through: encryption, access controls, authentication
- Threat to confidentiality: unauthorized access, data leaks, eavesdropping

**Integrity:**
- Ensures data has not been tampered with or corrupted
- Achieved through: hashing, digital signatures, audit logs
- Threat to integrity: man-in-the-middle attacks, unauthorized modifications

**Availability:**
- Ensures systems and data are accessible when needed
- Achieved through: redundancy, backups, disaster recovery plans
- Threat to availability: DDoS attacks, hardware failures, ransomware

**Real-world CIA Triad examples:**

| Scenario | CIA Element Violated |
|----------|---------------------|
| Hacker reads private emails | Confidentiality |
| Attacker changes financial records | Integrity |
| Ransomware shuts down hospital systems | Availability |
| Employee leaks customer database | Confidentiality |

---

### 3.2 Key Security Parameters

Security parameters are the measurable standards used to evaluate how secure a system is.

**Key Parameters:**

| Parameter | Description |
|-----------|-------------|
| **Authentication** | Verifying the identity of a user or system |
| **Authorization** | Determining what an authenticated user is allowed to do |
| **Non-repudiation** | Ensuring actions cannot be denied (digital signatures) |
| **Accountability** | Tracking who did what through logs and audit trails |

**Authentication Methods:**

| Type | Example | Security Level |
|------|---------|---------------|
| Something you know | Password, PIN | Low–Medium |
| Something you have | OTP, hardware token | Medium–High |
| Something you are | Fingerprint, Face ID | High |
| Multi-Factor (MFA) | Password + OTP | Very High |

---

### 3.3 Controls

Security controls are the **safeguards** put in place to protect data and systems. They fall into three categories:

**Administrative Controls** (Policy-based)
- Security policies and procedures
- Employee security awareness training
- Background checks and hiring practices
- Incident response plans

**Physical Controls** (Physical barriers)
- Locked server rooms and data centers
- Security cameras and alarm systems
- Biometric access to restricted areas
- Cable locks for devices

**Technical Controls** (Technology-based)
- Firewalls and intrusion detection systems
- Encryption of data at rest and in transit
- Multi-factor authentication
- Antivirus and endpoint protection
- SIEM for centralized monitoring

> 💡 **Key Point:** Organizations must use the most appropriate mix of all three control types — not just technical controls alone.

```
Best security = Administrative + Physical + Technical controls working together
```

---

### 3.4 Data Loss Prevention (DLP)

DLP is a strategy and set of tools designed to **prevent sensitive data from leaving an organization** without authorization.

**How data loss happens:**
- Accidental sharing — employee emails wrong person
- Malicious insiders — employee steals data before leaving
- External attacks — hacker exfiltrates data during a breach
- Lost/stolen devices — unencrypted laptop left in a taxi

**What DLP tools do:**
- Monitor data movement across the network
- Block unauthorized transfers of sensitive files
- Alert security teams when policy violations occur
- Prevent copying sensitive data to USB drives or personal email

**DLP in practice:**
```
Employee tries to email a file containing 500 credit card numbers
    ↓
DLP tool scans the email content
    ↓
Detects sensitive data pattern (credit card format)
    ↓
Blocks the email + alerts the security team
    ↓
Incident is logged and investigated
```

---

### 3.5 Career Highlight: Data Security Analyst

**What a Data Security Analyst does:**
- Monitors systems for security threats and vulnerabilities
- Implements and manages security controls
- Conducts risk assessments and security audits
- Responds to security incidents
- Ensures CIA Triad is maintained across the organization

**Skills needed:**
- Understanding of CIA Triad and security frameworks
- Knowledge of security tools (SIEM, IDS/IPS, DLP)
- Risk assessment and analytical thinking
- Knowledge of compliance requirements
- Incident response experience

---

*Notes by: Tushar Jagad | IBM SkillsBuild — Getting Started in Cybersecurity | course 1 Cybersecurity and Data*
