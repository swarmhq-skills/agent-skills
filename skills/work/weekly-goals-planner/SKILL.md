---
name: weekly-goals-planner
description: "Turns the user's notes and calendar into three clear goals for the week and the time blocks to work on them. Use on Monday morning or Sunday evening."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Weekly goals planner

Three goals for the week, and a plan to reach them.

## Requirements

- The user's notes and open tasks
- Calendar access

## When to use

- Monday morning
- Sunday evening

## Steps

1. Read the open tasks and the week's calendar.
2. Ask which outcomes matter most this week, and pick at most three.
3. Find free blocks and suggest when to work on each goal.
4. List what will probably not get done, so it is a choice.

## Rules

- Read only. Do not add or move calendar events without approval.
- Pick goals only from what the user says matters.
- Do not share the plan with anyone.

## Output format

```
Week goals (date)
- Goal 1 to 3 with a time block
- What will wait
- Risks to the plan
```
