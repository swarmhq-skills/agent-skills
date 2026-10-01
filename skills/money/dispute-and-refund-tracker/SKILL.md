---
name: dispute-and-refund-tracker
description: "Tracks open refunds and disputes, with the evidence, the channel and the next date to follow up, and drafts follow-ups for approval. Use when the user wants a refund, a chargeback or to complain about a charge."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Refund and dispute tracker

Track every refund until the money is back.

## Requirements

- The charge details and any receipts or emails

## When to use

- When a refund is requested
- Weekly while any case is open

## Steps

1. Record the case: merchant, amount, date, reason and evidence.
2. Find the official refund or complaint route for the merchant and the country. Cite the source.
3. Draft the message with facts only. Show it to the user for approval before sending.
4. Set a follow-up date and check the inbox for replies.

## Rules

- Never send a complaint or accept an offer without approval.
- Facts and dates only. No threats, no legal claims the user has not approved.
- Say when the official route cannot be verified.

## Output format

```
Case (merchant)
- Status and next date
- Evidence list
- Draft message awaiting approval
```
