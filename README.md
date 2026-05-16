# My Diet Plan

A weekly diet plan app with meal tracking, ingredient scaling, and offline support. Built as a zero-build static site for GitHub Pages.

## Features

- Weekly Indian vegetarian meal plan with breakfast, lunch, snack, and dinner
- Time-aware meal highlighting based on IST
- Ingredient scaling by number of people
- Tomorrow's prep reminders
- Dark mode with system preference detection
- Offline support via service worker (PWA)
- Installable on mobile via "Add to Home Screen"

## Usage

Open `index.html` in a browser, or serve the directory over HTTP:

```bash
npx serve .
```

## Deployment

Push to a GitHub repository and enable GitHub Pages from **Settings > Pages > Source: main branch**. The app works at `https://<username>.github.io/<repo>/`.

## Tech Stack

- HTML + vanilla JS (no build step)
- Bootstrap 5.3 (CDN)
- Bootstrap Icons (CDN)
- Google Fonts (Inter)
- Service Worker for offline caching
