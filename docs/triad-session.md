# Triad Working Session — Streakly Comeback Screen

*Attendees: PM (you), Raj (eng lead), Lena (designer). 30 minutes.*

## Agenda

**0–5 min: Recap**
- Day-7 retention dropped from 48% to 39% since the streak redesign shipped.
- Quick recap of the research synthesis (interviews, NPS, competitive research) and the hypothesis: "We believe that the Comeback screen — acknowledging a broken streak, preserving the user's best-streak stat, and offering a lesson-gated streak freeze — will deliver improved Day-7 retention for Streakly users in their first 7 days, as measured by Day-7 retention rate." (see [hypothesis.md](hypothesis.md))

**5–15 min: Live walkthrough**
- Click through both prototype paths: accept freeze → lesson → success, and decline → skip straight to success.
- Highlight what changed across two rounds of persona-based usability testing: softened freeze-offer tone, removed the artificial lesson-start delay, and the freeze now only activating on lesson completion.

**15–25 min: Discussion**

Questions for Raj:
- Is the lesson-gated freeze activation feasible with existing data/systems, or does it need new logic?
- Any concerns with the "broke a streak in week 1" eligibility logic?
- What instrumentation do we need in place to measure Day-7 retention impact once this ships?

Questions for Lena:
- Does the softened copy/tone on the freeze screen match brand voice?
- Any critique on the visual weight of the streak-number stat (flagged as scoreboard-like by usability testing)?

Questions for both:
- Does skipping the lesson entirely when a user declines the freeze feel right, or should the lesson always show regardless of freeze choice?
- What's missing before this is ready for a real (non-persona) usability round?

**25–30 min: Decisions & next steps**
- Lock decisions below, assign owners, agree on next step.

## Decisions to Walk Out With

1. Eligibility rule — who exactly sees the Comeback screen.
2. Freeze rules — duration, one-time vs. renewable.
3. Confirm or revise the decline → skip-lesson flow.
4. Design sign-off on tone/copy.
5. Next step — real-user testing date and/or A/B test scoping owner.

---

# Post-Session Alignment Doc Template

*Copy this section into a new doc after the session.*

**Date:**
**Attendees:**

## Decisions Made

| Decision | Owner | Rationale |
|----------|-------|-----------|
| | | |

## Open Items

| Item | Owner | Due Date |
|------|-------|----------|
| | | |

## Next Steps

-
