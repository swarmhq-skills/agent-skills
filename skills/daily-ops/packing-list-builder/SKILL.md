---
name: packing-list-builder
description: "Builds a packing list from the trip dates, the place, the weather forecast and the activities, and keeps a reusable base list. Use before any trip, or when the user asks what to pack."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Packing list builder

A packing list that fits the trip.

## Requirements

- Dates and destination
- Planned activities

## When to use

- A week before a trip
- When the plan changes

## Steps

1. Read the dates, place and activities. Ask for anything missing.
2. Check the forecast from a weather source for those dates and note its date.
3. Start from the base list, then add items for the weather and activities.
4. Group by bag and mark what must be bought or charged.

## Rules

- Take the forecast from a named source. Never guess the weather.
- Do not buy anything without approval.
- Mark documents and medication as "check yourself".

## Output format

```
Packing list (trip)
- Documents and money
- Clothes by day
- Tech and chargers
- Still to buy
```
