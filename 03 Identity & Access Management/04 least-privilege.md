# Principle of Least Privilege

## Definition

The Principle of Least Privilege means giving a user, process, device, or system only the permissions necessary to perform its authorized task.

### Example

A help desk employee needs to reset user passwords.

They do not need administrator access to every server.

Giving them only the permissions necessary for password resets follows least privilege.

---

## Why Least Privilege Matters

Least privilege can reduce:

- Unauthorized access
- Accidental changes
- Damage from compromised accounts
- Attack surface
- Potential impact of security incidents

---

## Least Privilege Applies To

Least privilege can apply to:

- Human users
- Applications
- Services
- Devices
- Service accounts
- Automated processes

---

## Just-in-Time Access

Just-in-time access provides elevated permissions only when they are needed and for a limited period.

### Example

An administrator normally does not have permanent access to a sensitive production system.

When maintenance is required, temporary elevated access is granted.

After the task is complete, the elevated access expires.

This reduces the amount of time powerful permissions are available.

---

## Key Idea

Give an identity:

**Only the access necessary**

and, when possible:

**Only for the time necessary**

---

## Memory Trick

**Least privilege = Least access necessary**