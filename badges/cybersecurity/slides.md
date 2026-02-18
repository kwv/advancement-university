# Cybersecurity Merit Badge ⚜️
## BSA Merit Badge

**Boy Scouts of America**

---

## Agenda

- Req 1 — Safety
- Req 2 — Ethics
- Req 3 — Fundamentals
- Req 4 — Threats, Vulnerabilities & Attacks
- Req 5 — Cyber Defenses
- Req 6 — Cryptography
- Req 7 — Connected Devices & IoT
- Req 8 — Cybersecurity Activities
- Req 9 — Careers

Note: Welcome scouts! Cybersecurity is one of the most critical fields of our time — and one of the most in-demand career paths. Everything you learn today is immediately useful in your own life.

---

## Requirement 1
# 🛡️ Safety

--

## 1a — Digital Safety Video

Watch the **Personal Safety Awareness "Digital Safety"** video

- Watch with a parent or guardian
- Be ready to discuss what you learned with your counselor

> Parent/guardian permission is required before viewing.

Note: Confirm with scouts that they have watched it before this session.

--

## 1b — Protecting Your Digital Footprint

**Your digital footprint** = everything you leave behind online

**Where it comes from:**
- Social media posts, likes, and comments
- Apps you install and permissions you grant
- Games and gaming platforms
- Search history, location data, purchase history

--

## 1b — How to Protect Your Footprint

**How to protect it:**
- 🔒 Review and tighten privacy settings on every platform you use
- 📱 Check app permissions — does a flashlight app really need your contacts?
- 🤔 Think before posting — the internet has a long memory
- 👤 Use different usernames across platforms

**Live demo:** Show privacy settings on one social media app together.

Note: Pull up Instagram, TikTok, or whatever platform scouts use most. Walk through the privacy settings together. Many scouts have never looked at these.

--

## 1c — Physical Health While Using Technology

**Eye Strain**
- Follow the **20-20-20 rule**: every 20 minutes, look 20 feet away for 20 seconds
- Adjust screen brightness to match your environment
- Position screens at arm's length, slightly below eye level

**Repetitive Stress Injuries**
- Take breaks from typing and clicking
- Use ergonomic keyboards and mice when possible
- Stretch your hands, wrists, and neck regularly

--

## 1c — Mobile Device Physical Safety

**Mobile Device Physical Safety**
- 🚶 Don't walk while looking at your phone
- 🚗 Never use devices while driving — even at slow speeds
- 🎧 Be aware of your surroundings when using headphones in public

> These are genuinely life-and-death safety habits.

Note: The distracted walking and driving points are genuinely life-and-death. Be direct about this.

---

## Requirement 2
# ⚖️ Ethics

--

## 2a — The Scout Law and the Internet

Pick **3 points of the Scout Law** and explain how they apply online.

**Examples:**

| Scout Law Point | Online Application |
|----------------|-------------------|
| **Trustworthy** | Don't spread misinformation or fake news |
| **Helpful** | Share knowledge; report vulnerabilities responsibly |
| **Friendly** | No cyberbullying — treat people online as you would in person |
| **Courteous** | Respect others' property, privacy, and creative work |
| **Kind** | Consider how your words land before you post |
| **Obedient** | Follow the law — the Computer Fraud and Abuse Act is real |
| **Thrifty** | Don't waste others' bandwidth or resources |
| **Clean** | Keep your digital spaces free of harmful content |

Note: Have scouts choose their own 3 and articulate the connection in their own words. There's no single right answer.

--

## 2b — Ethical Scenarios: What Would a Scout Do?

**Scenario 1: Unattended Computer**
You find a logged-in computer at the library. You could access anything.
> What should you do? What Scout Law principles apply?

**Scenario 2: Seeing Someone's Password**
Your friend's password appears on screen while they're logging in.
> Is it wrong to use it? Even if they're your best friend?

**Scenario 3: Unsecured Website**
You notice a website you use stores passwords in plain text — a serious flaw.
> Do you exploit it? Ignore it? Report it? To whom?

Note: These are real-world ethical dilemmas that security professionals face regularly. The third scenario introduces "responsible disclosure" — the ethical way to report vulnerabilities.

--

## The Right Answers

**Unattended computer:** Log it out or find the owner. Don't access anything — that's unauthorized access regardless of whether you "could."

**Friend's password:** Never use it without explicit permission. Trust is the foundation of all relationships — digital and physical.

**Unsecured website:** This is "responsible disclosure" — report it to the company privately, give them time to fix it, don't publicize or exploit it. Many companies have bug bounty programs that reward exactly this.

> Knowing how to hack something and choosing not to is what makes a security professional — not a criminal.

---

## Requirement 3
# 🏗️ Fundamentals

--

## 3a — Three Types of Computer Systems That Need Protection

**Personal Devices**
- Smartphones, laptops, tablets, gaming consoles
- Contains your private data, passwords, and communications
- Threat: theft, malware, unauthorized access

**Network Infrastructure**
- Routers, switches, servers that move data around
- The backbone of the internet and every organization
- Threat: interception, denial of service, unauthorized routing

--

## 3a — Industrial Control Systems

**Industrial Control Systems (ICS)**
- Power grids, water treatment, hospital equipment, traffic systems
- Control physical infrastructure that people depend on to live
- Threat: sabotage with potentially life-threatening consequences

> The 2021 Florida water treatment plant attack is a real example — an attacker tried to poison the water supply remotely.

Note: The ICS point is sobering — cyberattacks on water treatment plants and power grids have happened. The 2021 Florida water treatment plant attack is a well-documented real example.

--

## 3b — The CIA Triad

The three goals that all cybersecurity is built to protect:

| | What It Protects | Protected By | Violated By |
|---|---|---|---|
| 🔒 **Confidentiality** | Only authorized people can access the information | Encryption, access controls, passwords, MFA | Data breaches, eavesdropping, stolen credentials |
| ✏️ **Integrity** | Information is accurate and hasn't been tampered with | Checksums, digital signatures, audit logs | Data manipulation, ransomware, corrupted files |
| ⚡ **Availability** | Systems and data are accessible when needed | Backups, redundancy, DDoS protection | Ransomware, denial-of-service, hardware failures |

> Every cybersecurity threat, control, and response maps back to one or more of these three goals.

Note: Have scouts try to categorize the threats they've heard of (ransomware, phishing, DDoS) into CIA categories. Most threats hit multiple categories.

---

## Requirement 4
# ⚠️ Threats, Vulnerabilities & Attacks

--

## 4a — Three Key Terms

**Vulnerability**
- A weakness in a system that could be exploited
- Example: a website that doesn't sanitize user input (SQL injection risk)

**Threat**
- A potential danger that could exploit a vulnerability
- Example: a hacker who knows about that SQL injection flaw

**Exploit**
- The actual technique or code used to take advantage of a vulnerability
- Example: the SQL injection attack string the hacker types into the form

--

## 4a — The Lock Analogy

Think of it like a physical lock:

| Cyber Term | Lock Analogy |
|---|---|
| **Vulnerability** | 🔓 A weak lock on your door |
| **Threat** | 🦹 A burglar who knows your neighborhood |
| **Exploit** | 🔧 The specific lockpick technique they use |

> A **threat** uses an **exploit** to attack a **vulnerability**.

Note: Use a lock analogy: vulnerability = weak lock, threat = burglar who knows your neighborhood, exploit = the specific lockpick technique they use.

--

## 4b — Types of Malware

**Pick one to research in depth. Here are your options:**

| Type | How It Works | Primary Harm |
|------|-------------|-------------|
| **Virus** | Attaches to legitimate files; spreads when file is shared | Corrupts data, spreads to other systems |
| **Worm** | Self-replicating; spreads across networks automatically | Consumes bandwidth, crashes systems |
| **Trojan** | Disguised as legitimate software | Opens backdoor for attacker access |
| **Backdoor** | Hidden access point planted by attacker | Persistent, secret access to system |
| **Spyware** | Silently monitors activity | Steals credentials, personal data |
| **Ransomware** | Encrypts your files; demands payment | Loss of data; financial extortion |

Note: Ransomware is the most impactful right now — billions of dollars paid annually, hospitals and schools targeted. The Colonial Pipeline attack (2021) is a powerful real-world example.

--

## 4c — Risks of Public Wi-Fi

**Risk 1: Man-in-the-Middle (MITM) Attacks**
- An attacker positions themselves between you and the router
- They can intercept everything you send and receive
- Reduction: use HTTPS sites only; use a VPN

**Risk 2: Evil Twin Networks**
- Attacker creates a fake Wi-Fi network with a convincing name ("Starbucks_Free")
- You connect to them instead of the real network
- They see all your traffic
- Reduction: verify the exact network name with staff; use your phone's hotspot instead

> Free Wi-Fi is not free — you're often paying with your data.

Note: This is immediately actionable advice that scouts can use today. Ask if any of them have ever connected to a Wi-Fi network without thinking about it.

--

## 4d — Spoofing and Phishing

**Spoofing**
- Faking an identity — an email address, a phone number, a website, a caller ID
- Goal: make you trust a malicious source
- Example: an email that looks like it's from your bank, but isn't

**Phishing**
- Using spoofed communications to trick you into giving up credentials or data
- Variations: smishing (SMS), vishing (voice), spear phishing (targeted)

--

## 4d — Recognizing and Preventing Phishing

**How to recognize it:**
- 🚨 Sense of urgency ("Act NOW or your account will be closed!")
- 📧 Mismatched sender addresses (support@amaz0n.com)
- 👤 Generic greetings ("Dear Customer" instead of your name)
- 🔗 Suspicious links — hover before you click

**How to protect yourself:**
- Never click links in unsolicited emails — go directly to the website
- Call the organization directly using a known number if uncertain
- Report phishing emails to your email provider

Note: Show scouts a real phishing email example if you have one. The mismatch between display name and actual email address is always revealing.

--

## 4e — Current Events (Choose ONE)

**Option 1: Research a Recent Cybersecurity Incident**
- Find a recent cyberattack in the news
- Explain: What happened? How did they get in? What was the impact?
- Good sources: Krebs on Security, Wired, The Record, Ars Technica

**Option 2: Movie or Book with Cybersecurity Themes**
- Watch or read something where cybersecurity plays a major role
- Evaluate: How realistic is it? What got it right? What was Hollywood fiction?
- Suggestions: *Mr. Robot* (TV), *Hackers* (film), *Countdown to Zero Day* (book)

Note: Mr. Robot is widely considered the most technically accurate cybersecurity depiction in mainstream media. Many security professionals recommend it.

--

## 4f — Your Cyber Attack Surface

Create a list of **all the ways someone could access your personal information or devices**.

**Think about:**
- 💻 Every device you own with internet access
- 🔑 Every account you have (email, social, gaming, streaming)
- 📱 Every app on your phone and what data it can access
- 🌐 Public information about you (social media, school directory, yearbook)
- 🚪 Physical access points (your unlocked phone, your laptop left open)

> The full picture often surprises people. Most of us have a much larger attack surface than we realize.

Note: This exercise is genuinely eye-opening. Have scouts actually list theirs on paper. Many will hit 20+ items.

---

## Requirement 5
# 🔒 Cyber Defenses

--

## 5a — Three Technologies That Defend Systems

**Access Controls**
- Who is allowed in, and what are they allowed to do?
- Examples: passwords, key cards, biometrics, role-based permissions

**Antivirus / Anti-Malware**
- Scans files and behavior for known threats and suspicious patterns
- Must be kept updated — new malware appears constantly

**Firewall**
- Monitors and filters network traffic based on rules
- Blocks unauthorized connections in and out

**Also worth knowing:**
- **IDS/IPS** — Intrusion Detection/Prevention Systems — watches for attack patterns
- **VPN** — Virtual Private Network — encrypts your traffic and masks your location

Note: Ask scouts which of these they have on their devices right now. Many won't know — that's the point.

--

## 5b — Why Updates Matter

**Why you need to install updates:**
- Software always has flaws — developers find and fix them constantly
- Updates patch known vulnerabilities before attackers can exploit them
- Unpatched systems are the #1 way attackers get in

**What problems updates prevent:**
- Malware that exploits known vulnerabilities
- Data breaches through software flaws
- Ransomware that targets old, unpatched systems

> The 2017 WannaCry ransomware attack infected 200,000+ computers in 150 countries — almost all were running unpatched Windows systems. Microsoft had released the patch 59 days earlier.

--

## 5b (2) — Checking and Installing Updates

**Demonstrate how to:**

1. Check for available updates on your operating system
   - Windows: Settings → Windows Update
   - macOS: System Settings → General → Software Update
   - iOS: Settings → General → Software Update
   - Android: Settings → System → System Update

2. Download and install available updates

3. Verify your system is up to date after installation

> Make this a monthly habit — or turn on automatic updates.

Note: Do this live with scouts if possible. Walk through the process on a device together.

--

## 5c — System Security (Choose THREE)

**You need to complete THREE of the following nine options:**

| # | Activity |
|---|----------|
| 1 | 🔑 Create a strong password |
| 2 | 📱 Set up multi-factor authentication |
| 3 | 🗄️ Install and use a password manager |
| 4 | 🛡️ Run a virus scan |
| 5 | 🖥️ View running processes (CLI) |
| 6 | 🌐 View open network connections (CLI) |
| 7 | 💾 Back up a mobile device |
| 8 | 📡 Create a home network security checklist |
| 9 | 🔍 Identify and fix home vulnerabilities |

--

## 5c Option 1 — Strong Passwords

**What makes a password strong?**
- At least 12 characters (longer is better)
- Mix of uppercase, lowercase, numbers, and symbols
- No real words, names, or predictable patterns
- Unique — never reused across accounts

**What makes a password weak?**
- "password", "123456", your birthday, your pet's name
- Anything someone who knows you could guess

**Demo:** Change one account password to a strong password together.

> A 12-character random password would take a modern computer **centuries** to crack by brute force.

Note: Use haveibeenpwned.com to show scouts whether their email address has appeared in known data breaches — powerful motivation.

--

## 5c Option 2 — Multi-Factor Authentication (MFA)

**What is MFA?**
- Requiring two or more forms of verification to log in
- Something you **know** (password) + something you **have** (your phone) + something you **are** (fingerprint)

**Why it matters:**
- Even if your password is stolen, attackers can't log in without your second factor
- MFA stops the majority of automated credential attacks

**Authenticator apps** (better than SMS codes):
- Google Authenticator
- Microsoft Authenticator
- Authy

**Demo:** Set up MFA on one account using an authenticator app.

Note: SMS-based MFA is better than nothing but vulnerable to SIM-swapping attacks. App-based authenticators are significantly more secure.

--

## 5c Option 3 — Password Manager

**What is a password manager?**
- An app that generates, stores, and autofills strong, unique passwords for every account
- Encrypted vault — only you can open it with your master password

**Why you need one:**
- Humans can't remember 50+ unique strong passwords
- Reusing passwords is the #1 cause of account takeovers
- Password managers eliminate both problems

**Good options:**
- Bitwarden (free, open source)
- 1Password
- Dashlane

**Demo:** Install and set up a password manager. Show how it works.

Note: Bitwarden is free, open source, and highly regarded by security professionals. It's a great recommendation for scouts.

--

## 5c Option 4 — Run a Virus Scan

**Demo:**

1. Open your antivirus or security software
2. Run a full system scan
3. Review the results with your counselor
4. Discuss: What was checked? What would happen if something was found?

> Windows Defender (built into Windows) is genuinely good and free. No excuses for not having antivirus.

Note: Walk through the scan process and explain what each category of results means.

--

## 5c Option 5 — View Running Processes (CLI)

**Using the command line, see what programs are running:**

**Windows:**
```
tasklist
```
or in PowerShell:
```
Get-Process
```

**macOS / Linux:**
```
ps aux
```
or interactively:
```
top
```

**Discuss with your counselor:**
- What processes are running? Do you recognize them all?
- How would you spot a suspicious process?
- What would you do if you found something unexpected?

Note: Sorting by CPU or memory usage can surface suspicious processes. Researching unknown process names is a real investigation skill.

--

## 5c Option 6 — View Open Network Connections (CLI)

**See what your computer is currently connected to:**

**Windows:**
```
netstat -an
```

**macOS / Linux:**
```
netstat -an
```
or:
```
ss -tuln
```

**Discuss results:**
- What external addresses is your computer connected to?
- Which ports are open and listening?
- Does anything look unexpected?

Note: Show scouts how to look up an IP address they don't recognize using a WHOIS tool. Seeing a connection to a known ad server vs. an unknown foreign IP tells very different stories.

--

## 5c Option 7 — Back Up a Mobile Device

**Demo: Back up data from a mobile device**

**iOS:**
- iCloud: Settings → [your name] → iCloud → iCloud Backup → Back Up Now
- Computer: Connect to iTunes/Finder → Back Up Now

**Android:**
- Settings → System → Backup → Back Up Now
- Google One backup

**Verify the backup completed:**
- Check the timestamp of the last backup
- Confirm what is included (photos, contacts, app data)

> A backup you haven't tested is not a backup — it's a hope.

--

## 5c Option 8 — Home Network Security Checklist

Research best practices and create a **checklist of 5 things** every home should do:

**Starting points to research:**
1. Change default router username and password
2. Use WPA3 (or at minimum WPA2) encryption on Wi-Fi
3. Create a separate guest network for visitors and IoT devices
4. Disable remote management on the router if not needed
5. Keep router firmware updated
6. Use a strong, unique Wi-Fi password
7. Disable WPS (Wi-Fi Protected Setup) — it has known vulnerabilities

Note: Have scouts actually look at their home router settings (with parent permission). Many default passwords are never changed.

--

## 5c Option 9 — Identify and Fix Home Vulnerabilities

**With permission from a parent or guardian:**

1. Scan your home network for connected devices
   - Tools: Fing app, your router's device list
2. Identify any that are:
   - Using default passwords
   - Running outdated firmware
   - Unnecessary or unrecognized
3. Research vulnerabilities for those specific devices
4. Fix what you can: update firmware, change passwords, disable unused features

> Every device on your network is a potential entry point.

---

## Requirement 6
# 🔐 Cryptography

--

## 6a — Where Encryption Is Used

Research **3 situations** where encryption is used in cybersecurity.

**Common examples:**

| Situation | Type of Encryption | Why |
|-----------|-------------------|-----|
| HTTPS websites | TLS/SSL | Protects data in transit between browser and server |
| Full-disk encryption | AES-256 | Protects data if device is stolen |
| End-to-end messaging (Signal, iMessage) | E2E encryption | Only sender and receiver can read messages |
| Password storage | Hashing (bcrypt, SHA) | Passwords stored as one-way hashes, not plain text |
| VPN connections | OpenVPN, WireGuard | Encrypts all internet traffic on a network |

Note: Emphasize that HTTPS is something scouts can check right now on any website. It directly affects their safety every day.

--

## 6b — Is Your Connection Encrypted?

**How to tell if a website connection is encrypted:**

1. Look for **HTTPS** at the start of the URL (not HTTP)
2. Look for the **padlock icon** in the browser address bar
3. Click the padlock to view the certificate details
   - Who issued the certificate?
   - When does it expire?
   - What domain is it valid for?

**What it means:**
- HTTPS = your traffic to that site is encrypted
- HTTP = anyone on the network can read what you send and receive

> Never enter passwords or payment info on an HTTP site.

Note: Pull up a browser together and visit both an HTTPS and HTTP site if you can find one. Show the difference.

--

## 6c — Cryptography Hands-On (Choose ONE)

**You need to complete ONE of the following:**

--

## Option 1 — Substitution Cipher

**Create your own encryption code:**

1. Design a substitution cipher (each letter maps to a different letter or symbol)
2. Encrypt a message using your cipher
3. Give the ciphertext to your counselor — they decrypt it using your key
4. Discuss:
   - **Strengths:** Simple, no technology needed, hard to read at a glance
   - **Weaknesses:** Vulnerable to frequency analysis (E is the most common letter in English), key management is difficult, not secure for real use

> This is how Julius Caesar communicated with his generals — the ROT13 cipher is a famous example.

--

## Option 2 — End-to-End Encryption App

**Download Signal (or another E2E app) and demonstrate it.**

**Explain:**
- **What E2E encryption means:** only the sender and recipient can read the message — not the app company, not the government, not anyone who intercepts it in transit
- **How it works:** each device has a key pair; messages are encrypted with the recipient's public key and can only be decrypted with their private key
- **Why it's more secure than SMS:** regular texts travel unencrypted through your carrier's servers; E2E messages are encrypted the entire way

Note: Signal is recommended by security researchers worldwide and used by journalists, activists, and security professionals. It's free and well-designed for non-technical users.

--

## Option 3 — File Integrity with Hashing

**Use a hashing tool to demonstrate file integrity.**

1. Create a simple text file
2. Generate a checksum (hash) using SHA-256 or MD5
3. Have your counselor modify the file (even one character)
4. Generate the hash again
5. Compare — the hashes will be completely different

**Explain:**
- Hash functions are one-way — you can't reverse a hash to get the original file
- Even a tiny change produces a completely different hash
- This is how software downloads are verified — download the file, check the hash

**Tools:** `sha256sum` (Linux/macOS), `Get-FileHash` (PowerShell), or online tools

--

## Option 4 — PGP Encryption

**Create your own PGP key pair and send an encrypted message.**

1. Install GPG (GNU Privacy Guard)
2. Generate a public/private key pair
3. Share your **public key** with your counselor
4. Send an encrypted message that only they can decrypt
5. Receive and decrypt an encrypted message they send you

**Explain:**
- Public key: share with everyone — used to encrypt messages TO you
- Private key: never share — used to decrypt messages sent to you
- This is how secure email works; also used to verify software signatures

Note: GPG Keychain (macOS) and Gpg4win (Windows) make PGP more accessible. This option is the most technically advanced but the most rewarding.

---

## Requirement 7
# 📡 Connected Devices & IoT

--

## The Internet of Things

**IoT** — any physical device connected to the internet that can send or receive data.

Describe **4 devices** — for each, explain:
- Why connectivity is useful
- What risks it creates
- How it could be protected

--

## Four IoT Devices to Explore (1/2)

**🌡️ Smart Thermostat (e.g., Nest)**
- Useful: remote control, energy savings, learning your schedule
- Risks: reveals when you're home or away; vulnerable to hijacking
- Protection: strong password, network segmentation, firmware updates

**📺 Smart TV**
- Useful: streaming, voice control, app ecosystem
- Risks: built-in microphones and cameras; often poorly secured; collects viewing data
- Protection: disable microphone/camera when not in use; keep firmware updated

--

## Four IoT Devices to Explore (2/2)

**📹 Home Security Camera**
- Useful: monitor your home remotely; deter crime
- Risks: video feed can be intercepted if poorly secured; some brands have had mass breaches
- Protection: strong unique password; two-factor authentication; buy from reputable brands

**🎮 Gaming Console**
- Useful: online multiplayer, digital purchases, media streaming
- Risks: stores payment info; mic and camera can be accessed; child accounts may be exposed
- Protection: parental controls; unique password; review connected app permissions

Note: The Mirai botnet (2016) hijacked 600,000+ IoT devices (mostly cameras and routers) with default passwords and used them to take down a large portion of the internet. Default passwords are the core IoT security failure.

--

## The Golden Rules of IoT Security

1. **Change default passwords immediately** — factory defaults are public knowledge
2. **Put IoT devices on a separate guest network** — keeps them isolated from your computers
3. **Keep firmware updated** — IoT devices get security patches too
4. **Disable features you don't use** — remote access, UPnP, unused ports
5. **Research before you buy** — does this company take security seriously?

> Every device you connect to the internet is a potential door into your network.

---

## Requirement 8
# 🏆 Cybersecurity Activities

**Choose ONE of the following:**

--

## Option A — Learn About a Competition or Camp

Research a cybersecurity competition or program:

**CyberPatriot** (nationalcybersecurity.com)
- BSA-affiliated national competition
- Teams defend virtual networks against simulated attacks

**picoCTF** (picoctf.org)
- Capture the Flag competition from Carnegie Mellon
- Challenges in cryptography, forensics, web hacking, reverse engineering

**SANS CyberStart** (cyberstart.com)
- Free beginner-friendly cybersecurity training

**Share with your counselor:**
- What is the competition about?
- What skills does it build?
- How could you participate?

Note: CyberPatriot is specifically Scout-friendly and has many BSA-affiliated teams. It's the strongest path forward for scouts who want to go deeper.

--

## Option B — Participate in a Competition

Actually compete in a cybersecurity competition.

Good starting points for beginners:
- **picoCTF** — always-on, self-paced challenges
- **CyberPatriot** — annual competition season (fall/winter)
- **SANS CyberStart** — structured beginner program

Discuss your experience with your counselor:
- What challenges did you attempt?
- What did you learn that you didn't know before?
- What would you do differently next time?

--

## Option C — Give a Presentation

Present a cybersecurity topic to a group.

**Requirements:**
- Must be at least one demonstration or hands-on activity
- Must teach the audience something they can apply

**Strong topic ideas:**
- How phishing attacks work — with a live example
- How to check if your passwords have been breached
- Setting up and using a password manager
- How to secure your home Wi-Fi network
- What to do if your account is hacked

> Demonstrating something live is far more memorable than slides alone.

Note: This is an excellent option for scouts who want to work toward the Public Speaking merit badge simultaneously.

---

## Requirement 9
# 🎯 Careers

**Choose ONE of the following:**

--

# 3.5 Million
### Unfilled cybersecurity jobs worldwide — and growing

--

## Option A — Research Cybersecurity Careers

**Step 1:** Identify **3 cybersecurity careers**

**Step 2:** Research **one fully:**
- What training, education, or certifications are required?
- What experience is needed to enter the field?
- What are the expenses associated with entering (school, certs, bootcamp)?
- What is the starting salary range?
- What are the advancement opportunities and long-term career goals?
- What are the job duties day-to-day?

**Step 3:** Discuss with your counselor.

Note: Top certifications to mention: CompTIA Security+, CEH (Certified Ethical Hacker), CISSP, OSCP. Many are achievable as a teenager with self-study.

--

## Option B — Visit a Cybersecurity Organization

Visit a business or organization that does cybersecurity work.

**Find out:**
- What roles exist on their security team?
- What do people in those roles actually do day-to-day?
- How did team members get their knowledge and credentials?
- What does a typical incident look like for them?

Then discuss what you learned with your counselor.

Note: Good targets: local banks, hospitals, tech companies, government agencies (FBI, CISA have public outreach programs), and university security research labs.

--

## Cybersecurity Careers at a Glance

| Career | What They Do |
|--------|-------------|
| Security Analyst | Monitor systems for threats, investigate incidents |
| Penetration Tester (Ethical Hacker) | Legally attack systems to find vulnerabilities before criminals do |
| Incident Responder | Contain and recover from active cyberattacks |
| Security Engineer | Design and build secure systems and infrastructure |
| Forensic Analyst | Investigate cybercrimes, recover and analyze evidence |
| Threat Intelligence Analyst | Track adversaries and predict future attacks |
| CISO (Chief Information Security Officer) | Lead an organization's entire security strategy |

> The field desperately needs new talent — this could be you.

---

## To Earn This Badge

Everything you need to demonstrate or discuss:

- ✅ **Req 1** — Watched Digital Safety video; explained digital footprint protection; discussed physical health and safety
- ✅ **Req 2** — Related 3 Scout Law points to internet behavior; discussed ethical scenarios
- ✅ **Req 3** — Described 3 types of systems needing protection; explained the CIA Triad
- ✅ **Req 4** — Defined vulnerability/threat/exploit; researched one malware type; identified Wi-Fi risks; explained spoofing/phishing; completed current events option; created attack surface list
- ✅ **Req 5** — Described 3 defensive technologies; explained and demonstrated updates; completed THREE system security activities
- ✅ **Req 6** — Researched 3 encryption uses; showed how to verify HTTPS; completed ONE hands-on cryptography activity
- ✅ **Req 7** — Described 4 IoT devices: usefulness, risks, and protections
- ✅ **Req 8** — Completed ONE cybersecurity activity (competition research, participation, or presentation)
- ✅ **Req 9** — Researched 3 careers and one in depth, OR visited a cybersecurity organization

Note: Walk through this checklist with scouts before final sign-off. Have them speak to each item.

---

## Resources

- **Have I Been Pwned** (check if your email was in a breach): [haveibeenpwned.com](https://haveibeenpwned.com)
- **Krebs on Security** (cybersecurity news): [krebsonsecurity.com](https://krebsonsecurity.com)
- **Bitwarden** (free open-source password manager): [bitwarden.com](https://bitwarden.com)
- **Signal** (end-to-end encrypted messaging): [signal.org](https://signal.org)
- **picoCTF** (beginner CTF competitions): [picoctf.org](https://picoctf.org)
- **CyberPatriot** (BSA-affiliated competition): [uscyberpatriot.org](https://uscyberpatriot.org)
- **SANS CyberStart** (free beginner training): [cyberstart.com](https://cyberstart.com)
- **CISA** (U.S. Cybersecurity & Infrastructure Security Agency): [cisa.gov](https://cisa.gov)
- **BSA Cybersecurity Merit Badge**: [scouting.org](https://www.scouting.org/merit-badges/cybersecurity/)

Note: These are all free or low-cost resources. Scouts can continue learning long after earning the badge.
