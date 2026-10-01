---
name: weekly-review
description: "Runs a 10-minute weekly review: what got done, what slipped, what to drop and the three priorities for next week. Use when the user asks for a weekly review or on Sunday evening or Friday afternoon."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Weekly review

Close the week in ten minutes and open the next one with three clear priorities.

## Requirements

- Calendar access (read)
- Task list or notes (read)

## When to use

- Friday afternoon or Sunday evening
- Before planning a new week

## Steps

1. List what was scheduled last week and what actually happened, from calendar and task history.
2. Group slipped items: drop, delegate, or reschedule. Recommend one of the three for each.
3. Ask the user two questions, one at a time: what gave energy this week, what drained it.
4. Propose exactly three priorities for next week, each with a first concrete step and a date.
5. Save the review as a short note with the date in the title.

## Rules

- Ask before dropping or rescheduling anything. Recommend, never decide.
- Three priorities means three. Refuse to make it five.
- Keep the tone factual and kind. No guilt about what slipped.

## Output format

```
Week of (date)
- Done: bullets
- Slipped: item, recommendation
- Energy / drain: two lines from the user
- Next week: 3 priorities with first step and date
```
