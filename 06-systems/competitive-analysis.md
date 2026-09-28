# Skill: Competitive Analysis

*Project-local skill. Applies only when this workspace is open — not a globally installed Claude skill.*

## When to Use

When asked to research competitors in a given product space and produce a comparison matrix with identified white-space gaps.

## Input

- A short description of the product and the problem it's trying to solve (for framing relevance).
- A candidate list of 3-5 competitors to start from, or a description of the space to identify them in (e.g., "apps built around streaks, daily habits, and micro-learning").
- Any exclusions (e.g., "do not include social media or long-form course platforms").

## Process

1. **Identify 3-5 relevant competitors** matching the space and exclusions given.
2. **Research each one via live web search** — do not rely on unverified general knowledge for pricing, features, or recent changes without flagging it. If a search is not run or is rejected, that competitor must be marked as "not researched" and excluded from any comparison matrix or gap analysis — never presented as analyzed.
3. For each researched competitor, capture:
   - Core features
   - Pricing model
   - Target customer
   - How they keep users engaged after the first week (streaks, freezes, reminders, comeback flows, etc. — tailor to the specific engagement mechanic relevant to the product)
   - Notable recent changes
4. **Build a comparison matrix** only from competitors that were actually researched.
5. **Identify white-space gaps** — problems none of the researched competitors own well. Scale the number of gaps claimed to the number of competitors actually researched (e.g., don't claim 2 confirmed gaps from a single data point — frame single-competitor findings as "observations," not confirmed gaps).
6. Always include a **Scope Note** at the top of the output stating exactly which competitors were researched vs. only named as candidates, and cite sources for every researched competitor.

## Output Format

```
# Competitive Matrix — [Product]

## Scope Note
[What was researched vs. only named as a candidate]

## [Competitor Name]
- Core features:
- Pricing model:
- Target customer:
- How they keep users engaged after week 1:
- Notable recent changes:

Sources:
- [links]

(repeat per researched competitor)

## Comparison Matrix
[table, only if 2+ competitors researched]

## White-Space Gaps / Observations
[scaled to evidence — "observation" if only 1 competitor, "gap" if pattern confirmed across 2+]

## Next Steps
[remaining competitors to research, if any were named but not covered]
```

## Rules

- Never present an un-researched competitor as analyzed.
- Never claim more gaps than the evidence supports.
- Always cite sources for factual claims (pricing, features, recent changes).
