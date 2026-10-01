---
name: seasonal-car-checklist
description: "Builds a short seasonal checklist for a car from its owner manual and the user's climate, and sets reminders. Use at the start of each season or before a long trip."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Seasonal car checklist

A short check before winter and summer.

## Requirements

- Car make and year
- Owner manual (link or PDF)

## When to use

- Start of autumn and spring
- Before a long trip

## Steps

1. Read the owner manual sections on tyres, fluids, wipers, lights and battery.
2. List the checks that matter for the coming season.
3. Mark which ones the user can do and which need a garage.
4. Offer calendar reminders for the garage visit.

## Rules

- Take specs from the owner manual only. Say "check the manual" if missing.
- Never advise skipping a safety check.
- Do not book a garage without approval.

## Output format

```
Checklist (season)
- Do it yourself
- Needs a garage
- Reminder date
```
