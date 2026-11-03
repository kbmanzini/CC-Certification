# 16 – Domain 4 Review: Networking and Cloud Security

## Networking Fundamentals
- LAN: Local network.
- WAN: Connects networks over large distances.
- Router: Connects networks.
- Switch: Connects devices within a LAN.
- Access Point: Provides wireless connectivity.
- Bandwidth: Maximum capacity.
- Throughput: Successful data transfer.
- Latency: Delay.

## OSI Model
7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical

## TCP and UDP
- TCP: Reliable, ordered delivery.
- UDP: Lower overhead, no guaranteed delivery or order.

## Common Ports
- 22 SSH
- 23 Telnet
- 25 SMTP
- 53 DNS
- 67/68 DHCP
- 80 HTTP
- 123 NTP
- 443 HTTPS
- 3389 RDP

## Network Security
- Firewall: Enforces traffic rules.
- IDS: Detects and alerts.
- IPS: Can block suspicious activity.
- VPN: Protects communication paths.
- VLAN: Logically separates network devices.
- DMZ: Controlled zone for public-facing services.

## Network Threats
- DoS: Attempts to make a service unavailable.
- DDoS: DoS involving multiple sources.
- MITM: Attacker positions themselves between communicating parties.
- Virus: Attaches to a host.
- Worm: Can self-propagate.
- Trojan: Disguises malicious functionality.

## Cloud Security
- IaaS: Infrastructure as a Service.
- PaaS: Platform as a Service.
- SaaS: Software as a Service.
- Public Cloud: Provider infrastructure offered to customers.
- Private Cloud: Dedicated to one organization.
- Hybrid Cloud: Combines private and public environments.
- Community Cloud: Shared by organizations with common needs.

## Shared Responsibility
Cloud security responsibilities are divided between the provider and customer.

The customer always retains some responsibility for:
- User access.
- Credentials.
- Data handling.
- Secure configuration.
- Monitoring available security information.

## Quick Practice Questions

1. Which OSI layer is associated with IP routing?
   Answer: Layer 3 – Network.

2. Which protocol provides reliable, ordered transport?
   Answer: TCP.

3. What does DNS do?
   Answer: Resolves domain names to IP addresses and provides other DNS records.

4. What is the difference between IDS and IPS?
   Answer: IDS detects and alerts; IPS can take action to block suspicious activity.

5. What is a DMZ?
   Answer: A controlled network zone for services accessible from less-trusted networks.

6. What is micro-segmentation?
   Answer: Granular isolation between workloads or systems.

7. What does Zero Trust mean?
   Answer: Do not grant implicit trust; verify access explicitly and apply least privilege.

8. Which cloud service model gives customers the most control over virtual infrastructure?
   Answer: IaaS.

9. What is the shared responsibility model?
   Answer: The division of security responsibilities between a cloud provider and customer.

10. Why segment IoT devices?
    Answer: To restrict unnecessary communication and reduce the potential impact of a compromised device.

## Final Study Checklist

- [ ] Explain the OSI and TCP/IP models.
- [ ] Recognize IPv4 and IPv6.
- [ ] Identify common ports and protocols.
- [ ] Explain firewalls, IDS, IPS, HIDS, and NIDS.
- [ ] Compare TCP and UDP.
- [ ] Explain Wi-Fi, Bluetooth, and VPN security.
- [ ] Recognize common network threats.
- [ ] Explain VLANs, DMZs, and micro-segmentation.
- [ ] Compare Defense in Depth and Zero Trust.
- [ ] Identify cloud service and deployment models.
- [ ] Explain shared cloud security responsibilities.
- [ ] Describe security concerns for embedded systems, ICS, and IoT.