# Korea 2026 — Places Map

**🗺️ Live map: https://dust2dustin.github.io/korea-2026-map/**

Auto-built from ~101 saved Instagram/Facebook links. Tap a pin to open the place in **Naver Map** (directions) or jump to the **source reel**. Use **📍 (top-left)** to find your own location and see what is nearby. Toggle categories (top-right) or filter by name (top-left box).

## Files
- `korea-places.csv` — full data: name, Korean name, Naver match, category, address, confidence, Naver link, source link. (GitHub renders it as a sortable table — click it above.)
- `korea-places-review.md` — review doc grouped by confidence, incl. everything that did **not** resolve.

## Confidence tiers
- **High** — name/area auto-confirmed on Naver.
- **Check** — matched a Naver place but not auto-confirmed (often just English-vs-Korean naming; a few region/landmark rows grabbed an adjacent cafe — verify those).
- **Unresolved** — no clean single pin (regions like "Damyang bamboo forest", unnamed spots, romanized-only names). Listed in the review doc with their source links.

## Did not go through
- 2 Facebook reels (no readable caption via the extractor) and 1 Instagram Stories link (expired) — not processed. See the review doc.
