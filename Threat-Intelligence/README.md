Microsoft Sentinel — Threat Intelligence

Objective

To understand how Threat Intelligence can be integrated with
Microsoft Sentinel and used to improve security monitoring,
threat detection, and investigation.

What is Threat Intelligence?

Threat Intelligence is security information about known or
suspected threats that can help security teams identify and
investigate malicious activity.

Examples of Threat Indicators

Threat intelligence can contain indicators such as:

- IP addresses
- Domains
- URLs
- File hashes
- Other Indicators of Compromise (IOCs)

Threat Intelligence Workflow

Threat Intelligence
↓
Indicators of Compromise
↓
Microsoft Sentinel
↓
Security Data
↓
Correlation / Detection
↓
Alert
↓
SOC Investigation
↓
Response

SOC Use Case

A SOC analyst can compare security events against known
threat indicators.

For example, if an event contains an IP address that is
identified as malicious by a trusted threat-intelligence
source, the activity can be investigated further.

Investigation Process

1. Identify the indicator.
2. Determine the indicator type.
3. Review the related security event.
4. Check whether the indicator matches known threat intelligence.
5. Investigate related activity.
6. Determine whether the activity is malicious or legitimate.
7. Escalate or respond according to the investigation result.

Importance in a SOC

Threat intelligence can help analysts:

- Improve detection
- Add context to security events
- Prioritize suspicious activity
- Investigate Indicators of Compromise
- Support incident response

Skills Demonstrated

- Threat Intelligence
- Indicators of Compromise (IOCs)
- Security monitoring
- Threat detection
- Alert investigation
- Microsoft Sentinel
- SOC analysis

Practical Evidence

Screenshots from my practical Threat Intelligence
configuration and investigation are stored in the
"screenshots" directory.

