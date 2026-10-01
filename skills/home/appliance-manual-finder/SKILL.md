---
name: appliance-manual-finder
description: "Finds the official manual, the support page and the troubleshooting steps for a household appliance from its brand and model number. Use when something at home stops working, or when the user asks how to use or clean an appliance."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Appliance manual finder

The right manual and fix steps, from the model number.

## Requirements

- Brand and model number (or a photo of the label)
- Optional: a folder where manuals are saved

## When to use

- When an appliance fails or beeps
- When the user asks how to clean or set up an appliance

## Steps

1. Read the brand and model from the user, or from the label photo. Ask if it is unclear.
2. Search for the manufacturer's own support page and manual. Prefer the official domain.
3. Summarise the relevant section: the error code, the reset or cleaning steps, and when to call support.
4. Offer to save the manual link in the user's notes or folder.

## Rules

- Use official manufacturer pages only. Say "not found" rather than using a forum guess.
- Never suggest opening the appliance or doing electrical or gas work. Point to a qualified technician.
- Do not order parts or book repairs without approval.

## Output format

```
Appliance (brand, model)
- Official manual link
- Steps for this problem
- When to call support
```
