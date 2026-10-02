---
name: plant-care-reminders
description: "Makes a watering and care schedule for the user's houseplants from the plant names and the care instructions on the label or the grower's page. Use when the user lists plants or says one looks unhealthy."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Plant care reminders

Water and feed each plant on its own schedule.

## Requirements

- List of plants or photos of labels
- Optional: calendar access

## When to use

- When the user adds a plant
- Weekly

## Steps

1. Identify each plant from the name or label the user gives. Ask if unsure.
2. Find care instructions on the grower or a botanic garden page and note the source.
3. Build a weekly schedule grouping plants with similar needs.
4. Offer calendar reminders. Mark plants where the care advice conflicts between sources.

## Rules

- Cite the page each instruction came from. Say "not sure" for unclear plants.
- If a plant may be toxic to pets or children, say to check the source.
- Do not order products without approval.

## Output format

```
Plant schedule
- Plant, water, light, feed
- Source link
- Not sure
```
