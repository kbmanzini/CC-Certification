# Service Accounts and Automated Identities

## Service Accounts

A service account is an account used by an application, service, or automated process instead of a normal human user.

### Example

A database application uses a service account to connect to a database.

---

## Security Considerations

Service accounts should:

- Have only required permissions
- Use protected credentials
- Be monitored
- Be reviewed regularly
- Be disabled when no longer needed

---

## Automated Identities

IAM applies to more than human users.

Organizations may manage identities for:

- Applications
- Services
- Devices
- Automated processes
- Bots
- Other systems

---

## Least Privilege for Automated Systems

Automated identities should receive only the permissions they need.

### Example

An application only needs to read information from a database.

It should not automatically have permission to:

- Delete the database
- Modify unrelated records
- Create administrator accounts

---

## AI and IAM

Automated or AI-based systems can have identities and permissions that must be managed.

Organizations should consider:

- What the system can access
- What actions it can perform
- How its activity is monitored
- How its access is reviewed
- How its access is removed

---

## Key Idea

**Every identity—human or automated—should have appropriate access and accountability.**