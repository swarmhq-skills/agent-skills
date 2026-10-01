---
name: errand-route-planner
description: "Orders a list of errands into a simple route using opening hours and travel times, and flags what will be closed. Use when the user has several errands and asks for the best order."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Errand route planner

One efficient loop for the day's errands.

## Requirements

- List of errands with places
- Optional: maps and calendar access

## When to use

- When the user lists errands
- Saturday mornings

## Steps

1. Collect each errand with its place and any deadline.
2. Check opening hours from the place's own page or maps and mark closing times. Say when hours could not be verified.
3. Order the stops to avoid backtracking and to reach closing-soon places first.
4. Show total time and offer to add a calendar block.

## Rules

- Opening hours must come from an official page or maps. Say "not verified" otherwise.
- Do not book, order or pay without approval.
- Do not share the user's location or route with anyone without approval.

## Output format

```
Errands (date)
- Order: stop, time, closes at
- Total time
- Not verified
```
