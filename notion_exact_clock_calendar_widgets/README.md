# Notion Matcha Clock + Calendar Widgets

This package contains static HTML widgets designed to visually match the provided Notion screenshot.

## Files

- `clock.html` — live clock widget
- `calendar.html` — calendar widget, default locked to September 2024 with the 14th highlighted
- `combined.html` — side-by-side preview of both widgets

## Notion URLs after GitHub Pages is enabled

Replace `YOUR-GITHUB-USERNAME` and `REPO-NAME`:

- Clock:
  `https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/clock.html`

- Calendar:
  `https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/calendar.html`

- Combined:
  `https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/combined.html`

## Useful URL options

Clock:
- `clock.html?tz=America/Chicago`
- `clock.html?tz=America/New_York`
- `clock.html?format=24`
- `clock.html?fixed=2024-09-14T17:22:40-05:00` freezes the screenshot time.

Calendar:
- `calendar.html` exact screenshot default: September 2024, 14 highlighted.
- `calendar.html?mode=current` shows the current month and highlights today.
- `calendar.html?year=2024&month=9&highlight=14`

## Recommended Notion embed sizes

- Clock: place it in the center column and resize to a square-ish card.
- Calendar: place it in the right column and resize it wider than tall.
- Use the same pale green Notion callout/cards around them if needed.
