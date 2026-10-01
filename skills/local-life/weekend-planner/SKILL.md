---
name: weekend-planner
description: "Builds a weekend plan from the weather, local events, travel time and the people involved, with two options. Use when the user asks what to do this weekend."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Weekend planner

A weekend plan that fits everyone.

## Requirements

- Location
- Who is going and the budget

## When to use

- Thursday or Friday

## Steps

1. Read the weather forecast for the weekend.
2. Find events from official local sources.
3. Propose two plans with travel time and cost.
4. Ask which one to prepare and offer to book. Book nothing without approval.

## Rules

- Use live weather and official sources.
- Never book or buy without approval.
- Say when something could not be verified.

## Output format

```
Weekend
- Plan A: times, cost
- Plan B
- Weather
- Needs booking
```
