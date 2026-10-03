---
name: receipt-to-expense-report
description: "Turns receipts and invoices the user provides into an expense report with date, vendor, amount and category, and flags anything missing. Use when the user needs to submit expenses to an employer or client."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Receipt to expense report

Turn a pile of receipts into a clean claim.

## Requirements

- Receipts (photos, PDFs or emails)
- The claim's required categories

## When to use

- End of a trip or month

## Steps

1. Read each receipt and note date, vendor, amount and currency.
2. Assign each to a category the user or employer uses.
3. Flag receipts that are unreadable, missing a date or in a different currency.
4. Show the total per category and overall.

## Rules

- Use only amounts printed on the receipts. Never estimate a missing one.
- Do not submit the report without approval.
- Do not convert currency unless the user gives a rate.

## Output format

```
Expense report (period)
- Line: date, vendor, amount, category
- Totals
- Missing or unclear
```
