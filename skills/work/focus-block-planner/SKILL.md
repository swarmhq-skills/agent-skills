---
name: focus-block-planner
description: "Finds free blocks in the calendar and proposes focus time for the most important tasks, then holds the blocks after approval. Use when the user feels overbooked, or at the start of the week."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Focus block planner

Protect time for the work that matters.

## Requirements

- Calendar access
- The top 3 tasks of the week

## When to use

- Monday morning
- When a day is overbooked

## Steps

1. Read next week's calendar and find blocks of 60 minutes or more.
2. Match the top 3 tasks to blocks, preferring the user's best hours.
3. Propose the blocks. Wait for approval.
4. Create private calendar holds with no invitations after approval.

## Rules

- Create events only after approval.
- Never move or cancel existing meetings.
- Holds are private and have no attendees.

## Output format

```
Focus plan
- Block: day, time, task
- Not enough time for: list
```
