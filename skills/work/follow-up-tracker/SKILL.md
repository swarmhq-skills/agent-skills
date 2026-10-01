---
name: follow-up-tracker
description: "Finds promises and open questions in your sent email, tracks who owes what and drafts nudges after a set number of days. Use when the user asks what is waiting on others, or weekly."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Follow-up tracker

Nothing you promised falls through.

## Requirements

- Email access (read)

## When to use

- Weekly
- When the user asks "who owes me a reply?"

## Steps

1. Scan sent email for questions asked and promises made.
2. Check whether a reply or action came.
3. List items waiting on others and items the user owes, with days waiting.
4. Draft a polite nudge for items older than 5 days. Show it, send nothing.

## Rules

- Never send without approval.
- Do not nudge people about sensitive topics without asking.
- Only use what is in the emails.

## Output format

```
Open loops
- You owe: item, days
- Waiting on: person, item, days
- Draft nudges
```
