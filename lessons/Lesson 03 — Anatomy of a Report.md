# Lesson 3 — Anatomy of a Report

## Why this lesson matters

Once you know _what_ a report is (Lesson 1) and _which type_ to write (Lesson 2), the next problem is a blank page. Experienced analysts don't stare at a blank page — they fill in a skeleton they've used a hundred times. This lesson is that skeleton.

## The skeleton — six parts, in order

### 1. Title / Context line

One line. States what this report is about and the time period or scope.

> _"Q3 Regional Sales Performance Review — July to September"_

### 2. Executive Summary (2–4 sentences, always at the top)

This is the part busy people actually read. If they read nothing else, this has to carry the whole message: what happened, why, and what to do.

> _"West region exceeded target by 8%; East and Central both missed target by over 10%. The shortfall is concentrated in the furniture category, driven by shipping delays. Recommend renegotiating the East/Central logistics contract before Q4."_

Notice: that's a Descriptive + Diagnostic + Recommendation report, all types from Lesson 2, compressed into 3 sentences. This is the hardest part to write and the most important — write it _last_, after you've written everything else, so you're summarizing real work, not guessing.

### 3. Key Findings

The 2–4 specific, evidence-backed points that support the summary. Each finding should have a number attached to it, not just a claim.

> - Furniture category revenue down 18% YoY in East region
> - Average delivery time increased from 4.2 to 7.6 days in the same period
> - Customer complaint tickets tagged "late delivery" up 340%

Weak version (avoid): _"Furniture sales are down and customers are unhappy."_ — no numbers, no proof.

### 4. Insight / So-What

This is where you explain _why_ the findings matter and what's connecting them. This is the part most beginners skip — they list findings and stop.

> _"The pattern points to a single root cause — the East region's new shipping vendor, onboarded in July — rather than a demand problem. Product-level demand (units browsed, added to cart) is flat; the drop is entirely in completed orders, consistent with a fulfillment issue, not a sales issue."_

This paragraph is what separates a report from a bullet-point list. It's where you show you understood the data, not just described it.

### 5. Recommendation / Next Steps

Specific, actionable, and — where possible — owned by someone.

> - Renegotiate or replace the East region shipping vendor before Q4 peak season
> - Audit Central region's delivery times for the same pattern
> - Re-run this analysis in 30 days to confirm the fix worked

Weak version (avoid): _"We should look into improving shipping."_ — not specific, not actionable, no owner or timeline.

### 6. Limitations / Caveats (short, honest, 1–2 lines)

What the data _can't_ tell you. This isn't hedging — it's what makes a report trustworthy instead of overconfident.

> _"This analysis covers East and Central regions only; West was excluded as it met target. Delivery time data is self-reported by the vendor and not independently verified."_

Skipping this section is one of the fastest ways to lose credibility with an experienced stakeholder — they will ask "did you check X?" and you want to have already answered it.

## Seeing the full skeleton on a famous dataset

**Dataset: Titanic — Recommendation report, full skeleton**

1. **Title:** _Titanic Survival Analysis — Evacuation Policy Implications_
2. **Executive Summary:** _"Survival correlated far more strongly with cabin location and gender than with fare paid. Third-class passengers were nearly 3x more likely to die than first-class, primarily due to distance from lifeboats, not ticket price itself. Recommend any modern evacuation protocol prioritize physical proximity to exits over passenger category."_
3. **Key Findings:** 1st class survival ~63%, 3rd class ~24%; female survival ~74% vs male ~19%; survival rate drops sharply for cabins in lower/rear sections regardless of class.
4. **Insight:** _"Fare price alone doesn't explain the gap — grouping by cabin location shows class is really acting as a proxy for physical distance to lifeboats. This suggests the underlying cause is structural/logistical, not about who was prioritized."_
5. **Recommendation:** Design evacuation protocols around real-time proximity to exits, not passenger category; ensure lower-deck cabins have equal access routes.
6. **Limitations:** _"Cabin data is missing for ~77% of passengers, so the cabin-location finding is based on a partial sample and should be treated as directional, not conclusive."_

That's a complete, real report — six parts, each doing a distinct job.

## Quick check

1. Which section of the skeleton should you write _last_, and why?
2. Take your own capstone project (the Somalia displacement classifier). Write just the Executive Summary (2–4 sentences) for it, using this skeleton's style.
3. What's the difference between the "Key Findings" section and the "Insight / So-What" section? Why can't they be merged into one?

---

**Next: Lesson 4 — Reports Inside Power BI**
