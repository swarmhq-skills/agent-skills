---
name: delivery-tracker
description: "Finds order and shipping emails, extracts carrier, tracking number and expected date, and keeps one list of packages in transit. Use when the user asks where a package is, or daily on days with deliveries expected."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Package and delivery tracker

One list of what is on its way and when.

## Requirements

- Email access (read)

## When to use

- Daily when something is in transit
- When the user asks where an order is

## Steps

1. Search recent email for order confirmations and shipping notices.
2. Extract store, item, carrier, tracking number and expected date.
3. Check the carrier's tracking page for the status and say when it was read.
4. Flag late packages (past expected date by 2 days) and suggest the contact route.

## Rules

- Read only. Never contact a seller or file a claim without approval.
- Do not open links in suspicious emails. Report them instead.
- If tracking cannot be checked, say so.

## Output format

```
In transit (date)
- Item: carrier, status, expected
- Late: list
- Delivered: last 7 days
```
