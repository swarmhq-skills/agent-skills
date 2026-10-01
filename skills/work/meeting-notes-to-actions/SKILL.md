---
name: meeting-notes-to-actions
description: "Turns meeting notes or a transcript into decisions, actions with owners and dates, and a short follow-up message for approval. Use when the user pastes meeting notes or a transcript."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Meeting notes to actions

Turn messy notes into owners and dates.

## Requirements

- The notes or transcript

## When to use

- After each meeting

## Steps

1. Extract decisions made, in the participants' words.
2. List actions with owner and date. Mark "no owner" or "no date" when missing.
3. Draft a short follow-up message with decisions and actions.
4. Wait for approval before sending or adding tasks.

## Rules

- Never invent owners or dates.
- Keep sensitive remarks out of the follow-up.
- Send nothing without approval.

## Output format

```
Decisions
- List
Actions
- Owner, date, action
Draft follow-up
```
