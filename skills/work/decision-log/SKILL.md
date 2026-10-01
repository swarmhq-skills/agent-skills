---
name: decision-log
description: "Keeps a short running log of decisions with the date, the reason and who owns the follow-up. Use after a meeting or a chat where something was decided, or when someone asks why it was decided."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Decision log

Write decisions down so they do not get re-argued.

## Requirements

- Meeting notes or chat threads
- A log file or note

## When to use

- After a meeting
- When someone asks why we chose this

## Steps

1. Read the notes or thread and pick out each decision. Ignore ideas that were not decided.
2. Write one line per decision: date, what, why, owner.
3. Add it to the log, newest first.
4. When asked why, quote the log entry and its date.

## Rules

- Record only what the notes say was decided. Mark unclear items "to confirm".
- Do not share the log outside the team without approval.
- Never change an old entry. Add a new one that replaces it.

## Output format

```
Decision (date)
- What was decided
- Why
- Owner and next step
```
