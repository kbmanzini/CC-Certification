# 05 – Firewalls and Traffic Filtering

## What is a firewall?
A firewall monitors and controls network traffic according to defined security rules.

## Types of Firewalls

- Packet Filtering Firewall: Evaluates addresses, ports, and protocols.
- Stateful Firewall: Tracks connection state.
- Application-Aware Firewall: Can inspect application-level traffic.
- Host-Based Firewall: Runs on an individual computer or server.
- Network Firewall: Controls traffic between networks.

## Firewall Rules May Specify

- Source IP address.
- Destination IP address.
- Source and destination ports.
- Protocol.
- Application or service.
- Allow or deny action.

## Best Practices

- Permit only necessary traffic.
- Use restrictive security rules.
- Document firewall changes.
- Review rules periodically.
- Remove obsolete rules.
- Monitor important traffic.

## Limitations
A firewall is not a complete security solution.

It may not stop:
- Threats using permitted traffic.
- Compromised credentials.
- Malicious insiders.
- Unpatched applications.

## Remember
A firewall enforces traffic policy.
An IDS detects and alerts.
An IPS can block suspicious activity.