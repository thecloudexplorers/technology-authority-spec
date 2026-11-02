# Technology Authority Dashboard — <Team Name>

*Pin the spec version you follow: Technology Authority Spec v0.1*
*Last full cycle completed: -*

| Solution                | High level Designs (review) | Vendor connect | Audit Prep   | Customer review | Product EOL | Verdict / next action                                  |
| ----------------------- | --------------------------- | -------------- | ------------ | --------------- | ----------- | ------------------------------------------------------ |
| `platform-landing-zone` | 2026-09-28 🟢                | 2026-08-29 🔴   | 2026-09-01 🟡 | 2026-09-27 🟢    | -           | Vendor call scheduled 2026-10-15 (regular connect)     |
| `payments-service`      | 2026-10-01 🟢                | 2026-08-15 🔴   | 2026-09-20 🟡 | 2026-09-28 🟢    | 2027-09-30  | Vendor call scheduled 2026-10-07 (EOL notice received) |
| `customer-portal`       | 2026-07-10 🔴                | 2026-09-02 🟡   | 2026-07-30 🔴 | 2026-09-10 🟡    | 2029-12-31  | HLD + audit visits this week; no major change expected |
| `identity-platform`     | 2026-09-30 🟢                | 2026-09-30 🟢   | 2026-09-30 🟢 | 2026-09-30 🟢    | 2030-12-31  | Full cycle complete; all "no change"                   |

## About this dashboard

- **Signal:** this dashboard is a sensor. At a glance it tells you whether you
  need to look at something, and whether you have checked that it is still up
  to date.
- **Audience:** the Account Responsible(s). This dashboard is the technologists'
  (architects and tech leads) contribution to the quarterly business review.
- **Audits:** we are never responsible for an audit; we are consulted and
  supply evidence and information. The question here is: do I need to do
  something for an audit in the near future?
- **Solutions:** describe each solution on its own page and link to it from
  the Solution column.
- **Not the backlog:** links to backlog items are fine, but this dashboard is
  not the backlog.

**RAG rule (age of last visit):** 🟢 ≤ 1 month · 🟡 1–3 months ·
🔴 > 3 months · ⚪ not yet assessed
**Obligation:** visit all 4 aspects of each solution at least once per 3 months.

## Red items — actions this cycle

What turned red this cycle.

- [ ] `customer-portal`: HLD review + implementation audit
- [x] `payments-service`: vendor connect scheduled

## Visit log (one line per visit)

One level of detail below the dashboard: an informational action-item list.
Links to backlog items are allowed, but this is not the backlog.

| Date       | Solution            | Aspect | Verdict                                              |
| ---------- | ------------------- | ------ | ---------------------------------------------------- |
| 2026-09-30 | `identity-platform` | all    | No change, check-in complete                         |
| 2026-10-01 | `payments-service`  | Design | No change to HLD; vendor EOL pending separate action |

## Signals

> Cycle time: all 4 aspects × all solutions completed in **~5 weeks** — within
> the 3-month obligation. No monolith signal. Capacity is sufficient.
