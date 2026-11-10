# Security Event Triage

## 1. What Is a Security Event?

A security event is an observable occurrence related to the security of a system, network, or organization.

Examples:
- A user logs in.
- A firewall blocks a connection.
- A password is changed.
- An antivirus tool detects a suspicious file.
- A user receives an access-denied message.

Not every security event is an incident.

## 2. Event vs. Alert vs. Incident

| Term | Meaning |
|---|---|
| Event | An observable occurrence |
| Alert | A notification that something may require attention |
| Incident | An event or series of events that threatens security or violates policy |

Example:
- Event: Several failed login attempts.
- Alert: A monitoring tool flags the attempts.
- Possible incident: Investigation confirms unauthorized access.

## 3. What Is Triage?

Security triage is the process of reviewing alerts and determining which ones need investigation and how urgently they should be handled.

Triage helps security teams prioritize limited time and resources.

## 4. Common Triage Factors

When reviewing an alert, consider:

1. **Severity:** How serious could the event be?
2. **Impact:** What systems, accounts, or information could be affected?
3. **Scope:** How many systems or users may be involved?
4. **Urgency:** Is the activity ongoing?
5. **Confidence:** How reliable is the alert?
6. **Asset importance:** Does it involve a critical system?

## 5. Prioritization

A critical alert involving a sensitive business system may need immediate attention.

A low-risk alert involving a noncritical system may be handled later.

Priority should be based on organizational procedures and the potential risk—not just the number of alerts.

## 6. Basic Triage Process

1. Receive the alert.
2. Review the alert details.
3. Identify the affected system or account.
4. Check relevant logs and supporting evidence.
5. Determine whether the activity is expected or suspicious.
6. Assess severity, scope, and potential impact.
7. Escalate or follow the appropriate response procedure.
8. Document the findings.

## 7. Escalation

Escalation means passing an issue to someone with the appropriate authority, expertise, or responsibility.

Examples:
- A routine issue goes to the help desk.
- A suspicious account event goes to the security team.
- A confirmed major incident is escalated to incident response leadership.

## 8. Documentation

Good documentation should include:
- Alert or case number
- Date and time
- Systems or accounts involved
- Observed activity
- Evidence reviewed
- Actions taken
- People notified
- Current status

Documentation supports accountability and future investigation.

## 9. Indicators of Compromise (IOCs)

An IOC is an observable indicator that may suggest a system has been compromised.

Examples:
- A known malicious file hash
- A suspicious domain
- An unusual IP address
- Unexpected account activity
- Unexpected changes to system files

An IOC is evidence to investigate, not automatic proof of a compromise.

## Key Takeaways

- An event is not automatically an incident.
- An alert identifies activity that may need attention.
- Triage determines priority and next steps.
- Consider severity, impact, scope, urgency, and confidence.
- Document findings and escalate according to policy.