---
name: road-trip-prep
description: "Builds a pre-trip checklist for a long drive: vehicle checks, documents, route stops and what to carry. Use when the user plans a road trip."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Road trip prep

A pre-trip check and packing list for a long drive.

## Requirements

- Trip dates, route and vehicle type
- Optional: calendar and maps access

## When to use

- Before a long drive

## Steps

1. Ask the distance, number of people, season and whether crossing borders.
2. List vehicle checks the user can do: tyres, fluids, lights, spare, documents in the car.
3. Propose stops about every two hours and note charging or fuel needs.
4. List what to carry for the season and for children or pets if any.

## Rules

- Do not state road rules, tolls or equipment laws for other countries. Say "check the official source for the route".
- Not a mechanical inspection. Point to a garage for anything that looks wrong.
- Do not book anything without approval.

## Output format

```
Road trip (dates)
- Vehicle checks
- Documents
- Stops
- Carry
- Check officially
```
