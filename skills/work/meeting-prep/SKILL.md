---
name: meeting-prep
description: "Prepares a one-page brief for each meeting from the calendar invite, past emails and notes: who, goal, open items and questions. Use when the user asks to prepare for a meeting, or an hour before meetings."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Meeting prep

Walk into every meeting knowing why you are there.

## Requirements

- Calendar access
- Email access (read)

## When to use

- One hour before a meeting
- The evening before a big meeting

## Steps

1. Read the invite: attendees, title and description.
2. Find the last 3 email threads and notes with these people.
3. List open items from past discussions and decisions already made.
4. Suggest the goal and 3 questions to ask.

## Rules

- Read only.
- Say "no past context found" when there is none.
- Do not share private notes with attendees.

## Output format

```
Meeting (title, time)
- Who and role
- Goal
- Open items
- 3 questions
```
