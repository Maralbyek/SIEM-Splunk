# Finding 01 - Event Type Distribution

## Objective
Identify the most common event types in the dataset.

## SPL Query

```spl
index=main
| stats count by event_type
| sort - count
