# Learning Synthesis & Hypothesis — Streakly Comeback Experience

*Source: [change_log.md](../01-orient/change_log.md), [decision-brief.md](../02-research/decision-brief.md)*

## What We Know

- Day-7 retention dropped 9 points (48% → 39%) since the streak redesign shipped.
- 6 of 10 NPS responses cite the all-or-nothing reset and lack of a recovery path as the reason they disengaged or deleted the app.
- The same streak mechanic drives loyalty in power users and anxiety/churn in others, per the interview synthesis (Priya vs. Tom and Amara).
- Persona-based usability testing on the prototype found the original freeze-offer screen read as a sales pitch to a skeptical churned-user persona (Tom) and re-triggered anxiety in an anxious new-user persona (Amara) — the opposite of its intended effect.
- A forced ~4-second delay on the lesson-start button was flagged twice as pure friction with no functional benefit.

## What We Assume

- That synthetic persona testing predicts how real users will react — no real usability sessions have run yet.
- That fixing the tone and friction issues found in persona testing will actually move real Day-7 retention, not just make the mockup feel better.
- That users who break a streak in week 1 are the highest-leverage segment to target — based on Raj's observation, not a full segment-by-segment retention breakdown.
- That the newest flow change — the freeze only activating on lesson completion — won't feel like a bait-and-switch to real users. This change was made after the last testing round and hasn't been tested with any persona.
- That existing systems and data are sufficient to build the eligibility and freeze-rule logic without new integrations — Raj's claim, not yet engineering-validated in detail.

## What We Still Do Not Know

- Whether real users react the way the Priya, Tom, and Amara personas did.
- Whether the Comeback screen actually recovers any of the 9-point Day-7 retention drop — no A/B test has been run.
- The specific eligibility rules for who sees the Comeback screen, and the exact streak-freeze rules — still open in the PRD.
- Non-goals, and a specific retention target or timeframe for recovery — still open in the PRD.
- The competitive landscape beyond Duolingo — Babbel and Elevate were named but never researched.
- Whether the separate notification tone/frequency issue (flagged in NPS analysis) needs to be fixed concurrently, or would confound results if left unaddressed.

## Hypothesis

We believe that the Comeback screen — acknowledging a broken streak, preserving the user's best-streak stat, and offering a lesson-gated streak freeze — will deliver improved Day-7 retention for Streakly users in their first 7 days, as measured by Day-7 retention rate.
