# ROADMAP.md

Trading-Academy-Pro is built incrementally. This roadmap tracks the big
milestones. For file-by-file status, see `TODO.md`. For the full syllabus,
see `CURRICULUM.md`.

## Milestone 0 — Scaffolding ✅ Complete (2026-08-04)
Repository structure, governance docs (`MASTER_SKILL.md`, `CURRICULUM.md`,
`LEARNING_PATH.md`), templates, and trackers.

## Milestone 1 — Foundation Layer ✅ Complete (2026-08-04)
Modules 01–04 (Foundation, Market Structure, Indian Market, Global Market).
Goal: a student can explain what a market is, how orders work, and how
Indian and global exchanges relate to each other.

## Milestone 2 — Macro & Fundamentals Layer ✅ Complete (2026-08-04)
Modules 05–09 (Economics, Macroeconomics, Financial Statements, Fundamental
Analysis, Valuation).
Goal: a student can read a company's financials and place it in a macro
context.

## Milestone 3 — Technical Analysis Layer ✅ Complete (2026-08-04)
Modules 02 (revisited), 10–14 (Technical Analysis, Candlesticks, Chart
Patterns, Price Action, Volume).
Goal: a student can independently read a price chart.

## Milestone 4 — Advanced Market Reading Layer ✅ Complete (2026-08-04)
Modules 15–19 (Market Profile, Volume Profile, Wyckoff, Smart Money, ICT).
Goal: a student understands auction market theory and institutional
footprints.

## Milestone 5 — Derivatives Layer ✅ Complete (2026-08-05)
Modules 20–23, 26–27 (Futures, Options, Greeks, Volatility, Position Sizing,
Portfolio Management).
Goal: a student can price, structure, and risk-manage a derivatives position.

## Milestone 6 — Strategy & Risk Layer ✅ Complete (2026-08-05)
Modules 24–25, 28 (Trading Strategies, Risk Management, Trading Psychology).
Goal: a student has a written trading plan with defined risk rules.

## Milestone 7 — Quant/Algo Layer ✅ Complete (2026-08-05)
Modules 29–30 (Algorithmic Trading, Quantitative Trading).
Goal: a student understands how systematic/quant desks operate, even if they
trade discretionarily.

## Milestone 8 — Case Studies & Synthesis ✅ Complete (2026-08-05)
Module 31 (Case Studies) + capstone projects (Module 39).
Goal: a student can analyze a historical market event using the full toolkit.

## Milestone 9 — Support Systems ✅ Complete (2026-08-05)
Modules 32–38, 40 (Daily Analysis, Glossary, Flashcards, CheatSheets, Quizzes,
Assessments, Practice, Resources) + `daily_learning/`, `weekly_tests/`,
`monthly_exams/`, `mind_maps/`, `revision_guides/`, `simulation_exercises/`,
`decision_trees/`.
Goal: durable reference and assessment infrastructure exists for every module.

## Milestone 10 — v1.0 Release ✅ Achieved (2026-08-05)
386 files exist across all 40 modules (270 core lessons + special-module
reference content), cross-referenced, with zero broken links, zero broken
`[XX.YY]` citations, and zero duplicate lesson numbers (verified by
automated audit — see `CHANGELOG.md`, 2026-08-05 maintainer audit entry).
`TODO.md` shows zero remaining planned-but-ungenerated files. README
progress table shows 100%.

---

## Post-v1.0 — Maintenance Log

- **2026-08-05:** Independent pre-publication audit completed (`AUDIT_REPORT.md`,
  41 findings, 0 Critical). `INDEX.md` added — a generated, complete table of
  contents (every lesson/quiz/cheat sheet/case study/worksheet/glossary entry,
  with reading time, difficulty, and prerequisites).
- **2026-08-05:** `KNOWLEDGE_GRAPH.md` added — the full concept dependency
  graph for all 270 core lessons (prerequisites, related topics, next topic,
  advanced follow-ons, key misconception) plus a module-level Mermaid map and
  31 per-module lesson-level Mermaid diagrams. Generated from lesson source,
  not hand-authored — see `CHANGELOG.md` for methodology and validation.
- **2026-08-05:** `STUDY_PLAN.md` and four detail files
  (`STUDY_PLAN_30_DAY.md`/`_90_DAY.md`/`_180_DAY.md`/`_365_DAY.md`) added —
  day-by-day calendars pacing all 270 core lessons against a full-time-job
  availability profile, with weekly tests, monthly exams, and revision days
  every week without exception. See `CHANGELOG.md` for pacing methodology.
- **2026-08-06:** `ASSET_PLAN.md` added — a prioritized backlog of 393
  produced-graphic candidates (8 asset types) across all 270 core lessons,
  scored by module fit, title cues, and downstream reuse count. Planning
  only — no assets were produced.

## Post-v1.0 — Maintenance Phase (ongoing)
As of 2026-08-05, the repository is in **maintenance mode**: the
assistant acts as ongoing maintainer under a standing 10-point checklist
(duplicate-topic checks, link validation, doc updates, backlinks,
terminology consistency, file-size limits — see `CONTRIBUTING.md`) before
any new file is added. Future milestones focus on:

- **Milestone 11 — Revision Pass:** re-read early modules (01-09) with
  fresh eyes for consistency against later modules' terminology and depth.
- **Milestone 12 — Real-World Validation:** apply Module 32's daily
  analysis template and Module 39's capstone projects against genuinely
  live market data, feeding lessons learned back into lesson revisions.
- **Milestone 13 — Community Contribution:** if this repository is ever
  opened to outside contributors, formalize `CONTRIBUTING.md`'s review
  process against real pull requests.

No fixed timeline — this is explicitly a multi-year project, not a
sprint to a second release date.

---

## Versioning Philosophy

This repository follows the spirit of semantic versioning for curricula:

- **Patch (v1.0.x):** typo fixes, broken link fixes, small clarifications.
- **Minor (v1.x.0):** new lessons added, existing lessons expanded.
- **Major (vx.0.0):** curriculum restructuring, template changes that ripple
  across all existing lessons.

See `CHANGELOG.md` for the running log.
