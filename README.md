# Impacter Design System

Brand background and motion library for Impacter Pathway — dark navy `#0E2A4E` → coral `#FF6F61`.

## Viewing

Open `backgrounds/index.html` in a browser, or serve the repo locally:

```bash
cd backgrounds
python3 -m http.server 8000
# open http://localhost:8000
```

## Contents

- `backgrounds/index.html` — library home, links to every collection
- `backgrounds/static-gallery.html` — 14 static gradient/texture backgrounds shown as full website sections
- `backgrounds/interactive.html` — cursor-following spotlight, liquid metaballs, 3D dot terrain, tilt parallax
- `backgrounds/geometric.html` — magnetic dots, tile wall, isometric cubes, shape constellation
- `backgrounds/subtle.html` — low-motion variants: whisper glow, quiet dots, breathing lines, slow tide
- `backgrounds/voice-hero.html` — voice-intelligence hero with speech-like signal bars
- `backgrounds/assets/` — 15 standalone SVG backgrounds (scalable, drop-in)

## Usage notes

- All animations are dependency-free (no libraries); each section's HTML/CSS/JS can be lifted into a site as-is.
- SVG grain uses `feTurbulence` filters — renders in browsers, but not when imported into Figma (add a noise layer there instead).
- Interactive pages idle-animate gently and respond to `pointermove`.
