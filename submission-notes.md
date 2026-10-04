# NxtWave Growth Challenge — Submission Package

## Links
- **Growth Plan (5 slides):** https://claude.ai/artifact/K647iXMzyAGYwCbAC6MTgZ
- **Working Asset — live registration + referral tracker:** https://claude.ai/artifact/XKZiyRvNoV247DEqSPmcrP

> Both are private Claude Artifacts. Before submitting, open each one and use its **Share** button to make it viewable by anyone with the link — otherwise the reviewer can't open them.

---

## AI + Learning Notes

**1. Channel strategy**
- **Asked:** "What's the single best channel to spend ₹2,000 on in 7 days to get 500 students?"
- **AI suggested:** Lead with paid Instagram/Meta ads targeted at engineering students.
- **What I changed:** Rejected ads as the lead channel. ₹2,000 buys roughly 6–8k impressions — thin and untargeted for guaranteeing 500 qualified sign-ups. Led instead with free WhatsApp/Telegram seeding through coding clubs and placement cells, and moved the budget to referral vouchers (which compound) plus a small day-4 ad boost on whatever post was already performing.

**2. What to build**
- **Asked:** "What's the most effective single asset to build for this?"
- **AI suggested:** A standalone landing page, or separately, a WhatsApp automation bot, or an evaluation-automation tool.
- **What I changed:** The brief explicitly warned that most candidates would submit a plain landing page. Instead of picking one option from the list, I merged two: a landing page **with a built-in referral code + live leaderboard**, so the asset doesn't just collect registrations — it actively drives the remaining ones through peer invites.

**3. How referral links actually work**
- **Asked:** "How should I pass a referral code in the registration link?"
- **AI's first instinct:** Use a query parameter, e.g. `?ref=CODE123`.
- **What I changed:** Claude Artifacts only expose a bare `#fragment` to the page — no query string reaches it. Switched the referral link to `#CODE123`, read via `location.hash` client-side, with a regex check before trusting it as a real referral code.

---

## Reflection (also on slide 5 of the Growth Plan)

**What changed between first idea and final solution?**
The first pass was ad-led and spent the full ₹2,000 on paid reach. The funnel math didn't support reaching 500 that way, so the plan shifted to free, targeted seeding (clubs/placement cells) plus a referral loop, with the budget moved to referral incentives.

**If I had another 24 hours?**
I'd build the WhatsApp auto-reply bot for instant registration confirmation and reminders, and I'd A/B test two landing page headlines against real traffic instead of guessing which one converts better.

**What did AI suggest that I rejected, and why?**
AI's default instinct was to lead with paid Instagram ads. I rejected that as the primary channel — ₹2,000 is too thin to reliably reach 500 verified students through paid reach alone, and a referral loop scales for free once it's seeded.

---

## 3-Minute Video Script (outline)

**0:00–0:30 — The problem**
"NxtWave needs 500 final-year engineering students registered for a free AI workshop, in 7 days, on a ₹2,000 budget. Here's how I'd actually do it."

**0:30–1:15 — The plan**
Walk through the growth plan deck: who you're targeting (placement-anxious final-years, any branch), why they care (resume proof for interviews), and the two-channel strategy — club/placement-cell seeding to start, a referral loop to scale it to 500. Show the funnel math slide.

**1:15–2:30 — The build (screen share)**
Open the live landing page. Register as a demo student, show the referral link it generates, open that link in a new tab/incognito to register a "friend," and show the leaderboard and counter updating live. Call out that this is a real database, not a mockup.

**2:30–3:00 — How you thought**
One sentence each on: what changed from your first idea, what you'd improve with 24 more hours, and the one thing AI suggested that you rejected and why (the ads-first instinct).
