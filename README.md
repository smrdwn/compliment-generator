# Compliment Generator — Midnight Minimal (Vanilla)

A portfolio-grade **Compliment Generator** built with **static HTML/CSS/JavaScript**. It generates tasteful compliments with personalization controls, a deterministic “Quality Meter,” plus **persistent History + Favorites** via `localStorage`.

## Features

- **Personalization**
  - Target: Friend / Coworker / Partner / Customer
  - Tone: Sincere / Funny / Hype / Professional
  - Context: Birthday, Interview, Gym, Teamwork, Promotion, Customer win, Thank you, or none
  - Optional “Extra details” (sanitized to keep things friendly)

- **Quality Meter (Deterministic)**
  - Scores each compliment (0–100) and grades it:
    - Amazing / Very Good / Good / Average / Below Average
  - Based on length, specificity, context usage, tone alignment, and novelty (avoids repeats)

- **History + Favorites**
  - Auto-saves recent compliments to **History** (max **12**)
  - Star/Unstar to save in **Favorites**
  - Clear History / Clear Favorites buttons

- **Copy + Share**
  - Copy compliment to clipboard (with a safe fallback method)
  - Share via Web Share API when available, otherwise copies a share link

- **Safe-by-default UX**
  - Filters out “creepy/offensive” keywords from extra details
  - Keeps compliments focused on character, effort, impact, and professionalism

- **Accessibility & UX polish**
  - Keyboard shortcut: **Ctrl/Cmd + Enter** to generate
  - `aria-live` status updates
  - Reduced motion support (`prefers-reduced-motion`)
  - Clear focus rings and semantic layout

## Project Structure

```txt
/
├─ index.html
└─ favicon.png        (optional — referenced by index.html)
```
