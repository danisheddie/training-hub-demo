# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

A demo triathlon and endurance sports training hub for **Tony Stark**. Single-file vanilla HTML/CSS/JS SPA — no build system, no framework, no dependencies beyond Google Fonts.

- **Live URL:** https://danisheddie.github.io/training-hub-demo/
- **GitHub repo:** https://github.com/danisheddie/training-hub-demo
- **Primary file:** `Training Hub v2.html` — this is the active app
- `Training Hub.html` and `Training Plan.html` are legacy/archived versions, do not edit them
- `index.html` is a redirect stub to `Training Hub v2.html`

## Deploying changes

```bash
cd "/Users/danisheddie/Desktop/Training Hub Demo"
git add "Training Hub v2.html"
git commit -m "Description of change"
git push
```

GitHub Pages auto-deploys from `main`. Live in ~60 seconds.

`gh` CLI is installed at `~/bin/gh`.

## Athlete context (Tony Stark — demo)

**Races in plan:**
- Ironman 70.3 Cebu — 2 November 2026, goal: Sub-6:30
- City Half Marathon — 18 October 2026, goal: Sub-2:00

This is a demo repo for sharing/testing. Do not add personal data.
