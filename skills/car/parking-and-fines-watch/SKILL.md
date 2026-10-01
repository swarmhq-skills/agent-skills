---
name: parking-and-fines-watch
description: "Watches email and post notices for traffic and parking fines, extracts the deadline and amount and reminds you before reduced-amount deadlines. Use when a fine notice arrives."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Parking and fines watch

Catch a fine in time to pay it at the lower amount.

## Requirements

- Email access (read)

## When to use

- When a notice arrives
- Weekly

## Steps

1. Search email for fines, notices and toll debts.
2. Extract authority, plate, date, place, amount and deadlines as written.
3. Verify the notice against the official authority site. Never pay through an email link.
4. Remind before each deadline.

## Rules

- Treat links in fine emails as suspicious. Use the official site typed directly.
- Never pay without approval.
- Do not decide whether to contest. Give the official route.

## Output format

```
Fines
- Notice: authority, amount, deadline
- Verified on official site: yes or no
- Reminder dates
```
