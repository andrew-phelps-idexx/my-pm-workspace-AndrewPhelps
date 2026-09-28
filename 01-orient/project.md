# Streakly Comeback Experience — Project Brief

*Status: Problem alignment draft, ahead of Thursday planning meeting.*

## What Streakly Is

Streakly is a consumer habit + micro-learning app. Users pick a track and do a short daily lesson to learn a skill in five minutes a day, building a streak. The streak is the core habit loop. Launched 4 years ago, Series B funded ($42M), 2.1M registered users, 340K MAU, growing 28% YoY on MAU.

## Squad

Retention

## Current Phase

Discovery

## Key Stakeholders

- **Marcus** — leading the retention discussion / planning the Thursday meeting.
- **Raj** — data/analytics.
- **Lena** — user research/design.

*(Roles inferred from meeting notes, not formally confirmed job titles.)*

## Problem Statement

Day-7 retention has dropped from 48% to 39% since the streak redesign shipped.

The drop is sharpest among users who break their streak in week 1 — once someone misses two days in a row, churn is almost double.

User research (Lena) points to why: people build a good streak, miss a day because life happens, and return to find their counter reset to zero. It feels like a punishment, with no way back in. Today, the app doesn't acknowledge the break at all — same home screen, streak back at 0, nothing said. The "you lost your streak" push notification has a brutal tone, and tapping through it just drops the user back at day zero with nothing offered.

Working hypothesis: users go passive after a streak break because it feels like failure, and there's no graceful way back in. What's needed is something that pulls them back with a reason specific to them and their progress — not a generic "keep going!"

Open question raised by Marcus: is the core problem the streak reset mechanic itself, or the notifications that reach people right when they're most likely to quit? (Raj's take: probably both, but the bigger issue is that nothing happens after the break — no acknowledgment, no path forward.)

## Goals

- Understand and align, as a team, on why Day-7 retention dropped after the streak redesign — specifically why streak-breakers go passive — before designing solutions.
- Explore a graceful "comeback" experience for users who break a streak, rather than a cold reset to zero. Lena's early sketch: a Comeback screen shown when a streak breaks, surfacing the user's best-streak stat, a 60-second comeback lesson to rebuild momentum, and a one-tap streak-freeze to protect the streak once rebuilt.
- Confirm the idea is technically feasible with existing systems (Raj: doable with what we have; needs logic for who sees it and streak-freeze rules, but no new data sources).

## Non-Goals

Not specified in the notes yet. **Needs decision at Thursday's meeting.**

## Success Metrics

- Day-7 retention (currently 39%, down from a 48% baseline before the streak redesign) is the metric under discussion. No specific target or timeframe for recovery was set in the notes. **Needs decision at Thursday's meeting.**

## Proposed Solution

A Comeback screen, shown when a user breaks a streak, replacing the current cold reset-to-zero experience. Per Lena's sketch, it would surface:

- **Best-streak stat** — the user's personal best, so their history isn't erased by one miss.
- **A 60-second comeback lesson** — a short lesson designed to rebuild momentum quickly rather than dropping the user back at day zero with nothing.
- **One-tap streak-freeze** — lets the user protect a rebuilt streak going forward.

Per Raj, this is technically doable with existing systems and data sources; it requires new logic for (a) who is eligible to see the Comeback screen and (b) the streak-freeze rules. Both are open items below.

## Validation Plan

*Proposed draft — not yet reviewed by the team. Intended as a starting point for Thursday's discussion, not a decided plan.*

- **Hypothesis to test:** users go passive after a streak break because the break feels like failure and there's no graceful way back in (vs. alternative explanations, e.g. notification tone/timing alone).
- **Proposed approach:** an A/B test comparing the current experience (cold reset + existing "you lost your streak" push) against the Comeback screen, targeted at users who break a streak in week 1 — the segment where Raj found the sharpest retention drop.
- **Primary metric:** Day-7 retention for users who break a streak in week 1.
- **Supporting metrics:** rate of second consecutive missed day after a break (the point where Raj found churn nearly doubles), streak-freeze usage rate, comeback-lesson completion rate.
- **Open design questions for Thursday:** whether to isolate the reset mechanic and notification tone as separate variants (per Marcus's question on which is the core problem) or test the combined Comeback screen as one treatment; test duration; minimum sample size.

## Open Questions

- Is the root problem the streak reset itself, the notification tone/timing, or both? (Marcus, Raj)
- Who should see the Comeback screen, and what are the rules for who gets a streak-freeze? (Raj)
- What should the tone and content of the "you lost your streak" notification be, if it changes? (Lena)
- Should the reset mechanic and notification tone be tested as separate variants, or is the Comeback screen tested as one combined treatment?
- What Non-Goals should be defined for this project?
- What is the target Day-7 retention recovery, and by when?
- Full alignment on the problem statement is pending the Thursday meeting (Marcus wants the team aligned on the problem before designing solutions).
