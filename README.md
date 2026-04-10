# SnakeLog

A mobile-first Progressive Web App for tracking a snake breeding inventory — built for [802 Clutch](https://802clutch.com) and hosted free on Cloudflare Pages.

## What it does

802 Clutch breeds and sells snakes as a side business. They needed a better way to track animals across species, morphs, and breeds — with photos, weights over time, and quick filtering when someone asks "what do you have available."

SnakeLog solves that:

- **Photo capture** — take or upload a photo directly from your phone camera
- **Structured records** — classify each animal by species, breed, and morph via dropdowns; add notes
- **Weight logging** — log weigh-ins over time per animal
- **Filterable gallery** — browse the full collection, filtered by morph or species
- **Installable** — works as a home screen app on iPhone via service worker; no App Store required

## Technical details

- Single-file PWA (`index.html` + `sw.js` + `manifest.json`)
- No backend, no database — data lives in browser localStorage
- Deployed on Cloudflare Pages (free tier)
- Designed specifically for iPhone: `safe-area-inset` support, `apple-mobile-web-app-capable` meta, touch-optimized UI
- Dark theme with glassmorphism aesthetic

## Stack

- Vanilla HTML / CSS / JavaScript
- Service Worker for offline capability and installability
- Cloudflare Pages for hosting

## Status

Live and in active use by the client.

