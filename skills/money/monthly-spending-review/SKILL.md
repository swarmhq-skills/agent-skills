---
name: monthly-spending-review
description: "Summarizes a month of transactions by category, compares with the previous months and highlights the biggest changes. Use when the user asks where the money goes, or at month end."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Monthly spending review

Where the money went, in plain numbers.

## Requirements

- Bank statements (PDF or CSV)

## When to use

- Month end
- When the user asks for a spending breakdown

## Steps

1. Load the month and the previous 3 months of transactions.
2. Categorize each transaction. Mark categories as "provisional" when the purpose is not clear.
3. Show totals per category and the change versus the 3-month average.
4. Highlight the 3 biggest changes and ask what explains them.

## Rules

- Transfers, loans and taxes are not consumption. Keep them separate.
- Do not judge spending. Report and ask.
- Never present estimates as facts. Say "provisional".
- This is not financial advice.

## Output format

```
Month (name)
- In and out
- By category
- Biggest changes: 3
- Questions
```
