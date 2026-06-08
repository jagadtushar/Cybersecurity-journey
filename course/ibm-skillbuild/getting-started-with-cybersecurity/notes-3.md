# Notes 3 — IBM: Protecting a Device with Malwarebytes
> **Platform:** IBM SkillsBuild  
> **Learning plan:** Getting Started in Cybersecurity  
> **course:** 3 of 3  
> **Status:** ✅ Completed (100%)

---

## 📋 Table of Contents
- [Module 1: Threats to Devices and Networks](#module-1-threats-to-devices-and-networks)
- [Module 2: Protecting a Device with Malwarebytes](#module-2-protecting-a-device-with-malwarebytes)

---

## Module 1: Threats to Devices and Networks

### 1.1 Malware

Malware (malicious software) is any software intentionally designed to cause damage, gain unauthorized access, or disrupt systems.

**Types of Malware:**

| Type | How It Works | Real-World Impact |
|------|-------------|-------------------|
| **Virus** | Attaches to legitimate files, spreads when file is opened | Corrupts files, slows system |
| **Worm** | Self-replicates across networks without user action | Spreads rapidly, consumes bandwidth |
| **Trojan** | Disguised as legitimate software | Opens backdoor for attacker |
| **Ransomware** | Encrypts all files, demands payment | Business shutdown, data loss |
| **Spyware** | Secretly monitors user activity | Steals passwords, financial data |
| **Adware** | Displays unwanted ads, often bundled with spyware | Slows device, privacy risk |
| **Rootkit** | Hides deep inside OS, gives attacker admin access | Nearly invisible, hard to remove |
| **Keylogger** | Records every keystroke typed | Captures passwords, credit cards |
| **Botnet** | Turns device into a remotely controlled "zombie" | Used for DDoS attacks, spam |

**How malware gets onto your device:**
```
Phishing emails with malicious attachments
Downloading software from untrusted sources
Clicking on malicious links or ads
Infected USB drives
Visiting compromised websites (drive-by downloads)
Exploiting unpatched software vulnerabilities
```

**Signs your device may be infected:**
- System is unusually slow
- Programs crash frequently
- Pop-up ads appearing constantly
- Unexpected files or programs appear
- Antivirus is disabled without your action
- High network activity even when idle

---

### 1.2 Antimalware Software

Antimalware software is your primary technical defense against malware on a device.

**How antimalware works:**

| Method | Description |
|--------|-------------|
| **Signature-based detection** | Matches files against a database of known malware signatures |
| **Heuristic analysis** | Detects suspicious behavior even for unknown malware |
| **Real-time protection** | Continuously monitors the system for threats as they happen |
| **Scheduled scanning** | Scans the entire system at set times automatically |
| **Quarantine** | Isolates suspicious files so they cannot cause harm |
| **Sandboxing** | Runs suspicious files in an isolated environment to test behavior |

**Popular antimalware tools:**

| Tool | Best For |
|------|---------|
| **Malwarebytes** | On-demand scanning, removing existing infections |
| **Windows Defender** | Built-in real-time protection for Windows |
| **AdwCleaner** | Removing adware, spyware, browser hijackers, PUPs |
| **Kaspersky** | Comprehensive real-time protection |
| **Bitdefender** | Strong detection with low system impact |

**Best practices for antimalware:**
- ✅ Keep antimalware software updated at all times
- ✅ Run scheduled scans regularly (at least weekly)
- ✅ Never disable real-time protection
- ✅ Act on quarantine alerts — review and delete flagged files
- ✅ Use multiple tools if needed (Malwarebytes + Windows Defender work well together)

---

### 1.3 Social Engineering

Social engineering is the manipulation of people — rather than systems — to gain unauthorized access or information. It is the most common attack vector because humans are easier to exploit than well-configured technology.

**Why social engineering works:**
- People naturally want to be helpful
- Authority figures are trusted without verification
- Urgency causes people to skip security checks
- Fear of consequences makes people act quickly without thinking

**Common Social Engineering Techniques:**

| Attack | Description | Example |
|--------|-------------|---------|
| **Phishing** | Fake emails that appear legitimate | Email claiming your bank account is locked |
| **Spear Phishing** | Targeted phishing using personal details | Email using your name, company, and manager's name |
| **Vishing** | Voice phishing over phone calls | Fake "IT support" calling to ask for your password |
| **Smishing** | SMS phishing via text messages | Text saying "your package is delayed, click here" |
| **Pretexting** | Creating a fake identity/scenario | Attacker poses as auditor needing system access |
| **Baiting** | Leaving infected USB drives in public places | USB labeled "Salary List 2024" left in a parking lot |
| **Tailgating** | Physically following someone into a restricted area | Walking behind an employee through a secure door |
| **Quid Pro Quo** | Offering a service in exchange for information | "I'll fix your computer if you give me your login" |

**How to defend against social engineering:**
```
✔ Always verify the identity of anyone requesting access or info
✔ Never share passwords — not even with "IT support"
✔ If an email creates urgency, slow down and verify separately
✔ Check email sender addresses carefully (not just display names)
✔ When in doubt, contact the person through official channels
✔ Report suspicious contacts to your security team
```

---

### 1.4 Cookies

Cookies are small text files that websites store on your browser to remember information about you and your session.

**Types of Cookies:**

| Type | Description | Privacy Risk |
|------|-------------|-------------|
| **Session Cookies** | Temporary, deleted when browser closes | Low — keeps you logged in during session |
| **Persistent Cookies** | Stay on your device for a set time period | Medium — tracks return visits |
| **First-Party Cookies** | Set by the website you are visiting | Low — improves your experience |
| **Third-Party Cookies** | Set by external advertisers on the site | High — used for cross-site tracking |
| **Secure Cookies** | Only transmitted over HTTPS connections | Low — encrypted in transit |
| **Zombie Cookies** | Recreate themselves after deletion | Very High — very hard to remove |

**What cookies are used for:**
- Keeping you logged into websites
- Remembering your shopping cart
- Storing your preferences and settings
- Tracking your browsing behavior for advertising
- Analytics and website performance monitoring

**Security risks of cookies:**
- **Session Hijacking** — Attacker steals your session cookie to impersonate you
- **Cross-Site Scripting (XSS)** — Malicious script steals cookies from your browser
- **Cross-Site Request Forgery (CSRF)** — Uses your cookies to perform actions without your knowledge
- **Tracking** — Third-party cookies build a detailed profile of your browsing habits

**How to manage cookies safely:**
- Regularly clear cookies and browsing data
- Use browser extensions that block third-party cookies
- Read cookie consent notices before accepting all
- Use private/incognito mode for sensitive browsing
- Enable "Block third-party cookies" in browser settings

---

### 1.5 Eavesdropping

Eavesdropping (also called network sniffing or packet sniffing) is when an attacker secretly intercepts and listens to network communications.

**How eavesdropping happens:**
```
Your Device  ──── unencrypted data ────►  Network  ──── Attacker intercepts here
```

**Types of eavesdropping attacks:**

| Attack | Description |
|--------|-------------|
| **Passive Eavesdropping** | Attacker silently listens to network traffic without changing it |
| **Active Eavesdropping** | Attacker intercepts AND modifies the communication (MitM) |
| **Man-in-the-Middle (MitM)** | Attacker secretly sits between two communicating parties |
| **Wi-Fi Sniffing** | Capturing unencrypted data on public Wi-Fi networks |
| **Packet Sniffing** | Using tools like Wireshark to capture raw network packets |

**Common scenarios:**
- Using public Wi-Fi at a café without a VPN
- Connecting to a fake "Free WiFi" hotspot set up by an attacker
- HTTP (non-HTTPS) websites sending data in plain text

**Defense against eavesdropping:**
- Always use HTTPS websites (look for the padlock 🔒)
- Use a VPN on any public or untrusted network
- Avoid accessing sensitive accounts on public Wi-Fi
- Use encrypted messaging apps (Signal, WhatsApp)
- Verify Wi-Fi network names before connecting

---

### 1.6 VPNs (Virtual Private Networks)

A VPN creates an encrypted tunnel between your device and the internet, hiding your data from anyone trying to intercept it.

**How a VPN works:**
```
Without VPN:
Your Device ──── plain text data ────► Internet ──── Anyone can see this

With VPN:
Your Device ──── encrypted tunnel ────► VPN Server ──── encrypted ────► Internet
                                         (your real IP is hidden)
```

**What a VPN does:**
- Encrypts all your internet traffic
- Hides your real IP address
- Makes your traffic appear to come from the VPN server location
- Prevents ISP (Internet Service Provider) from seeing your activity
- Protects you on public Wi-Fi networks

**What a VPN does NOT do:**
- Does not make you completely anonymous
- Does not protect against malware or phishing
- Does not hide activity from the VPN provider itself
- Does not protect against cookies or browser tracking

**Types of VPNs:**

| Type | Use Case |
|------|---------|
| **Remote Access VPN** | Individual connecting securely to corporate network |
| **Site-to-Site VPN** | Connecting two office networks together |
| **Personal VPN** | Individual protecting personal privacy online |

**Trusted VPN tools:**
- Malwarebytes Privacy VPN
- ProtonVPN (strong privacy focus, free tier available)
- Mullvad VPN (no logs, strong privacy)
- Corporate VPNs (Cisco AnyConnect, Palo Alto GlobalProtect)

> 💡 **Key Insight:** A VPN is essential on any public Wi-Fi. Even if someone captures your traffic, all they see is encrypted gibberish.

---

## Module 2: Protecting a Device with Malwarebytes

> This module was a hands-on simulation. The steps below document exactly what was performed during the activity.

### Overview of Malwarebytes Suite

Malwarebytes offers four main products for Windows device protection:

| Tool | Purpose |
|------|---------|
| **Malwarebytes** | Scans and removes malware — viruses, exploits, ransomware |
| **AdwCleaner** | Removes adware, spyware, browser hijackers, PUPs |
| **Privacy VPN** | Hides IP address, encrypts internet traffic |
| **Browser Guard** | Blocks ads, trackers, and malicious websites in browser |

---

### Task 1: Scan for Malware Using Malwarebytes

**Key areas of the Malwarebytes interface:**

| Section | What It Shows |
|---------|--------------|
| **Detection History** | Number of quarantined files (potentially malicious files moved to a safe location) |
| **Scanner** | Scheduled scans and option to start a scan immediately |
| **Real-Time Protection** | Switches for real-time antimalware protection services (On by default) |

**What quarantine means:**
> Quarantined files are potentially malicious files that Malwarebytes has moved to a location where they cannot cause harm. They are not deleted immediately — you review and choose to delete or restore them.

---

### Task 2: Detect and Remove Adware and Spyware Using AdwCleaner

**What AdwCleaner targets** (different from Malwarebytes):
- Adware
- Spyware targeting browser activity
- Potentially Unwanted Programs (PUPs)
- Browser hijackers
- Unwanted browser tools
- Hard-to-remove pre-installed software

**AdwCleaner vs Malwarebytes — Key Difference:**
```
Malwarebytes  →  Targets system-level malware (viruses, ransomware, exploits)
AdwCleaner    →  Targets browser-level threats (adware, spyware, PUPs, hijackers)
```
> Using both together gives more complete protection.

---

### Task 3: Conceal Device IP Address Using Privacy VPN

**What Privacy VPN does:**
- Hides your real IP address from malicious actors
- Encrypts your online data in transit
- Makes your traffic appear to originate from the VPN server location

**Why this matters:**
- Your IP address reveals your approximate physical location
- Websites, trackers, and attackers can use your IP to identify you
- A VPN replaces your real IP with the VPN server's IP

---

### Task 4: Block Online Security Threats Using Browser Guard

**What Browser Guard does:**
- Blocks ads and trackers on websites
- Blocks websites known for phishing, malware, or other threats
- Works as a browser extension (toolbar icon)

**Browser Guard protection types:**
- Ads and trackers blocking
- Malware site blocking
- Scam site blocking
- PUP (Potentially Unwanted Program) site blocking

The complete step-by-step simulation transcript is stored separately here:

📄 `malwarebytes-simulation-transcript.pdf`

---

*Notes by: Tushar Jagad | IBM SkillsBuild — Getting Started in Cybersecurity | course 3 Protecting a Device with Malwarebytes*
