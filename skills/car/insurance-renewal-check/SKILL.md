---
name: insurance-renewal-check
description: "Reads the insurance policy and renewal notice, lists coverage, price change and exclusions and prepares questions to ask or compare. Use when a renewal notice arrives, or 60 days before the renewal date."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Insurance renewal check

Review the renewal before it renews itself.

## Requirements

- The policy and renewal notice

## When to use

- 60 days before renewal
- When a renewal notice arrives

## Steps

1. Extract coverage, deductible, premium, period and exclusions.
2. Compare with last year's premium and coverage.
3. List questions: why did the price change, what changed in coverage, discounts.
4. If the user brings other quotes, compare like for like and say what differs.

## Rules

- Do not recommend cancelling or switching without the user's decision.
- Quote the policy, never summarize from memory.
- Never sign or pay.

## Output format

```
Renewal (date)
- Premium vs last year
- Coverage and deductible
- Questions to ask
- Quotes compared
```
