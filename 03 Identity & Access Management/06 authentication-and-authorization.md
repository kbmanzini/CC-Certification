# Authentication and Authorization

## Authentication

Authentication verifies a user's identity.

It answers:

> **Who are you?**

Examples include:

- Password
- PIN
- Security token
- Fingerprint
- Facial recognition

---

## Authorization

Authorization determines what an authenticated identity is allowed to access or do.

It answers:

> **What are you allowed to do?**

---

## Example

A user logs into a computer.

### Authentication

The system verifies the user's identity using their password.

### Authorization

The system determines that the user can access certain files but cannot access administrator settings.

---

## Authentication vs. Authorization

| Authentication | Authorization |
|---|---|
| Verifies identity | Determines permissions |
| "Who are you?" | "What can you do?" |
| Uses credentials/factors | Uses permissions/access rules |
| Happens before authorization | Follows successful authentication |

---

## Important Exam Concept

A user can be successfully authenticated but still not be authorized to access a particular resource.

### Example

You successfully log into a computer.

That does not automatically mean you can:

- Access another user's files
- Install software
- Change security settings
- Access restricted databases

---

## Memory Trick

**Authentication = Who?**

**Authorization = What?**