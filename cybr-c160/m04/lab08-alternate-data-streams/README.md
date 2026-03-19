# Lab 08: Identifying and Locating Alternate Data Streams

**Module:** M04 | **Course:** CYBR C160 | **Date:** November 16, 2025

## Tools Used
- Windows Command Prompt
- NTFS Alternate Data Streams
- NDG NetLab (Windows 10 VM)

## What I Did
Used CMD to create a base text file, attached an executable (calc.exe)
as a hidden Alternate Data Stream, then used dir /r to detect and
expose the hidden stream — practicing both attacker and defender sides.

## Key Concepts
- NTFS Alternate Data Streams as a data hiding technique
- Creating and detecting ADS via Command Prompt
- dir /r command for ADS discovery
- Anti-forensics awareness

## Why This Matters
ADS is an NTFS feature attackers use to hide malicious files inside
innocent-looking ones, invisible in normal directory listings.
Detecting ADS is tested on Security+ and used in real investigations.

## Screenshots
*See screenshots/ folder*
```
Commit message:
```
Add Lab 08
