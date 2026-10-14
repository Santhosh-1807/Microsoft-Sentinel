# Microsoft Sentinel Watchlists

## Overview

This project explores Microsoft Sentinel Watchlists and their use in security monitoring, threat detection, and security incident investigation.

Watchlists allow SOC analysts to import reference data and compare it with security events to identify relevant information during investigations.

## Objectives

- Understand Microsoft Sentinel Watchlists.
- Learn how to create and configure a watchlist.
- Import reference data using a CSV file.
- Understand watchlist aliases and SearchKey.
- Query watchlist data using Kusto Query Language (KQL).
- Explore practical SOC investigation use cases.

## Technologies Used

- Microsoft Sentinel
- Microsoft Azure
- Log Analytics Workspace
- Kusto Query Language (KQL)
- CSV

## What Is a Watchlist?

A watchlist is a collection of reference data that Microsoft Sentinel can use to enrich security events and support investigations.

SOC analysts can use watchlists to maintain information about:

- IP addresses
- User accounts
- Hostnames
- Critical organizational assets
- Other security-related reference data

## Watchlist Workflow

1. Prepare reference data in a CSV file.
2. Open Microsoft Sentinel.
3. Navigate to the Watchlists section.
4. Create a new watchlist.
5. Upload the CSV file.
6. Configure the watchlist alias and SearchKey.
7. Verify the imported data.
8. Query the watchlist using KQL.
9. Use the results to support security investigations.

## Sample CSV Data

Example data for testing:

| IPAddress | Description |
|---|---|
| 192.0.2.10 | Example approved IP |
| 198.51.100.20 | Example test IP |

These IP addresses are reserved for documentation and testing purposes.

Save the data as `sample-watchlist.csv` if you want to practise importing a CSV file.

## KQL Query Example

Use the following query to retrieve data from a watchlist.

```kusto
_GetWatchlist('ipwatchlist')
| project SearchKey
