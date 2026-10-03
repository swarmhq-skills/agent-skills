---
name: home-repair-request-tracker
description: "Keeps a simple list of repairs the user needs done at home, with who was contacted, what was promised and the next step. Use when more than one repair is open at once."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Home repair request tracker

Know what is broken, who you called and what is next.

## Requirements

- The repairs the user wants tracked
- Optional: names and contact details of tradespeople the user gives

## When to use

- When a repair is reported
- When the user asks "what is still open?"

## Steps

1. Add each repair with date reported, place in the home and short description.
2. Record who was contacted, the date and what they said.
3. List open repairs by age, oldest first, with the next step for each.
4. Draft a polite follow-up for the user to send when a promised date passes.

## Rules

- Do not contact anyone without approval.
- Do not guess prices or timelines. Record only what the user was told.
- Keep the log to what the user provides.

## Output format

```
Open repairs
- Repair: place, issue, date reported
- Contact and what was said
- Next step and date
Closed repairs
```
