---
name: energy-tariff-review
description: "Reads your last 12 months of energy bills, summarizes usage and costs and lists questions to compare plans, without guessing prices. Use when the user asks if they should change energy plan."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Energy tariff review

Check if your energy plan still fits how you use it.

## Requirements

- The last 12 months of bills
- Optional: the plan's price list

## When to use

- Once or twice a year
- After a price change notice

## Steps

1. Extract monthly usage, peak and off-peak split if present, fixed charges and unit prices.
2. Summarize annual cost and usage pattern.
3. Prepare the questions to ask or compare: price per unit by period, fixed fees, contract length, exit fees.
4. If the user shares another plan's price list, compute the annual cost with the same usage and show the formula.

## Rules

- Never invent tariffs or prices. Use only numbers from the bills or from a price list the user provides or an official source you cite.
- Do not switch or sign anything without approval.

## Output format

```
Energy (12 months)
- Usage and cost
- Pattern: one line
- Questions to compare
- Estimated cost under another plan, if given
```
