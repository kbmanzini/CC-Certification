# Domain 5 Review — Security Operations and Incident Response

## 1. Domain Overview

Domain 5 covers how organizations protect information, monitor security activity, understand threats, respond to incidents, manage assets, and evaluate security controls.

The main areas in these notes are:

1. Data security and classification
2. Encryption and hashing
3. Logging, monitoring, and SIEM
4. Security event triage
5. Threat actors and threat intelligence
6. Threat frameworks
7. Incident response and exercises
8. Asset and configuration management
9. Security testing and teaming

## 2. Important Definitions

| Term | Definition |
|---|---|
| Data classification | Organizing data by sensitivity |
| Data masking | Hiding sensitive information |
| Data sanitization | Making stored data unrecoverable or inaccessible |
| Encryption | Transforming readable data into protected ciphertext |
| Hashing | Producing a fixed-length digest from data |
| Digital signature | Helps verify authenticity and integrity |
| PKI | Infrastructure for managing public keys and certificates |
| Log | Record of an event |
| SIEM | System for collecting and analyzing security events |
| Event | An observable occurrence |
| Alert | Notification that activity may require attention |
| Incident | An event or series of events that threatens security |
| IOC | Indicator that may suggest compromise |
| Threat actor | Individual or group that may cause harm |
| Threat intelligence | Analyzed information about threats |
| Asset inventory | Record of organizational assets |
| Configuration baseline | Approved system configuration |
| Configuration drift | Difference between actual and approved settings |
| Vulnerability | A weakness that could be exploited or cause harm |
| Threat modeling | Process for identifying potential threats and weaknesses |

## 3. Comparisons to Know

### Symmetric vs. Asymmetric Encryption

- Symmetric: One shared secret key.
- Asymmetric: Public and private key pair.

### Encryption vs. Hashing

- Encryption: Designed to be reversed with the correct key.
- Hashing: Designed to be one-way.

### Event vs. Alert vs. Incident

- Event: Something happened.
- Alert: A tool or person flags something for attention.
- Incident: A security-impacting event or series of events.

### SIEM vs. Log Management

- Log management: Collects and stores logs.
- SIEM: Collects, correlates, and analyzes security events.

### False Positive vs. False Negative

- False positive: Reports a threat that is not actually present.
- False negative: Fails to detect an actual threat.

### Threat Intelligence vs. Threat Hunting

- Threat intelligence: Information about threats.
- Threat hunting: Proactively searches for possible threats.

### Vulnerability Assessment vs. Penetration Testing

- Vulnerability assessment: Identifies and evaluates weaknesses.
- Penetration testing: Evaluates security through authorized testing.

### SAST vs. DAST

- SAST: Examines code without running the application.
- DAST: Tests a running application.

### Red vs. Blue vs. Purple Team

- Red: Evaluates defenses.
- Blue: Defends and responds.
- Purple: Encourages collaboration and improvement.

## 4. Incident Response Lifecycle

Know the general sequence:

1. Preparation
2. Detection and analysis
3. Containment
4. Eradication
5. Recovery
6. Lessons learned

Remember:
- Containment limits impact.
- Eradication addresses the cause.
- Recovery restores services.
- Lessons learned improve future response.

## 5. NIST Cybersecurity Framework 2.0

Know all six functions:

1. Govern
2. Identify
3. Protect
4. Detect
5. Respond
6. Recover

## 6. MITRE ATT&CK

Know these terms:

- Tactic: An adversary's goal.
- Technique: How the adversary attempts to achieve that goal.
- Procedure: A specific implementation of a technique.

## 7. Practice Questions

Choose the best answer for each question.

### Question 1
Which process organizes information according to sensitivity?

A. Data masking  
B. Data classification  
C. Hashing  
D. Monitoring  

### Question 2
Which method transforms readable data into ciphertext?

A. Hashing  
B. Logging  
C. Encryption  
D. Sanitization  

### Question 3
Which type of encryption uses the same secret key to encrypt and decrypt?

A. Symmetric  
B. Asymmetric  
C. Hashing  
D. Digital signing  

### Question 4
What is the primary purpose of hashing?

A. To route network traffic  
B. To create a fixed-length digest  
C. To decrypt a file  
D. To assign permissions  

### Question 5
What does SIEM stand for?

A. Secure Internet Encryption Management  
B. Security Information and Event Management  
C. System Integrity Evaluation Method  
D. Security Identity Enforcement Model  

### Question 6
What is a false positive?

A. A real threat that goes undetected  
B. A harmless event incorrectly reported as a threat  
C. A confirmed security incident  
D. A missing log entry  

### Question 7
What is the purpose of security triage?

A. Delete all alerts  
B. Prioritize and evaluate alerts  
C. Replace all security policies  
D. Encrypt every log file  

### Question 8
What is an IOC?

A. An indicator that may suggest a compromise  
B. A type of encryption  
C. A cloud service model  
D. An asset inventory  

### Question 9
Which type of threat intelligence focuses on high-level business risks and trends?

A. Technical  
B. Tactical  
C. Strategic  
D. Operational  

### Question 10
Which framework organizes adversary tactics and techniques?

A. MITRE ATT&CK  
B. DHCP  
C. AES  
D. SIEM  

### Question 11
Which NIST CSF 2.0 function focuses on discovering possible cybersecurity events?

A. Govern  
B. Protect  
C. Detect  
D. Recover  

### Question 12
Which incident response phase limits the impact of an incident?

A. Preparation  
B. Containment  
C. Recovery  
D. Lessons learned  

### Question 13
What is chain of custody?

A. A record of who handled evidence and when  
B. A list of network devices  
C. A method of encrypting backups  
D. A software update schedule  

### Question 14
What is a tabletop exercise?

A. A live attack against a production system  
B. A discussion-based incident response exercise  
C. A type of firewall  
D. A data classification method  

### Question 15
What does configuration drift mean?

A. A system's settings differ from its approved baseline  
B. A system has been securely erased  
C. A user changes their password  
D. A network connection becomes encrypted  

### Question 16
Why are end-of-support systems a security concern?

A. They always have too much storage  
B. They may no longer receive security updates  
C. They cannot connect to a network  
D. They automatically encrypt all data  

### Question 17
Which testing method examines application code without running the application?

A. DAST  
B. SAST  
C. SIEM  
D. DLP  

### Question 18
Which team primarily focuses on defending systems and responding to threats?

A. Red team  
B. Blue team  
C. Purple team  
D. Audit team  

### Question 19
What is threat modeling used for?

A. Identifying potential threats and weaknesses  
B. Assigning IP addresses  
C. Creating user passwords  
D. Replacing incident response plans  

### Question 20
What should happen after a security weakness is corrected?

A. Ignore the finding  
B. Delete all documentation  
C. Retest to verify the correction  
D. Disable all monitoring  

## 8. Answer Key

1. B — Data classification  
2. C — Encryption  
3. A — Symmetric  
4. B — A fixed-length digest  
5. B — Security Information and Event Management  
6. B — A harmless event incorrectly reported as a threat  
7. B — Prioritize and evaluate alerts  
8. A — An indicator that may suggest a compromise  
9. C — Strategic  
10. A — MITRE ATT&CK  
11. C — Detect  
12. B — Containment  
13. A — A record of evidence handling  
14. B — A discussion-based exercise  
15. A — Settings differ from the approved baseline  
16. B — They may no longer receive security updates  
17. B — SAST  
18. B — Blue team  
19. A — Identifying potential threats and weaknesses  
20. C — Retest to verify the correction  

## 9. Final Study Checklist

Before taking the exam, make sure you can explain these concepts without looking at your notes:

- [ ] Data classification and labeling
- [ ] Data masking and sanitization
- [ ] Data at rest, in transit, and in use
- [ ] Symmetric and asymmetric encryption
- [ ] Hashing and digital signatures
- [ ] PKI and digital certificates
- [ ] Logs and SIEM
- [ ] False positives and false negatives
- [ ] Events, alerts, and incidents
- [ ] Security triage and IOCs
- [ ] Threat actors and motivations
- [ ] Threat intelligence types
- [ ] MITRE ATT&CK
- [ ] NIST CSF 2.0
- [ ] Incident response lifecycle
- [ ] Tabletop exercises
- [ ] Chain of custody
- [ ] Asset inventories and asset lifecycles
- [ ] End-of-life and end-of-support systems
- [ ] Configuration baselines and drift
- [ ] SAST vs. DAST
- [ ] Vulnerability assessments vs. penetration testing
- [ ] Red, blue, and purple teams
- [ ] Threat modeling

**Study tip:** Focus on understanding what each concept does, why an organization uses it, and how it differs from similar concepts. Those distinctions are especially useful when answering certification questions.