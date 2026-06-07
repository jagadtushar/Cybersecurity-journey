# 🛡️ Cisco — Introduction to Cybersecurity
> **Status:** ✅ Completed  
> **Modules:** 5 | **Total Topics:** 20+

---

## 📋 Table of Contents
- [Module 1: Introduction to Cybersecurity](#module-1-introduction-to-cybersecurity)
- [Module 2: Attacks, Concepts and Techniques](#module-2-attacks-concepts-and-techniques)
- [Module 3: Protecting Your Data and Privacy](#module-3-protecting-your-data-and-privacy)
- [Module 4: Protecting the Organization](#module-4-protecting-the-organization)
- [Module 5: Will Your Future Be in Cybersecurity?](#module-5-will-your-future-be-in-cybersecurity)

---

## Module 1: Introduction to Cybersecurity

### 1.1 The World of Cybersecurity

Cybersecurity is the practice of protecting systems, networks, and programs from digital attacks. These attacks usually aim to access, change, or destroy sensitive information, extort money, or interrupt normal business processes.

**Why Cybersecurity Matters:**
- Every device connected to the internet is a potential target
- Data is one of the most valuable assets today
- Cyber attacks can affect individuals, businesses, and even governments

**Key Concepts:**
| Term | Definition |
|------|------------|
| **Cybersecurity** | Protection of internet-connected systems from cyber threats |
| **Data** | Raw facts stored digitally (text, numbers, images, etc.) |
| **Network** | A group of connected devices that share resources |
| **Vulnerability** | A weakness in a system that can be exploited |
| **Threat** | Any potential danger to an information system |
| **Risk** | The likelihood that a threat will exploit a vulnerability |

**The CIA Triad — Core Principle of Cybersecurity:**
```
C — Confidentiality  →  Only authorized people can access data
I — Integrity        →  Data is accurate and has not been tampered with
A — Availability     →  Data and systems are accessible when needed
```

---

### 1.2 Organizational Data

Organizations collect and store large amounts of data. Protecting this data is a critical cybersecurity responsibility.

**Types of Organizational Data:**
- **Traditional Data** — Employee records, intellectual property, financial data
- **Internet of Things (IoT) Data** — Data from smart devices and sensors
- **Big Data** — Extremely large datasets analyzed for patterns

**Data Classification Levels:**
| Level | Description | Example |
|-------|-------------|---------|
| **Confidential** | Highest protection needed | Passwords, credit card info |
| **Private** | For internal use only | Employee salaries, HR records |
| **Sensitive** | Requires careful handling | Medical records |
| **Public** | Can be shared freely | Press releases, public websites |

**McCumber Cube:**
A model used to think about information security across three dimensions:
1. Security goals (CIA Triad)
2. Information states (Storage, Transmission, Processing)
3. Security measures (Technology, Policy, People)

---

### 1.3 What Was Taken?

When a cyber attack occurs, various types of data or assets can be stolen or compromised.

**What Attackers Target:**
- **Personal Identity Information (PII)** — Name, address, date of birth, SSN
- **Protected Health Information (PHI)** — Medical records and health history
- **Intellectual Property** — Trade secrets, patents, proprietary code
- **Financial Data** — Bank accounts, credit cards, transaction history
- **Login Credentials** — Usernames and passwords

**Real-World Impact of Data Breaches:**
- Financial loss for individuals and companies
- Reputation damage
- Legal consequences and regulatory fines
- Loss of customer trust

> 💡 **Key Insight:** Data breaches don't always happen immediately — attackers sometimes stay hidden inside a network for months before acting.

---

### 1.4 Cyber Attackers

Not all attackers are the same. Understanding *who* attacks and *why* helps build better defenses.

**Types of Threat Actors:**
| Type | Description | Motivation |
|------|-------------|------------|
| **Script Kiddies** | Unskilled attackers using existing tools | Fame, fun |
| **Hacktivists** | Hack for political or social causes | Ideology |
| **Cybercriminals** | Organized groups seeking financial gain | Money |
| **State-Sponsored** | Government-backed attackers | Espionage, warfare |
| **Insider Threats** | Employees or ex-employees | Revenge, money |

**Hacker Categories:**
-  **White Hat** — Ethical hackers, work with permission to find vulnerabilities
-  **Black Hat** — Malicious hackers, illegal activity
-  **Grey Hat** — In between; may hack without permission but report findings

---

### 1.5 Cyberwarfare

Cyberwarfare refers to the use of technology to attack a nation's systems, causing damage comparable to actual warfare.

**Goals of Cyberwarfare:**
- Disrupting critical infrastructure (power grids, water systems)
- Stealing classified government data
- Spreading misinformation
- Disabling military communication systems

**Famous Example:**
- **Stuxnet** — A malicious worm discovered in 2010, believed to be developed by the US and Israel, that targeted Iran's nuclear facilities and physically destroyed centrifuges using software

**Key Terms:**
| Term | Meaning |
|------|---------|
| **Cyberwarfare** | Internet-based conflict between nations |
| **Critical Infrastructure** | Systems essential to national security (power, water, finance) |
| **Advanced Persistent Threat (APT)** | Long-term, targeted attack usually by nation-states |

---

## Module 2: Attacks, Concepts and Techniques

### 2.1 Analyzing a Cyber Attack

A cyber attack is a deliberate action to steal, expose, alter, disable, or destroy data or systems.

**Stages of a Cyber Attack (Cyber Kill Chain):**
```
1. Reconnaissance   →  Attacker gathers information about the target
2. Weaponization    →  Creates malware or exploit
3. Delivery         →  Sends the attack (email, USB, website)
4. Exploitation     →  Executes the attack on the victim
5. Installation     →  Installs malware on the victim's system
6. Command & Control → Attacker remotely controls the system
7. Actions on Objectives → Steals data, causes damage
```

**Indicators of Attack (IoA) vs Indicators of Compromise (IoC):**
- **IoA** — Signs that an attack is *happening* (unusual login attempts)
- **IoC** — Evidence that an attack *has happened* (unknown files, changed passwords)

---

### 2.2 Methods of Infiltration

Attackers use many techniques to gain unauthorized access to systems.

**Common Attack Methods:**

**Social Engineering:**
> Manipulating people psychologically to give up confidential information.
- **Phishing** — Fake emails tricking users into clicking malicious links
- **Spear Phishing** — Targeted phishing aimed at a specific person
- **Vishing** — Voice phishing (phone calls)
- **Smishing** — SMS phishing (text messages)
- **Pretexting** — Creating a fake scenario to manipulate victims
- **Tailgating** — Physically following someone into a restricted area

**Malware Types:**
| Malware | Description |
|---------|-------------|
| **Virus** | Attaches to files; spreads when file is opened |
| **Worm** | Self-replicates across networks without user action |
| **Trojan** | Disguised as legitimate software |
| **Ransomware** | Encrypts files; demands payment for decryption |
| **Spyware** | Secretly monitors and collects user activity |
| **Adware** | Displays unwanted ads; often bundles spyware |
| **Rootkit** | Hides deep in OS; gives attacker admin access |
| **Keylogger** | Records every keystroke the user types |

**Other Attack Techniques:**
- **DoS (Denial of Service)** — Floods a server with traffic to make it unavailable
- **DDoS (Distributed DoS)** — DoS attack launched from multiple sources (botnet)
- **Man-in-the-Middle (MitM)** — Attacker secretly intercepts communication between two parties
- **SQL Injection** — Inserts malicious SQL code into a web form to access databases
- **Cross-Site Scripting (XSS)** — Injects scripts into web pages viewed by other users

---

### 2.3 Security Vulnerability and Exploits

A **vulnerability** is a weakness. An **exploit** is the method used to take advantage of that weakness.

**Types of Vulnerabilities:**
- **Software Vulnerabilities** — Bugs or flaws in code
- **Hardware Vulnerabilities** — Physical weaknesses in devices
- **Human Vulnerabilities** — People being tricked or making mistakes
- **Network Vulnerabilities** — Poorly configured firewalls, open ports

**CVE — Common Vulnerabilities and Exposures:**
- A public database of known vulnerabilities
- Each vulnerability gets a unique CVE ID (e.g., CVE-2021-44228)
- Used by security teams to track and patch vulnerabilities

**Zero-Day Exploit:**
> An attack that targets a vulnerability that is unknown to the software vendor — no patch exists yet.

---

### 2.4 The Cybersecurity Landscape

The cybersecurity landscape is constantly evolving with new technologies and threats.

**Emerging Threats:**
- **IoT Attacks** — Smart devices with weak security being hijacked
- **Cloud Security Risks** — Misconfigured cloud storage exposing data
- **AI-Powered Attacks** — Attackers using AI to automate and improve attacks
- **Supply Chain Attacks** — Targeting software vendors to reach their customers

**Security Landscape Key Facts:**
- Cybercrime costs the world trillions of dollars annually
- The average time to detect a breach is over 200 days
- Human error is responsible for the majority of data breaches

---

## Module 3: Protecting Your Data and Privacy

### 3.1 Protecting Your Devices and Network

Your first line of defense starts with securing your own devices and home/work network.

**Device Protection Best Practices:**
- ✅ Keep your OS and software updated (patches fix vulnerabilities)
- ✅ Use strong, unique passwords for every account
- ✅ Enable a firewall on your computer
- ✅ Install reputable antivirus/antimalware software
- ✅ Enable full-disk encryption (BitLocker on Windows)
- ✅ Lock your device when not in use
- ✅ Only download software from trusted sources

**Network Protection:**
- Use **WPA3** (or at minimum WPA2) encryption on Wi-Fi
- Change default router username and password
- Disable remote management on routers
- Use a **VPN** on public Wi-Fi networks
- Segment your network (keep IoT devices on a separate network)

**Firewall Types:**
| Type | Description |
|------|-------------|
| **Packet Filtering** | Checks packet headers against rules |
| **Stateful Inspection** | Tracks active connections |
| **Application Layer** | Inspects data at application level |
| **Next-Gen Firewall (NGFW)** | Combines all above + deep packet inspection |

---

### 3.2 Data Maintenance

Proper data maintenance ensures data is protected throughout its lifecycle.

**Data States:**
- **Data at Rest** — Stored on a device or server (encrypt it)
- **Data in Transit** — Being sent over a network (use HTTPS/TLS)
- **Data in Use** — Actively being processed in memory

**Data Destruction Methods:**
- **Deleting** — NOT secure (data can be recovered)
- **Overwriting** — Replaces data with random bits
- **Degaussing** — Uses magnetic field to erase magnetic storage
- **Physical Destruction** — Shredding/destroying the physical drive

---

### 3.3 Who Owns Your Data?

When you use online services, your data is often collected, stored, and used by companies.

**Key Concepts:**
- **Terms of Service (ToS)** — Legal agreement you accept when using a service
- **Privacy Policy** — Explains how a company collects and uses your data
- **Data Broker** — Companies that collect and sell personal data

**Your Rights (in many regions):**
- Right to access your data
- Right to correct inaccurate data
- Right to delete your data ("Right to be forgotten")
- Right to know how your data is used

> 💡 **Remember:** If a service is free, YOU are often the product. Your data is being monetized.

---

### 3.4 Safeguarding Your Online Privacy

**Practical Privacy Tips:**
- Use a **password manager** (Bitwarden, KeePass)
- Enable **Two-Factor Authentication (2FA)** on all accounts
- Use **private browsing** / incognito mode when needed
- Regularly review app permissions on your phone
- Use **encrypted messaging apps** (Signal, WhatsApp)
- Be careful what you post on social media (OSINT risk)

**Authentication Methods:**
| Method | Example | Security Level |
|--------|---------|----------------|
| Something you know | Password, PIN | Low–Medium |
| Something you have | OTP, hardware key | Medium–High |
| Something you are | Fingerprint, Face ID | High |
| Multi-Factor (MFA) | Password + OTP | Very High |

---

### 3.5 Discover Your Own Risky Online Behavior

Common risky behaviors that most people do without realizing:
- Reusing the same password across multiple sites
- Clicking links in emails without verifying the sender
- Using public Wi-Fi without a VPN
- Ignoring software update notifications
- Oversharing personal information on social media
- Not logging out of accounts on shared computers

> 💡 **Self-audit:** Go to **haveibeenpwned.com** to check if your email has been in a data breach.

---

## Module 4: Protecting the Organization

### 4.1 Cybersecurity Devices and Technologies

Organizations use a range of specialized tools and technologies to protect their infrastructure.

**Key Security Technologies:**
| Technology | Purpose |
|------------|---------|
| **Firewall** | Filters incoming/outgoing network traffic |
| **IDS (Intrusion Detection System)** | Monitors and alerts on suspicious activity |
| **IPS (Intrusion Prevention System)** | Monitors AND blocks suspicious activity |
| **SIEM** | Collects and analyzes security logs from all systems |
| **VPN** | Encrypts remote connections to corporate network |
| **Proxy Server** | Acts as gateway between users and internet |
| **Honeypot** | Decoy system designed to attract attackers |
| **WAF (Web App Firewall)** | Protects web applications from attacks |
| **EDR** | Endpoint Detection and Response on devices |
| **DLP** | Data Loss Prevention — stops sensitive data from leaving |

**Network Segmentation:**
Dividing a network into smaller zones so that if one is compromised, attackers can't easily reach others. Uses:
- VLANs (Virtual Local Area Networks)
- DMZ (Demilitarized Zone) — for public-facing servers

---

### 4.2 Behavior Approach to Cybersecurity

Modern cybersecurity doesn't just rely on tools — it focuses on understanding and analyzing behavior.

**Key Approaches:**
- **Security Awareness Training** — Educating employees about threats
- **Penetration Testing (Pen Testing)** — Simulated attacks to find weaknesses before real attackers do
- **Vulnerability Assessments** — Scanning systems for known weaknesses
- **Risk Management** — Identifying, assessing, and reducing risks

**Security Policies:**
Organizations create formal policies to guide security practices:
- Acceptable Use Policy (AUP)
- Password Policy
- Incident Response Policy
- Bring Your Own Device (BYOD) Policy

**Incident Response Steps:**
```
1. Preparation     →  Have a plan before incidents happen
2. Identification  →  Detect and confirm the incident
3. Containment     →  Stop the spread
4. Eradication     →  Remove the threat
5. Recovery        →  Restore systems to normal
6. Lessons Learned →  Document and improve
```

---

### 4.3 Cisco's Approach to Cybersecurity
⚠️ *To be completed — skipped during course*

---

## Module 5: Will Your Future Be in Cybersecurity?

### 5.1 Legal and Ethical Issues

Cybersecurity professionals must operate within legal and ethical boundaries.

**Key Laws and Regulations:**
| Law/Regulation | Description |
|----------------|-------------|
| **GDPR** | EU data protection regulation |
| **HIPAA** | US health data protection |
| **CFAA (Computer Fraud and Abuse Act)** | US law on unauthorized computer access |
| **IT Act 2000** | India's primary cybercrime law |

**Ethical Principles for Cybersecurity Professionals:**
- Only test systems you have **written permission** to test
- Protect the privacy of individuals
- Report vulnerabilities responsibly (**Responsible Disclosure**)
- Do not access data beyond what is needed
- Be honest about your findings

**Legal vs Ethical:**
> Something can be legal but unethical, or ethical but illegal. A good cybersecurity professional understands both dimensions.

---

### 5.2 Education and Careers

**Cybersecurity Career Paths:**
| Role | Responsibilities |
|------|-----------------|
| **SOC Analyst** | Monitor alerts, respond to incidents |
| **Penetration Tester** | Simulate attacks to find vulnerabilities |
| **Security Engineer** | Design and build security systems |
| **Incident Responder** | Handle active breaches and recovery |
| **Threat Intelligence Analyst** | Research emerging threats |
| **GRC Analyst** | Governance, Risk, Compliance |
| **Cloud Security Engineer** | Secure cloud infrastructure |
| **CISO** | Chief Information Security Officer — top security role |

**Skills Every Cybersecurity Professional Needs:**
- Networking fundamentals (TCP/IP, DNS, HTTP)
- Linux command line
- Basic scripting (Python, Bash)
- Analytical and problem-solving mindset
- Continuous learning habit (field changes fast!)

---

## 🔑 Key Takeaways from the Entire Course

```
1. Cybersecurity protects the CIA Triad: Confidentiality, Integrity, Availability
2. Threats come from many actors: criminals, nation-states, insiders
3. Social engineering targets humans, not just machines
4. Defense requires layers: tools + policies + people + awareness
5. Legal and ethical boundaries always apply
6. Cybersecurity is a growing field with many career paths
```

---

## 📚 Useful Resources
- [Cisco NetAcad](https://www.netacad.com)
- [Have I Been Pwned](https://haveibeenpwned.com) — Check if your email was breached
- [CVE Database](https://cve.mitre.org) — Public vulnerability database
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [TryHackMe](https://tryhackme.com) — Hands-on practice
- [Hack The Box](https://hackthebox.com) — Advanced practice labs

---

*Notes by: Tushar Jagad | Course: Cisco Introduction to Cybersecurity | Status: ✅ Completed*
