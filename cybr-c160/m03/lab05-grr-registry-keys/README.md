# Lab 05: Remotely Pulling Windows Registry Keys with GRR

**Module:** M03 | **Course:** CYBR C160 | **Date:** November 7, 2025

## Tools Used
- GRR Rapid Response
- Registry Flow
- NDG NetLab (Windows 10 VMs)

## What I Did
Logged into GRR, located the target host, launched a Registry Flow
to remotely query specific Windows Registry keys, and reviewed the
returned key data without logging into the machine directly.

## Key Concepts
- Windows Registry as a forensic artifact source
- GRR Registry Flow for remote key extraction
- Persistence mechanism locations in the Registry
- Non-invasive remote investigation techniques

## Why This Matters
The Registry stores persistence mechanisms, recently accessed files,
installed software, and attacker footprints. Querying it remotely
lets threat hunters investigate without alerting an attacker.

## Screenshots
*See screenshots/ folder*
```
Commit message:
```
Add Lab 05
