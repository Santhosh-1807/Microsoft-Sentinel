Microsoft Sentinel — Threat Detection & Mitigation Workflow

Objective

To understand the threat detection and mitigation workflow in
Microsoft Sentinel and how a SOC analyst can identify,
investigate, and respond to suspicious security activity.

Threat Detection Workflow

Security Data
↓
Microsoft Sentinel
↓
Threat Detection
↓
Alert
↓
Investigation
↓
Threat Validation
↓
Mitigation / Response

Detection

Microsoft Sentinel can analyze security data and identify
suspicious activity that may represent a security threat.

The detected activity can generate alerts for investigation.

Alert Investigation

When an alert is generated, a SOC analyst should investigate:

- What happened?
- Which user or entity was involved?
- When did the activity occur?
- What was the source?
- What IP address was involved?
- Are there related events?
- Is the activity malicious or legitimate?

Threat Validation

The analyst evaluates the available evidence to determine
whether the alert represents:

- True Positive
- False Positive
- Benign / Expected Activity

Mitigation

If malicious activity is confirmed, appropriate response and
mitigation actions can be taken according to the organization's
incident-response procedures.

Possible actions may include:

- Containing the affected account or system
- Blocking malicious activity
- Resetting compromised credentials
- Removing persistence
- Escalating the incident
- Continuing monitoring

SOC Analyst Workflow

1. Monitor alerts
2. Triage the alert
3. Investigate the available evidence
4. Correlate related events
5. Determine severity
6. Validate the threat
7. Take or recommend mitigation actions
8. Document the investigation

Skills Demonstrated

- Threat detection
- Alert triage
- Security monitoring
- Incident investigation
- Threat validation
- Mitigation concepts
- SOC workflow

Practical Evidence

Screenshots from the practical demonstration are stored in
the "screenshots" directory.


