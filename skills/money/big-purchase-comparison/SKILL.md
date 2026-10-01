---
name: big-purchase-comparison
description: "Compares a few options for a large purchase (appliance, laptop, furniture) from official specs and current listed prices, with sources. Use when the user is deciding what to buy and wants a short, honest comparison."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Big purchase comparison

Compare options and prices before a large purchase.

## Requirements

- What the user wants to buy and the budget
- Must-have features

## When to use

- When the user asks which one to buy
- Before a purchase above the user's usual spending

## Steps

1. Write down the must-haves and the budget.
2. Find 3 options and open each maker's own page for the specs. Note the current price and the date it was seen.
3. Compare on the must-haves first, then on price, warranty and return window.
4. Recommend one with the main reason, and say what would change the answer.

## Rules

- Every price and spec needs a source link and a date. Say "not verified" otherwise.
- Do not buy, reserve or pay without approval.
- Mention a downside of the recommended option.

## Output format

```
Options (price, date seen, link)
- Must-have check
- Recommendation and why
- What would change it
```
