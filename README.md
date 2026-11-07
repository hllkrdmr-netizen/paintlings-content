# Paintlings content

Public game images for the Paintlings app (VDOX Lab). The app downloads them on demand.
No code here. © 2026 VDOX Lab.

- `spot/` — Spot the pixel mode: `manifest.json` + per category `<id>.png` (A), `<id>_b.png` (B), `<id>.json` (diffs).
- `dots/` — Dot to dot mode: `manifest.json` + per category `bg.jpg` and per picture `<id>.png` (finished colour picture, transparent) + `<id>.json` (dots, 0..1 of the PNG).
- The app downloads from a fixed commit hash (never from `main`), so published files never change under it. Spot v1 images: commit 24823a6.
