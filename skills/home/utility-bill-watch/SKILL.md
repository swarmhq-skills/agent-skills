---
name: utility-bill-watch
description: "Reads your utility bills (electricity, water, gas, internet), compares each with the previous months and flags unusual jumps, price changes and duplicate charges. Use when a bill arrives, or when the user asks why a bill is high."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Utility bill watch

Catch a bill that jumped before it is due.

## Requirements

- Email or a folder with your bills (PDF or text)

## When to use

- When a new bill arrives
- Monthly summary
- When a bill looks high

## Steps

1. Find the latest bill and the previous 6 from the same provider.
2. Extract amount, period, usage and unit price when shown.
3. Flag a bill if it is more than 20 percent above the 6-month average, or if the unit price changed, or if a charge appears twice.
4. For each flag, quote the line from the bill and suggest one question to ask the provider.

## Rules

- Read only. Never contact the provider or pay anything without approval.
- Quote numbers from the bills, never estimate missing ones.
- Say "cannot tell" when usage data is missing.

## Output format

```
Bills (month)
- Provider: amount, vs average
- Flags: reason and quote
- Question to ask: one line
```
