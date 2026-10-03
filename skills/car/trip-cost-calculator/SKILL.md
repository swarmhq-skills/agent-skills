---
name: trip-cost-calculator
description: "Estimates the cost of a car trip from the distance, the car's own fuel use figure and the fuel price the user gives, plus tolls and parking the user lists. Use before a long drive or when comparing driving with the train."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Trip cost calculator

Know what the drive will cost before you go.

## Requirements

- Distance and route
- Car's fuel use from the manual
- Fuel price, tolls, parking

## When to use

- Before a trip

## Steps

1. Take the distance from a maps source and note which.
2. Take the fuel use from the car's manual or the user.
3. Multiply to get fuel cost. Add the tolls and parking the user lists.
4. Show the total and the cost per person if the user says how many travel.

## Rules

- Use the fuel price the user gives. Say that real use varies.
- Take tolls from the operator's own page, or say "not verified".
- Do not book or pay for anything.

## Output format

```
Trip cost (route)
- Distance and source
- Fuel cost
- Tolls and parking
- Total and per person
```
