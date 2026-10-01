---
name: subscription-audit
description: "Finds recurring charges in bank statements and email receipts, lists each subscription with cost and last charge, and highlights ones to review or cancel. Use when the user asks what subscriptions they have, or monthly."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Subscription audit

Find what you are paying for every month and what you do not use.

## Requirements

- Bank statements (PDF or CSV) or email receipts

## When to use

- Quarterly
- When a surprise charge appears

## Steps

1. Scan statements for charges that repeat on a similar date and amount.
2. Match each with an email receipt when possible to name the service.
3. List: service, amount, frequency, last charge, annual cost.
4. Mark "review" for services the user says they do not use or that overlap. Do not decide for them.
5. For cancellations, give the official cancel route and offer to draft the message.

## Rules

- Read only. Never cancel or message anyone without explicit approval.
- Say "unknown charge" instead of guessing the merchant.
- Statements stay private; do not copy them elsewhere.

## Output format

```
Subscriptions
- Monthly total and annual
- Per service: amount, last charge
- Review: list
- Unknown: list
```
