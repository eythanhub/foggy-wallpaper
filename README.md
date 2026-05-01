# Foggy Wallpaper — HUB Void Smoke

An animated HTML/Canvas wallpaper for HUB Institute. It renders a real-time smoky fog simulation with a centered floating logo, built entirely with the Canvas API — no external dependencies.

## Preview

- Dark background (`#010130`) with animated smoke particles
- Centered HUB Institute logo with a glowing corona effect
- Smooth animation in pure JavaScript

## Project Structure

```
.
├── HUB_VoidSmoke_Wallpaper.html   # Main page (Canvas animation)
├── server.js                      # Minimal Node.js HTTP server
├── package.json                   # Project metadata
└── Procfile                       # Start command (Heroku / Railway)
```

## Run Locally

Make sure you have **Node.js ≥ 18** installed, then:

```bash
npm start
```

The server starts at [http://localhost:3000](http://localhost:3000).

The `PORT` environment variable is respected if set.

## Deployment

The included `Procfile` enables one-click deployment on compatible platforms (Heroku, Railway, Render…):

```
web: node server.js
```
