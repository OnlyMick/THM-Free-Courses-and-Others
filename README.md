# Free Cybersecurity Roadmap (TryHackMe & Beyond)

This repository is a sequential learning path designed to take you from absolute zero to mastering the fundamentals, leveraging the best free-tier resources available across multiple platforms: **TryHackMe, HTB Academy, HackMyVM, PortSwigger and OverTheWire**.

> **HTB Academy Cube System (Free Tier)**: All HTB Academy modules in this roadmap are **Tier 0**. They cost 10 Cubes to unlock but **refund the full 10 Cubes upon 100% completion**, making them completely free. New accounts start with 60 free Cubes, so you can chain Tier 0 modules forever at zero net cost. Unlock HTB modules strictly one at a time, in the order they appear. Do **NOT bulk unlock** from the dashboard.

> If any link 404s, search the module name in the [HTB Modules Library](https://academy.hackthebox.com/app/library/modules) (filter: Tier 0).

> **Note on THM rooms**: TryHackMe only allows 1 hour on their free-tier VMs before resetting them. For local machines (HackMyVM), download VMware/VirtualBox and use Host-Only networking. For THM guided rooms: The move is to **keep a local notepad with all your commands, findings, and flags**. When the 1-hour timer expires, just create a new free THM account, spin up the VM again, and copy-paste your way back to where you left off.

**Remember: Take notes, don't try to do everything in your head.**

---

## Phase 0: Onboarding & Setup
Learn how to use the platforms.

- [Tutorial](https://tryhackme.com/room/tutorial)
- [Welcome](https://tryhackme.com/room/welcome)
- [OpenVPN](https://tryhackme.com/room/openvpn)
- [Search Skills](https://tryhackme.com/room/searchskills)
- [HTB Academy: Intro to Academy](https://academy.hackthebox.com/app/module/15)

---

## Phase 1: Absolute Basics & Environment Setup
Learn the fundamentals of the operating systems you will be interacting with, the hacker mindset, and the human element of security.

### 1.1 Security Theory
- [HTB Academy: Introduction to Information Security](https://academy.hackthebox.com/app/module/293)
- [The CIA Triad (optional)](https://tryhackme.com/room/theciatriad)
- [Security Principles (optional)](https://tryhackme.com/room/securityprinciples)
- [Phishing Basics](https://tryhackme.com/room/phishingbasics)
- [The Hacker Methodology](https://tryhackme.com/room/hackermethodology)
- [Pentesting Fundamentals](https://tryhackme.com/room/pentestingfundamentals)
- [Careers in Cyber](https://tryhackme.com/room/careersincyber)

### 1.2 OS Fundamentals
- [HTB Academy: Setting Up](https://academy.hackthebox.com/app/module/87)
- [HTB Academy: Windows Fundamentals](https://academy.hackthebox.com/app/module/49)
- [HTB Academy: Linux Fundamentals](https://academy.hackthebox.com/app/module/18)
- [Linux Strength Training](https://tryhackme.com/room/linuxstrengthtraining)
- [Inside a Computer System](https://tryhackme.com/room/insideacomputer)
- [Operating Systems: Introduction](https://tryhackme.com/room/operatingsystemsintroduction)
- [Data Representation](https://tryhackme.com/room/datarepresentation)
- [Data Encoding](https://tryhackme.com/room/dataencoding)

### End-of-Phase
- [OverTheWire: Bandit (levels 0-17)](https://overthewire.org/wargames/bandit/)

---

## Phase 2: Networking & Web Theory
Learn how machines communicate, how the web works, and the most critical web vulnerability frameworks before touching any exploitation tool.

### 2.1 Networking
- [HTB Academy: Introduction to Networking](https://academy.hackthebox.com/app/module/34)
- [Introductory Networking (optional)](https://tryhackme.com/room/introtonetworking)
- [Intro to LAN](https://tryhackme.com/room/introtolan)
- [DNS in Detail](https://tryhackme.com/room/dnsindetail)
- [Network Services](https://tryhackme.com/room/networkservices)

### 2.2 Web Fundamentals
- [HTB Academy: Introduction to Web Applications](https://academy.hackthebox.com/app/module/75)
- [Web Application Basics (optional)](https://tryhackme.com/room/webapplicationbasics)
- [HTTP in Detail](https://tryhackme.com/room/httpindetail)
- [Web Security Essentials](https://tryhackme.com/room/websecurityessentials)

---

## Phase 3: Scripting & The Hacker's Tooling
Learn to automate tasks and master the industry-standard tools for scanning, content discovery, password cracking, and network analysis.

### 3.1 Scripting & Utilities
- [Python: Core Concepts](https://tryhackme.com/room/pythoncoreconcepts)
- [Bash Scripting](https://tryhackme.com/room/bashscripting)
- [Regular Expressions](https://tryhackme.com/room/catregex)
- [CyberChef: The Basics](https://tryhackme.com/room/cyberchefbasics)

### 3.2 Reconnaissance & Scanning
- [Google Dorking](https://tryhackme.com/room/googledorking)
- [Shodan.io](https://tryhackme.com/room/shodan)
- [Nmap Basic Port Scans](https://tryhackme.com/room/nmap02)
- [OpenVAS (optional)](https://tryhackme.com/room/openvas)

### 3.3 Network Traffic Analysis
- [HTB Academy: Network Packet Analysis](https://academy.hackthebox.com/app/module/325)
- [HTB Academy: Intro to Network Traffic Analysis](https://academy.hackthebox.com/app/module/81)
- [Network Traffic Basics (optional)](https://tryhackme.com/room/networktrafficbasics)
- [TShark (optional)](https://tryhackme.com/room/tshark)

### 3.4 Web Tooling & Exploitation Frameworks
- [Content Discovery](https://tryhackme.com/room/contentdiscoveryx)
- [HTB Academy: Attacking Web Applications with Ffuf](https://academy.hackthebox.com/app/module/54)
- [ffuf (optional)](https://tryhackme.com/room/ffuf)
- [Hydra](https://tryhackme.com/room/hydra)
- [Metasploit: The Basics](https://tryhackme.com/room/metasploitthebasics)
- [HTB Academy: Using the Metasploit Framework](https://academy.hackthebox.com/app/module/39)

### End-of-Phase
- [Simple CTF](https://tryhackme.com/room/easyctf)
- [OverTheWire: Bandit (levels 18-34)](https://overthewire.org/wargames/bandit/)

---

## Phase 4: Web Exploitation & Crypto
Understand how web applications are attacked.

> **Note on proxies**: THM teaches [OWASP ZAP](https://www.zaproxy.org/download/) for free. Use ZAP to learn the concepts of proxying and intercepting, then download [Burp Suite Community Edition](https://portswigger.net/burp/downloads) to use with PortSwigger later.

### 4.1 Web Foundations & OWASP
- [HTB Academy: Web Requests](https://academy.hackthebox.com/app/module/35)
- [Introduction to OWASP ZAP](https://tryhackme.com/room/learnowaspzap)
- [OWASP Top 10 2025: IAAA Failures](https://tryhackme.com/room/owasptopten2025three)
- [OWASP Top 10 2025: Insecure Data Handling](https://tryhackme.com/room/owasptopten2025one)
- [OWASP Top 10 2025: Application Design Flaws](https://tryhackme.com/room/owasptopten2025two)
- [Broken Access Control](https://tryhackme.com/room/owaspbrokenaccesscontrol)

### 4.2 Web Vulnerabilities
- [HTB Academy: SQL Injection Fundamentals](https://academy.hackthebox.com/app/module/33)
- [SQL Injection Introduction (optional)](https://tryhackme.com/room/sqlinjectionintroduction)
- [SQLMAP](https://tryhackme.com/room/sqlmap)
- [XSS](https://tryhackme.com/room/axss)
- [CSRF](https://tryhackme.com/room/csrfV2)
- [SSRF](https://tryhackme.com/room/ssrfhr)
- [HTB Academy: File Inclusion](https://academy.hackthebox.com/app/module/23)
- [Insecure Deserialisation](https://tryhackme.com/room/insecuredeserialisation)
- [Introduction to Flask](https://tryhackme.com/room/flask)
- [SSTI](https://tryhackme.com/room/learnssti)

### 4.3 Cryptography
- [Cryptography Basics](https://tryhackme.com/room/cryptographybasics)
- [Breaking Crypto the Simple Way](https://tryhackme.com/room/breakingcryptothesimpleway)

### End of THM for the Phase
- [c4ptur3-th3-fl4g](https://tryhackme.com/room/c4ptur3th3fl4g)

### External Academy: PortSwigger
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [PortSwigger Labs](https://portswigger.net/web-security/all-topics) — Complete the "Apprentice" labs for: SQL Injection, XSS, CSRF, SSRF, OS Command Injection, Path Traversal, Access Control, and Authentication.
- [PortSwigger Labs Solutions](https://github.com/ricardojoserf/Portswigger-Labs#1)

---

## Phase 5: Initial Exploitation & Easy CTFs
Time to put it all together. These guided rooms and easy CTFs will teach you how to gain that initial foothold in a machine.

### 5.1 Methodology & Transversal Skills
- [HTB Academy: Introduction to Penetration Testing](https://academy.hackthebox.com/app/module/295)
- [HTB Academy: File Transfers](https://academy.hackthebox.com/app/module/24)
- [Basic Pentesting (optional)](https://tryhackme.com/room/basicpentestingjt)

### 5.2 Guided CTFs
- [Vulnversity](https://tryhackme.com/room/vulnversity)
- [Bounty Hacker](https://tryhackme.com/room/cowboyhacker)
- [Agent Sudo](https://tryhackme.com/room/agentsudoctf)
- [Fowsniff CTF](https://tryhackme.com/room/ctf)
- [Overpass](https://tryhackme.com/room/overpass)
- [Blue](https://tryhackme.com/room/blue)
- [Ignite](https://tryhackme.com/room/ignite)
- [Develpy](https://tryhackme.com/room/bsidesgtdevelpy)

### End-of-Phase (Local Lab)
> **Note**: Download the VM and run it locally on VMware or VirtualBox. Make sure to put the VM on a **Host-Only network**. If you get stuck, search GitHub for `"HackMyVM [Machine Name] writeup"`.

- [HackMyVM: Driftingblues3](https://hackmyvm.eu/machines/machine.php?vm=Driftingblues3)
- [HackMyVM: Driftingblues5](https://hackmyvm.eu/machines/machine.php?vm=Driftingblues5)
- [HackMyVM: Driftingblues6](https://hackmyvm.eu/machines/machine.php?vm=Driftingblues6)

**If you don't want to follow the Saga:**
- [HackMyVM: Gift](https://hackmyvm.eu/machines/machine.php?vm=Gift)
- [HackMyVM: First](https://hackmyvm.eu/machines/machine.php?vm=First)
- [HackMyVM: Pwned](https://hackmyvm.eu/machines/machine.php?vm=Pwned) *(Recommended)*

---

## Phase 6: Privilege Escalation
You are inside the machine, but you are just a low-privileged user. Learn how to become root/Administrator.

### 6.1 Post-Exploitation & Hash Cracking
- [Post-Exploitation Basics](https://tryhackme.com/room/postexploit)
- [Crack the hash](https://tryhackme.com/room/crackthehash)
- [Crack The Hash Level 2](https://tryhackme.com/room/crackthehashlevel2)

### 6.2 Linux Privilege Escalation
- [Linux Privilege Escalation: Enumeration](https://tryhackme.com/room/linprivenum)
- [Linux Privilege Escalation](https://tryhackme.com/room/linuxprivesc)
- [Sudo Security Bypass](https://tryhackme.com/room/sudovulnsbypass)
- [Linux PrivEsc Arena](https://tryhackme.com/room/linuxprivescarena)
- [Linux Process Analysis](https://tryhackme.com/room/linuxprocessanalysis)

### 6.3 Windows Privilege Escalation
- [Windows PrivEsc](https://tryhackme.com/room/windows10privesc)
- [Bypassing UAC](https://tryhackme.com/room/bypassinguac)
- [Windows PrivEsc Arena](https://tryhackme.com/room/windowsprivescarena)

### End-of-Phase (Local Lab)
> **Note**: Make sure to put the VM on a **Host-Only network**.

- [HackMyVM: Driftingblues7](https://hackmyvm.eu/machines/machine.php?vm=Driftingblues7)
- [HackMyVM: Driftingblues8](https://hackmyvm.eu/machines/machine.php?vm=Driftingblues8)
- [HackMyVM: Driftingblues9](https://hackmyvm.eu/machines/machine.php?vm=Driftingblues9)

**If you don't want to follow the Saga:**
- [HackMyVM: Noob](https://hackmyvm.eu/machines/machine.php?vm=Noob)
- [HackMyVM: Friendly](https://hackmyvm.eu/machines/machine.php?vm=Friendly)

---

## Phase 7: Red Team Operations, Active Directory & Specialized Vectors
The corporate environment, offensive infrastructure, alternative attack vectors and professional reporting.

### 7.1 Red Team Foundations & Frameworks
- [Red Team Fundamentals](https://tryhackme.com/room/redteamfundamentals)
- [HTB Academy: MITRE ATT&CK Framework](https://academy.hackthebox.com/app/module/332)
- [OPSEC](https://tryhackme.com/room/opsec)
- [Writing Pentest Reports](https://tryhackme.com/room/writingpentestreports)

### 7.2 Active Directory
- [HTB Academy: Introduction to Active Directory](https://academy.hackthebox.com/app/module/74)
- [Intro to AD Authentication (optional)](https://tryhackme.com/room/introtoactivedirectoryauthentication)
- [AD: Basic Enumeration](https://tryhackme.com/room/adbasicenumeration)
- [Intro to AD Breaching](https://tryhackme.com/room/introductiontoactivedirectorybreaching)
- [Attacktive Directory](https://tryhackme.com/room/attacktivedirectory)

### 7.3 Wireless
- [Wifi Hacking 101](https://tryhackme.com/room/wifihacking101)
- [Wireless Security](https://tryhackme.com/room/wirelesssecurity)

### End-of-Phase
- [Relevant](https://tryhackme.com/room/relevant)
- [Internal](https://tryhackme.com/room/internal)

---

## Phase 8: Reverse Engineering & Malware Analysis
Take the software apart to understand how it works.

### 8.1 Architecture & Assembly
- [x86 Architecture Overview](https://tryhackme.com/room/x8664arch)
- [Windows Reversing Intro](https://tryhackme.com/room/windowsreversingintro)
- [Windows x64 Assembly](https://tryhackme.com/room/win64assembly)
- [Dissecting PE Headers](https://tryhackme.com/room/dissectingpeheaders)
- [Reversing ELF](https://tryhackme.com/room/reverselfiles)

### 8.2 Exploitation Fundamentals
- [Intro To Pwntools](https://tryhackme.com/room/introtopwntools)
- [ret2libc](https://tryhackme.com/room/ret2libc)
- [HTB Academy: Stack-Based Buffer Overflows on Linux x86](https://academy.hackthebox.com/app/module/31)
- [HTB Academy: Stack-Based Buffer Overflows on Windows x86](https://academy.hackthebox.com/app/module/89)

### 8.3 Malware Analysis Basics
- [MAL: Malware Introductory](https://tryhackme.com/room/malmalintroductory)
- [MAL: Researching](https://tryhackme.com/room/malresearching)

### End-of-Phase
- [Basic Malware RE](https://tryhackme.com/room/basicmalwarere)
- [Gatekeeper](https://tryhackme.com/room/gatekeeper)
- [OverTheWire: Leviathan](https://overthewire.org/wargames/leviathan/) **OR** [OverTheWire: Behemoth](https://overthewire.org/wargames/behemoth/)

---

## Phase 9: Blue Team & Defense
Understand the defensive side of cybersecurity.

### 9.1 SOC Fundamentals & Monitoring
- [SOC Fundamentals](https://tryhackme.com/room/socfundamentals)
- [Intro to Detection Engineering](https://tryhackme.com/room/introtodetectionengineering)
- [Incident Response Process](https://tryhackme.com/room/incidentresponseprocess)
- [Intro to Log Analysis](https://tryhackme.com/room/introtologanalysis)
- [HTB Academy: Threat Hunting with SIEM](https://academy.hackthebox.com/app/module/329)
- [Introduction to SIEM (optional)](https://tryhackme.com/room/introtosiem)
- [Windows Logging for SOC](https://tryhackme.com/room/windowsloggingforsoc)
- [Linux Logging for SOC](https://tryhackme.com/room/linuxloggingforsoc)
- [Monitoring Active Directory](https://tryhackme.com/room/monitoringactivedirectory)

### 9.2 Threat Intelligence & Hunting
- [Threat Intelligence for SOC](https://tryhackme.com/room/threatintelligenceforsoc)
- [HTB Academy: Cyber Kill Chain](https://academy.hackthebox.com/app/module/331)
- [HTB Academy: Identifying Threats and Malicious Software](https://academy.hackthebox.com/app/module/333)
- [HTB Academy: Phishing Email Analysis](https://academy.hackthebox.com/app/module/540)
- [Phishing Analysis Fundamentals (optional)](https://tryhackme.com/room/phishingemails1tryoe)
- [HTB Academy: Threat Hunting for C2 with RITA](https://academy.hackthebox.com/app/module/328)
- [C2 Detection - Command & Carol (optional)](https://tryhackme.com/room/detecting-c2-with-rita-aoc2025-m9n2b5v8c1)
- [Threat Hunting With YARA](https://tryhackme.com/room/threathuntingwithyara)

### 9.3 Digital Forensics & Incident Response
- [HTB Academy: DFIR with EDR](https://academy.hackthebox.com/app/module/330)
- [Intro to Digital Forensics](https://tryhackme.com/room/introdigitalforensics)
- [Memory Analysis Introduction](https://tryhackme.com/room/memoryanalysisintroduction)
- [Volatility Essentials](https://tryhackme.com/room/volatilityessentials)

### End-of-Phase
- [h4cked](https://tryhackme.com/room/h4cked)
- [SOC L1 Alert Triage](https://tryhackme.com/room/socl1alerttriage)

---

## Final Capstone CTFs
These are not learning rooms, they are practical challenges.

- [0day](https://tryhackme.com/room/0day)
- [dogcat](https://tryhackme.com/room/dogcat)
- [The Marketplace](https://tryhackme.com/room/marketplace)
- [Mr Robot CTF](https://tryhackme.com/room/mrrobot)

---

## Advanced Tracks (Optional Specializations)
These are still free-tier courses, so they don't go into much depth. After choosing **ONE** specialization, you will need to look for paid courses. You might find something else for free on YouTube, but usually without hands-on practice.

### Advanced Web Hacking (Insane CTFs Prep)
- [OWASP Juice Shop](https://tryhackme.com/room/owaspjuiceshop)
- [OWASP Mutillidae II](https://tryhackme.com/room/owaspmutillidae)
- [SQL Injection Lab](https://tryhackme.com/room/sqlilab)
- [HTTP Request Smuggling](https://tryhackme.com/room/httprequestsmuggling)
- [HTTP/2 Request Smuggling](https://tryhackme.com/room/http2requestsmuggling)
- [Advanced SQL Injection](https://tryhackme.com/r/room/advancedsqlinjection)
- [NoSQL Injection](https://tryhackme.com/r/room/nosqlinjectiontutorial)
- [Race Conditions](https://tryhackme.com/room/raceconditions)
- [Chaining Vulnerabilities](https://tryhackme.com/room/chainingvulnerabilitiesZp)
- [WAF: Introduction](https://tryhackme.com/room/wafintroduction)
- [Detecting Web Attacks](https://tryhackme.com/room/detectingwebattacks)

**External:**
- [PortSwigger (Practitioner and Expert labs)](https://portswigger.net/web-security)
- [OverTheWire: Natas (Levels 11-34)](https://overthewire.org/wargames/natas/)

### Advanced Red Team
- [Attacktive Directory (Review)](https://tryhackme.com/room/attacktivedirectory)
- [AD Certificate Templates](https://tryhackme.com/room/adcertificatetemplates)
- [Enterprise](https://tryhackme.com/room/enterprise)
- [RazorBlack](https://tryhackme.com/room/raz0rblack)
- [VulnNet: Active](https://tryhackme.com/room/vulnnetactive)
- [Investigating Windows](https://tryhackme.com/room/investigatingwindows)
- [Investigating Windows 2.0](https://tryhackme.com/room/investigatingwindows2)
- [Investigating Windows 3.x](https://tryhackme.com/room/investigatingwindows3)
- [Registry Persistence Detection](https://tryhackme.com/room/registrypersistencedetection)

**External:**
- [GOAD (Local Lab — pay attention to minimum requirements)](https://github.com/Orange-Cyberdefense/GOAD)

### Advanced Malware Analysis & Reverse Engineering
- [Aster](https://tryhackme.com/room/aster)
- [Classic Passwd](https://tryhackme.com/room/classicpasswd)
- [REloaded](https://tryhackme.com/room/reloaded)
- [JVM Reverse Engineering](https://tryhackme.com/room/jvmreverseengineering)
- [Malware Classification](https://tryhackme.com/room/malwareclassification)
- [Introduction to EDR](https://tryhackme.com/room/introductiontoedrs)
- [APT28 Inception Theory](https://tryhackme.com/room/apt28inceptiontheory)
- [Linux Function Hooking](https://tryhackme.com/room/linuxfunctionhooking)
- [File and Hash Threat Intel](https://tryhackme.com/room/fileandhashthreatintel)
- [Dunkle Materie](https://tryhackme.com/room/dunklematerieptxc9)
- [Android Malware Analysis](https://tryhackme.com/room/androidmalwareanalysis)

**External:**
- [OverTheWire: Narnia](https://overthewire.org/wargames/narnia/)
- [Crackmes.one](https://crackmes.one/)
- [MalwareBazaar](https://bazaar.abuse.ch/)

### Advanced DFIR & Blue Team
- [IR Timeline Analysis](https://tryhackme.com/room/dfirtimelineanalysis)
- [Digital Forensics Case B4DM755](https://tryhackme.com/room/caseb4dm755)
- [Memory Forensics](https://tryhackme.com/room/memoryforensics)
- [Compromised Windows Analysis](https://tryhackme.com/room/compromisedwindowsanalysis)
- [Servidae: Log Analysis in ELK](https://tryhackme.com/room/servidae)
- [Splunk: Exploring SPL](https://tryhackme.com/room/splunkexploringspl)
- [Windows Incident Surface](https://tryhackme.com/room/winincidentsurface)
- [Linux Incident Surface](https://tryhackme.com/room/linuxincidentsurface)
- [Linux Threat Detection 1](https://tryhackme.com/room/linuxthreatdetection1)

**External:**
- [CyberDefenders.org](https://cyberdefenders.org/)

### Cloud, Containers & Modern Infrastructure
- [Cloud Security Pitfalls](https://tryhackme.com/room/cloudsecuritypitfalls)
- [Intro to Docker](https://tryhackme.com/room/introtodockerk8pdqk)
- [Insekube](https://tryhackme.com/room/insekube)
- [K8s Runtime Security](https://tryhackme.com/r/room/k8sruntimesecurity)
- [K8s Best Security Practices](https://tryhackme.com/r/room/k8sbestsecuritypractices)
- [Cluster Hardening](https://tryhackme.com/r/room/clusterhardening)

**External:**
- [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)
