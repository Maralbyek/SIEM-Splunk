# Finding 02 - Process Creation Overview

## Objective

Identify the most frequently executed processes within the dataset.

## SPL Query

```spl
index=main event_type="Process Creation"
| stats count by process_name
| sort - count
| head 10
