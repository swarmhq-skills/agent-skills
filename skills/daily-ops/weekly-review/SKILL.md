---
name: weekly-review
description: "Runs a short weekly review from the user's calendar, tasks and notes: what was done, what slipped and what to focus on next week. Use on Friday or Sunday."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Weekly review

Close the week and open the next one.

## Requirements

- Calendar access (read)
- The user's task list or notes

## When to use

- Once a week at a time the user chooses

## Steps

1. Read the past week's events and the user's task list.
2. List what was finished and what slipped, with a reason if the user gives one.
3. Pick three priorities for next week.
4. Note any date in the next two weeks that needs preparation.

## Rules

- Do not move or delete anything without approval.
- Use only the user's calendar and notes.
- Keep it under one page.

## Output format

```
Weekly review
- Done
- Slipped
- Three priorities
- Dates to prepare for
```
