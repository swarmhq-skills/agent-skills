---
name: birthday-and-gift-planner
description: "Keeps birthdays and occasions, reminds you two weeks before and suggests gifts within the budget, based on what the user tells you. Use when a birthday is coming up."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: parenting
---

# Birthday and gift planner

Remember the dates and find the right gift.

## Requirements

- A list of dates the user gives

## When to use

- Two weeks before each date

## Steps

1. Keep the list of people and dates the user provides.
2. Remind two weeks before.
3. Ask interests and budget and suggest 3 gift ideas with where to buy.
4. Never buy without approval.

## Rules

- Never buy or message anyone without approval.
- Use only information the user shares, not guesses about people.
- Keep the list private.

## Output format

```
Coming up
- Person, date
- 3 ideas with budget
- Order by date
```
