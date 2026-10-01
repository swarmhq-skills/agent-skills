---
name: bill-due-reminders
description: "Finds due dates in bills and emails and sends reminders three days before and on the due day. Use when a bill arrives, or when the user asks what is due."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Bill due reminders

Never pay a bill late again.

## Requirements

- Email access (read)
- Calendar access (optional)

## When to use

- Daily
- When a bill arrives

## Steps

1. Scan email for bills and invoices with a due date.
2. Extract provider, amount, due date and how to pay as written on the bill.
3. Remind three days before and on the day, only for bills not marked paid.
4. Ask the user to confirm payments so the list stays right.

## Rules

- Never pay anything. Reminders only.
- Bills with a payment link are treated as suspicious until the user confirms the sender.
- Say "no due date found" when none is shown.

## Output format

```
Due soon
- Today: provider, amount
- In 3 days: list
- Overdue: list
```
