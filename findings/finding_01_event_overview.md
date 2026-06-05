# Finding 01 - Event Type Overview

## Objective
Understand the distribution of events in the dataset.

## SPL Query

```spl
index=main
| stats count by event_type
| sort -count
