---
name: annual-cost-of-ownership
description: "Adds up the yearly cost of owning something, such as a car, a pet or a subscription bundle, from the figures the user provides. Use when the user wants to know the true cost before or after buying."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Annual cost of ownership

What something really costs per year.

## Requirements

- List of costs with amounts and how often
- Optional: the item's purchase price

## When to use

- Before a purchase
- Yearly review

## Steps

1. List every cost the user gives with its frequency.
2. Convert each to a yearly amount.
3. Add the purchase price spread over the years the user expects to keep it.
4. Show the total per year and per month, and the largest cost.

## Rules

- Use only the figures the user gives. Say which costs are missing.
- This is arithmetic, not advice.
- Never log in to any account.

## Output format

```
Cost of ownership (item)
- Cost, per year
- Total per year and month
- Largest cost
- Missing costs
```
