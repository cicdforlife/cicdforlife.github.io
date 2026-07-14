# CI/CD for Life — brand kit

The wordmark and sticker kit. **Two palettes, on purpose:**

- **Brand identity (digital):** phosphor green `#00FF41` on a near-black "screen," with a CRT bloom. Old-school terminal.
- **Print stickers:** CRT green `#0B6E3F` badge with white `CI/CD`, flat and dithered. The bloom is a *gradient*, and gradients over dark fields band badly on home laser printers — so print gets its own treatment.

## Brand identity (phosphor)

| File | Use |
|---|---|
| `wordmark.svg` | **Source of truth.** Outlined paths — no fonts required. Includes an SVG `feGaussianBlur` bloom. |
| `wordmark-stacked.svg` | Same, two-row lockup — for square/round spaces, pins, avatars. |
| `wordmark.html` | Drop-in HTML/CSS partial. CSS `text-shadow` bloom + optional "pipeline: passing" badge. `data-theme="light"` for light backgrounds. |
| `cicd-for-life-sticker-dark.png` | Horizontal display lockup on a dark card. 1714×487. |
| `cicd-for-life-stacked-dark.png` | Stacked display lockup on a dark card. 852×575. |
| `cicd-for-life-light.png` | Horizontal, transparent bg, dark "for Life" — for light surfaces. 1530×303. |
| `cicd-for-life-stacked-light.png` | Stacked, transparent bg, dark "for Life". 732×455. |
| `favicon-32/180/512.png` | Tab (32), Apple touch (180), general (512). Phosphor CI/CD on a black screen tile. |

## Print-only stickers (CRT green)

**Physical stickers only — not the digital brand.** Three deliberate differences:

- Badge is `#0B6E3F` **CRT green**, not the phosphor screen.
- `CI/CD` is **white** — on a color laser this is a knockout (bare paper, no toner), so lettering prints crisper than black-over-green.
- Background is **flat neutral near-black with fine dither, no gradient and no bloom** — gradients over a narrow dark range are the main cause of whitish banding on laser prints.

White on `#0B6E3F` measures **6.33:1** contrast — essentially the same legibility the original black-on-green had.

| File | Size |
|---|---|
| `sticker-print-horizontal.png` | 1714×487 — 5.71" × 1.62" @ 300 dpi |
| `sticker-print-stacked.png` | 852×575 — 2.84" × 1.92" @ 300 dpi |

Both are 300 DPI, flattened to opaque RGB (no alpha), so they lose the die-cut transparency. For a true die-cut, give a print shop `wordmark.svg` / `wordmark-stacked.svg` instead.

**Printer settings matter as much as the file:** turn **off** Toner Save / Economy Mode, set Media Type to a **heavier stock** (Thick / Label / Cardstock), print at highest quality.

## Colors

| Token | Hex | Use |
|---|---|---|
| Phosphor | `#00FF41` | Brand `CI/CD` glyphs, bloom |
| Screen | `#080A08` | Badge field (the "CRT") |
| Phosphor rim | `#00731E` | Badge border |
| CRT green | `#0B6E3F` | **Print stickers only** — badge fill |
| Pipeline green | `#23A865` | Functional UI accent (links, labels, status). Tuned for small-text legibility; deliberately *not* replaced by phosphor. |
| Iron | `#14161B` | Background / dark surface |

## Type

- **CI/CD** — IBM Plex Mono, SemiBold (the engineering/terminal voice)
- **for Life** — Archivo Black (the athletic display voice)
