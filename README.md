# NxtWave Growth Challenge — Submission

Growth plan + working registration asset for NxtWave's free workshop, **"Build Your First AI Project in 60 Minutes."**

## Links
- **Growth Plan (5 slides):** https://claude.ai/artifact/K647iXMzyAGYwCbAC6MTgZ
- **Working asset — live registration + referral tracker:** https://claude.ai/artifact/XKZiyRvNoV247DEqSPmcrP
- **This repo's copy of the page:** [`index.html`](index.html)

## What's in this repo
- `index.html` — the registration landing page: scroll-scrubbed background video, referral-code system, live seat counter and leaderboard (backed by a real database on the hosted version above — this static copy needs that runtime to drive the live data).
- `scroll-bg.mp4` — the all-intra-encoded background video, scrubbed by scroll position via canvas.
- `nxtwave-logo-white.png` — cropped logo asset used in the nav and closing moment.
- `fonts/` — the Crovas display typeface used for headings (demo license, personal use).
- `submission-notes.md` — AI + Learning notes, reflection answers, and the video script outline.

## Stack
Single-file HTML/CSS/JS, no build step, no framework — vanilla canvas for the scroll-video effect, `IntersectionObserver` for scroll-triggered sequencing, and a small backend-as-a-service database for the registration/referral data on the hosted version.
