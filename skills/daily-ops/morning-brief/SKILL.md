---
name: morning-brief
description: "Builds a short daily brief from calendar, email and tasks: today's schedule, what needs a reply, deadlines and one decision for the day. Use when the user asks for a morning brief, daily plan or \"what is on today\", or on a daily schedule."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Morning brief

One message each morning with your day, your open loops and the one decision that matters.

## Requirements

- Calendar access (read)
- Email access (read)
- Optional: a task list

## When to use

- Every morning at a fixed time
- When you ask "what is on today?"

## Steps

1. Read today's and tomorrow's calendar events. Flag conflicts, back-to-back blocks and travel gaps.
2. Scan email from the last 24 hours. List only messages that need a reply from you, newest first, with one line on why.
3. Pull tasks or deadlines due in the next 3 days.
4. Pick ONE decision or action that would make the day better if done first. Say why in one sentence.
5. Write the brief using the output format below. Keep it under 150 words.

## Rules

- Never send or reply to anything. This skill only reads and summarizes.
- Quote facts from the source. If something is unclear, say "unclear" instead of guessing.
- Skip newsletters, receipts and promotions unless they carry a deadline.
- If nothing needs attention, say so in one line. A short brief is a good brief.

## Output format

```
Today (date)
- Schedule: 3 to 5 lines, with times
- Needs a reply: up to 5 items, one line each
- Deadlines: next 3 days
- Do first: one action and why
```
