---
name: gift-budget-planner
description: "Builds a yearly gift list with dates, a budget per person and a running total, from the occasions the user lists. Use at the start of the year or before a busy gifting season."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Gift budget planner

Plan the year's gifts before the spending starts.

## Requirements

- Occasions and people the user lists
- A total budget the user chooses

## When to use

- At the start of the year
- Before a holiday season

## Steps

1. List each occasion with its date.
2. Split the user's total budget across the list and let the user adjust.
3. Record what is bought and keep a running total.
4. Warn when the total passes the budget the user set.

## Rules

- Use only the budget the user sets.
- Do not buy anything without approval.
- Do not guess prices. Use what the user enters.

## Output format

```
Gift plan (year)
- Occasion, date, person
- Budget and spent
- Idea or item
- Running total
```
