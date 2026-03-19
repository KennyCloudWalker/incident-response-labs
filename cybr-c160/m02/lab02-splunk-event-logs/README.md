# Lab 02: Exploring Windows Event Logs with Splunk

**Module:** M02 | **Course:** CYBR C160 | **Date:** October 27, 2025

## Tools Used
- Splunk Enterprise
- SPL (Splunk Query Language)
- NDG NetLab (Windows 10 VM)

## What I Did
Logged into Splunk via browser, navigated to Search & Reporting, ran
SPL queries using index=wls and EventID=4624 to identify successful
user logins, and applied time range filters to scope results.

## Key Concepts
- Splunk Search & Reporting interface
- SPL query syntax: index and field filters
- EventID 4624 — successful logon events
- Time-based filtering in SIEM investigations

## Why This Matters
This is a real SOC workflow. When an incident occurs analysts query
the SIEM to find authentication events fast. Splunk is the leading
SIEM platform in enterprise environments.

## Screenshots
*See screenshots/ folder*
```
4. Commit message:
```
Add Lab 02
