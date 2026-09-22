# CIA Triad

The CIA Triad is a fundamental cybersecurity model consisting of:

- Confidentiality
- Integrity
- Availability

These principles help organizations protect information and systems.

---

## Confidentiality

### What it means

Confidentiality means preventing information from being accessed or disclosed by people who are not authorized to see it.

### Examples

- Passwords
- Access permissions
- Encryption
- Multi-factor authentication (MFA)
- Access control systems

### Example

A hospital stores patient records. Only authorized employees should be able to view those records.

If an unauthorized person accesses the records, confidentiality has been violated.

### Remember

**Confidentiality = Who can see it?**

---

## Integrity

### What it means

Integrity means protecting information from unauthorized or accidental changes and maintaining its accuracy and completeness.

### Examples

- Hashing
- Digital signatures
- Access controls
- Checksums
- Version control

### Example

A company's database contains an employee's salary information. Someone changes the salary without authorization.

The information was improperly modified, so integrity was violated.

### Remember

**Integrity = Has it been changed or corrupted?**

---

## Availability

### What it means

Availability means ensuring that authorized users can access systems and information when they need them.

### Examples

- Backups
- Redundant systems
- Disaster recovery
- System monitoring
- Protection against denial-of-service attacks

### Example

A hospital's computer system goes offline and doctors cannot access important records.

The information may still be secure, but authorized users cannot access it.

This is an availability problem.

### Remember

**Availability = Can authorized users access it when they need it?**

---

# CIA Triad Example

Imagine an online banking system.

### Confidentiality

Only authorized customers and employees should be able to view account information.

### Integrity

Unauthorized people should not be able to change account balances or transactions.

### Availability

Customers should be able to access their accounts when they need them.

---

# How the Three Work Together

A secure system needs to consider all three principles.

For example, a system could have:

- Excellent confidentiality but poor availability if nobody can access the data.
- Excellent availability but poor confidentiality if everyone can access the data.
- Good confidentiality and availability but poor integrity if attackers can secretly change the data.

Security controls should therefore protect the appropriate CIA requirements based on the organization's risks.

---

# Quick Exam Questions

### Who can see the information?

**Confidentiality**

### Was the information changed without authorization?

**Integrity**

### Can authorized users access the information when needed?

**Availability**

---

# My Understanding

The CIA Triad gives me three questions to ask about a system:

1. **Confidentiality:** Who is allowed to see the information?
2. **Integrity:** Can I trust that the information has not been improperly changed?
3. **Availability:** Can authorized users access it when they need it?

The three principles work together to protect information and systems.