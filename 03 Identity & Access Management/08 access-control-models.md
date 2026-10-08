# Access Control Models

## Overview

Access control models define how decisions are made about who can access resources.

Important models include:

- Discretionary Access Control (DAC)
- Mandatory Access Control (MAC)
- Role-Based Access Control (RBAC)

---

# Discretionary Access Control (DAC)

In DAC, the owner of a resource can decide who receives access.

### Example

A user creates a folder and chooses which coworkers can read or modify it.

The owner has discretion over access.

### Key Idea

**DAC = Owner decides**

---

# Mandatory Access Control (MAC)

In MAC, access is controlled by centrally defined security rules and classifications.

Users generally cannot change access simply because they own a resource.

### Example

A system may classify information according to security levels.

Access is based on established security rules and authorization levels.

### Key Idea

**MAC = Mandatory rules decide**

---

# Role-Based Access Control (RBAC)

In RBAC, permissions are assigned to roles.

Users are assigned to the appropriate roles.

### Example

An organization creates:

**HR Role**
- Employee records
- Benefits system

**Help Desk Role**
- Support systems
- Password-reset tools

**Accounting Role**
- Accounting applications
- Financial records

### Key Idea

**RBAC = Role decides**

---

# Comparison

| Model | Main Idea |
|---|---|
| DAC | Resource owner controls access |
| MAC | Centrally enforced rules control access |
| RBAC | Access is based on role |

---

# Memory Trick

**DAC → Owner**

**MAC → Mandatory**

**RBAC → Role**