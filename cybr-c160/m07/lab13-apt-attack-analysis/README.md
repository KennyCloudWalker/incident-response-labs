# Lab 13: Analyzing APT-Style Attack Methods with Splunk

**Module:** M07 | **Course:** CYBR C160 | **Date:** December 2, 2025

## Tools Used
- Splunk Enterprise
- SPL (Splunk Query Language)
- NDG NetLab (Windows 10 VM)

## What I Did
Ran targeted SPL queries against Windows event logs to identify
reconnaissance commands — whoami, net localgroup, netstat, wmic,
tasklist — executed during a simulated APT attack window, then
traced the attacker's full methodology through the log data.

## Sample SPL Query Used
earliest=12/2/2020:14:00:00 latest=12/3/2020:08:00:00
index=wls WLS_FileTail | stats count by RawData

## Key Concepts
- APT reconnaissance command patterns
- Time-bounded SPL queries for incident scoping
- Attacker methodology tracing via SIEM
- Post-compromise behavior identification in logs

## Why This Matters
APT actors follow recognizable patterns — recon commands, user
enumeration, network mapping. This lab shows I can identify that
behavior in Splunk. This is exactly what a Tier 1 or Tier 2 SOC
analyst does when responding to an APT alert.

## Screenshots
*See screenshots/ folder*
```
Commit message:
```
Add Lab 13
