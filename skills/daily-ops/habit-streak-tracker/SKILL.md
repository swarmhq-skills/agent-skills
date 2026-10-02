---
name: habit-streak-tracker
description: "Tracks a small habit the user chooses, such as a daily walk or reading, from a check-in the user sends, and shows the weekly pattern and a gentle nudge. Use when the user wants to build or keep a habit."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Habit streak tracker

Keep a habit going with a simple weekly view.

## Requirements

- The habit and its target
- Daily check-in from the user

## When to use

- Daily check-in
- Sunday summary

## Steps

1. Record the habit and a target the user picks, in a way that is easy to meet.
2. Log each check-in with the date. Do not log what was not reported.
3. Show the week as a simple row and the current streak.
4. After a missed day, suggest the smallest next step, with no blame.

## Rules

- Only record what the user reports.
- Keep the log private to the user.
- Never give medical or diet advice. Point to a professional for that.

## Output format

```
Habit (week)
- Days done
- Streak
- Small next step
```
