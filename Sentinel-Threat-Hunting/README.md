# Microsoft Sentinel Threat Hunting Using KQL

## Project Overview

This project explores threat hunting in Microsoft Sentinel using Kusto Query Language (KQL). It focuses on searching security logs, identifying suspicious activities, and investigating potential threats.

Threat hunting enables SOC analysts to proactively search for suspicious behavior that may not have triggered existing security alerts.

## Objectives

- Understand threat hunting in Microsoft Sentinel.
- Learn to write and execute KQL hunting queries.
- Analyze security logs and authentication events.
- Identify suspicious patterns in security data.
- Investigate potential threats using available evidence.
- Document findings and recommend appropriate security actions.

## Technologies Used

- Microsoft Sentinel
- Microsoft Azure
- Log Analytics Workspace
- Kusto Query Language (KQL)
- Security Logs
- MITRE ATT&CK Framework

## Threat Hunting Methodology

The threat hunting process follows these steps:

1. **Define a Hypothesis:** Identify suspicious behavior to investigate.
2. **Identify Data Sources:** Select relevant security log tables.
3. **Write KQL Queries:** Create queries to search for specific activity.
4. **Analyze Results:** Review events and identify unusual patterns.
5. **Investigate Evidence:** Examine timestamps, users, IP addresses, and related events.
6. **Determine Findings:** Assess whether the activity requires further investigation.
7. **Document Results:** Record evidence and investigation conclusions.
8. **Recommend Actions:** Suggest appropriate response or detection improvements.

## Practical KQL Queries

### 1. Retrieve Sign-In Logs

```kusto
SigninLogs
| take 10
