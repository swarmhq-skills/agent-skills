---
name: emergency-fund-tracker
description: "Calculates how many months of basic expenses the user's savings would cover, from figures the user provides, and tracks progress toward a goal the user sets. Use when the user asks if their savings are enough."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Emergency fund tracker

See how many months of expenses you could cover.

## Requirements

- Monthly essential expenses
- Current savings
- Optional: target in months

## When to use

- Monthly
- When income or expenses change

## Steps

1. List the essential monthly expenses the user gives and add them up.
2. Divide savings by that total to get months covered.
3. Show progress against the user's own target, and the monthly amount needed to reach it by a date they pick.
4. Save the numbers so next month shows the change.

## Rules

- Use only the figures the user gives. Never log in to a bank.
- This is arithmetic, not financial advice. Say so once.
- Do not suggest products or accounts.

## Output format

```
Emergency fund (month)
- Essential expenses total
- Months covered
- Gap to target and monthly amount
```
