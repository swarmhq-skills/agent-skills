---
name: price-drop-and-return-window-watch
description: "Tracks recent purchases with their return deadlines and any price match or adjustment window the seller states, and reminds before each closes. Use when the user buys something or asks what can still be returned."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Price drop and return window watch

Do not miss a return deadline or a price adjustment.

## Requirements

- Receipts or order emails
- Optional: calendar access

## When to use

- When a new order arrives
- Weekly review
- When the user asks about a return

## Steps

1. Read the order emails and receipts. Note seller, item, price, date and the return or adjustment window if the seller states one.
2. List what can still be returned and until when. Quote the seller wording.
3. Remind three days before a deadline, added to the calendar after approval.
4. If the user wants to return something, show the seller's steps. Do not start the return.

## Rules

- Only use deadlines stated by the seller. Say "not stated" when it is missing.
- Never start a return, claim or payment without approval.
- Do not state consumer rights. Say "check the seller policy and local rules".

## Output format

```
Returns (date)
- Closing soon: item, seller, deadline
- Open: item, seller, deadline
- Not stated: item, seller
```
