# Finding 03 - PowerShell Activity Investigation

## Objective

Identify the systems responsible for PowerShell execution events.

## SPL Query

```spl
index=main event_type="Process Creation" process_name="powershell.exe"
| stats count by source_ip
| sort - count
