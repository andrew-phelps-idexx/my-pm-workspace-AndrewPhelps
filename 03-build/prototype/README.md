# Streakly Comeback Screen — Prototype

A static, clickable HTML prototype of the Comeback screen, built for sharing with users today. Open `index.html` in any browser — no build step, no server, no login.

## PM Brief

**User:** 24-year-old who hit a 6-day streak, missed two days, and has not opened the app since.

**Job to be done:** Get back in without feeling they lost everything.

**Flow:**
1. Screen acknowledging the break, showing the best-streak stat (6 days) preserved as an achievement.
2. Streak-freeze offer — accept or skip. Protects the next missed day going forward (not retroactive).
3. 60-second comeback lesson.
4. Success / confirmation screen.

**Success condition:** User completes the 60-second comeback lesson.

**Constraints:** Mobile only. Simple — no login. Uses only data Streakly already has; no new integrations.

## Key Decisions Made During the Interview

- **The streak was already reset by the time this screen loads.** Under the current mechanic, missing two days already zeroed out the live counter before the user reopened the app — this matches what Tom described in the interview synthesis and what 6 of 10 NPS responses complained about. The best-streak stat shown on screen 1 is preserved history, not a live counter.
- **The freeze offer is forward-looking, not retroactive.** It can't undo the reset that already happened, but it protects the user from hitting zero again the next time they miss a day — chosen because it's a standing, repeatable feature (unlike a one-time retroactive restore), and because the core complaint in the research was "there was no way to recover" and "no way to avoid this happening again," not "give me my exact days back."
- **The freeze offer is step 2, ahead of the lesson** — moved up from an initially proposed step 3, so the user is reassured about the future before being asked to re-engage.
- **Success is completing the lesson, not accepting the freeze.** Accepting the freeze is optional; the flow allows skipping it and still reaching the success screen.
- **Streak length was corrected mid-build from 12 days to 6 days** across the brief and prototype.
