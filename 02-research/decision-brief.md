# Decision Brief — Streakly Comeback Experience

*For: Marcus, Head of Product*

## Situation

Streakly's Day-7 retention has dropped 9 points (48% → 39%) since the streak redesign shipped, concentrated in users who break a streak in week 1 and rarely return. Three independent research streams — user interviews, NPS feedback, and competitive research — now converge on the same root cause.

## Key Findings

- The streak mechanic that drives loyalty in power users (Priya's 30-day celebration moment) is the same mechanic causing anticipatory anxiety in new users (Amara, day 4) and driving churn after a break (Tom, lost a 12-day streak).
- 6 of 10 NPS responses cite the all-or-nothing reset and lack of a recovery path as the reason they disengaged or deleted the app — the single most frequent complaint.
- Notification tone/frequency is a separate, distinct problem in NPS feedback: users are disabling notifications entirely, cutting off any future re-engagement channel.
- Duolingo's only comeback mechanism found (a June 2026 one-time streak-restoration event) was temporary, not a standing feature — no competitor researched so far owns a permanent, personalized comeback experience.
- Both interviews and NPS feedback independently flag the same gap: nothing acknowledges a user's actual state on return (a 2-day streak and a return after 2 weeks look identical).

## Options Considered

1. **Ship the proposed Comeback screen** (best-streak stat, 60-second comeback lesson, one-tap streak-freeze) — directly addresses the reset/recovery gap, feasible with existing systems, though eligibility and freeze rules are still open.
2. **Fix notification tone/frequency only** — lower effort, addresses a real but narrower complaint, doesn't touch the larger reset/recovery theme behind the explicit churn evidence.
3. **Do nothing / keep monitoring** — lowest cost, but retention is already declining with active evidence of user loss across two independent sources.

## Recommended Action

Ship the Comeback screen for users who break a streak in week 1.

## Why Now

Three independent sources now agree on the diagnosis, lowering the risk of acting on a hunch; the fix is cheap to build (no new data sources needed), and no competitor has claimed this space with more than a one-time event.
