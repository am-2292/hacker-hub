# hacker-hub
A starter hub for RBOIS hacking

## Communities
- OWASP: Community focused on improving software security.
- DEF CON Forums: Community for meetups and finding nearby people with similar interests in hacking and security research.
- FIRST: A large community of security and incident response professionals, connecting practitioners in similar industries along with government, and academia sectors. 
- Red Team Village: Community focused on offensive security and red teaming.
- Infosec.Exchange: Community focused on information security, useful for following researchers and finding niche discussions.

## Researchers
- SpecterOps: Publishes deep technical content providing useful information for red-team, identity, and attack-path research.
- Bishop Fox: Publishes red teaming guidance, strategy, and tooling overviews.
- TrustedSec: Content revolves around red team blogs, tradecraft discussions, and lessons learned engagement.
- Mandiant/Google Group: Provides content on adversary behavior, and modern intrusion trends.
- CISA: Publishes real-life findings and common weaknesses observed during assessments.
- DFIR Report: A collection of real-world incident responses from investigations.

## Tooling
- MITRE ATT&CK: categorizes adversary techniques into subcomponents along the attack phases. 
### CLI and GUI Tools
- NMAP: Ever wonder what devices are connected to your network, open ports, or actively running services? This tool will show it. 
- Wireshark: Performs deep packet analysis on all traffic traversing through your network. Capturing details about visited websites, connected protocols, as well as any unencrypted passwords sent over the network.
- Metasploit: Considered the toolbox inside the toolbox. It’s an exploitation framework meaning it’s used in labs to test how systems respond to known vulnerabilities. It gives you understanding how vulnerabilities are categorized, and how payloads work. Study the moves to learn how to defend against them.
- BurpSuite: Ever wonder happens between your browser and a website when you click login? That’s what BurpSuite reveals. It identifies websites containing insecure cookies and improperly configured forms. Additionally, it serves as a web proxy, giving users the ability to review and modify, if needed, web requests before submission. 
- Aircrack NG: Is a suite of tools that teaches users about Wi-Fi security. Capturing wireless packets to help users understand how encryption types such as WPA2/WPA3 work through analysis.
- Hydra: It’s a password testing login tool. It tries different username/password combinations to see how easy it is to guess credentials. 
- John the Ripper/Hashcat: Both are password hash analysis tools. They don’t steal passwords; they test the strength of hashed ones. These tools try to reverse week ones. You can use test hashes in a controlled environment, see how different algorithms behave, and realize that even one missing capital letter can make a password a thousand times easier to guess.
- Nikto: The webserver detective. Nikto scans websites to identify common security issues, outdated software, exposed directories, or missing headers. It doesn’t hack it just reports what’s wrong. It’s the first step in finding problems before bad actors do. Run it on your own servers or local lab; it’s a great way to understand web hygiene.
- Enum4linux: It’s about information gathering. It’s used to enumerate or map out windows and SMB services on a network. Basically, it asks what users exist here, what shares are open, what policies are set.
- SQLMap: It’s a tool that researchers use to test SQL injections. It automates the detection of database vulnerabilities in test environments. Remember you don’t run this on real sites. Use lab apps like DBWA (damn vulnerable web app) to see how queries can be exploited and fix. Understanding SQLMap conceptually teaches you one big thing, never trust user input in your web apps.
- OWASP Zap: The open-source sibling of BurpSuite. Zap scan for common web flaws, Cross-site scripting, misconfigurations, insecure cookies, and visualizes everything neatly. It’s beginner friendly, open-source, and a perfect place to start learning about web security scanning. 
- NetCat (NC): You can use it to create simple connections between devices, send data, check open ports, and even transfer files. It’s powerful in debugging and learning how raw network communications really work.
### AI Tools
- GPTShield: Secures AI tools, preventing malicious prompt attempts and data leaks. 
- AIM-Hacker: Analyzes code looking for vulnerabilities, generating fixes that developers can use for patching identified weaknesses.
- DarkMentor: A chatbot that was trained on leaked hacking guides. It is an underground tutor for cyber criminals. 
- CodeXploit: Generates and tests exploits using AI-powered fuzzying. 
### GADGETS
- PROXMARK3: An RFID/NFC hacking tool. It can read, clone, and crack access cards used in offices, hotels, and secure buildings. 
- KEYLOGGERS: This tool records every single keystroke on the device it is directly connected to. 
- LAN TURTLE: Once plugged into the network, it secretly gives remote access to the hacker. It can sniff traffic, monitor communications, and install persistent backdoors in the network. 
- USB KILLER: When connected, this tool will release a high voltage surge into the USB port, effectively frying the motherboard causes permanent damage to the computer. Hackers use this for sabotage, while security professionals use it for stress testing the hardware. 
- HACKEF ONE: It is a software defined radio. It can transmit and receive almost any radio signal, from walkie-talkies, garage doors, satellite, and aircraft systems. With it, hackers can jam signals, replay them, or clone them. Ethical researchers use them to test wireless protocols. 
- RUBBER DUCKY USB: This tool executes pre-loaded code once plugged in, generating open command terminals, disabling antivirus software, creating backdoors, along with stealing data. 
- FLIPPER ZERO: This tool uses RFIDs, NFCs, RF frequencies, etc. once cloned to bypass access controls.
- WIFI PINEAPPLE: It creates a fake Wi-Fi hotspot that appears legitimate. It can intercept data as well as perform website redirection and malware injections on any connect device, without the device owner’s knowledge.
### MOBILE APPS
- Droid Sheep: This app allows you to intercept web session profiles over a network. It can capture session cookies, allowing you to test the security of web applications and ensure they are protected against session hi-jacking. 
- AndroRat: A remote admin and security tool for identifying device vulnerabilities.
- Zanti: This is a mobile penetration testing toolkit that lets you assess the security of your network, detailing recommendations for securing any identified vulnerabilities.
- Fing Fing: Actively scan your network, providing detailed information on connected devices as well as alerting you to any unauthorized devices detected in your network. 
- dSploit: This tool is capable of performing man-in-the-middle attacks, allowing you to intercept and modify network traffic. 
- USD Cleaver: This app is designed to gather information from connected windows devices, capable of extracting passwords, and Wi-Fi keys, in addition to other sensitive data. 
- Orbot: Anonymizes your online activities, allowing you access to previously censored websites and services.
### OSINT
- Google Dorking: Indexes massive amounts of information from websites across the internet. Attackers use advanced search operators called Google Dorks to find sensitive information which includes exposed documents, login portals, confidential files, and personal data. 
- Dehashed: It is a great tool for searching through data breaches and compromised credentials. It is a massive database of leaked information. 
- Lookups.io: Pulls data from hundreds of public sources to build detailed profiles.
- Urlscan.io: A web-based sandbox that analyzes websites.
- Hunter.io: Handy for finding emails linked to domains. 
- Pipl: Allows you to perform deep dive research into a person’s online presence.
- SpiderFoot: Scans hundreds of publicly available sources to help you build a profile on your target. 
- Censys: Scans hundreds of publicly available sources for potentially exposed servers, services, and certificates.
- Exploit Database: Archives public exploit codes and vulnerabilities. Ideal for studying real-world attack techniques and finding real-world vulnerable surfaces using dorks.  
- Maltego It’s the tool you want when you need to map relationships and connections between people, organizations, and infrastructure. It allows you to visualize data and follow threads across networks. 
- Have I PWNED: Crucial for checking if your information has been involved in any data breach. 
- Burp Suite/Web Security Academy: is a web security tool and free training platform. One of the most widely used tools for finding web vulnerabilities and learning exploitation.
## Writeups/Case Studies
- The DFIR Report Case Studies: Publishes detailed breakdowns of real cyber intrusions. 
- PortSwigger Web Security Research: Publishes articles on new web attack techniques, detailing how discovered vulnerabilities can be weaponized.
- SpecterOps Blog: Publishes research articles on advanced attacks used in enterprise environments. 
- SANS Reading Room: Publishes in-depth technical papers that covers a plethora of cybersecurity topics.
## Events/Conferences
- DEF CON: A hacker conference where the latest tools, newest exploits, and advanced research are presented.
- Black Hat: A conference that delivers technical briefings and training in cybersecurity. Releases high-quality research and recorded talks for learning.
- Red Team Village Content: A collection of talks and training content from Red Team Village events. Focuses specifically on offensive security techniques and real-world tactics.
- Rabbit Holes
- Null Byte: A resource for hands-on hacking tutorials, walkthroughs, and guides that is focused on app exploitation, Wi-Fi hacking, OSINT, social engineering (Facebook), and tool usage. 

## Rabbit Holes
### GitHub Repositories
#### Reverse Engineering Tooling
- Tools analyzing compiled binaries and malware to understand how malicious software works.
- 1.	Ghidra
- 2.	Ida-pro
#### Advanced Red Team Tools
- PowerUpSQL: A tool for discovering, auditing, and exploiting Microsoft SQL server environments.
- MicroBurst: A PowerShell toolkit for attacking and auditing Microsoft Azure environments.
- PowerHuntShares: A tool to find and analyze overly permissive SMB file shares in Active Directory environments.
- Inveigh Zero: A Windows-based spoofing and man-in-the-middle tool. 
- RayV Lite: A hardware hacking tool for exploiting microchips.

## Obscure Resources
- LOLBAS Project: A list of legitimate Windows binaries that can be abused by attackers. Showing how attackers use built-in tools instead of malware to evade detection.
- GTFOBins: A list of Unix binaries that can be exploited for privilege escalation.
- Malware Traffic Analysis: A site with real packet captures and malware traffic examples. Lets you practice analyzing real malicious network activity.
- LiveOverflow: A YouTube channel that walks through hard to understand hacking concepts.
### PODCASTS
- 1.	Darknet Diaries 
- 2.	Hacker Public Radio
- 3.	Off the Hook
- 4.	Hack the Planet
- 5.	H4unted Hacker
## Starter Projects
- 1.	Create malware with Python (I created malware with Python)
- 2.	Hacking websites with BurpSuite
- 3.	How to Catch Hackers (How to build a Honeypot and Catch Hackers)


