This course item explains the concept of network mapping, its tools, and its significance in cybersecurity.

Network Mapping and Tools:

Network mapping is the process of visualizing a network's physical and logical connections, including devices like routers, switches, firewalls, and servers.
Nmap is a popular open-source tool used for network discovery and security auditing, identifying devices, open ports, operating systems, and potential security risks.
Wireshark is a network protocol analyzer that captures and displays detailed network traffic, helping analyze data packets and detect anomalies.

Benefits for Cybersecurity Professionals:

Network mapping helps manage complex networks by clearly showing components and connections, aiding in troubleshooting and planning expansions.
It supports security by detecting unauthorized devices or changes, enabling proactive network management and documentation.

Use by Attackers:

Attackers use network mapping to identify vulnerabilities, unguarded entry points, and defenses within a network.
They leverage this information to navigate networks stealthily, prioritize targets, and craft tailored attacks such as phishing or social engineering campaigns.



This course item explains the concept of packet sniffing as an internet security threat and how it is used by both IT professionals and attackers.

Packet and Packet Sniffing Basics:

Packets are small units of data transmitted over networks, consisting of a header (with source and destination IP addresses and packet number) and a payload (the actual data).
Packet sniffing is the technique of capturing and analyzing these data packets as they travel through a network, often by placing a network interface card into promiscuous mode to capture all traffic.

Uses of Packet Sniffing:

IT professionals use packet sniffing for network diagnostics, performance monitoring, and monitoring web and communication activity within authorized networks.
Attackers use packet sniffing illegally to intercept unencrypted sensitive information such as personal identifiers, financial data, and login credentials.

Types of Packet Sniffing and Protection Strategies:

Passive sniffing involves discreetly monitoring data on networks like LANs or WiFi without detection, while active sniffing manipulates network traffic to intercept packets on switched networks.
Protection strategies include regularly updating software, using strong passwords and multi-factor authentication, being cautious with emails, using VPNs on public WiFi, and prioritizing HTTPS encrypted websites.



This course item explains the concept of IP spoofing, its use in cyberattacks, and defense mechanisms.

IP Spoofing and Its Role in Attacks:

IP spoofing involves altering the source IP address in packet headers to hide the sender's true identity or impersonate another host.
It is commonly used in distributed denial of service (DDoS) attacks to flood targets with traffic while concealing attacker identities.

Types of Attacks Using IP Spoofing:

Botnets use IP spoofing to mask the identities of compromised devices controlled by attackers, making tracking difficult.
Man-in-the-middle attacks intercept and modify communications between two systems by forging IP addresses to access sensitive data or redirect users.

Defense Mechanisms Against IP Spoofing:

Ingress filtering inspects incoming packets at network entry points to block those with forged or suspicious source IP addresses.
Egress filtering checks outgoing packets to prevent internal devices from sending spoofed packets, adding a layer of protection.



This course content explains denial of service (DoS) attacks, their types, and defenses against them.

Types of DoS Attacks:

Ninja attack: A targeted, single-packet attack exploiting protocol rules or buffer overflows to crash a system immediately.
Death by 1000 cuts: Multiple small attacks like SYN flood, where many incomplete connection requests consume system resources gradually.
Distributed Denial of Service (DDoS): An attack using a botnet of compromised systems to flood a target with overwhelming traffic from many sources.

Defenses Against DoS Attacks:

Infinite capacity is ideal but impractical; redundancy with multiple systems helps avoid single points of failure.
Pacing and filtering incoming traffic can limit attack impact; egress filtering helps prevent attacks from originating within your network.
Hardening systems by removing unnecessary services, changing default credentials, and patching software reduces vulnerabilities.

Monitoring and Response:

Continuous monitoring helps distinguish between legitimate high traffic and attacks using tools like SIEM and XDR.
Incident response with dynamic playbooks enables quick, effective action to mitigate attacks and minimize damage.



This course item explains injection attacks, focusing on SQL injection and cross-site scripting (XSS), their mechanisms, and consequences.

Injection Attacks Overview:

Injection attacks involve inserting malicious code into queries or web applications to manipulate data or execute unauthorized commands.
These attacks exploit vulnerabilities in systems, often older ones, causing unauthorized data access or control.

SQL Injection:

SQL injection tricks databases into executing unintended commands, allowing attackers to access or manipulate sensitive data.
Consequences include breaches of confidentiality, compromised authentication, loss of authorization controls, and data integrity violations.

Cross-Site Scripting (XSS):

XSS attacks embed harmful scripts into web pages, which execute on users' browsers, stealing data or altering content.
There are two main types: server-side XSS (reflected and stored) and client-side XSS (reflected and stored), differing by where and how the malicious scripts are injected and executed.



This course content explains the concept and importance of security controls in protecting organizational assets from threats.

Types of Security Controls:

Administrative controls involve policies, procedures, and training to ensure proper security practices by employees and stakeholders.
Physical controls protect tangible assets like hardware and facilities through measures such as biometric security and alarm systems.
Technical controls use hardware, software, or firmware to safeguard information confidentiality, integrity, and availability, including firewalls and intrusion detection systems.

Integration of Controls:

Effective security requires combining administrative, physical, and technical controls based on risk assessment.
For example, securing a data center involves access policies (administrative), biometric locks (physical), and firewalls (technical).

Functions of Security Controls:

Deterrent controls: discourage security violations by signaling consequences or monitoring.

Preventive controls: aim to stop incidents before they occur by blocking unauthorized actions.

Detective controls: identify and alert to security breaches or suspicious activities.

Corrective controls: address and mitigate the impact of security incidents and prevent recurrence.

Example Application:

In a server room, CCTV serves as a detective physical control, lockdown protocols as corrective, signage as deterrent, and key card access as preventive control.
Overall, security controls are essential to maintain confidentiality, integrity, and availability of critical information and assets by preventing, detecting, and responding to threats.



This course content explains how different types of cybersecurity controls—administrative, physical, and technical—align with various control functions to protect an organization's assets.

Control Types and Their Functions:

Controls are categorized by their primary functions: preventive, detective, deterrent, and corrective.
Each control type contributes differently to safeguarding information, personnel, and assets.

Administrative Controls:

Include policies for hiring, data classification, separation of duties, and security awareness training.
Serve functions such as enforcing rules, monitoring employee activity, conducting audits, and implementing incident response plans.

Physical Controls:

Comprise gates, locks, fences, surveillance cameras, security guards, and environmental monitoring.
Aim to physically prevent unauthorized access, detect intrusions, deter threats, and maintain or repair security measures.

Technical Controls:

Consist of antivirus software, firewalls, multifactor authentication, intrusion detection systems, and security information and event management (SIEM) systems.
Focus on preventing, detecting, and correcting technical vulnerabilities and unauthorized access through software and hardware solutions.



This course item explains the concept of system security, its importance, and the key methods and tools used to protect computer systems.

Definition and Importance of System Security:

A computer system includes hardware and software components like CPU, memory, input/output devices, and storage that perform computing operations.
System security protects these systems and their data from unauthorized access, damage, or theft, preventing disruptions from minor issues to major failures.

Methods to Maintain System Security:

Access controls restrict resource access to authorized users through passwords, two-factor authentication, biometrics, and VPNs.
Encryption secures data confidentiality by encoding information so only those with the decryption key can access it.
Patching involves updating software to fix vulnerabilities and improve security.
Regular backups create copies of data to restore systems after data loss or cyberattacks.

Tools for System Security:

System-level firewalls monitor and control network traffic on individual computers to block unauthorized access.
Antivirus software scans for and protects against viruses and malware using updated threat databases.



This course item explains the concept of network security, its objectives, and the various tools and methods used to protect network infrastructure.

Network Security Overview:

Network security protects networking infrastructure from unauthorized access, exploitation, or theft by establishing a secure environment for devices, programs, users, and applications.
It uses a multilayered defense approach called defense in depth, with barriers at the network perimeter and internal safeguards to protect critical components.

Primary Objectives of Network Security:

Block unauthorized entities from accessing network assets.
Identify and stop ongoing cyber threats and infractions.
Ensure legitimate users can securely access network resources when needed.

Key Network Security Tools and Techniques:

Firewalls filter unauthorized or malicious traffic at network entry points, ranging from basic packet filtering to advanced AI-powered next-generation firewalls.
Network Access Control (NAC) manages user authentication and device risk assessments to control network entry and permissions.
Intrusion Detection and Prevention Systems (IDPS) monitor traffic beyond firewalls to detect and proactively respond to threats.
Virtual Private Networks (VPNs) encrypt internet traffic and mask IP addresses, securing remote connections.
Network segmentation divides networks into smaller segments with unique policies to limit attacker movement and contain breaches.
Endpoint security protects devices like computers and mobile devices using antivirus, antimalware, and personal firewalls.
Security Information and Event Management (SIEM) systems aggregate and analyze security data to detect and respond to threats in real time.
Security Orchestration, Automation, and Response (SOAR) platforms automate security workflows and incident responses to improve efficiency and reduce alert fatigue.



This course item focuses on the concept of application security by design within the software development lifecycle (SDLC).

Software Development Lifecycle (SDLC):

SDLC is a structured sequence of stages in software development: planning, requirements analysis, design, programming, testing, deployment, and maintenance.
It is commonly used in large-scale developments to organize and manage the software creation process.

Importance of Application Security:

Application security involves integrating secure practices throughout every phase of the SDLC to protect against increasing digital threats and cyberattacks.
The goal is to detect, resolve, and prevent security issues from the design stage through maintenance, known as security by design.

Key Secure Coding Practices:

Input validation ensures data is correct and safe before processing, preventing attacks like SQL injection.
Error handling manages software errors gracefully to avoid crashes or vulnerabilities.
Secure logging tracks activities while protecting logs from unauthorized access.
Avoid hardcoded credentials to prevent unauthorized access by storing sensitive information securely.
Access control restricts data and functionality access to authorized users only.
Encryption protects sensitive data during storage and transmission using trusted cryptography libraries.
Software security testing identifies vulnerabilities before deployment to ensure robust defense against attacks.



This course item focuses on the vulnerability management process in cybersecurity, emphasizing how organizations identify, assess, and mitigate security weaknesses in their digital environments.

Vulnerability Management Process:

The first step is to define and categorize potential scan targets, including all devices, applications, and systems connected to the network.
Maintaining an up-to-date inventory and grouping assets by function and criticality helps prioritize and schedule scans effectively.

Vulnerability Scanning and Tools:

Regular automated scans are essential to detect new vulnerabilities quickly, ideally scheduled during off-peak hours to minimize disruption.
Selecting scanning tools with robust assessment capabilities, scalability, and clear reporting is crucial; notable tools include Nessus (proprietary) and OpenVAS (open source).

Application Security Testing Techniques:

Application vulnerability scanning integrates into the software development lifecycle using three main techniques: Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), and Interactive Application Security Testing (IAST).
Proper configuration of scans balances depth and system impact, using plugins and updates to improve accuracy and prioritize remediation efforts.



This course item covers the importance of incident response (IR) and digital forensics in cybersecurity, emphasizing the need for organizations to have a structured IR strategy to handle inevitable security incidents.

Incident Response Lifecycle:

The IR lifecycle consists of four key phases: preparation and planning; detection and analysis; containment, eradication, and recovery; and post-incident activities.
Preparation involves forming an IR team with diverse expertise, defining roles, and establishing communication channels, while detection requires tools like intrusion detection systems and SIEM to identify suspicious activities.

Role of Digital Forensics in Incident Response:

Digital forensics provides the tools and techniques to collect, preserve, and analyze digital evidence, helping to understand the nature and impact of security incidents.
It supports attribution of attacks, aids recovery efforts, and informs improvements in security measures through detailed documentation and maintaining a strict chain of custody for evidence.

Post-Incident Activities and Continuous Improvement:

After recovery, organizations conduct post-incident reviews to identify weaknesses and update their IR plans based on lessons learned.
Effective incident management is a continuous process that strengthens defenses against future cyber threats and ensures clear communication with stakeholders.



