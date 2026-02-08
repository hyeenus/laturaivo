# Laturaivo

Laturaivo (Finnish for “Slope Rage”) is a fast-paced side-scrolling ski beat ’em up built in plain HTML5 Canvas and vanilla JavaScript.

## Features

- Single-file browser game (`index.html`) with no external framework dependencies
- Pixel-art sprite pipeline with animated enemies and player actions
- Player combat: pole strike, slalom slash, nordic boost, long-pole upgrade, and gun power-up
- Boss fight with projectile interactions
- Music, SFX, combo/score system, pickups, and HUD

## Controls

- `Arrow Keys`: Move
- `Z`: Basic pole strike
- `X`: Slalom slash
- `C`: Nordic boost
- `P`: Pause
- `Enter`: Start / restart from title or game over screens

## Run Locally

Open `index.html` directly in a modern browser, or run a local static server:

```bash
cd /Users/anssisaviluoto/Documents/Laturaivo
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Deploy to GitHub Pages

1. Push this project to a GitHub repo.
2. In GitHub: `Settings` → `Pages`.
3. Under **Build and deployment**, select:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
4. Save and wait for deployment.

Your game will be available at:

`https://<your-username>.github.io/<your-repo>/`

## Project Layout

- `/Users/anssisaviluoto/Documents/Laturaivo/index.html`: Game code and render loop
- `/Users/anssisaviluoto/Documents/Laturaivo/graphics`: Sprite sheets and background assets
- `/Users/anssisaviluoto/Documents/Laturaivo/music1.mp3`, `/Users/anssisaviluoto/Documents/Laturaivo/music2.mp3`, `/Users/anssisaviluoto/Documents/Laturaivo/music3.mp3`: Music tracks
