# NPS Feedback Findings — Streakly

*For: Marcus. Source: 10 raw NPS free-text responses.*

## Method

10 raw feedback comments were bucketed by theme, then split into praise vs. complaints. Themes mentioned in more than one response are ranked by frequency below; themes mentioned only once are noted separately since they don't clear the "more than once" bar but are still relevant.

## Themes Mentioned More Than Once (Ranked by Frequency)

| Rank | Theme | Mentions | Example quotes |
|------|-------|----------|-----------------|
| 1 | Streak break leads to a total reset, causing disengagement or deletion | 3 | "I hit a 20-day streak, missed one day, and it reset to zero. I haven't opened the app since." / "The moment I lost my streak the whole thing lost its meaning." / "The second I lost it, I was done." |
| 1 (tied) | No recovery mechanism after breaking a streak; users want a forgiving comeback | 3 | "I broke my streak once and there was no way to recover it. Other apps let you freeze a streak." / "I want Streakly to feel like a coach that helps me get back on track, not a scorekeeper." / "I wish it would make coming back easier instead of making me feel like I failed." |
| 3 | Notifications feel excessive, random, or nagging | 2 | "The daily reminder just started to feel like nagging." / "I got three in one afternoon and just turned them all off." |

## Single-Mention Themes Worth Flagging

- **No acknowledgment of user state on the home screen:** "The home screen looks the same whether I'm on a 2-day streak or coming back after two weeks away. Nothing acknowledges where I am."
- **App is forgettable between sessions, no useful re-engagement pull:** "I just forget it exists after a couple of days. If it pulled me back with something useful I'd come back."

## Praise vs. Complaints

**Praise (2 of 10 responses):**
- "The first week was genuinely fun."
- "Love the lessons."

**Complaints (8 of 10 responses):** everything else — dominated by the streak-reset/no-recovery theme and notification frustration above.

## Top 3 Actionable Issues

1. **All-or-nothing streak reset with no recovery path.** Highest combined frequency (6 of 10 responses touch this directly), and the only issue with explicit churn evidence — users describe stopping app use or deleting it outright after a break. This directly reinforces the Comeback screen concept already proposed in the retention PRD.
2. **Notification tone and frequency.** Distinct from the "you lost your streak" tone already flagged in the PRD — this feedback shows a broader problem with notification frequency and randomness, to the point users are disabling notifications entirely, which removes any future channel for re-engagement.
3. **No acknowledgment of user state on the home screen.** Only one direct mention, but it's structurally the same gap the Comeback screen is meant to close (treating a 2-day streak the same as a return after two weeks away). Worth explicitly scoping into the Comeback screen work rather than treating as a separate fix.

## Bottom Line

Issues #1 and #3 reinforce the case for the Comeback screen already in the retention PRD — this feedback is independent evidence for the same underlying problem. Issue #2 (notification tone/frequency) is a new, distinct problem not yet in scope and should be raised as a separate discussion item.
