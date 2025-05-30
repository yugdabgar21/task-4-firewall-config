# Task 4: Firewall Configuration on Windows

#### By: Yug Dabgar (aka MASTERxD)

## Overview
In this task, I explored basic firewall rule configuration using Windows Defender Firewall. The goal was to understand how to block or allow specific ports and control traffic based on rules.

## Platform Used
- Windows 11
- Windows Defender Firewall (Advanced Settings)

## Steps Performed

### 1. Checked Default Rules
- Opened Windows Firewall and reviewed existing **Inbound** and **Outbound** rules.

### 2. Blocked Telnet (Port 23)
- Created a new **Inbound Rule** to block TCP port 23 (Telnet).
- Applied the rule to all network profiles (Domain, Private, Public).

### 3. (Optional) Allowed SSH (Port 22)
- Added an **Allow Rule** for port 22 as an example of how to permit trusted services.

### 4. Removed the Telnet Rule
- Deleted the custom rule to restore default settings and test rollback control.

## Files Included
- `screenshots/`
  - `firewall_default_rules.png` – View of current system rules
  - `telnet_block_rule.png` – Custom rule blocking port 23
  - `rule_removed.png` – Rule deleted to revert config

## Conclusion
This exercise helped me understand how firewall rules work on Windows. Being able to block or allow specific traffic is a key part of hardening a system against common network threats.
