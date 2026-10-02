---
name: expense-category-cleanup
description: "Takes a list of transactions the user exports and assigns each to a category, flagging the ones it cannot place so the user can decide. Use when a spending summary has too much in \"other\"."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Expense category cleanup

Fix the "other" pile in your spending.

## Requirements

- Exported transactions (CSV)
- The user's category list

## When to use

- When the user exports statements
- Before a monthly review

## Steps

1. Read the export and the category list the user wants.
2. Assign each transaction to a category from the merchant name. Reuse earlier choices the user made.
3. List the unclear ones separately with the merchant name and amount.
4. Save the user's answers as rules for next time.

## Rules

- Read only. Never log in to a bank or change any account.
- Do not guess when a merchant name is ambiguous. Ask.
- Keep the file on the user's device. Do not share transactions.

## Output format

```
Categories (month)
- Total per category
- Needs your decision: merchant, amount
- New rules saved
```
