# Technology Authority Spec

**Status:** draft v0.1 - *your team's commitment, not your org chart.*

## 1. The Responsibility

A team adopting this spec holds **technology authority** over the solutions it
owns. That means the team commits to visiting each of the following four
aspects of every solution under its control **at least once every 3 months**:

| # | Aspect | Visit means... |
| --- | --- | --- |
| 1 | Design | Reviewing the High-Level Design (HLD); is it still true? |
| 2 | Vendor | Connecting with the technology vendor(s): roadmap, EOL, support |
| 3 | Audit | Checking the implemented reality against the intended design |
| 4 | Customer | Hearing from the customer: satisfaction, retrospective, feedback |

A visit may be as brief as *"no change, check-in complete"*, or as significant
as a major re-architecture if the technology demands it (e.g. an impending
end-of-support date).

## 2. The Control

The authority is exercised through **one dashboard**, a single file, visible
to all stakeholders, listing every solution under control with the date of
its last visit for each of the four aspects.

Age of a visit date:

- **Green**: within 1 month
- **Yellow**: 1 to 3 months old
- **Red**: older than 3 months

The team commits to returning every red item to green within its next cycle.

## 3. The Signals

The dashboard is a sensor, not a report:

- **Red items without action**: the authority is not being exercised. Either
  act, or stop practicing this spec (see `5. The Kill Condition`).
- **The full list cannot be cycled in 3 months**: the team either has a
  capacity shortage, or its stack has become a monolith and should be broken
  into more manageable teams.
- **Every visit must leave one line of record** ("no change" / "change
  scheduled <date>" / ...) so the dashboard is self-documenting in audits and
  handovers.

## 4. Format & Tooling

The spec is **format-agnostic**. A hand-edited markdown file is a fully
compliant implementation. Automation may support a manual implementation but
can never replace the team's ownership of its dashboard.

## 5. The Kill Condition

**This dashboard either drives action, or you should delete it.**
If the team stops acting on its red items, continuing to maintain the
dashboard produces fiction, not governance. In that case, honestly retire
the spec rather than keep a zombie practice alive.
