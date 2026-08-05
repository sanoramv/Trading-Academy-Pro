# STUDY_PLAN.md — Four Pacing Tracks Through the Academy

This file is the **overview and shared rulebook** for four day-by-day study
schedules. The actual daily calendars live in their own files (see below) —
this file explains the assumptions, the shared day template, and how to pick
between them.

## Assumptions

Every plan is paced against one stated availability profile:

- **Weekdays (Mon-Fri):** 60-90 minutes/day.
- **Weekends (Sat-Sun):** 3-4 hours/day.
- The learner has a full-time job. No plan assumes a weekday study block
  longer than 90 minutes, and no plan ever schedules a new lesson on a
  Sunday — see "Revision days are never skipped" below.

If your actual availability is higher or lower, the day-by-day structure
still applies — just move faster or slower through it; the *order* and the
*revision cadence* are the parts worth keeping fixed.

## The Four Plans

| Plan | Level | Duration | Weekday Load | Saturday Load | Coverage | Detail File |
|---|---|---|---|---|---|---|
| 30-Day | Beginner | 30 days (5 wks) | 1 lesson/day | 2 lessons | `[01.01]`–`[04.01]` (29 of 270 lessons) — Foundation, Market Structure, Indian Market, first step into Global Market | [`STUDY_PLAN_30_DAY.md`](STUDY_PLAN_30_DAY.md) |
| 90-Day | Intermediate | 90 days (13 wks) | 1 lesson/day | 2 lessons | `[01.01]`–`[10.07]` (89 of 270 lessons) — adds Global Market, Economics, Macroeconomics, Financial Statements, Fundamental Analysis, Valuation, and most of Technical Analysis | [`STUDY_PLAN_90_DAY.md`](STUDY_PLAN_90_DAY.md) |
| 180-Day | Professional | 180 days (26 wks) | 1 lesson/day | 3 lessons | `[01.01]`–`[24.02]` (204 of 270 lessons) — adds the rest of Technical Analysis, Candlesticks, Chart Patterns, Price Action, Volume, Market Profile, Volume Profile, Wyckoff, Smart Money, ICT, Futures, Options, Greeks, Volatility, and the start of Trading Strategies | [`STUDY_PLAN_180_DAY.md`](STUDY_PLAN_180_DAY.md) |
| 365-Day | Mastery | 365 days (52 wks) | 1 lesson/day | 3 lessons | `[01.01]`–`[31.10]` — **all 270 core lessons**, then a Mastery/Practice phase (daily analysis, spaced review, case-study re-analysis, capstone projects) for the rest of the year | [`STUDY_PLAN_365_DAY.md`](STUDY_PLAN_365_DAY.md) |

Coverage numbers come from actually pacing all 270 core lessons (Modules
01-31, real per-lesson reading times from `INDEX.md`/`KNOWLEDGE_GRAPH.md`)
against the availability profile above at a fixed daily rhythm — they are
not round numbers chosen for effect. See "How the schedule was built" below.

**These are four independent tracks, not four sequential stages.** Pick the
one that matches how much time you actually have over the whole period, not
just this week. If you finish a shorter plan and want to continue:
- Restart at `[01.01]` under the next tier's rhythm (re-covering early
  lessons is not wasted time — the Revision/Weekly Test days in the new plan
  will move faster because the material is already familiar), **or**
- Jump straight to the lesson ID your previous plan ended on and continue
  the new plan's weekday/Saturday rhythm from there — `INDEX.md` and
  `KNOWLEDGE_GRAPH.md` will tell you exactly what that lesson's prerequisites
  and next steps are.

**180-Day Professional caveat:** this plan does not yet reach Module 25
(Risk Management) — the academy's own lesson ordering (see
`KNOWLEDGE_GRAPH.md`) puts the full market-reading and derivatives toolkit
before it. Module 25 only assumes Module 01 fundamentals and has no other
hard prerequisite, so if you plan to trade with real capital before you
finish this plan, read `[25.01]`–`[25.08]` out of sequence first, or use the
365-Day Mastery plan instead.

## The Shared Day Template

Every day in every plan is one of five kinds:

| Kind | When | What it contains |
|---|---|---|
| **New Lesson** | Most weekdays and Saturdays | The day's new lesson(s), sized to the weekday/Saturday budget above, using that lesson's *own* Quiz and Homework sections (never new content invented for the plan) |
| **Revision Day** | Every Sunday | No new lessons. Flashcard (Module 34) + CheatSheet (Module 35) review of the week's material, a cumulative **Weekly Test**, and a Market Journal entry |
| **Monthly Exam** | Every 4th Sunday | A Revision Day upgraded to a cumulative **Monthly Exam** (Module 37 Assessment) covering the last 4 weeks, plus a progress-tracker update |
| **Post-Core (365-Day only)** | After all 270 lessons are done | A rotating weekly cycle: Daily Market Analysis (Module 32), Practice Drills (Module 38), Spaced flashcard/cheat-sheet review (34/35) cycling through all 31 modules, Case Study re-analysis (Module 31), and Capstone Project sessions (Module 39) |
| **Final Review** | The plan's last day, always | Full cumulative review + a Final Capstone Assessment + a completion reflection in your Market Journal, regardless of what weekday it happens to fall on |

**Revision days are never skipped.** Every plan reserves every Sunday for
review and testing — no plan schedules a new lesson on a Sunday, ever. This
was an explicit, non-negotiable constraint on how the schedules were built.

Per-day fields (Lessons, Reading Time, Exercises, Quiz, Homework, Estimated
Completion Time) all point back to real content that already exists in the
academy — a lesson's own Core Concepts worked example, its own Quiz, its own
Homework — rather than inventing parallel exercises. This keeps the plan a
*schedule*, not a second copy of the curriculum.

**Estimated Completion Time** = reading time + 40 minutes/lesson (quiz +
redoing the worked example + homework). That per-lesson overhead is fixed
across all four plans; it was checked against the corpus's longest lesson
(45 minutes) to confirm even a max-length lesson day fits its budget.

## How the Schedule Was Built

1. All 270 core lessons were ordered exactly as `CURRICULUM.md`/`INDEX.md`
   order them (Module 01 → Module 31, lesson 01 → last lesson) — this order
   is the academy's verified prerequisite order (see `AUDIT_REPORT.md`:
   zero circular dependencies), so following it in sequence never puts a
   lesson before something it depends on.
2. Each weekday consumes exactly 1 lesson; each Saturday consumes 2 (30-
   and 90-day plans) or 3 (180- and 365-day plans, which can afford a
   slightly heavier weekend session over their longer horizon); Sundays
   consume 0.
3. Every 7th day is a Revision Day; every 28th day is upgraded to a Monthly
   Exam.
4. The plan's final day is always overridden to a Final Review, regardless
   of the weekly cycle.
5. Whatever calendar length remains after all 270 lessons are scheduled (the
   365-day plan only) is filled with the Post-Core rotation described above.

This is why the 30/90/180-day plans stop mid-curriculum at an exact lesson
(not a round number) — that is genuinely as much of the academy as fits,
without new-lesson days ever exceeding the stated time budget or a single
Sunday ever being used for new material.

## Tracking Your Progress

- Copy `progress_tracker/STUDENT_PROGRESS_TEMPLATE.md` before you start —
  Monthly Exam days ask you to update it.
- Copy `market_journal/JOURNAL_TEMPLATE.md` before you start — every
  Revision Day, Monthly Exam, and the Final Review write to it.
- `LEARNING_PATH.md` describes the same lesson order in narrative form
  without day-by-day pacing, if you'd rather self-pace entirely.

---

*Generated 2026-08-05 from real per-lesson reading times and the academy's
verified prerequisite order. Educational content only. Not investment
advice.*
