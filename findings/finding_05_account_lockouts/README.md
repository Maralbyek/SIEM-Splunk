# Finding 5 - Account Lockout Analysis

## Objective
Identify users experiencing the highest number of account lockouts.

## SPL Query

```Shell
index=main event_type="Account Lockout"
| stats count by username
| sort - count
