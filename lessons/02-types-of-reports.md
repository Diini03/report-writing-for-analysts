# Lesson 2: Types of Analytical Reports

## Why classification matters

Analysts who have not been taught to classify reports tend to write the same document regardless of the situation, typically a broad summary of everything they found. Analysts with more experience choose the type of report before writing a single sentence, because the type determines the structure, the length, and what belongs at the top.

There are five report types that cover the large majority of situations a data analyst will encounter.

| Type           | Central question                                        | Typical use                        |
| -------------- | ------------------------------------------------------- | ---------------------------------- |
| Status         | Where do things currently stand                         | Recurring reviews, progress checks |
| Diagnostic     | Why did this happen                                     | Investigating an unexpected change |
| Predictive     | What is likely to happen next                           | Planning, early warning            |
| Recommendation | What should be done                                     | Supporting a decision              |
| Exploratory    | What is present in this data that was not already known | Early stage analysis of new data   |

## Status reports

A status report presents a snapshot without attempting to explain causes. It is descriptive by design.

> Quarterly revenue reached 412,000, six percent below target. The West region met its target. East and Central both fell short.

Status reports are the most common report type in ongoing business operations, and the least demanding to write, because no causal claim is being made.

## Diagnostic reports

A diagnostic report identifies the likely cause behind a change that has already been observed.

> Customer churn increased by four percent this quarter. The increase is concentrated among customers on the lowest priced plan who had reduced their product usage in the two weeks before cancelling, which suggests disengagement rather than price sensitivity as the primary driver.

The distinction from a status report is direct. A status report states that churn increased. A diagnostic report explains why.

## Predictive reports

A predictive report projects a trend forward and states what is likely to occur if current conditions continue.

> Based on current growth rates, demand is projected to exceed available capacity within twelve days if no adjustment is made.

This is the report type most directly connected to statistical modelling and machine learning work, since a model's forecast frequently becomes the evidence a predictive report is built on.

## Recommendation reports

A recommendation report states what should be done, based on the evidence presented. It is the type most frequently expected in interview settings, because it demonstrates judgment rather than description alone.

> Evacuation outcomes in the Titanic dataset were more strongly associated with cabin proximity to exits than with passenger class. A modern evacuation protocol modeled on this pattern should prioritize physical location over category.

A recommendation report is identifiable by its ending. It closes with a stated action, not an open observation.

## Exploratory reports

An exploratory report is used before a specific question has been formed, typically when an analyst is examining a new dataset for the first time and looking for patterns worth investigating further.

> Port of embarkation shows a stronger association with survival than ticket fare does, which may indicate that embarkation port is acting as a proxy for cabin location rather than for economic status. This warrants further investigation before any conclusion is drawn.

Exploratory reports frequently lead into one of the other four types once a specific pattern has been identified as worth pursuing.

## Reports are usually combined

In practice, most professional reports blend two of these types in a single document, most commonly diagnostic and recommendation together: an explanation of why something occurred, followed by a stated action in response to it. When an analyst is asked how they would report on a dashboard, this combination is generally what is being requested, even when the question itself does not name a specific report type.
