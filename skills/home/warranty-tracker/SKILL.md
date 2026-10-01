---
name: warranty-tracker
description: "Collects purchase receipts for appliances and electronics, records warranty end dates and reminds you before they expire. Use when something breaks, or when the user buys a product."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Appliance warranty tracker

Know what is still under warranty before it breaks.

## Requirements

- Email receipts or a folder of receipts

## When to use

- When a product breaks
- Each quarter, list warranties ending in the next 90 days

## Steps

1. Find purchase receipts and invoices for appliances and electronics.
2. Record item, store, purchase date, price and warranty length when stated.
3. Compute the end date. Mark as "assumed" if the length is not on the receipt.
4. List items ending within 90 days and what proof is needed to claim.

## Rules

- Do not assume a warranty length. Say "not stated" and give the legal minimum only after checking an official source.
- Never submit a claim without approval.

## Output format

```
Warranties
- Ending soon: item, date
- Active: count
- Not stated: list
```
