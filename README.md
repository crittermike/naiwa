# Naiwa

A faithful web recreation of the **Naiwa** virtual-companion app, featuring the character **Reverie**.

Single self-contained `index.html` — no build step, no dependencies.

**Live:** https://crittermike.github.io/naiwa/

## Features
- Character home screen with recycle / Cards / Settings toolbar
- Cards bottom sheet (Action / Scene / Companion) with owned, locked, and trophy cards
- Tap a card to change the scene; purchase dialog for locked cards
- Reactions popover, settings screen with Horizontal Mirror and Keep Screen On toggles
- iOS status bar + Dynamic Island chrome

## Deep links
- `?view=cards` or `?view=settings`
- `?card=<id>` (e.g. `?card=hatching`)

Built as a static artifact and deployed via GitHub Pages.
