---
name: training-load-check
description: "Reviews the last four weeks of training volume and recovery signals and flags when load is climbing too fast or recovery is falling. Use when the user asks if they are overtraining, planning a hard week, or before a race."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: health
---

# Training load check

A weekly check that you are building fitness and not just fatigue.

## Requirements

- Training history (hours or distance per week) and recovery data such as resting heart rate and sleep

## When to use

- Weekly, after the last long session
- Before a hard training week or a race

## Steps

1. Sum training volume per week for the last 4 weeks. Compute the change from week to week.
2. Compare resting heart rate and sleep in the same weeks against the user's own 8-week average.
3. Flag a week as "watch" if volume rose more than 20 percent and resting heart rate or sleep moved the wrong way for 3 or more days.
4. Suggest one adjustment for the coming week: hold, reduce by about 20 percent, or continue.

## Rules

- Not medical advice. Chest pain, dizziness or injury means stop and see a professional.
- Use the user's own baseline, never population averages.
- Say plainly when there is not enough data.

## Output format

```
Training (4 weeks)
- Volume by week with change
- Recovery signals vs your baseline
- Status: fine / watch
- Next week: hold / reduce / continue and why
```
