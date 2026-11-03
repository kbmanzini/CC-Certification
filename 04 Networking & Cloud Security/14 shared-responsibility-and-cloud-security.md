# 14 – Shared Responsibility and Cloud Security

## What is the shared responsibility model?
Cloud security responsibilities are divided between the Cloud Service Provider (CSP) and the customer.

The exact division depends on the service model, provider, and contract.

## General Responsibilities

IaaS:
- Provider manages physical facilities, hardware, and core infrastructure.
- Customer typically manages guest operating systems, applications, identities, and data.

PaaS:
- Provider manages more of the operating system and platform.
- Customer remains responsible for application code, data, and identities.

SaaS:
- Provider manages most of the application stack and infrastructure.
- Customer still manages users, access, and appropriate data handling.

## Customer Responsibilities

- Configure access permissions.
- Protect credentials.
- Enable MFA where available.
- Classify and protect data.
- Configure storage securely.
- Review available security logs.
- Understand backup responsibilities.
- Review service agreements.

## SLA – Service-Level Agreement
Defines expected service levels and related responsibilities or remedies.

May include:
- Availability.
- Performance.
- Support.
- Response commitments.

## MSP – Managed Service Provider
An organization that manages technology services for another organization.

## Remember
Using a cloud provider does not transfer every security responsibility to that provider.