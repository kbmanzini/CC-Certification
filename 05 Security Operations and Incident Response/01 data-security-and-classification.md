# Data Security and Classification

## 1. What Is Data Security?

Data security is the practice of protecting information from unauthorized access, disclosure, alteration, destruction, or loss.

The goal is to protect data throughout its lifecycle:
- Creation
- Storage
- Use
- Sharing or transmission
- Archiving
- Disposal

## 2. Data Classification

Data classification organizes information according to its sensitivity and the level of protection it requires.

Common classification levels include:

| Classification | Meaning | Example |
|---|---|---|
| Public | Approved for anyone to access | Public website |
| Internal | Intended for an organization | Internal procedures |
| Confidential | Limited to authorized people | Employee records |
| Restricted | Highly sensitive information | Financial or highly sensitive business data |

Organizations may use different classification names.

## 3. Data Labeling

Data labeling identifies a document or resource's classification.

Examples:
- PUBLIC
- INTERNAL USE ONLY
- CONFIDENTIAL
- RESTRICTED

Labels help people recognize how information should be handled.

## 4. Data Masking

Data masking hides sensitive information while preserving enough of the data for a particular task.

Example:

Original:
`555-23-9876`

Masked:
`XXX-XX-9876`

Common uses:
- Software testing
- Training environments
- Customer service displays
- Reports that do not require complete information

Masking is not automatically encryption. It may permanently replace or hide parts of the original data.

## 5. Data Encryption

Encryption transforms readable information (plaintext) into unreadable information (ciphertext) using an algorithm and a key.

Only someone with the appropriate key can decrypt the information.

Common uses:
- Protecting files
- Securing network communications
- Protecting stored customer information
- Securing laptops and mobile devices

## 6. Data Sanitization

Data sanitization makes stored information unrecoverable or inaccessible before equipment is reused, transferred, or disposed of.

Methods can include:
- Secure erasure using appropriate tools
- Cryptographic erasure, where encryption keys are securely destroyed
- Physical destruction of storage media when necessary

Simply deleting a file or emptying the recycle bin may not securely remove its data.

## 7. Data at Rest, in Transit, and in Use

- **At rest:** Data stored on a device, server, or storage system.
- **In transit:** Data moving across a network.
- **In use:** Data currently being processed or accessed.

Different protections may be needed for each state.

## 8. Data Loss Prevention (DLP)

DLP technologies and policies help prevent sensitive information from being improperly shared, transferred, or exposed.

Examples:
- Detecting sensitive information in outgoing email
- Restricting unauthorized file transfers
- Monitoring uploads to external services
- Alerting on unusual data movement

## 9. Important Comparisons

| Term | Purpose |
|---|---|
| Classification | Determines how sensitive data is |
| Labeling | Marks data with its classification |
| Masking | Hides some or all sensitive values |
| Encryption | Makes data unreadable without a key |
| Sanitization | Removes data so it cannot be recovered through normal means |
| DLP | Helps prevent unauthorized data movement |

## Key Takeaways

- Classify data according to its sensitivity.
- Apply protections appropriate to the classification.
- Encryption protects confidentiality.
- Sanitization is important before equipment is reused or disposed of.
- Data must be protected throughout its lifecycle.