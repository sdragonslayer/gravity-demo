# Gravity Sandbox

An interactive N-body gravity simulator in the browser, built with [three.js](https://threejs.org/).

## Features

- Click and drag to launch bodies, with a live predicted path
- Collisions that merge bodies or shatter them into fragments
- Presets: solar system, binary star, figure-8, colliding galaxies, random
- Bloom glow, orbit trails, and a camera that can follow a selected body

## Running

No build step. The page loads three.js from a CDN, so it just needs to be served over HTTP:

```sh
npx serve .
# or
python -m http.server
```

Then open the printed URL in a browser.

## Controls

| Key | Action |
| --- | --- |
| `Space` | Pause / resume |
| `1`–`5` | Load a preset |
| `R` | Add random planets |
| `C` | Clear (keeps the sun) |
| `V` | Reset view |
| `F` | Follow selected body |
| `Delete` | Delete selected body |
| `T` / `B` / `G` | Toggle trails / bloom / grid |
| `H` | Hide the panel |
| `Esc` | Deselect |
