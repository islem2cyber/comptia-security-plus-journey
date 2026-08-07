# Use Data Sources to Support an Investigation Quiz

Test your understanding of the data sources and evidence used during cybersecurity investigations.

---

# Part 1 — Multiple Choice Questions

## Question 1

Which type of log records successful and failed user login attempts?

A. DNS Logs  
B. Authentication Logs  
C. NetFlow Logs  
D. Web Server Logs

---

## Question 2

Which Windows Event Log primarily records security-related events such as logins and privilege changes?

A. Application Log  
B. Setup Log  
C. Security Log  
D. System Log

---

## Question 3

Which Linux directory contains most system log files?

A. /usr/log
B. /home/log
C. /var/log
D. /etc/log

---

## Question 4

Which network log helps identify which device was assigned a specific IP address?

A. DNS Log
B. DHCP Log
C. VPN Log
D. Proxy Log

---

## Question 5

Which data source records complete network packets for detailed forensic analysis?

A. NetFlow
B. PCAP
C. DNS Logs
D. Authentication Logs

---

## Question 6

What information does NetFlow primarily provide?

A. Complete packet contents
B. Network traffic metadata and flow statistics
C. File system changes
D. Email attachments

---

## Question 7

Which endpoint artifact can reveal websites visited by a user?

A. Registry Keys
B. Browser History
C. Event Viewer
D. NetFlow

---

## Question 8

Which cloud logging service records AWS API activity?

A. Azure Activity Logs
B. Google Cloud Audit Logs
C. AWS CloudTrail
D. Amazon Inspector

---

## Question 9

What is the primary purpose of a SIEM during an investigation?

A. Encrypt files
B. Centralize, correlate, and analyze security events
C. Replace antivirus software
D. Configure firewalls

---

## Question 10

Why is evidence correlation important?

A. It deletes duplicate logs.
B. It combines evidence from multiple sources to reconstruct incidents.
C. It encrypts investigation data.
D. It reduces storage requirements.

---

# Part 2 — True or False

## Question 11

Firewall logs can show allowed and blocked network connections.

- True
- False

---

## Question 12

DNS logs may reveal communication with malicious domains.

- True
- False

---

## Question 13

Packet captures (PCAP) contain the full contents of network traffic.

- True
- False

---

## Question 14

Authentication logs are not useful during account compromise investigations.

- True
- False

---

## Question 15

Maintaining the chain of custody helps preserve the integrity and legal admissibility of evidence.

- True
- False

---

# Part 3 — Scenario-Based Questions

## Question 16

An analyst needs to determine which workstation was using the IP address **192.168.10.55** during a security incident.

Which data source should be reviewed first?

A. DNS Logs
B. DHCP Logs
C. NetFlow
D. Browser History

---

## Question 17

Investigators suspect malware communicated with an external command-and-control server. They need to inspect the actual packets exchanged.

Which data source provides the most detailed evidence?

A. NetFlow
B. PCAP
C. Windows Security Log
D. Authentication Log

---

## Question 18

A SOC analyst receives alerts from firewalls, IDS, endpoints, Active Directory, and cloud services. They need one platform to correlate all events and build a complete attack timeline.

Which technology should be used?

A. Antivirus
B. SIEM
C. VPN
D. DHCP

---

## Question 19

During an investigation, analysts discover suspicious login attempts followed by privilege escalation and malware execution. These events were identified by combining authentication logs, endpoint logs, and firewall logs.

What investigation technique made this possible?

A. Port Scanning
B. Evidence Correlation
C. Disk Defragmentation
D. Data Compression

---

## Question 20

An investigator carefully documents who collected a hard drive, when it was collected, every person who handled it afterward, and verifies its hash before analysis.

What investigation principle is being followed?

A. Patch Management
B. Threat Hunting
C. Chain of Custody
D. Vulnerability Scanning

---

# Answer Key

| Question | Answer |
|----------|--------|
| 1 | B |
| 2 | C |
| 3 | C |
| 4 | B |
| 5 | B |
| 6 | B |
| 7 | B |
| 8 | C |
| 9 | B |
| 10 | B |
| 11 | True |
| 12 | True |
| 13 | True |
| 14 | False |
| 15 | True |
| 16 | B |
| 17 | B |
| 18 | B |
| 19 | B |
| 20 | C |

---

# Score

| Score | Result |
|--------|--------|
| **18–20** | Excellent – You have a strong understanding of investigation data sources, evidence collection, and log correlation. |
| **15–17** | Good – You understand most concepts. Review PCAP, NetFlow, cloud logs, and evidence correlation. |
| **10–14** | Fair – Revisit the lesson, especially log sources, SIEM, and chain of custody. |
| **Below 10** | Review the notes carefully before moving on to the next domain. |