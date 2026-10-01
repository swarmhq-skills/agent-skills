---
name: receipt-organizer
description: "Collects receipts from email and photos, extracts date, merchant, amount and tax, and files them by year and category with consistent names. Use when the user sends a receipt, or for tax or expense time."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Receipt organizer

Every receipt filed, named and findable.

## Requirements

- Email access or a folder with receipt images and PDFs

## When to use

- When a receipt arrives
- Before tax time

## Steps

1. Find receipts in email and in the receipt folder.
2. Extract date, merchant, total and tax. If unreadable, mark it and ask.
3. Name each file YYYY-MM-DD merchant amount and put it in year and category folders.
4. Produce a CSV with all fields for the period.

## Rules

- Keep originals unchanged. Copy, never delete.
- Do not guess an unreadable amount.
- Store in a private location only.

## Output format

```
Receipts
- Filed: count
- Unreadable: list
- CSV: path
```
