---
name: garmin-sleep-stress-correlations
description: "Looks for patterns between your sleep, stress, resting heart rate and training data (for example from a Garmin export) and the things you log: food, alcohol, caffeine, travel, busy days. Use when the user asks why they slept badly, wants a weekly health pattern report, or logs food or alcohol."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: health
---

# Sleep and stress correlations

Connect last night's sleep to the things you did, and see patterns instead of single numbers.

## Requirements

- Daily sleep, stress and resting heart rate data: a Garmin Connect export (CSV) or any connector that provides it
- Optional: calendar, for busy and travel days
- Optional: a simple log of food, alcohol and caffeine you tell the agent

## When to use

- Mid-morning, after the watch has synced
- Weekly pattern report
- Whenever you log food or alcohol and ask "does this matter?"

## Steps

1. Load the last 30 days of sleep duration, sleep score, stress and resting heart rate. Note any missing days.
2. Load the user's log (food, alcohol, caffeine, late meals) and calendar context (busy days, travel).
3. Compare nights with and without each logged factor. Report the difference in averages and how many nights are behind each number.
4. Report only patterns with at least 8 nights behind them. Mark everything else "too early to say".
5. End with one experiment the user can try for two weeks, such as "no alcohol on weeknights".

## Rules

- This is pattern-spotting, not medical advice. Never diagnose. Suggest seeing a doctor for persistent symptoms.
- Correlation is not causation. Use words like "tends to" and "went along with", never "caused".
- Do not assume which days are special. Use the calendar or what the user tells you.
- Health data stays with the user and the agent. Never share it with anyone else.
- Keep the sleep report as its own message, separate from the morning brief.

## Output format

```
Sleep this week (date range)
- Averages: sleep hours, score, stress, resting HR
- Patterns (8+ nights): factor, difference, n nights
- Too early to say: list
- Try for two weeks: one experiment
```
