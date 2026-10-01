---
name: calendar-conflict-check
description: "Scans the next two weeks of the calendar for overlaps, tight back-to-back events and travel that does not fit. Use each week, or when the user adds a new event."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Calendar conflict check

Catch double bookings and impossible days early.

## Requirements

- Calendar access

## When to use

- Sunday evening
- When a new event is added

## Steps

1. Read the next 14 days of events.
2. Find overlaps, events with under 15 minutes between places, and events with no travel time.
3. Group the findings by day, with the two events involved.
4. Suggest one way to resolve each, but do not move anything.

## Rules

- Read only. Never move, delete or accept events without approval.
- Do not show private event titles to anyone else.
- Say "location missing" instead of guessing travel time.

## Output format

```
Conflicts (date)
- The two events
- Why it is a problem
- Suggested fix
```
