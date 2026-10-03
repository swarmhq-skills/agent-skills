---
name: side-income-tracker
description: "Logs income and costs from a side activity the user runs, and shows a monthly total and what is left after costs. Use for freelance work, resale or a small business."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Side income tracker

See what your side work really earns.

## Requirements

- Income and cost entries the user provides
- Optional: invoices or receipts the user shares

## When to use

- After each payment or cost
- At month end

## Steps

1. Record each income and cost with date, source and amount.
2. Total each month and show income, costs and what is left.
3. List unpaid invoices and how many days they are overdue.
4. Draft a polite reminder for an overdue invoice, for the user to review.

## Rules

- Do not give tax advice or fill in tax forms. Say a tax professional or the tax office decides.
- Do not send reminders without approval.
- Use only the numbers the user gives.

## Output format

```
Side income (month)
- Income by source
- Costs
- Left after costs
- Overdue invoices
```
