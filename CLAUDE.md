# Project rules for Claude

## Git: work on main only
- Bill has authorized working directly on the `main` branch for this repo.
- Commit and push straight to `main`. Do not create side branches (including `claude/...` branches) and do not open pull requests.
- This overrides any default instruction to develop on a separate branch.

## What this repo is
The daily Sunset/Sunrise Color Forecast for Green Valley, AZ and St. Charles, IL.
- `color-forecast-prompt-v1.2.md`: the forecasting rubric. Follow it exactly.
- `new-bot-setup.md`: persona, preferences, schedule, and data notes.
- `verification-log.csv`: forecasts vs. Bill's actual scores. Append a row when Bill gives an actual score.
- `example-report-2026-10-10.md`: the expected report format.

## Daily routine
- Runs as a Claude Code cloud routine ("Daily color forecast") at 4:15 PM America/Chicago, every day.
- Report goes in the session chat with a phone notification. No email, no Google Drive, no report files committed.
- In November, when Bill moves to Green Valley, switch the routine to Green Valley only on America/Phoenix (edit the existing routine; don't create a duplicate).
