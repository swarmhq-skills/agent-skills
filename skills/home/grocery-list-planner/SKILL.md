---
name: grocery-list-planner
description: "Plans meals for the week from the household's tastes and constraints and turns them into a grocery list grouped by store section, minus what is already at home. Use when the user asks for a meal plan or a shopping list."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Grocery list planner

Turn the week's meals into one shopping list.

## Requirements

- Household size, diet constraints and budget
- What is already at home

## When to use

- Weekly, before shopping
- When the user asks what to cook

## Steps

1. Ask for allergies, dislikes, cooking time per day and a weekly budget.
2. Propose 5 dinners that share ingredients to reduce waste.
3. Build the list grouped by section and subtract what is at home.
4. Note the 2 meals that use the most perishable items so they get cooked first.

## Rules

- Never ignore a stated allergy. Ask again if unsure.
- Prices are estimates and are labeled as such.
- Do not place orders without approval.

## Output format

```
Week plan
- Dinners: 5 lines
- List by section
- Cook first: 2 meals
```
