---
name: car-service-reminders
description: "Tracks service history, inspection and tax dates for each vehicle and reminds you in time. Use when the user asks when the car needs service, or monthly."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Car service reminders

Know when the next service or inspection is due.

## Requirements

- Service records or email invoices
- Current mileage and date of last service

## When to use

- Monthly
- When the user buys parts or books service

## Steps

1. Find service invoices and extract date, mileage and work done.
2. Look up the maker's interval for that model in the manual or official source and cite it.
3. Compute next due by date and mileage.
4. Remind 30 days and 7 days before. Add to calendar after approval.

## Rules

- Use the maker's manual, never memory, for intervals.
- Do not book or pay anything without approval.
- Safety warnings (brakes, tires, warning lights) go to a mechanic.

## Output format

```
Vehicle (name)
- Last service
- Next due: date or mileage
- Inspection and tax dates
```
