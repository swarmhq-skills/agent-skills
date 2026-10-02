---
name: home-inventory-list
description: "Builds a room-by-room inventory of household items from photos or notes the user provides, with purchase date and receipt location when known. Use when the user wants to prepare for insurance, moving, or just know what they own."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Home inventory list

A simple list of what you own and what it is worth.

## Requirements

- Photos or notes of each room
- Optional: receipts folder

## When to use

- When the user starts an inventory
- Before renewing home insurance

## Steps

1. Go room by room with the photos or notes the user gives.
2. List each item with a short description and, if the user knows it, the purchase date and price.
3. Note where the receipt or manual is saved. Write "unknown" when not known.
4. Save as a simple table the user can update.

## Rules

- Use only what is in the photos and notes. Do not guess prices or brands.
- Keep the list on the user's own device or drive. Do not share it without approval.
- Never include serial numbers or addresses in anything shared outside the household.

## Output format

```
Inventory (room)
- Item, description
- Purchase date, price if known
- Receipt location
```
