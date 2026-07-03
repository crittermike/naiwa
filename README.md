# Naiwa

A web recreation of the **Naiwa** virtual-companion app, featuring the character **Reverie** as a real-time **3D dancing character**.

Single self-contained `index.html` — Three.js via CDN, no build step.

**Live:** https://crittermike.github.io/naiwa/

## Features
- Full-screen, procedurally-modeled **3D Reverie** rendered with Three.js (lighting, soft shadows, bloom)
- **10 scenes**, each with its own dance/movement, camera, mood, lighting, particles, and music
- Genuine articulated choreography per scene — bop, shush, adore, slump, hatch-jumps, party, sail, self-hug, disco, walk
- **Web Audio** engine: per-scene melodies, drums, chords, ambience, and laughter
- Tap Reverie for a giggle + hop; shuffle for a random new vibe
- Cards bottom sheet (Action / Scene / Companion) with owned, locked, and trophy cards + purchase dialog
- Reactions popover; Settings with Sound & Music, Horizontal Mirror, and Keep Screen On toggles

## Deep links
- `?view=cards` or `?view=settings`
- `?card=<id>` (e.g. `?card=hatching`)

Built as a static artifact and deployed via GitHub Pages.
