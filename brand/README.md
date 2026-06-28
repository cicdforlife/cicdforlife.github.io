# CI/CD for Life — brand kit

The wordmark, extracted as reusable assets.

## Files

| File | Use |
|---|---|
| `wordmark.svg` | **Source of truth.** Outlined paths — no fonts required. Scales to any size; use for print, design tools, the web. Renders dark "for Life" (for light backgrounds). |
| `wordmark.html` | Drop-in HTML/CSS header partial. Live web fonts + optional "pipeline: passing" build badge. Set `data-theme="light"` for light backgrounds. |
| `cicd-for-life-sticker-dark.png` | **Primary sticker.** Die-cut dark card, green badge, white text. Transparent outside the rounded card. 1714×486. |
| `cicd-for-life-light.png` | Transparent background, dark text — for printing on white/light vinyl or placing on light surfaces. 1546×318. |
| `favicon-32/180/512.png` | Browser tab (32), Apple touch icon (180), general (512). Stacked CI/CD green tile. |

## Colors

- Pipeline green `#23A865` — the brand accent (a passing build)
- Badge text `#0E0F12`
- "for Life" on dark `#EDEFF2` · on light `#14161B`
- Card surface `#222632` → `#1B1E25`, border `#3C4252`

## Type

- **CI/CD** — IBM Plex Mono, SemiBold (the engineering/log voice)
- **for Life** — Archivo Black (the athletic display voice)

## Sticker printing notes

PNGs are high-res (≈300 dpi at ~5–6"). The dark sticker is already die-cut
(transparent around the rounded card), so a print shop can cut to the rounded
outline. For a white-bordered die-cut, ask the printer to add a 2–3 mm keyline.
Use `wordmark.svg` if they prefer vector — it has no font dependencies.
