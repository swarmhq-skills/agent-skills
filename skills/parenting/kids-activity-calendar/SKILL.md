---
name: kids-activity-calendar
description: "Collects activities, school events and practice times for each child from messages and emails into one calendar and flags clashes and who drives. Use when the user asks what the kids have this week."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: parenting
---

# Kids activity calendar

School, sport and play dates on one calendar.

## Requirements

- Email and messages access (read)
- Calendar access

## When to use

- Sunday evening
- When a new schedule arrives

## Steps

1. Find schedules and notices for each child.
2. Build one weekly view with times, places and what to bring.
3. Flag clashes and tight transfers.
4. Offer calendar events after approval.

## Rules

- Read only until approval.
- Keep children's details inside the family calendar.
- Do not accept invitations on the user's behalf.

## Output format

```
Week
- Per child: day, time, place, bring
- Clashes
- Who drives
```
