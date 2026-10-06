Microsoft Sentinel — User & Entity Behavior Analytics (UEBA)

Objective

To understand User and Entity Behavior Analytics (UEBA) in
Microsoft Sentinel and how behavioral analysis can help SOC
analysts identify unusual or suspicious activity.

What is UEBA?

User and Entity Behavior Analytics (UEBA) analyzes activity
associated with users and other entities to identify unusual
behavior.

Instead of looking only at individual security events, UEBA
provides behavioral context that can help identify anomalies.

Basic Workflow

User / Entity Activity
↓
Data Collection
↓
Behavior Analysis
↓
Baseline / Behavioral Context
↓
Anomalous Activity
↓
Investigation
↓
Response

Entities

Examples of entities that can be investigated include:

- Users
- IP addresses
- Hosts
- Devices
- Applications
- Other security-related entities

Behavioral Analysis

UEBA can help identify activity that differs from expected
behavior.

Examples may include:

- Unusual login behavior
- Unusual location
- Unusual access patterns
- Unusual activity for a user
- Suspicious changes in behavior

SOC Analyst Use Case

A SOC analyst can use UEBA-related information to prioritize
and investigate potentially suspicious activity.

The analyst should compare the unusual behavior with other
available evidence before deciding whether the activity is
malicious.

Investigation Process

1. Identify the unusual behavior.
2. Identify the affected user or entity.
3. Review the activity timeline.
4. Examine related security events.
5. Compare the activity with expected behavior.
6. Determine whether the activity is suspicious.
7. Escalate or respond when appropriate.

Important Security Principle

An anomaly does not automatically mean an attack.

UEBA provides behavioral context that can help an analyst
decide which activity requires further investigation.

Skills Demonstrated

- UEBA
- Behavioral analysis
- Anomaly detection
- User investigation
- Entity investigation
- Security monitoring
- SOC analysis
- Microsoft Sentinel

Practical Evidence

Screenshots from my UEBA configuration and investigation are
stored in the "screenshots" directory.


Chapter 8: Microsoft Sentinel User & Entity Behavior Analytics (UEBA)
