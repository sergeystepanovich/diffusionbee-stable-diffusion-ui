---
name: seegy-cover-art
description: Generate Stable Diffusion / DiffusionBee prompt packs for SEEGY cover art and promo visuals. Use for singles, remixes, Flowave art, and social squares.
---

# SEEGY cover-art prompts

## Steps

1. Read visual direction in `seegy/BRAND.md`.
2. Ask only if critical info is missing: track title mood keywords, aspect ratio (1:1 cover vs 16:9 promo), text-on-image yes/no.
3. Output a prompt pack ready for DiffusionBee.

## Prompt rules

- Mood: cinematic night, melodic journey, neon haze, cosmic depth, horizon energy
- Palette: deep navy/black, electric cyan, violet accents, warm amber — avoid pastel SaaS purple-white
- If text on image: **SEEGY** as dominant brand; track title secondary
- Include a negative prompt that kills blurry faces, watermark, cluttered flyer text, lowres
- Offer 3 variants: (A) abstract geometric light, (B) landscape/horizon night, (C) silhouette / human-scale festival energy

## Output format

```
Track: <title>
Aspect: <1:1 | 9:16 | 16:9>
Text on image: <yes/no>

A) Abstract
Positive: ...
Negative: ...

B) Horizon
Positive: ...
Negative: ...

C) Silhouette
Positive: ...
Negative: ...

DiffusionBee tips:
- Steps: 30–50 for finals
- Guidance: 7–9
- Suggested modifiers: SEEGY Night Atmosphere, SEEGY Neon Geometry
```

## Modifier chips

Prefer styles from `electron_app/src/modifiers.json` under SEEGY / cinematic camera terms already present.
