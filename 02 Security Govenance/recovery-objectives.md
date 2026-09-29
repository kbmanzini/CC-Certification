# Recovery Objectives: RTO and RPO

## Recovery Time Objective (RTO)

The Recovery Time Objective is the target amount of time within which a system, service, or business function should be restored after a disruption.

In simple terms:

**RTO = How long can we be without the service?**

### Example

A payment service has an RTO of four hours.

The recovery plan aims to restore the service within four hours after the disruption.

An RTO is a target, not a guarantee.

## Recovery Point Objective (RPO)

The Recovery Point Objective describes the maximum targeted amount of data loss measured in time that an organization is prepared to tolerate after a disruption.

In simple terms:

**RPO = How much recent data can we afford to lose?**

### Example

A system has an RPO of 30 minutes.

The organization aims to limit data loss to the equivalent of no more than 30 minutes of updates.

The actual result depends on backup methods, replication, and the incident.

## RTO vs. RPO

### RTO

Focuses on the time needed to restore a service.

### RPO

Focuses on the amount of recent data that could be lost, expressed as time.

## Easy Memory Trick

* **RTO = Time to get the service running again.**
* **RPO = Point in time to which data should be recoverable.**

## Why These Objectives Matter

Organizations use recovery objectives to select appropriate backup, replication, infrastructure, and recovery strategies.

More demanding objectives may require more resources and planning.

## CC Exam Tips

If a question asks how quickly a service needs to be restored, think:

**RTO**

If it asks how much data loss is acceptable, think:

**RPO**

## What I Learned

RTO sets a target for service restoration time, while RPO sets a target for the maximum tolerable data loss measured in time.
