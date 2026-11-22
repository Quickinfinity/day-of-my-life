# Project: Day of My Life

- **Created:** 2026-11-21
- **Owner:** Joe Quick
- **Repo:** https://github.com/Quickinfinity/day-of-my-life
- **Description:** Day-of-your-life counter with day lookup, "When I was your age", and a daily KJV verse.

## Objectives
- Our own copy of the app first built in Grok Build, with an in-app menu and no "Created with Grok" badge
- Embedded on ibrainos.com under the Day of My Life tab

## Tech Stack
- One static `index.html` (vanilla JS + CSS), hosted on GitHub Pages
- Verse text from bible-api.com, KJV only

## Project-Specific Rules
- This repo is the master. Push to `main` deploys.
- GitHub Pages caches for 10 minutes: after a release, bump the `?v=N` stamp on the iframe src in ibrainos.com page 53 (see the ibrainos-website skill).
- Bible text: KJV only.
- Keep the localStorage keys (`doml.birthdate`, `doml.verse.v3`, `doml.child`).
- Use relative asset paths; the site is served from `/day-of-my-life/`.
