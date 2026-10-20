# Microsoft Sentinel Log Ingestion Using Azure Monitor Agent (AMA)

## Project Overview

This project explores how to collect and ingest security logs into Microsoft Sentinel using Azure Monitor Agent (AMA).

Centralized log collection enables SOC analysts to monitor system activity, investigate security events, and detect potential threats.

## Objectives

- Understand Azure Monitor Agent (AMA).
- Learn how log ingestion works in Microsoft Sentinel.
- Understand Data Collection Rules (DCRs).
- Learn how logs are collected from supported machines.
- Understand the role of Log Analytics workspaces.
- Verify ingested security logs using Kusto Query Language (KQL).

## Technologies Used

- Microsoft Sentinel
- Microsoft Azure
- Azure Monitor Agent (AMA)
- Data Collection Rules (DCRs)
- Log Analytics Workspace
- Kusto Query Language (KQL)

## What Is Azure Monitor Agent?

Azure Monitor Agent (AMA) is an agent used to collect monitoring data from supported machines and send it to Azure Monitor.

It can collect supported logs and events according to configured Data Collection Rules.

Microsoft Sentinel can use this collected data for security monitoring and investigation.

## What Are Data Collection Rules?

Data Collection Rules (DCRs) define which data to collect, how to collect it, and where to send it.

They help administrators configure log collection for supported data sources.

## Log Ingestion Workflow

1. Identify the machine or data source.
2. Configure the required Azure Monitor Agent.
3. Create or configure a Data Collection Rule.
4. Select the required data sources.
5. Associate the rule with the supported machine.
6. Send collected data to the configured Log Analytics workspace.
7. Verify that the logs have arrived.
8. Use Microsoft Sentinel to analyze the available security data.

## Role of Log Analytics Workspace

The Log Analytics workspace stores the collected log data.

Microsoft Sentinel uses the workspace to query and analyze supported security data.

The availability of particular log tables depends on the configured data sources and collection settings.

## KQL Verification Examples

### 1. Check Syslog Data

```kusto
Syslog
| take 10
