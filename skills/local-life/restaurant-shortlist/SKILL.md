---
name: restaurant-shortlist
description: "Builds a shortlist of three restaurants for an occasion from the group's needs, location and budget, with current hours and a link to the official page. Use when the user asks where to eat."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Restaurant shortlist

Three good places, not twenty.

## Requirements

- Location, group size, budget, diet needs

## When to use

- When the user asks where to eat

## Steps

1. Ask the occasion, area, budget and dietary needs.
2. Search recent sources and the official page of each candidate.
3. Check opening hours today and whether booking is needed.
4. Present three with one reason each. Book nothing without approval.

## Rules

- Use current sources. Say when hours are unverified.
- Never book without approval.
- Always respect dietary limits.

## Output format

```
Shortlist
- Place: why, price, hours
- Booking needed
```
