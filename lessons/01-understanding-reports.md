# Lesson 1: Understanding Reports

## The core distinction

A dashboard and a report are often treated as the same thing. They are not.

A dashboard presents data. It shows figures, trends, and comparisons, and it lets the viewer explore them. A report interprets data. It explains what the figures mean, why they occurred, and what should happen as a result.

> A dashboard shows what happened. A report explains what it means and what should be done next.

This distinction is the foundation of this entire course. Every lesson that follows builds on it.

## Why the distinction matters

A data analyst's value is rarely in producing numbers. Numbers are usually easy to produce once the data is clean and the tool is set up correctly. The harder and more valuable skill is turning those numbers into something a decision maker can act on. Two analysts can build the same dashboard from the same dataset and still be worth very different amounts to an organization, depending on whether either of them can also explain what the dashboard means.

This is also, in practice, one of the most common gaps between analysts who are technically capable and analysts who get hired. Interview questions such as "how would you present this to a stakeholder" or "what would you do after building this dashboard" are testing exactly this distinction.

## What a report actually requires

A report, regardless of length or format, needs three things to function.

| Requirement | Question it answers                                              |
| ----------- | ---------------------------------------------------------------- |
| Audience    | Who is reading this, and what do they need from it               |
| Insight     | What does the data reveal, beyond what is visible on the surface |
| Action      | What should the reader do as a result                            |

If any one of these is missing, the result is not a report. It is a description of data with sentences attached to it.

## A working example

Consider a well known public dataset, passenger records from the Titanic. A dashboard built from this data might show that passengers in first class survived at a considerably higher rate than passengers in third class, roughly 63 percent compared to 24 percent. This is accurate, and it is also incomplete on its own.

A report built from the same data adds interpretation:

> Survival was more strongly associated with a passenger's physical distance from the lifeboats than with the class of ticket they held. Because first class cabins were generally located closer to the boat deck, class appears to be correlated with survival largely as a byproduct of cabin location. An evacuation policy modeled on this data should prioritize physical proximity to exits rather than passenger category.

The underlying data has not changed. What changed is that the reader now understands why the pattern exists and what to do with that understanding.

## Reports exist to support decisions

A useful way to test whether something qualifies as a report is to ask a simple question after reading it: does this change what I would do next? If the answer is no, the document has described data but has not reported on it.

This is the standard the rest of this course is built around.
