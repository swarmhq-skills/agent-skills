---
name: card-payoff-planner
description: "Turns the balances, rates and minimum payments the user provides into a simple payoff plan, using plain arithmetic. Use when the user wants to pay off a card or loan faster and see the effect of extra payments."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Card payoff planner

A clear plan to pay down a balance.

## Requirements

- Balance, interest rate and minimum payment for each debt
- How much extra per month the user can pay

## When to use

- When the user asks how to pay a debt off
- After a change in income or rates

## Steps

1. List each debt with its balance, rate and minimum payment.
2. Compute the months to pay off with minimums only.
3. Compare two orders: highest rate first, and smallest balance first. Show months and total interest for each.
4. Show the effect of the extra amount the user mentioned.

## Rules

- Use only the figures the user gives. Do not guess a rate.
- This is arithmetic, not financial advice. Say so once.
- Never log in to a bank or move money.

## Output format

```
Debts (balance, rate)
- Minimums only: months
- Two orders compared
- Effect of the extra payment
```
