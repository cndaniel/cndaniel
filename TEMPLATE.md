# Use this profile as a template

This repo is a **GitHub template** — you can generate your own copy without forking:

**[→ Use this template](https://github.com/cndaniel/cndaniel/generate)** (or fork it, both work)

## Setup — 3 steps

1. **Name the repo after your username.** GitHub only renders a profile README when the
   repo is named exactly `<your-username>/<your-username>` and is public.

2. **Edit `assets/header.svg`** — everything is plain hand-written SVG, no build step:
   - `DANIEL` → your name (2 places: the `.mega` text and the `.ghost` echo behind it)
   - `SYSTEMS · SIGNALS · AGENTS` → your slogan
   - The four direction words at the bottom (`network infra`, …) → your own tracks
   - The corner annotations (`SHT 01 / 01 /// DO NOT SCALE`, `EST. MMXVI`, …) → your own
     metadata, or delete them entirely. Avoid coordinates/timezone — they leak location.
   - Colors auto-adapt to dark/light mode via `prefers-color-scheme` — edit the two
     palettes in the `<style>` block if you want different tones

3. **Edit `README.md`**:
   - The `index/` code block → your own direction lines (dot-leader style: name, dots, keywords)
   - The badge wall → your stack. Badges follow one pattern, copy-paste and swap:
     `https://img.shields.io/badge/<label>-0d1117?style=for-the-badge&logo=<slug>&logoColor=<hex>`
     — logo slugs are at [simpleicons.org](https://simpleicons.org). Keep the `0d1117`
     background: it melts into GitHub's dark mode so only the logos float.

## Design notes

- The scanline, blinking cursor, and staggered fade-ins are pure SMIL/CSS animation
  inside the SVG — GitHub renders them as-is, no JavaScript, no third-party services.
- No stats cards on purpose: they leak your timezone/activity pattern and look empty
  if your work is mostly private. This layout is **private-by-default**.
- Everything renders in both dark and light mode — check both before publishing.
