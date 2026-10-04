Microsoft Sentinel — Microsoft Entra ID Integration

Objective

To connect Microsoft Entra ID with Microsoft Sentinel and
enable security-related Entra ID logs to be collected for
security monitoring and investigation.

Technology

- Microsoft Entra ID
- Microsoft Sentinel
- Log Analytics Workspace
- Azure Monitor / Diagnostic Settings
- Microsoft Entra ID logs

Integration Workflow

Microsoft Entra ID
↓
Diagnostic Settings / Data Connector
↓
Log Analytics Workspace
↓
Microsoft Sentinel
↓
Security Monitoring
↓
Investigation

Why Entra ID Logs Are Important

Microsoft Entra ID provides authentication and identity-related
information that can help a SOC analyst investigate suspicious
account activity.

Examples of useful security events include:

- Failed sign-in attempts
- Successful sign-ins
- Suspicious authentication activity
- User account activity
- Authentication-related anomalies

Configuration Process

1. Open Microsoft Entra ID.
2. Identify the required logging configuration.
3. Configure the required diagnostic settings or connector.
4. Select the appropriate Log Analytics Workspace.
5. Send the required Entra ID logs to the workspace.
6. Verify that the configuration is active.
7. Open Microsoft Sentinel.
8. Verify that the expected data is available.

SOC Analyst Use Case

After Entra ID data is available in Sentinel, a SOC analyst
can use the collected authentication data for monitoring,
detection, investigation, and threat hunting.

Skills Demonstrated

- Microsoft Entra ID
- Microsoft Sentinel integration
- Identity and access monitoring
- Log ingestion
- Azure security monitoring
- SIEM fundamentals

Practical Evidence

Screenshots of my Entra ID configuration and Sentinel log
verification are stored in the "screenshots" directory.
