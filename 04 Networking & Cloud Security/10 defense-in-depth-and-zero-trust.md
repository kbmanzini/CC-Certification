# 10 – Network Segmentation and VLANs

## What is network segmentation?
Network segmentation divides a larger network into smaller sections.

It helps:
- Reduce unnecessary communication.
- Limit the spread of incidents.
- Enforce different security policies.
- Protect sensitive resources.

## Common Approaches

VLAN:
Logically separates devices into distinct Layer 2 network segments.

DMZ:
A separate network zone for services that must be reachable from less-trusted networks.

Micro-segmentation:
Applies granular controls between individual workloads, applications, or systems.

NAC (Network Access Control):
Applies access policies to devices seeking to connect.

## Why Segment Networks?

- Separate guest devices from internal systems.
- Isolate public-facing services.
- Limit lateral movement.
- Apply different controls to servers and workstations.
- Restrict IoT devices.

## Remember
VLAN = Logical network separation.
DMZ = Controlled zone for public-facing services.
Micro-segmentation = Granular isolation.