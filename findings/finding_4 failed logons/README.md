# Finding 04 - Failed Authentication Analysis

## Objective

Identify source IP addresses responsible for the highest number of failed authentication attempts.

## SPL Query

```spl
index=main event_type="Failed Logon"
| stats count by source_ip
| sort - count
| head 10
