# Sunset/Sunrise Color Predictor: handoff package (2026-10-13)

This package rebuilds Bill Meier's daily sky-color forecast in a new assistant.

## Files
- color-forecast-prompt-v1.2.md: the full forecasting prompt (rubric, data sources, scoring, output format, calibration lessons). This is the core.
- verification-log.csv: every forecast vs. Bill's actual score since 9/26.
- example-report-2026-10-10.md: a real report (St. Charles GO 8, actual 9) showing the expected format.
- new-bot-setup.md: paste-in instructions for the new bot (persona, preferences, routine).

## Quick start
1. Create new  and paste the "Bot instructions" section of new-bot-setup.md into its instructions or first message.
2. Upload color-forecast-prompt-v1.2.md and verification-log.csv to its computer (or paste them in).
3. Ask it to create the daily routine described in new-bot-setup.md.
4. Run one forecast manually to test it.
