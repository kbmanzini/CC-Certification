# 02 – OSI and TCP/IP Models

## OSI Model
The Open Systems Interconnection (OSI) model describes network communication using seven layers.

| Layer | Name | Purpose |
|---|---|---|
| 7 | Application | Network services used by applications |
| 6 | Presentation | Data formatting and translation |
| 5 | Session | Establishes and manages sessions |
| 4 | Transport | End-to-end delivery and ports |
| 3 | Network | Logical addressing and routing |
| 2 | Data Link | Frames and local network delivery |
| 1 | Physical | Signals, cables, and radio |

Mnemonic:
All People Seem To Need Data Processing.

## TCP/IP Model

- Application: HTTP, HTTPS, DNS, SMTP.
- Transport: TCP and UDP.
- Internet: IP addressing and routing.
- Network Access: Ethernet and Wi-Fi.

## TCP vs. UDP

TCP:
- Connection-oriented.
- Reliable delivery.
- Maintains data order.
- Retransmits missing data when needed.

UDP:
- Connectionless.
- Lower overhead.
- Does not guarantee delivery or order.

## Encapsulation
As data moves down networking layers, each layer adds information needed for delivery.

## Exam Reminders
- IP and routing: Layer 3.
- TCP and UDP: Layer 4.
- Ethernet and Wi-Fi: Data Link and Physical layers.