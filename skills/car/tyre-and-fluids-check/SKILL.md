---
name: tyre-and-fluids-check
description: "Gives the user a short monthly car check for tyres, oil, coolant and washer fluid, using the figures in the owner manual. Use monthly or before a long trip."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Tyre and fluids check

A five-minute monthly check with the right numbers.

## Requirements

- Car make and year
- Owner manual (link or PDF)

## When to use

- First weekend of the month
- Before a long trip

## Steps

1. Read the owner manual for tyre pressure, fluid types and check procedures.
2. List the checks in a short order the user can follow in five minutes.
3. Record the readings the user reports and compare with the manual.
4. Flag anything outside the manual range and suggest the user see a garage.

## Rules

- Take every figure from the owner manual. Say "check the manual" when it is missing.
- Never advise driving with a safety warning light on.
- Do not book a garage without approval.

## Output format

```
Monthly check (date)
- Tyre pressure vs manual
- Fluid levels
- Flags and next step
```
