---
name: weekly-status-update
description: "Builds a weekly status update from calendar, tasks and notes: done, in progress, blocked and next, ready for the user to edit. Use when the user needs a weekly update for a team or manager."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Weekly status update

A status update that writes itself.

## Requirements

- Calendar, tasks or notes

## When to use

- Friday afternoon

## Steps

1. List what was completed from tasks and meetings.
2. List what is in progress and expected dates.
3. List blockers and who can unblock them.
4. Draft the update in the user's style, under 200 words.

## Rules

- Do not claim outcomes that are not in the sources.
- The user edits and sends. This skill never sends.

## Output format

```
Status (week)
- Done
- In progress
- Blocked
- Next week
```
