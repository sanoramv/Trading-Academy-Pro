# CHANGELOG.md

All notable changes to Trading-Academy-Pro are logged here, most recent first.
Format loosely follows [Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]

### 2026-08-07 — Added REFERENCES.md: authoritative sources cross-linked to every lesson
- Added `REFERENCES.md` — for every one of the 270 core lessons, its
  recommended further reading organized by 14 requested source types
  (Books, Academic papers, SEBI, NSE, BSE, RBI, Federal Reserve, CME,
  CBOE, SEC, BIS, IMF, World Bank, Investopedia), plus a 15th "Other
  Practitioner & Data Resources" bucket for real cited sources
  (TradingView, StockCharts, CRISIL/ICRA, etc.) that don't fit the 14.
- **No reference was invented.** Every citation was extracted directly
  from each lesson's own existing `## Further Reading` section (569
  citations total, sorted into 314 distinct sources) — this file
  organizes and cross-links material the curriculum already vetted, it
  does not add new sources. Fixed an extraction bug along the way where
  multi-line Further Reading bullets were being truncated to their first
  line; re-extracted with the full text preserved.
- Structure: Part 1 is a Master Source Directory (one entry per
  regulator/exchange with its real, well-known domain — e.g. sebi.gov.in,
  nseindia.com, rbi.org.in — plus deduped Books and Academic Papers
  lists); Part 2 is a per-module, per-lesson table of exactly which of
  those sources each lesson cites.
- One lesson, `[04.06]` Correlation Between Global Markets, cites no
  external source in its own Further Reading (only cross-module
  references) — its entry says so explicitly rather than inventing one.
- Validated: all 270 lessons appear exactly once, all file links resolve,
  zero broken citations. File is 677 lines — well within the 2,000-line
  cap.
- Cross-linked from `CURRICULUM.md`'s header alongside `INDEX.md`,
  `KNOWLEDGE_GRAPH.md`, `STUDY_PLAN.md`, and `ASSET_PLAN.md`.

### 2026-08-07 — Fixed all 16 lowest-scoring (5-6/10) PEDAGOGICAL_REVIEW.md lessons
- Applied the specific recommended improvement to every lesson
  `PEDAGOGICAL_REVIEW.md` scored 5-6/10:
  - **`07.06`** Revenue Recognition — split channel stuffing, related-party
    transactions, and mark-to-market misuse into three separate
    sub-explanations, each with its own concrete numeric mini-example.
  - **`08.09`** Industry/Sector Analysis — added a Five-Forces-in-Practice
    table giving each Porter's Force its own distinct, concrete
    illustration instead of one combined airline narrative.
  - **`09.03`** DCF Fundamentals (was the lowest score, 5/10) — added a
    complete worked 3-year DCF (FCF projection, discounting, terminal
    value, summed to a per-share estimate) before homework requires
    replicating it.
  - **`09.04`** Dividend Discount Model — added a plugged-in Gordon Growth
    calculation (D1=Rs 20, r=12%, g=6% -> Rs 333/share) plus a
    demonstration of the g<r constraint's sensitivity.
  - **`12.03`** Triple Top/Bottom — restructured to lead with the
    rarity-vs-reliability trade-off (the lesson's one genuinely new idea)
    and cut confirmation-mechanics exposition already covered in `12.02`.
  - **`15.03`** Profile Shapes — added three realistic, letter-by-letter
    TPO profile examples (Normal/Trend/P-shape) for genuine visual
    pattern-recognition practice, beyond the existing idealized outlines.
  - **`16.02`** Volume Profile POC — added a worked example showing a
    concrete case where TPO-based and Volume-based POC genuinely disagree
    for the same session, sharpening the differentiation from `15.02`.
  - **`17.03`** Accumulation Schematic — added a fully-annotated,
    phase-by-phase worked chart (all 7 named events with illustrative
    dates/prices) before homework assigns independent real-chart labeling.
  - **`20.06`** Rollover Mechanics — added a worked rollover-cost
    calculation (basis difference x lot size + transaction costs).
  - **`20.07`** Index vs Stock Futures — added a scenario-based quiz
    question requiring settlement-type identification, not recall.
  - **`20.09`** Speculation with Futures — added a worked loss table for a
    short futures position across five rising price points, plus a
    matching homework calculation, making "unlimited loss" concrete.
  - **`23.01`** What Is Volatility — added a full historical-volatility
    calculation from 6 daily returns (mean -> variance -> SD ->
    annualized), and removed a stray leftover editorial note-to-self
    that had been left in the published lesson.
  - **`25.06`** Correlation Risk — removed the disclaimed portfolio-variance
    formula entirely; replaced with a fully worked numeric clustering
    example (5 positions, 2 clusters) requiring only addition.
  - **`27.03`** Modern Portfolio Theory — added a full two-asset portfolio
    variance calculation showing the actual diversification benefit
    (12.45% vs. a naive 15% weighted-average volatility), plus a matching
    homework problem.
  - **`29.07`** Algo Trading Regulations — replaced vague "recent
    framework" language with a dated, year-level regulatory timeline
    (2008, 2011-2013, 2018, 2021-2022, 2025).
  - **`30.02`** Statistical Foundations — added a full mean/variance/SD
    calculation from 5 daily returns, tying the result explicitly back to
    `23.01`'s "historical volatility."
- All worked examples independently re-verified arithmetically during
  authoring (every intermediate step recomputed, not just the final
  answer) before being written into the lesson files.
- Updated `PEDAGOGICAL_REVIEW.md` with a remediation-status note; scores
  were intentionally *not* re-run, so the file's listed scores describe
  pre-fix state (documented explicitly to avoid the file becoming
  misleading).
- Validated: all 16 files re-checked for broken links, missing citations,
  and duplicate section headers (zero found); all remain well within the
  2,000-line cap (largest touched file: `15.03` at 354 lines).

### 2026-08-07 — Added PEDAGOGICAL_REVIEW.md: instructional-design review of all 270 lessons
- Added `PEDAGOGICAL_REVIEW.md` — every core lesson (Modules 01-31) scored
  1-10 on 8 pedagogical dimensions (intuitiveness, example sufficiency,
  analogy effectiveness, length, beginner overload, quiz quality, homework
  meaningfulness), with a specific recommended improvement per lesson.
- Produced by 8 independent reviewers (one per module cluster, same
  clusters used for the fact-check pass), each blind to the others' work,
  instructed not to rubber-stamp every lesson — resulting distribution:
  overall average 7.79/10, 1 lesson at 5/10, 15 at 6/10, 66 at 7/10, 145 at
  8/10, 43 at 9/10, none below 5 or at 10.
- A "Cross-Cutting Patterns" section synthesizes themes multiple blind
  reviewers independently rediscovered: quizzes test recall over
  application curriculum-wide (flagged by all 8 reviewers independently);
  worked numerical examples are the biggest quality differentiator in
  math-heavy lessons; real historical events outperform hypothetical
  examples; a handful of lesson-pairs are structurally redundant
  (`02.01`/`02.02`, `12.02`/`12.03`, `25.01-02`/`26.01-02`); beginner
  overload concentrates in ~6 identifiable lessons, not diffusely; Trading
  Psychology (Module 28) defied its a-priori "motivational poster" risk
  and scored highest of any module (8.63).
- Global Exemplars (43 lessons at 9/10) and Lowest-Scoring (16 lessons at
  5-6/10) tables extracted for quick reference.
- Read-only, as instructed — no lesson files were modified.
- Validated: all 270 lessons appear exactly once across the per-module
  tables, all file links resolve, all table rows well-formed. File is 710
  lines — well within the 2,000-line cap.

### 2026-08-07 — Fixed all 14 High-confidence FACT_CHECK_REPORT.md findings
- Corrected 14 High-confidence factual issues across 12 lesson files, plus
  one non-categorized editorial artifact, all identified by the same-day
  `FACT_CHECK_REPORT.md` review:
  - **FACT-002** — `02.04`: Nifty 18,000 breakout redated Dec 2022 (was "late 2023").
  - **FACT-004** — `01.06`: Zomato IPO proceeds correctly split between the ₹9,000cr fresh issue (to Zomato) and ₹375cr OFS (to Info Edge).
  - **FACT-008** — `07.08`: goodwill no longer described as amortized (impairment-tested instead), in both the Definition and US Market Example.
  - **FACT-011** — `09.03`: WACC definition now specifies after-tax cost of debt.
  - **FACT-022** — `19.04`: OTE/Fibonacci empirical-support claim corrected to match the 2022 *Expert Systems with Applications* finding of no standalone edge.
  - **FACT-024/FACT-025** — `20.03`, `20.06`: NSE's September 2025 F&O expiry-day change (Thursday → Tuesday) corrected everywhere it appeared — definitions, ASCII diagrams, flowcharts, revision notes, flashcards, and the quiz Q&A in both files (13 total instances).
  - **FACT-027** — `23.02`: removed the anachronistic 2004-election India-VIX claim (VIX launched 2008); replaced with the 2019 election example.
  - **FACT-028** — `23.06`: Volmageddon VIX spike corrected from "~20%" to the verified ~116% (17.31→37.32).
  - **FACT-029** — `25.02`: added the stop-loss slippage/gap-risk caveat to the Definition, Common Mistakes, Key Takeaways, Revision Notes, Learning Objectives, and Flashcards (6 instances) — risk-per-trade is now framed as *intended*, not guaranteed, loss.
  - **FACT-031** — `26.04`: added the Kelly Criterion's negative/mis-estimated-edge behavior (guaranteed long-run capital destruction, not just lower returns).
  - **FACT-032** — `30.06`: Citadel Securities founding year corrected 1999 → 2002, in both the Historical Example and Revision Notes.
  - **FACT-033** — `31.01`: S&P 500 GFC recovery duration corrected from "over four years" to "~5.5 years (March 2013)" in the ASCII diagram, Key Takeaways, and Revision Notes (3 instances).
  - **FACT-034** — `31.06`: H1 title corrected to "Adani Group–Hindenburg Report Episode (January 2023)" to match its actual content. The underlying filename was deliberately left unchanged to avoid breaking existing links; the new title was then propagated to every file that displayed the old one: `KNOWLEDGE_GRAPH.md`, `INDEX.md`, `ASSET_PLAN.md`, `STUDY_PLAN_365_DAY.md` (4 occurrences), `CURRICULUM.md`, `docs/31_Case_Studies/_Index.md`, `31.05`'s body text and Next Lesson link, and `MASTER_SKILL.md`'s own example citation.
  - **Editorial artifact** — `28.08`: removed a stray "MASTER_SKILL.md" text leak from body prose.
- **Not fixed in this pass:** Medium-confidence-and-below findings (FACT-001,
  FACT-003, FACT-005–021 except those above, FACT-023, FACT-026, FACT-030)
  remain open, along with AUDIT-041 (a related but distinct SEBI Act timing
  issue in `31.03`) — deferred to a future remediation pass, per the
  explicit "High confidence findings first" scope of this batch.
- Updated `FACT_CHECK_REPORT.md` and `AUDIT_REPORT.md` with remediation-status
  notes marking which findings are now fixed vs. still open, so both reports
  stay accurate rather than becoming stale historical snapshots.
- Validated: all touched files re-checked for broken links/citations (zero
  found), all remain within the 2,000-line cap (largest touched file:
  `KNOWLEDGE_GRAPH.md` at 1,999 lines, unchanged by this pass).

### 2026-08-07 — Added FACT_CHECK_REPORT.md: Chief Technical Editor content review
- Added `FACT_CHECK_REPORT.md` — a factual review of all 270 core lessons
  for incorrect statements, outdated information, oversimplified
  explanations, unsourced claims, trading myths presented as fact,
  statements needing nuance, and concepts needing caveats.
- 34 findings, each with File, Section, exact verbatim sentence, why it's
  problematic, a corrected version, and a confidence level (17 High, 2
  Medium-High, 12 Medium, 4 Low-Medium, 2 Low), plus one non-categorized
  editorial artifact (a stray `MASTER_SKILL.md` text leak in `28.08`).
- Produced by 8 independent full-corpus read-throughs (one per module
  cluster), each fact-checked against real-world financial/historical
  knowledge and cross-verified where checkable (dates, formulas,
  magnitudes). Findings were deliberately not padded — several clusters
  reported as few as 3 genuine issues rather than forcing one per lesson.
- Confirms and fully details 5 items the 2026-08-05 audit only flagged
  briefly: SEBI Act timeline (AUDIT-041), Kelly Criterion's negative-edge
  blind spot (AUDIT-035), Volmageddon VIX magnitude understated ~6x
  (AUDIT-032), Citadel Securities founding year (AUDIT-040), and the
  31.06 title/content mismatch (AUDIT-005).
- Surfaced 2 cross-cutting patterns: an unsourced "US quantitative
  researchers report..." phrase reused across 3 lessons in the
  Wyckoff/Smart Money/ICT cluster, and the same understated S&P 500 GFC
  recovery duration ("~4 years" vs. actual ~5.5 years) independently
  appearing in two different lessons (`25.05` and `31.01`).
- One genuinely new, previously undetected issue: NSE moved its F&O
  expiry day from Thursday to Tuesday in September 2025, making two
  Futures lessons (`20.03`, `20.06`) outdated.
- **Read-only, as explicitly instructed — no lesson files were modified.**
  Corrections remain proposed, not applied, pending separate authorization.

### 2026-08-06 — Added ASSET_PLAN.md: prioritized visual-asset backlog
- Added `ASSET_PLAN.md` — for all 270 core lessons, identifies which of 8
  asset types (Flowchart, Timeline Diagram, Infographic, Decision Tree,
  Candlestick Illustration, Option Payoff Diagram, Market Structure
  Diagram, Order Flow Diagram) a *produced* graphical asset would add value
  beyond the ASCII diagram every lesson already has. 393 backlog items
  total (most lessons produced one, some two).
- Planning only, as explicitly requested — **no images, diagrams, or
  illustration files were created**.
- Scoring is auditable, not a black box: each item records its **Signal**
  (which module-affinity and/or title-keyword match triggered it) and a
  **Score** = `type_weight × 10 + downstream_reuse_count × 3 +
  foundational_bonus`, where `downstream_reuse_count` reuses the same
  reverse-prerequisite computation `KNOWLEDGE_GRAPH.md`'s "Advanced Topics"
  column already validated.
- Items are grouped into 4 priority tiers (P0-Critical/P1-High/P2-Medium/
  P3-Low, the same convention `AUDIT_REPORT.md` uses) by score quantile:
  81/78/138/96 items respectively.
- Validated: all 270 lessons appear at least once, all file links and
  `[XX.YY]` citations resolve, all table rows well-formed. File is 621
  lines — well within the 2,000-line cap.
- Cross-linked from `CONTRIBUTING.md` (new "Visual Assets" section covering
  how to pick up a backlog item) and `CURRICULUM.md`'s header, alongside
  `INDEX.md`, `KNOWLEDGE_GRAPH.md`, and `STUDY_PLAN.md`.

### 2026-08-05 — Added STUDY_PLAN.md: 30/90/180/365-day pacing tracks
- Added `STUDY_PLAN.md` (overview, shared day template, assumptions) plus
  four detail files — `STUDY_PLAN_30_DAY.md` (Beginner), `_90_DAY.md`
  (Intermediate), `_180_DAY.md` (Professional), `_365_DAY.md` (Mastery) —
  giving a literal day-by-day calendar through the academy, calibrated to
  60-90 min/weekday and 3-4 hrs/weekend.
- Pacing is generated, not hand-typed: all 270 core lessons are consumed in
  `CURRICULUM.md`/`INDEX.md` order (the academy's verified prerequisite
  order — zero circular dependencies per `AUDIT_REPORT.md`) at 1 lesson per
  weekday and 2 (30/90-day) or 3 (180/365-day) lessons per Saturday, using
  each lesson's real reading time. Resulting coverage: 30-day reaches
  `[04.01]` (29 lessons), 90-day reaches `[10.07]` (89 lessons), 180-day
  reaches `[24.02]` (204 lessons), 365-day completes all 270 core lessons
  and then runs a Post-Core Mastery/Practice phase (Daily Analysis, Practice
  Drills, spaced flashcard review, Case Study re-analysis, Capstone Project
  sessions) for the remainder of the year.
- **Every Sunday is a Revision Day with no new lessons — zero exceptions,
  by construction** (the day-assignment logic never places a new lesson on
  day-of-week 7). Every 4th Sunday is upgraded to a cumulative Monthly Exam
  (Module 37 Assessment). Each plan's final day is always a Final Review +
  Capstone Assessment regardless of where it falls in the weekly cycle.
- Every day's Exercises/Quiz/Homework fields reference that lesson's own
  Core Concepts example, Quiz, and Homework sections rather than inventing
  parallel content — the plan schedules the existing curriculum, it doesn't
  duplicate it.
- Flagged an honest scope gap in the 180-Day Professional plan: it does not
  reach Module 25 (Risk Management) before its 180 days are up. Documented
  in `STUDY_PLAN.md` with a pointer to fast-track Module 25 (its only hard
  prerequisite is Module 01) or use the 365-Day plan instead.
- Validated: all file links across all 5 files resolve, every `[XX.YY]`
  citation resolves to a real lesson ID, every table row has the expected
  column count. Largest file (`STUDY_PLAN_365_DAY.md`) is 736 lines — all
  five files are well within the 2,000-line cap.
- Cross-linked from `README.md`'s "How to Use This Repository" and
  `CURRICULUM.md`'s header, alongside `INDEX.md` and `KNOWLEDGE_GRAPH.md`.

### 2026-08-05 — Added KNOWLEDGE_GRAPH.md: full concept dependency graph
- Added `KNOWLEDGE_GRAPH.md` at repository root — for every one of the 270
  core lessons (Modules 01-31): Prerequisites, Related Topics, Next Topic,
  Advanced Topics, and a one-line Key Misconception, plus a Mermaid diagram
  per module (31 diagrams) and one module-level master Mermaid diagram
  covering all 40 modules.
- All fields extracted programmatically from each lesson's own
  `## Prerequisites`, `## Next Lesson`, and `## Misconceptions` sections —
  not hand-typed. "Related Topics" comes from `[XX.YY]` cross-references the
  lesson body itself makes outside its Prerequisites/Next sections (falling
  back to nearest same-module lessons only where a lesson makes none).
  "Advanced Topics" is computed by reversing the prerequisite graph: lessons
  that list this one as a prerequisite, excluding whichever is already the
  Next Topic.
- Modules 32-40 (the support layer) are documented separately as a
  qualitative dependency chain rather than lesson-by-lesson, since they use
  reference/assessment formats without the `XX.YY` prerequisite structure —
  consistent with how their own `_Index.md` files already describe them.
- Added a "Recurring Threads" section identifying concepts that resurface
  across many modules (risk management, order mechanics, volatility,
  Wyckoff/Smart Money/ICT) rather than staying confined to one module.
- Validated: all 33 Mermaid code fences balanced, all 270 lesson file links
  resolve, all `[XX.YY]` citations resolve to a real lesson ID, all 270
  lessons appear in exactly one module table (zero missing, zero duplicated).
- File is 1,999 lines — within the 2,000-line maintainer guideline despite
  covering all 270 lessons across 5 relationship dimensions each, achieved
  by compressing simple linear prerequisite chains into single Mermaid
  chain-arrows (`A --> B --> C`) instead of one edge line per step.
- Cross-linked from `README.md`'s "How to Use This Repository" and
  `CURRICULUM.md`'s header, alongside the existing `INDEX.md` link.

### 2026-08-05 — Added INDEX.md: complete, generated table of contents
- Added `INDEX.md` at repository root — a single reference covering all
  270 core lessons (Modules 01-31) plus all 116 files in the support
  modules (32-40): every quiz, cheat sheet, flashcard deck, glossary
  file, practice drill, capstone project, and resource file.
- Per-lesson metadata (title, difficulty level, estimated time,
  prerequisites, "next lesson") is extracted programmatically from each
  lesson's own front matter and Prerequisites section — not hand-typed —
  so it stays accurate as long as the source lessons do. Regeneration
  method documented in `CONTRIBUTING.md`.
- Difficulty levels (🟢 Beginner / 🟡 Intermediate / 🔴 Advanced /
  ⚪ Reference) are assigned per module, consistent with `ROADMAP.md`'s
  existing milestone groupings, not a newly invented scale.
- Validated: all 1,216 file links and all 40 table-of-contents anchor
  links resolve correctly (automated check, zero broken).
- Cross-linked from `README.md`'s "How to Use This Repository" and
  `CURRICULUM.md`'s header, distinguishing INDEX.md's role (generated,
  linkable reference) from CURRICULUM.md's role (planning source of truth).

### 2026-08-05 — Repository enters maintenance mode
- Adopted a mandatory 10-point maintainer checklist (duplicate-topic
  checks, link validation, doc updates, backlinks, terminology
  consistency, ~2,000-line file-size cap) for all future file changes —
  formalized in `CONTRIBUTING.md`'s new "Maintainer Checklist" section.
- Ran a full repository audit: **zero broken `_Index.md` links**, **zero
  broken `[XX.YY]` cross-reference citations** (270 valid lesson IDs
  checked across all 373 files in `docs/`), **zero duplicate lesson
  numbers**. Largest file is 331 lines — well within the new 2,000-line cap.
- Updated `ROADMAP.md`: marked all 10 build milestones complete with
  dates, added a "Post-v1.0 — Maintenance Phase" section outlining
  future direction (revision pass, real-world validation, community
  contribution) with no fixed timeline, consistent with treating this
  as a multi-year project.

### 2026-08-05 — Module 40 Resources: COMPLETE (6/6 files) — 🎉 BUILD COMPLETE (v1.0)
- Added `docs/40_Resources/_Index.md`, `Recommended_Books.md`,
  `Regulator_Resources.md`, `Data_Sources.md`, `Keep_Learning_Guide.md`,
  and `Full_Book_Bibliography.md` (consolidating every book/paper cited
  across Modules 01-31).
- **386/353 planned files complete** (exceeded the original ~353
  estimate significantly).
- **All 40 modules of Trading-Academy-Pro are now complete**, per
  `MASTER_SKILL.md §8`'s Definition of Done: `docs/` spans 40 modules
  with 300+ lesson/reference files, every module has an index, and
  `TODO.md` shows zero remaining planned-but-ungenerated files.
  Future work shifts from generation to revision and real-world testing.

### 2026-08-05 — Module 39 Projects: COMPLETE (7/7 files)
- Added `docs/39_Projects/_Index.md` and 6 capstone project briefs:
  trading plan, stock screener, strategy backtest, risk dashboard,
  macro dashboard, and a full-quarter paper-trading report — each with
  objectives, requirements, deliverable format, evaluation criteria,
  and a worked example fragment.
- **380/353 planned files complete.** Starting Module 40: Resources — the final module.

### 2026-08-05 — Module 38 Practice: COMPLETE (9/9 files)
- Added `docs/38_Practice/_Index.md` and 8 hands-on drills: chart
  marking (structure, patterns), options payoff worksheet, Greeks
  calculation worksheet, risk-sizing calculator, journaling drill,
  manual mini-backtest drill, and psychology self-audit — each with
  step-by-step instructions and fully worked examples.
- **373/353 planned files complete.** Starting Module 39: Projects.

### 2026-08-05 — Module 37 Assessments: COMPLETE (9/9 files)
- Added `docs/37_Assessments/_Index.md` and 8 formal exams: Beginner
  Certification, Intermediate Certification, Derivatives Proficiency,
  Risk Management Proficiency, Capstone Readiness, Professional-Track
  Final, Quant Track, and the 31-question Full Academy Final Exam.
- **364/353 planned files complete.** Starting Module 38: Practice.

### 2026-08-05 — Module 36 Quizzes: COMPLETE (9/9 files)
- Added `docs/36_Quizzes/_Index.md` and 8 consolidated cluster quizzes,
  each following `templates/QUIZ_TEMPLATE.md`'s Recall/Application/
  Judgment structure with full answer keys and scoring guides.
- **355/353 planned files complete** (exceeded the ~353 estimate,
  reflecting the academy's genuinely thorough build).
- Starting Module 37: Assessments.

### 2026-08-05 — Module 35 CheatSheets: COMPLETE (11/11 files)
- Added `docs/35_CheatSheets/_Index.md` and 10 cluster quick-reference
  sheets mirroring Module 34's grouping — formulas, key rules, and
  compact diagrams for fast lookup.
- **346/353 planned files complete.** Starting Module 36: Quizzes.

### 2026-08-05 — Module 34 Flashcards: COMPLETE (11/11 files)
- Added `docs/34_Flashcards/_Index.md` and 10 cluster decks (Foundation,
  Indian Market, Macro, Technical Analysis, SMC/ICT/Wyckoff,
  Derivatives, Risk & Strategy, Psychology, Quant & Algo, Case
  Studies), each with 20 active-recall cards drawing from across Modules 01-31.
- **335/353 planned files complete.** Starting Module 35: CheatSheets.

### 2026-08-05 — Module 33 Glossary: COMPLETE (5/5 files)
- Added `docs/33_Glossary/_Index.md` and 4 alphabetical glossary files
  (A-D, E-L, M-R, S-Z), consolidating ~100 terms from across Modules
  01-31, each cross-referenced to its originating lesson.
- **324/353 planned files complete.** Starting Module 34: Flashcards.

### 2026-08-05 — Module 32 Daily Market Analysis: COMPLETE (5/5 files)
- Added `docs/32_Daily_Market_Analysis/_Index.md`, `DAILY_ANALYSIS_TEMPLATE.md`,
  and 3 hypothetical worked examples (trend day, range day, RBI
  event-driven day), each applying multiple Module 02-30 concepts together.
- **319/353 planned files complete.** Starting Module 33: Glossary.

### 2026-08-05 — Module 31 Case Studies: COMPLETE (10/10 lessons)
- Completed lessons `31.06`-`31.10`: Adani Group/Hindenburg episode
  (Jan 2023), GameStop short squeeze (2021), LTCM collapse (1998),
  dot-com bubble (2000), Satyam scandal (2009, "India's Enron").
- **314/353 planned files complete.**
- **Modules 01-31 — the entire core curriculum — is now fully
  complete.** Starting the special modules (32-40): Daily Market
  Analysis, Glossary, Flashcards, CheatSheets, Quizzes, Assessments,
  Practice, Projects, Resources.

### 2026-08-05 — Module 30 Quantitative Trading: COMPLETE (8/8 lessons)
- Completed lessons `30.05`-`30.08`: factor investing (Fama-French),
  market making (Citadel Securities, Jane Street), risk models/
  portfolio optimization (VaR, RiskMetrics 1994), and quant trading
  careers/firms landscape (India & global).
- **303/353 planned files complete.** Starting Module 31: Case Studies.
- Modules 21-30 (Options through Quant Trading) now fully complete —
  this academy's entire derivatives-through-quant progression is done.

### 2026-08-05 — Module 29 Algorithmic Trading: COMPLETE (8/8 lessons)
- Completed lessons `29.05`-`29.08`: execution algorithms (TWAP/VWAP/
  Iceberg), simple trading bot architecture (Knight Capital 2012 case
  study), SEBI algo trading regulation in India, and high-frequency
  trading mechanics (Flash Boys).
- **294/353 planned files complete.** Starting Module 30: Quantitative Trading.

### 2026-08-05 — Module 28 Trading Psychology: COMPLETE (8/8 lessons)
- Added `docs/28_Trading_Psychology/_Index.md` and all 8 lessons: the
  knowing-doing gap, fear/greed cycle, cognitive biases (Kahneman &
  Tversky's Prospect Theory, 1979), revenge trading/tilt, FOMO/
  overtrading, discipline and trading plans, emotional resilience
  (Steenbarger), and professional vs retail psychology.
- Every lesson cross-references Modules 24-27's discipline threads
  (`[24.12]`, `[25.08]`, `[26.01]`) into a unified psychological framework.
- **285/353 planned files complete.** Starting Module 29: Algorithmic Trading.

### 2026-08-05 — Module 27 Portfolio Management: COMPLETE (8/8 lessons)
- Completed lessons `27.05`-`27.08`: rebalancing (calendar/threshold),
  sector rotation and business cycle investing (Stovall), core-
  satellite structure, and performance measurement (Sharpe, Sortino,
  Beta, Alpha — Sharpe 1966).
- **276/353 planned files complete.** Starting Module 28: Trading Psychology.

### 2026-08-05 — Module 26 Position Sizing: COMPLETE (6/6 lessons)
- Added `docs/26_Position_Sizing/_Index.md` and all 6 lessons: `26.01`
  position sizing as the "real edge" (Van Tharp), `26.02` fixed
  fractional, `26.03` ATR/volatility-based, `26.04` Kelly Criterion
  (Kelly 1956, Thorp), `26.05` options defined vs undefined risk
  sizing, `26.06` scaling in/out.
- **267/353 planned files complete.** Starting Module 27: Portfolio Management.

### 2026-08-05 — Module 25 Risk Management: COMPLETE (8/8 lessons)
- Completed lessons `25.05`-`25.08`: maximum drawdown, correlation risk
  across positions, black swan events/tail risk (Taleb), and the
  personal risk management rulebook synthesis.
- Real-world anchors: 2007-2009 S&P 500 ~57% drawdown, 2008 GFC
  correlation-goes-to-one, LTCM 1998, Taleb's "The Black Swan" (2007).
- **260/353 planned files complete.** Starting Module 26: Position Sizing.

### 2026-08-05 — Module 24 Trading Strategies: COMPLETE (12/12 lessons)
- Completed lessons `24.06`–`24.12`: swing trading, intraday scalping,
  positional/momentum investing, options income (theta selling),
  event-driven trading, combining strategies into a portfolio of
  systems, and strategy journaling/iteration.
- Every strategy framework specifies entry/exit/sizing/applicable
  conditions per `[24.01]`'s expectancy criteria, and cross-references
  Modules 02, 10, 13, 14, 21-23 directly.
- **251/353 planned files complete.** Starting Module 25: Risk Management.

### 2026-08-05 — Module 23 Volatility: COMPLETE (6/6 lessons)
- Added `docs/23_Volatility/_Index.md` and all 6 lessons: `23.01`
  Historical vs Implied Volatility, `23.02` India VIX, `23.03` US VIX
  ("fear gauge"), `23.04` Volatility Skew and Smile, `23.05` Volatility
  Regimes and Mean Reversion, `23.06` Trading Volatility Directly.
- Covers the volatility risk premium, the 1987-crash origin of equity
  skew, Engle's ARCH/GARCH volatility clustering research, and the
  February 2018 "Volmageddon" case study (cross-referenced from `[22.08]`).
- **238/353 planned files complete.** Starting Module 24: Trading Strategies.

### 2026-08-05 — Module 22 Greeks: COMPLETE (8/8 lessons)
- Added `docs/22_Greeks/_Index.md` and all 8 lessons: `22.01` Intro to
  Greeks, `22.02` Delta, `22.03` Gamma, `22.04` Theta, `22.05` Vega,
  `22.06` Rho & second-order Greeks, `22.07` Greeks in Practice,
  `22.08` Greeks-Based Position Adjustment Case Study (worked Nifty
  iron condor scenario across 3 sessions).
- Every Greek explicitly ties back to Module 21 concepts (moneyness,
  time value, theta decay trap, iron condor payoff).
- **231/353 planned files complete.** Starting Module 23: Volatility.

### 2026-08-05 — Module 21 Options: COMPLETE (12/12 lessons)
- Added `21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md` —
  synthesizes the module's recurring buyer failure mode (theta decay
  trap) and connects it back to `[21.03]`/`[21.04]`/`[21.11]`.
- **223/353 planned files complete.** Starting Module 22: Greeks.

### 2026-08-05 — Module 21 Options: in progress (11/12 lessons)
- Added `21.11_Option_Chain_Analysis_NSE.md` — reading the NSE option
  chain (OI, Chg in OI, IV, PCR) to infer support/resistance and sentiment.
- **222/353 planned files complete.** Next: `[21.12]` Common Option Buyer Mistakes.

### 2026-08-05 — Module 21 Options: in progress (10/12 lessons)
- Added `21.10_Iron_Condor_and_Iron_Butterfly.md` — four-leg,
  range-bound, defined-risk premium-collection strategies.
- **221/353 planned files complete.** Next: `[21.11]` Option Chain Analysis (NSE).

### 2026-08-05 — Module 21 Options: in progress (9/12 lessons)
- Added `21.09_Straddles_and_Strangles.md` — non-directional,
  magnitude-of-move strategies combining long call + long put.
- **220/353 planned files complete.** Next: `[21.10]` Iron Condor and Iron Butterfly.

### 2026-08-05 — Module 21 Options: in progress (8/12 lessons)
- Added `21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md` — bull call
  and bear put spreads, defined-risk two-leg structures built from
  `[21.05]`/`[21.06]` payoffs.
- **219/353 planned files complete.** Next: `[21.09]` Straddles and Strangles.

### 2026-08-05 — Module 21 Options: in progress (7/12 lessons)
- Added `21.07_Basic_Option_Strategies_Covered_Call_Protective_Put.md` —
  covered call and protective put as stock + single-option combinations,
  built directly on `[21.05]`/`[21.06]` payoff formulas.
- **218/353 planned files complete.** Next: `[21.08]` Spreads.

### 2026-08-05 — Module 21 Options: in progress (6/12 lessons)
- Added `docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md`:
  - Short call and short put payoff formulas, framed as the exact mirror
    of `[21.05]`'s long call/put payoffs.
  - Breakeven (identical to the corresponding long position), maximum
    profit (capped at premium), and maximum loss (unlimited for short
    call, capped-but-large for short put), with ASCII payoff diagrams.
  - Indian (Nifty short call) and US (AAPL short put) hypothetical
    worked examples.
  - 2007–08 short-volatility-style risk historical analogy.
- **217/353 planned files complete.** Next: `[21.07]` Basic Option
  Strategies — Covered Call, Protective Put.

### 2026-08-05 — Module 21 Options: in progress (5/12 lessons)
- Added `docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md`:
  - Long call and long put payoff formulas derived from `[21.04]`'s
    intrinsic value decomposition.
  - Breakeven, maximum loss, and maximum profit for both positions, with
    ASCII payoff diagrams.
  - Indian (Nifty call) and US (AAPL put) hypothetical worked examples.
  - March 2020 COVID crash historical example illustrating asymmetric
    long-option payoff behavior.
- **216/353 planned files complete.** Next: `[21.06]` Option Payoff
  Diagrams — Short Call, Short Put.

### 2026-08-04 — Module 01 Foundation: COMPLETE (10/10 lessons)
- Added `docs/01_Foundation/_Index.md` — module index and lesson table.
- Added all 10 Foundation lessons:
  - `01.01` What Is a Financial Market — the VOC (1602), BSE (1875)/NSE
    (1992)/NYSE (1792), market vs. exchange.
  - `01.02` What Is Trading vs Investing — time horizon/decision-basis
    framework, dot-com bubble case.
  - `01.03` Asset Classes Overview — equity/debt/currency/commodities/
    derivatives, 2013 Taper Tantrum cross-asset example.
  - `01.04` How Stock Exchanges Work — order books, price-time priority,
    NSE's 1992 electronic transition.
  - `01.05` Market Participants — retail/institutional/market makers,
    FII/DII dynamics, GameStop 2021.
  - `01.06` Primary Market vs Secondary Market — IPO mechanics, Zomato
    (2021) and Coal India (2010) IPO examples.
  - `01.07` Order Types Explained — Market/Limit/SL/SL-M/Bracket/Cover
    orders, 2010 Flash Crash slippage example.
  - `01.08` How an Order Actually Executes — broker RMS → exchange →
    clearing pipeline, T+1 settlement.
  - `01.09` Brokers, Depositories & Clearing Corporations — NSDL/CDSL/
    NSCCL roles, post-1992-scam reforms.
  - `01.10` Reading Your First Stock Quote — LTP/Bid/Ask/Volume/OI, module
    capstone homework.
- Every lesson follows the full `MASTER_SKILL.md` §3 template, is
  cross-referenced to adjacent lessons, and includes Indian + US market
  examples, a real historical example, a 5-question quiz with answers, and
  homework.
- **24/353 planned files complete.** Starting Module 02: Market Structure.

### 2026-08-04 — Module 02 Market Structure: COMPLETE (8/8 lessons)
- Added `docs/02_Market_Structure/_Index.md` and all 8 lessons:
  - `02.01` What Is Market Structure — trend/range/uptrend/downtrend basics.
  - `02.02` Trend, Range, and Structure Basics — "structure until proven
    otherwise," initiation/continuation/exhaustion phases.
  - `02.03` Higher Highs, Higher Lows, Lower Highs, Lower Lows — formal
    HH/HL/LH/LL definitions, Nifty 2021 top and Nasdaq 2022 top examples.
  - `02.04` Support and Resistance — First Principles — zones vs. lines,
    polarity flip, Nifty 18,000 example.
  - `02.05` Break of Structure (BOS) vs Change of Character (CHOCH) —
    trend-continuation vs. reversal-warning breaks.
  - `02.06` Liquidity — What It Really Means — buy-side/sell-side
    liquidity, 2010 Flash Crash example.
  - `02.07` Swing Points and Fractals — formal n-bar swing rules, Elliott
    Wave's fractal insight.
  - `02.08` Multi-Timeframe Structure Analysis — bias/setup/entry-timing
    three-tier framework, module capstone.
- **33/353 planned files complete.** Starting Module 03: Indian Market.

### 2026-08-04 — Module 03 Indian Market: COMPLETE (10/10 lessons)
- Added `docs/03_Indian_Market/_Index.md` and all 10 lessons:
  - `03.01` History of Indian Stock Markets — BSE (1875) to NSE (1992),
    crisis-to-reform pattern.
  - `03.02` SEBI — Role, Powers, and Investor Protection — regulate/
    develop/protect mandate, SCORES portal.
  - `03.03` NSE vs BSE — Structure and Indices — dual-listing, arbitrage.
  - `03.04` Nifty 50 and Sensex — Construction Methodology — free-float
    market cap weighting.
  - `03.05` Indian Market Timings, Circuits & Trading Sessions — pre-open,
    circuit filters vs. breakers, March 2020 example.
  - `03.06` T+1 Settlement and the Indian Clearing System — settlement
    cycle evolution, NSCCL/ICCL.
  - `03.07` FIIs, DIIs & Domestic Retail — Who Moves Nifty — SIP-driven
    DII resilience, 2013 Taper Tantrum contrast.
  - `03.08` Indian Derivatives Market (F&O) Overview — weekly index
    options, SEBI retail loss data.
  - `03.09` Indian Market Regulations — Insider Trading, Circuit Filters,
    Surveillance — UPSI, front-running, circular trading.
  - `03.10` Union Budget & RBI Policy — Their Effect on Indian Markets —
    surprise-vs-expectations framework, May 2022 surprise hike, module
    capstone.
- **44/353 planned files complete.** Starting Module 04: Global Market.

### 2026-08-04 — Module 04 Global Market: COMPLETE (8/8 lessons)
- Added `docs/04_Global_Market/_Index.md` and all 8 lessons:
  - `04.01` Major Global Exchanges — NYSE/NASDAQ/LSE/TSE/HKEX, the
    trading-day relay, Nikkei's 1989-2024 cycle.
  - `04.02` Global Market Trading Hours and Overlaps — session overlaps,
    London+NY as highest-liquidity window.
  - `04.03` How US Markets Influence Indian Markets — GIFT Nifty
    (ex-SGX Nifty), July 2023 migration.
  - `04.04` Currency Pairs and the Global FX Market — base/quote
    mechanics, USD/INR, 2013 Taper Tantrum.
  - `04.05` Global Indices Overview — S&P 500/Dow/Nasdaq/DAX/Nikkei,
    price- vs. free-float weighting.
  - `04.06` Correlation Between Global Markets — "correlations go to 1 in
    a crisis," March 2020 and 2008 GFC examples.
  - `04.07` Emerging Markets vs Developed Markets — MSCI/FTSE
    classification, India's EM status.
  - `04.08` How to Read a Global Macro Calendar — consensus-vs-actual
    framework, weekly habit-building, module capstone.
- **53/353 planned files complete.** Starting Module 05: Economics.

### 2026-08-04 — Module 05 Economics: COMPLETE (8/8 lessons)
- Added `docs/05_Economics/_Index.md` and all 8 lessons: `05.01` What Is
  Economics and Why Traders Need It, `05.02` Demand and Supply
  Fundamentals, `05.03` Inflation (demand-pull/cost-push, CPI, 1970s Great
  Inflation), `05.04` Interest Rates (discounting mechanism, 2022 growth
  stock repricing), `05.05` GDP and Economic Growth (C+I+G+NX, real vs.
  nominal), `05.06` Unemployment and Labor Markets (participation rate,
  US NFP), `05.07` Fiscal Policy vs Monetary Policy (RBI 2016 inflation
  targeting), `05.08` Business Cycles (module capstone synthesizing all
  prior lessons).
- **62/353 planned files complete.** Starting Module 06: Macroeconomics.

### 2026-08-04 — Module 06 Macroeconomics: COMPLETE (10/10 lessons)
- Added `docs/06_Macroeconomics/_Index.md` and all 10 lessons: `06.01`
  Central Banks Explained (RBI/Fed/ECB), `06.02` How Interest Rate
  Decisions Are Made (dot plot, 2013 Bernanke testimony), `06.03`
  Quantitative Easing and Tightening (Fed balance sheet 2008/2020),
  `06.04` Currency Devaluation and Exchange Rate Regimes (India's managed
  float), `06.05` Balance of Payments and CAD (2013 Fragile Five), `06.06`
  Global Liquidity Cycles and Risk-On/Risk-Off (2020-2022 full cycle),
  `06.07` Yield Curves and Inversion (2s10s spread), `06.08` Commodity
  Super-Cycles (2000s China-driven cycle), `06.09` Geopolitics and
  Markets (2022 Russia-Ukraine, US-China trade tensions), `06.10` India's
  Macro Framework (RBI's 2016 flexible inflation targeting, module
  capstone synthesizing all of Modules 05-06).
- **73/353 planned files complete.** Six modules now fully complete:
  Foundation, Market Structure, Indian Market, Global Market, Economics,
  Macroeconomics. Starting Module 07: Financial Statements.

### 2026-08-04 — Module 07 Financial Statements: started
- Added `docs/07_Financial_Statements/_Index.md` and `07.01` The Three
  Financial Statements — Overview (Income Statement/Balance Sheet/Cash
  Flow Statement framework, Enron and Satyam scandals as motivation).
- **75/353 planned files complete.**

### 2026-08-04 — Module 07: Lesson 07.02
- Added `07.02` Reading the Income Statement — Revenue→Gross Profit→
  Operating Profit (EBIT)→Net Profit cascade, margin ratios, Amazon's
  historical thin-margin reinvestment example.
- **76/353 planned files complete.**

### 2026-08-04 — Module 07: Lesson 07.03
- Added `07.03` Reading the Balance Sheet — Assets=Liabilities+Equity
  identity, current/non-current classification, Current Ratio, Debt-to-
  Equity Ratio, tangible book value, 2008 GFC leverage example.
- **77/353 planned files complete.**

### 2026-08-04 — Module 07 Financial Statements: COMPLETE (10/10 lessons)
- Added `07.05` How the Three Statements Connect, `07.06` Revenue
  Recognition and Earnings Quality (Enron/Satyam), `07.07` Debt, Equity &
  Capital Structure (leverage double-edge), `07.08` Depreciation,
  Amortization & Non-Cash Items (EBITDA), `07.09` Reading an Indian
  Annual Report (Auditor's opinion types), `07.10` Reading a US 10-K and
  10-Q (SEC EDGAR, Sarbanes-Oxley, module capstone).
- **84/353 planned files complete.** Seven modules now fully complete.
  Starting Module 08: Fundamental Analysis.

### 2026-08-04 — Module 08 Fundamental Analysis: COMPLETE (10/10 lessons)
- Added `docs/08_Fundamental_Analysis/_Index.md` and all 10 lessons:
  `08.01` What Is Fundamental Analysis (Benjamin Graham, Warren Buffett),
  `08.02` Top-Down vs Bottom-Up Analysis, `08.03` Profitability Ratios
  (ROE/ROA/ROCE, DuPont framework), `08.04` Liquidity and Solvency Ratios
  (Current/Quick Ratio, 2008 GFC), `08.05` Efficiency Ratios (Cash
  Conversion Cycle, Amazon), `08.06` EPS/P/E/PEG (dot-com bubble),
  `08.07` Competitive Moats (5 categories, Titan, Visa/Mastercard, Kodak),
  `08.08` Management Quality and Governance (Berkshire Hathaway, Satyam),
  `08.09` Industry Analysis (Porter's Five Forces, industry life cycle),
  `08.10` Screening Stocks Fundamentally (Screener.in, Finviz, module
  capstone).
- **95/353 planned files complete.** Eight modules now fully complete.
  Starting Module 09: Valuation.

### 2026-08-04 — Module 09 Valuation: COMPLETE (8/8 lessons)
- Added `docs/09_Valuation/_Index.md` and all 8 lessons: `09.01` What Is
  Valuation (price vs. value, Buffett), `09.02` Relative Valuation
  (P/E/P/B/EV-EBITDA), `09.03` DCF Fundamentals (WACC, terminal value),
  `09.04` Dividend Discount Model (Gordon Growth), `09.05` Growth vs
  Value Stocks (rate sensitivity, 2022 example), `09.06` Valuation Traps
  (Kodak), `09.07` Sum-of-the-Parts Valuation (Reliance, conglomerate
  discount), `09.08` Valuation in Market Cycles (multiple expansion/
  contraction, module capstone).
- **104/353 planned files complete.** Nine modules now fully complete —
  the entire fundamental-analysis arc (Modules 05-09) is done. Starting
  Module 10: Technical Analysis.

### 2026-08-04 — Module 10: started
- Added `docs/10_Technical_Analysis/_Index.md` and `10.01` What Is
  Technical Analysis and Does It Work (EMH debate, TA's three core
  assumptions, structure-reading value).
- **106/353 planned files complete.**

### 2026-08-04 — Module 10 Technical Analysis: COMPLETE (12/12 lessons)
- Added `10.02`-`10.12`: Dow Theory, Chart Types, Timeframes, Trendlines/
  Channels, Moving Averages, Momentum Oscillators (RSI/Stochastic/MACD),
  Volume Confirmation, Fibonacci, Divergence (regular/hidden), Multi-
  Indicator Confluence, and a synthesized 7-step TA Checklist (module
  capstone).
- **117/353 planned files complete.** Ten modules now fully complete.
  Starting Module 11: Candlesticks.

### 2026-08-04 — Module 11: started
- Added `docs/11_Candlesticks/_Index.md`, `11.01` Anatomy of a
  Candlestick, `11.02` Single Candlestick Patterns — Doji, Hammer,
  Shooting Star (Hammer vs. Hanging Man context lesson).
- **119/353 planned files complete.**

### 2026-08-04 — Module 11 Candlesticks: COMPLETE (10/10 lessons)
- Added `11.03`-`11.10`: Marubozu/Spinning Top, Engulfing/Harami,
  Piercing Line/Dark Cloud Cover, Morning/Evening Star, Three White
  Soldiers/Three Black Crows, Candlestick Patterns in Context (5-point
  contextual checklist synthesis), Japanese History (Dojima Rice
  Exchange, Munehisa Homma nuance), and Pattern Reliability (backtesting
  evidence, module capstone).
- **129/353 planned files complete.** Eleven modules now fully complete.
  Starting Module 12: Chart Patterns.

### 2026-08-04 — Module 12 Chart Patterns: COMPLETE (10/10 lessons)
- Added all 10 lessons: Head and Shoulders (neckline/CHOCH translation),
  Double/Triple Top-Bottom, Triangles, Flags/Pennants, Cup and Handle
  (O'Neil), Wedges (counter-intuitive slope), Rounding Top/Bottom,
  Broadening Formations, Pattern Failures/False Breakouts (module
  capstone).
- **140/353 planned files complete.** Twelve modules now fully complete.
  Starting Module 13: Price Action.

### 2026-08-04 — Module 13: started
- Added `docs/13_Price_Action/_Index.md` and `13.01` What Is Pure Price
  Action Trading (generalizing beyond named patterns, Al Brooks
  reference).
- **142/353 planned files complete.**

### 2026-08-04 — Module 13 Price Action: COMPLETE (10/10 lessons)
- Added `13.03`-`13.10`: Supply/Demand Zones, Breakouts vs Fakeouts,
  Pullbacks vs Reversals, Inside/Outside Bars, Key Levels, Range Trading,
  Trend-Following, and a synthesized Discretionary Playbook (module
  capstone, complementing `[10.12]`'s technical checklist).
- **151/353 planned files complete.** Thirteen modules now fully
  complete. Starting Module 14: Volume.

### 2026-08-04 — Module 14 Volume: COMPLETE (6/6 lessons)
- Added all 6 lessons: What Volume Really Tells You, Volume Spread
  Analysis (Tom Williams/Wyckoff lineage), Volume at Breakouts vs Ranges,
  Open Interest vs Volume (four-quadrant framework), Climactic Volume/
  Exhaustion (Wyckoff Selling/Buying Climax), and a synthesized
  Confirmation Checklist (module capstone, integrating with `[10.12]`
  and `[13.10]`).
- **158/353 planned files complete.** Fourteen modules now fully
  complete. Starting Module 15: Market Profile.

### 2026-08-04 — Module 15 Market Profile: COMPLETE (6/6 lessons)
- Added all 6 lessons: Introduction to Market Profile/TPO (Steidlmayer,
  CBOT, Auction Market Theory), Value Area/POC/Range, Profile Shapes
  (Normal/P/b/Trend Day), Initial Balance, Using Market Profile for
  Intraday Bias (open-type classification), and Composite Profiles
  (module capstone, connecting to `[02.08]`'s multi-timeframe framework).
- **165/353 planned files complete.** Fifteen modules now fully
  complete. Starting Module 16: Volume Profile.

### 2026-08-04 — Module 16 Volume Profile: COMPLETE (6/6 lessons)
- Added all 6 lessons: Introduction to Volume Profile (volume-at-price
  vs. time-at-price), Value Area High/Low/POC construction methodology,
  High Volume Nodes vs Low Volume Nodes (internal profile structure,
  connecting to `[13.03]`), Volume Profile vs Market Profile — Key
  Differences (full comparison synthesis), Session/Composite/Fixed Range
  Volume Profile configurations, and Trading Strategies Using Volume
  Profile (module capstone: Value Migration, LVN Target, and HVN
  Reaction Trading archetypes).
- **172/353 planned files complete.** Sixteen modules now fully
  complete. Starting Module 17: Wyckoff.

### 2026-08-04 — Module 17 Wyckoff: COMPLETE (8/8 lessons)
- Added all 8 lessons: Richard Wyckoff — History and Philosophy, The
  Three Laws of Wyckoff (Supply/Demand, Cause/Effect, Effort/Result),
  Accumulation Schematic (Phases A-E), Distribution Schematic (Phases
  A-E), Springs/Upthrusts/Tests, Composite Man Concept, Wyckoff in
  Modern Markets (applicability to algorithmic/electronic markets), and
  a module-capstone Wyckoff Case Study on a hypothetical, illustrative
  Indian stock ("Company XYZ Ltd.," explicitly fictional, consistent
  with the academy's no-stock-tips policy).
- **181/353 planned files complete.** Seventeen modules now fully
  complete. Starting Module 18: Smart Money Concepts.

### 2026-08-04 — Module 18 Smart Money Concepts: COMPLETE (8/8 lessons)
- Added all 8 lessons: What Are Smart Money Concepts (SMC) — direct
  Wyckoff lineage, Liquidity Pools (Buy-Side/Sell-Side), Order Blocks,
  Fair Value Gaps/Imbalances, Mitigation and Inducement, Premium and
  Discount Zones, SMC vs Classical Technical Analysis (full comparison
  table), and a module-capstone lesson on Criticisms and Limitations of
  SMC (retrospective bias, limited academic validation, commercial
  incentive distortion, subjective identification).
- **190/353 planned files complete.** Eighteen modules now fully
  complete. Starting Module 19: ICT.

### 2026-08-04 — Module 19 ICT: COMPLETE (8/8 lessons)
- Added all 8 lessons: Introduction to ICT Concepts (direct SMC/Wyckoff
  lineage), Market Maker Models (Buy/Sell), Kill Zones and Time-Based
  Trading, Optimal Trade Entry (OTE), Power of Three (Accumulation,
  Manipulation, Distribution), Judas Swing Concept, ICT Concepts
  Applied to Indian Index Futures (localization of US/London-centric
  Kill Zones, circuit-limit considerations), and a module-capstone
  lesson Evaluating ICT (evidentiary spectrum synthesis, completing the
  full Wyckoff-SMC-ICT arc across Modules 17-19).
- **199/353 planned files complete.** Nineteen modules now fully
  complete. Starting Module 20: Futures.

### 2026-08-04 — Module 20 Futures: COMPLETE (10/10 lessons)
- Added all 10 lessons: What Is a Futures Contract, Futures vs Forwards
  vs Spot, Contract Specifications (lot size/expiry/tick size), Margin/
  Mark-to-Market/Leverage, Basis/Contango/Backwardation, Rollover
  Mechanics (Indian F&O expiry cycle), Index Futures vs Stock Futures,
  Hedging with Futures, Speculation with Futures (asymmetric risk
  profile), and a module-capstone lesson on Commodity Futures Basics
  (MCX overview).
- **210/353 planned files complete.** Twenty modules now fully
  complete. Starting Module 21: Options.

### 2026-08-04 — Repository Scaffolding
- Added full directory structure: `docs/01_Foundation/` through
  `docs/40_Resources/`, plus `daily_learning/`, `weekly_tests/`,
  `monthly_exams/`, `progress_tracker/`, `mind_maps/`, `revision_guides/`,
  `market_journal/`, `templates/`, `worksheets/`, `simulation_exercises/`,
  `decision_trees/`.
- Added `MASTER_SKILL.md` — the teaching constitution governing every lesson.
- Added `CURRICULUM.md` — full syllabus map, ~353 planned files across 40
  modules.
- Added `LEARNING_PATH.md` — recommended student sequencing across 8 stages
  plus 3 specialization tracks.
- Added `TODO.md` — live build tracker.
- Added `README.md` — repository overview and progress table.
- Added `ROADMAP.md` — 10-milestone build plan.
- Added `CONTRIBUTING.md` — lesson-writing process and style guide.
- Added `LICENSE` (CC BY-NC-SA 4.0).
- Added `templates/LESSON_TEMPLATE.md`, `templates/QUIZ_TEMPLATE.md`,
  `templates/CASE_STUDY_TEMPLATE.md`.
- Added `progress_tracker/STUDENT_PROGRESS_TEMPLATE.md`.
- Added `market_journal/JOURNAL_TEMPLATE.md`.
- **Phase 0 (Repository Scaffolding) complete — 13 files.** Next up: Module
  01 Foundation, Lesson 01.01 "What Is a Financial Market."

---

*Entries are added chronologically as each lesson or infrastructure file is
generated. See `TODO.md` for the granular per-file status.*
