# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

Static HTML slide deck for **Vibe Coding: de la Idea al Producto Digital con IA**, an 8-class course developed in partnership with eCloud Agency and Vercel for Tecnoteca Rosario. No framework, no build step, no package manager — everything is self-contained HTML/CSS/JS. Classes 7 and 8 (both "Demo Day") share a single slide deck, so there are 7 `clases/clase-*.html` files for 8 classes.

## Previewing locally

```bash
# Open the landing page directly
open index.html

# Or serve with Python to avoid font/path issues
python3 -m http.server 8000
# then visit http://localhost:8000
```

## File structure

- `index.html` — Landing page linking to all 7 class slide decks.
- `clases/clase-{N}.html` — One self-contained slide deck per class (clase-1–clase-7; clase-7 covers both class 7 and class 8, "Demo Day").
- `README.md` — Course syllabus (source of truth for class objectives and deliverables).

## Slide deck architecture

Each `clases/clase-*.html` file is fully self-contained (no external dependencies except the Google Fonts import). Slides share a common pattern:

- **CSS variables** defined in `:root` — dark palette (`--bg-dark`, `--bg-panel`), accent colors (`--accent-green`, `--accent-teal`, `--accent-purple`, `--accent-amber`), and typography (`--text-primary`, `--text-secondary`, `--text-muted`).
- **`#stage`** — 1100px wide, 16:9 aspect ratio container. Each `.slide` inside is shown one at a time via JS.
- **`#nav`** — Fixed bottom pill with prev/next buttons and a slide counter. Navigation is driven by a small inline script that toggles `.active` on `.slide` elements and updates a `#progress-bar` at the top.
- **`#progress-bar`** — 3px fixed bar at the top that tracks completion as slides advance.

When adding a new slide to an existing class, copy an existing `.slide` block and it will automatically be picked up by the navigation script (which counts `.slide` elements to determine total).

## Design system

The `index.html` landing and all class files share the same CSS variable names and visual language (Inter font, dark background `#060a12`, green/teal gradient accents). Keep new content consistent with these values rather than introducing new color tokens.
