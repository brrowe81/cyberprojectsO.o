# DFIR Case Study 1: Memory + Disk Analysis

## Overview
- **Date:** Sept 2025
- **Objective:** Investigate a suspicious `.exe` on a Windows VM using both memory and disk forensics.
- **Tools:** Volatility 3, Autopsy 4.22.1

## Evidence Collected
- **Memory dump:** `ramdump.raw` (not committed to repo)
- **Disk image:** `windows-disk.vmdk` (not committed to repo)
- **Volatility outputs:**
  - [pslist](./evidence/pslist_output.txt)
  - [cmdline](./evidence/cmdline_output.txt)
  - [netscan](./evidence/netscan_output.txt)

---

## Memory Analysis (Volatility)

### pslist

