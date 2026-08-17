# Example Report: Titanic Survival Analysis — Evacuation Policy Implications

_A full Recommendation-type report, following the six-part skeleton from [Lesson 3](../lessons/03-anatomy-of-a-report.md)._

## Executive Summary

Survival correlated far more strongly with cabin location and gender than with fare paid. Third-class passengers were nearly 3x more likely to die than first-class, primarily due to distance from lifeboats, not ticket price itself. Recommend any modern evacuation protocol prioritize physical proximity to exits over passenger category.

## Key Findings

- 1st class survival rate: ~63%
- 3rd class survival rate: ~24%
- Female survival rate: ~74% vs male: ~19%
- Survival rate drops sharply for cabins in lower/rear sections, regardless of class

## Insight / So-What

Fare price alone doesn't explain the gap — grouping by cabin location shows class is really acting as a proxy for physical distance to lifeboats. This suggests the underlying cause is structural/logistical, not about who was prioritized.

## Recommendation

- Design evacuation protocols around real-time proximity to exits, not passenger category
- Ensure lower-deck cabins have equal access routes to the extent structurally possible

## Limitations

Cabin data is missing for ~77% of passengers, so the cabin-location finding is based on a partial sample and should be treated as directional, not conclusive.
