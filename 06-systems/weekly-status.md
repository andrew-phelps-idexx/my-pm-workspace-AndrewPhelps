# Skill: Weekly Status Update

*Project-local skill. Applies only when this workspace is open — not a globally installed Claude skill.*

## When to Use

When asked to turn raw notes into a leadership-ready weekly status update.

## Input

Raw bullet-point notes, unformatted, in any order.

## Output

A formatted update with exactly these four sections, in this order:

- **Shipped**
- **In Progress**
- **Blockers**
- **Next Week**

Rules:

- Maximum 3 bullets per section. If there are more than 3 relevant items, keep the 3 most important and drop the rest.
- Plain declarative language. No jargon, no buzzwords, no filler phrases like "leveraging" or "synergy."
- Each bullet is one short sentence stating what happened or will happen — not a description of the process.
- If a section has nothing to report, write "None" under that heading rather than omitting the section.

## Example

**Input notes:**
- shipped the comeback screen backend logic, still need eligibility rules
- freeze feature blocked on data team giving us streak history API
- fixed the notification tone copy, in review
- next week: get eligibility rules signed off, start A/B test setup
- also fixed a minor bug in streak counter

**Output:**

**Shipped**
- Comeback screen backend logic.
- Fixed a bug in the streak counter.

**In Progress**
- Notification tone copy, currently in review.

**Blockers**
- Streak-freeze feature is blocked on the data team providing the streak history API.

**Next Week**
- Get streak eligibility rules signed off.
- Start A/B test setup.
