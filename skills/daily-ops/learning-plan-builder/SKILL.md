---
name: learning-plan-builder
description: "Builds a simple learning plan for a skill the user chooses, from their available time and goal, with a weekly schedule and checkpoints. Use when the user wants to learn a language, tool or subject."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Learning plan builder

A realistic plan to learn something new.

## Requirements

- The skill and the goal
- Hours available per week

## When to use

- When the user starts learning something
- Monthly check-in

## Steps

1. Ask what the user wants to be able to do and by when.
2. Break the goal into stages, each with a small checkpoint they can test.
3. Find free or official learning materials and note the source.
4. Lay out a weekly schedule that fits the user's hours.

## Rules

- Link only to materials the user can open. Say "not verified" for anything unchecked.
- Do not enrol in or pay for a course without approval.
- Never promise a result or a timeline.

## Output format

```
Learning plan (skill)
- Stages and checkpoints
- Weekly schedule
- Materials and sources
```
