---
name: car-cost-log
description: "Logs fuel, tolls, parking, insurance, tax and service costs and shows cost per month and per 100 km. Use when the user sends a car receipt or asks what the car costs."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Car cost log

What the car really costs per month.

## Requirements

- Receipts, statements or notes the user sends

## When to use

- When a receipt arrives
- Monthly summary

## Steps

1. Record each cost with date, type and amount.
2. At month end total by type.
3. Compute cost per month and per 100 km if distance is known.
4. Show the trend of the last 6 months.

## Rules

- Only use amounts from receipts or from the user.
- Say "distance unknown" instead of estimating it.

## Output format

```
Car costs (month)
- By type
- Per month and per 100 km
- Trend
```
