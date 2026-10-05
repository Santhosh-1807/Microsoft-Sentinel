Microsoft Sentinel — Analytics Rules & Threat Detection

Objective

To understand how Analytics Rules are used in Microsoft Sentinel
to detect suspicious activity and generate security alerts.

What is an Analytics Rule?

An Analytics Rule defines the logic that Microsoft Sentinel uses
to identify suspicious or potentially malicious activity in
security data.

Analytics Rules can use queries and conditions to detect
security events and generate alerts for investigation.

Detection Workflow

Security Logs
↓
KQL Query
↓
Analytics Rule
↓
Detection
↓
Alert
↓
Incident
↓
Investigation

Main Components

An Analytics Rule can include:

- Rule name
- Description
- Severity
- Query
- Query scheduling
- Trigger conditions
- Entity mapping
- Alert configuration
- Incident creation
- MITRE ATT&CK mapping

Detection Logic

The detection logic is normally created using Kusto Query
Language (KQL).

Example workflow:

Security Events
↓
KQL filters relevant events
↓
Analytics Rule evaluates the query
↓
Suspicious activity detected
↓
Alert generated

Alert Severity

Detections can be assigned an appropriate severity based on
the potential impact of the activity.

Examples:

- Informational
- Low
- Medium
- High

Severity should be selected based on the actual detection
and its potential security impact.

SOC Analyst Use Case

Analytics Rules help SOC teams continuously monitor security
data and automatically identify activity that requires
investigation.

A SOC analyst can then:

1. Review the generated alert.
2. Identify affected entities.
3. Investigate related events.
4. Determine whether the alert is a true or false positive.
5. Escalate or respond according to the investigation result.

Skills Demonstrated

- Microsoft Sentinel
- Analytics Rules
- KQL
- Threat Detection
- Alert Generation
- Security Monitoring
- SOC Alert Triage
- MITRE ATT&CK concepts

Practical Evidence

Screenshots from my Analytics Rule configuration and detection
testing are stored in the "screenshots" directory.
