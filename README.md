# Cyber Security

#### Technical Skills: Splunk, Qradar, Crowdstrike, Qualys, Tenable Nessus, Lacework, Cisco Umbrella, Jira, Confluence, Docker, Kubernetes, AWS, Azure( Sentinel, Defender for EndPoint), GCP, Frameworks (MITRE ATT&CK, Cyber Kill Chain), Active Directory,Network Security Groups, Autopsy, FTK Imager, SIFT, WireShark, TCPdump, Python, Powershell

## Education						       		
- M.Eng, Cybersecurity Engineering	 | University of Maryland at College Park (_May 2024_)	 			        		
- B.Tech, Electronics and Communication Engineering | Jawaharlal Nehru Technological University Hyderabad (_May 2019_)

## Work Experience
**Security Operations Intern @ Workiva, Inc (_May 2023 - Present_)**
- Implemented secure cloud configurations by identifying common cloud misconfigurations in AWS, Azure and GCP, resulting in a notable reduction in security incidents over the same time interval.
- Assisted in Incident Response of various security threats and anomalies to identify the root cause analysis and provide assistance with the mitigations.
- Identified indicators of misconfigurations and indicators of attack, contributing to enhanced threat detection and mitigation efforts.
- Established policies to identify suspicious and unused software, effectively reducing the attack surface and strengthening overall security posture.
- Setting up Splunk Alerts for the security tooling and SOPs for SOC team monitoring.
- Developed an automated dashboard to show the current excluded and blocked cloud or endpoint processes that streamlined communication and collaboration across teams, improving overall efficiency.


**Detection and Response Analyst @ Deloitte (_July 2019 - August 2022_)**
- Utilized client-specific SIEM tools (Splunk/Qradar/Sentinel) for ongoing alerts, reducing false positives by 20% through alert tuning.
- Developed Alerts using Kusto Query Language and created Standard Operating Procedures.
- Proficient in triaging Windows Event Logs, Syslogs, Web Firewall Traffic, DNS, and Okta Logs for comprehensive log analysis.
- Leveraged Endpoint Security Tools to perform further investigation into host devices and successfully contain identified security incidents.


## Projects
**Penetration Testing of a Active Directory Network**
- Network Details: two Windows hosts, one Windows server, one Ubuntu server, Insecure AWS S3 Bucket.
- Tools Used: Kali Linux, NMAP, Metasploit, smbclient, gobuster, John The Ripper, Hashcat, Powershell.
- Documented the vulnerabilities and necessary recommendations in a Penetration Test Report.
- Vulnerabilities and Misconfiguration Indentfied
  - Ubuntu Server with sensitive Information ( Username )
  - A Windows 7 Host with Eternal Blue Vulnerability ( CVE-2017-0144 )
  - Keepass Password Manager Vulnerability ( CVE-2023-32784 )
  - S3 Bucket containing sensitive files with public read access
**Forensic Investigation of a Compromised Windows Machine**
- Artifact: Windows XP VM
- Tools Used: Autopsy, SIFT Work Station, Base64 Decoder, Veracrypt, Wireshark, VirusTota
- Documented the findings in a Forensic Report in legal format.
- Findings:
  - Found a suspicious .exe process running on the machine.
  - Extracted the suspicious process and analysed them for network traffic.
  - Found the processes to be sending malcious messages to a C2 server.
  - Found encrypted files on the machine and decrypted them using veracrypt and obtained pass key from the network traffic.

