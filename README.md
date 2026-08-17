# Basic SIEM Project

This project demonstrates basic SIEM concepts using Splunk. It focuses on analysing security logs, creating simple detections, and documenting security findings.

The project will be gradually expanded to include more realistic SOC monitoring activities.

## Project Scope

Initial focus:

- Basic log analysis
- Understanding security events
- Simple SPL queries
- Detection logic
- Security findings documentation

## Technologies Used

- Splunk
- SPL (Search Processing Language)
- Windows/Linux Logs
- Git
- GitHub

## Current Status

Project initialization. The project is currently focused on building the basic SIEM environment and analysing initial security events.
## Example SPL Commands
```Shell
index=* | stats count
index=* | stats count by event_type
index=* event_type="Failed Logon"
index=* event_type="Account Lockout"
