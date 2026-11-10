# Pixel puzzle (colour nonogram) — WORK IN PROGRESS, not used by the app yet

Each category folder: `puzzles.json` (per puzzle: n = grid size, grid = rows of palette index or -1 empty,
pal = RGB palette, role picture/masterpiece/spare, image = the painted reward picture), `1.png`…`7.png`
(painted pictures, transparent background, shown when the puzzle is solved) and `sheet_src.png` (the ChatGPT sheet).
Every puzzle is checked with a colour line solver: solvable by logic alone, single solution.
Optional `givens`: [row, col] cells shown already filled at the start (only where logic alone needs a nudge; ocean-depths masterpiece has 8 of 900). A spare may be unsolvable; it is never shown.
Tiers: easy 15x15 (masterpiece 20), medium 20x20 (masterpiece 25), hard ~25. Colour palette tuning pass still to do.
