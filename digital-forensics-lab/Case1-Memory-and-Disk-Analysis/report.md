# DFIR Case Study 1: Memory + Disk Analysis

## Overview
- **Date:** Sept 2025
- **Objective:** Investigate suspicious `.exe` on Windows VM via memory & disk forensics.

## Evidence
- Memory: `ramdump.raw` (not committed)
- Disk: `windows-disk.vmdk` (not committed)
- Tools: Volatility 3, Autopsy 4.22.1
- Text outputs: [pslist](./evidence/pslist_output.txt) • [cmdline](./evidence/cmdline_output.txt) • [netscan](./evidence/netscan_output.txt)

## Memory Analysis (Volatility)
**pslist (snippet)**
