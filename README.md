<p align="center">
  <img src="./brand/cicd-for-life-sticker-dark.png" alt="CI/CD for Life" width="420">
</p>

<h3 align="center">Strength training for people who ship.</h3>

<p align="center"><em>Continuous Improvement / Continuous Deployment — applied to the one system you can never re-provision: your body.</em></p>

<p align="center">
  <code>status: early preview · v0.1</code>
</p>

---

## What is this?

**CI/CD for Life** is an outreach project that pitches strength training to tech people in a language they already trust — the CI/CD pipeline. The core idea: you've built elaborate pipelines so a thousand small, tested changes reach production safely. Then you go home and run your own body on no pipeline at all — no commits, no tests, no observability, no rollback. This project maps the discipline you already practice in software onto training and competition.

It's currently a small set of artifacts I'm sharing with friends to get feedback before taking it wider.

## The concept

| CI/CD | Training |
|---|---|
| Small, frequent commits | Consistent sessions over hero workouts |
| Continuous integration | Accumulation phase |
| Build | Hypertrophy / volume block |
| Test | Top sets, AMRAPs, heavy singles |
| Staging | Taper / mock meet |
| Deploy | Meet day (the nine attempts) |
| Observability | Recovery telemetry (sleep, bar speed, RPE) |
| Rollback | Deload / autoregulation |

## What's in here

```
.
├── index.html              # Landing page (ties everything together)
├── manifesto/
│   ├── index.html          # The manifesto — the full argument, fully cited
│   └── cicd-for-life-manifesto.pdf
├── diagram/
│   └── index.html          # The pipeline-as-barbell diagram
└── brand/
    ├── wordmark.svg         # Logo — outlined, font-free, scalable
    ├── wordmark.html        # Reusable HTML/CSS wordmark partial
    ├── cicd-for-life-sticker-dark.png   # Primary die-cut sticker
    ├── cicd-for-life-light.png          # For light/white surfaces
    ├── favicon-32 / 180 / 512.png
    └── README.md            # Brand usage notes
```

## View it live

This repo is a static site — no build step. Enable **GitHub Pages** to share a link with friends:

1. Push this repo (see commands below).
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`, **Save**.
3. Wait ~1 minute. Your site appears at:
   - `https://cicdforlife.github.io/<repo-name>/` for a normal repo, **or**
   - `https://cicdforlife.github.io/` if you name the repo exactly **`cicdforlife.github.io`** (cleanest URL).

All links in the site are relative, so it works either way.

## View it locally

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just double-click `index.html`.

## Feedback wanted 🙏

This is a draft and the whole point right now is to find what's weak. Two ways to weigh in:

- **Open an issue** on this repo with whatever — a typo, a "this claim is a stretch," a "the metaphor breaks here."
- **Email** [cicdforlife@gmail.com](mailto:cicdforlife@gmail.com).

Questions I'm chewing on: Does the CI/CD metaphor land or feel forced? Is the manifesto persuasive or preachy? Would any of this actually get you (or a teammate) under a barbell?

## License

This repo deliberately splits into three, so the community gets generosity where it helps and the brand stays protected where it matters:

| Material | Terms | File |
|---|---|---|
| **Site code** (HTML/CSS/templates) | MIT — reuse freely | [`LICENSE`](./LICENSE) |
| **Written content** (the Manifesto, prose) | CC BY-NC 4.0 — share with credit, non-commercial | [`CONTENT-LICENSE.md`](./CONTENT-LICENSE.md) |
| **Brand** (name + wordmark/logo) | © 2026, all rights reserved — not for reuse | [`NOTICE`](./NOTICE) |

In short: borrow the code, share the writing (with credit, non-commercially), leave the brand alone. For commercial use of any content, email [cicdforlife@gmail.com](mailto:cicdforlife@gmail.com).

The manifesto cites public health sources (WHO, Harvard Health, Mayo Clinic, AHA, and peer-reviewed trials); it's an evidence-informed argument, **not medical advice**.

---

<p align="center"><code>$ cicd --deploy self --strength --twice-weekly</code></p>
