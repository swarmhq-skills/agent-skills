---
name: shared-expense-splitter
description: "Adds up shared expenses between people and shows the simplest way to settle. Use when the user shares costs for a trip, a house or an event and asks who owes what."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Shared expense splitter

Who owes whom after a trip, a dinner or a shared home.

## Requirements

- Expense list with who paid and who shares each one

## When to use

- At the end of a trip or event
- Monthly for shared homes

## Steps

1. Write down each expense: what, amount, currency, who paid, who shares it.
2. Calculate each person's share and the net balance. Show the calculation.
3. Suggest the fewest payments that settle everyone.
4. Ask for confirmation of every figure before the user shares the result.

## Rules

- Use only the figures the user gives. Show the arithmetic so it can be checked.
- Never send payment requests or messages to others without approval.
- Say when currencies differ and ask for the rate the user wants to use.

## Output format

```
Settle up
- Total spent
- Each person's share
- Balances
- Payments to settle
```
