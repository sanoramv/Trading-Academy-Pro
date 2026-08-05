# INDEX.md — Complete Table of Contents

> A single, complete reference to every lesson, quiz, cheat sheet, flashcard
> deck, case study, worksheet/drill, glossary entry, and project in
> Trading-Academy-Pro — with estimated reading time, difficulty level, and
> prerequisites for each core lesson.
>
> **This file is distinct from, and complements:** `README.md` (project
> overview + build-progress table), `CURRICULUM.md` (syllabus map and
> planning source of truth), `LEARNING_PATH.md` (recommended student
> sequencing, with rationale), and `TODO.md` (live build/maintenance
> tracker). Use *this* file when you know roughly what you're looking for
> and want to jump straight to it, or when you want to see a lesson's
> prerequisites and estimated time before starting it.

**Generated from source data on 2026-08-05.** All titles, prerequisites,
and time estimates below are extracted directly from each file's own
metadata — not independently re-estimated — so this index stays accurate
as long as the underlying lessons are. If a lesson's Prerequisites or
`Estimated time` line changes, re-run the extraction (see
`CONTRIBUTING.md`'s Maintainer Checklist) rather than hand-editing this file.

**Coverage:** 270 core lessons (Modules 01–31) + 116 support-module files
(Modules 32–40) + 125 glossary entries = **386 total files** referenced below.

---

## How to Use This Index

1. **Browsing by topic:** Jump to a module section below (Table of Contents), or use your browser/editor's find function for a keyword.
2. **Checking readiness:** Every lesson row shows its `Prerequisites` — confirm you've covered those lesson IDs before starting.
3. **Planning study time:** The `Time` column is each lesson's own stated estimate (sum a module's column for a rough total).
4. **Difficulty levels** are assigned **per module**, not per lesson, using the tier definitions below — consistent with `ROADMAP.md`'s milestone groupings, not a separate, invented scale.

### Difficulty Legend

| Badge | Level | Modules | What it means |
|---|---|---|---|
| 🟢 | **Beginner** | 01–09 | Zero prior market knowledge assumed. Covers foundations, Indian/global market structure, economics, and how to read a company's financials. |
| 🟡 | **Intermediate** | 10–19 | Assumes Beginner-tier completion. Covers chart reading, candlesticks, patterns, volume/profile analysis, and institutional order-flow frameworks (Wyckoff/SMC/ICT). |
| 🔴 | **Advanced** | 20–31 | Assumes Beginner + Intermediate completion. Covers derivatives, risk management, position sizing, portfolio theory, psychology, algorithmic/quantitative trading, and historical case-study synthesis. |
| ⚪ | **Reference** | 32–40 | Usable at any level — daily-analysis templates, glossary, flashcards, cheat sheets, quizzes, assessments, practice drills, capstone projects, and further resources. |

### Table of Contents (Jump To)

**Core Curriculum:** [01](#module-01--foundation) · [02](#module-02--market-structure) · [03](#module-03--indian-market) · [04](#module-04--global-market) · [05](#module-05--economics) · [06](#module-06--macroeconomics) · [07](#module-07--financial-statements) · [08](#module-08--fundamental-analysis) · [09](#module-09--valuation) · [10](#module-10--technical-analysis) · [11](#module-11--candlesticks) · [12](#module-12--chart-patterns) · [13](#module-13--price-action) · [14](#module-14--volume) · [15](#module-15--market-profile) · [16](#module-16--volume-profile) · [17](#module-17--wyckoff) · [18](#module-18--smart-money-concepts) · [19](#module-19--ict) · [20](#module-20--futures) · [21](#module-21--options) · [22](#module-22--greeks) · [23](#module-23--volatility) · [24](#module-24--trading-strategies) · [25](#module-25--risk-management) · [26](#module-26--position-sizing) · [27](#module-27--portfolio-management) · [28](#module-28--trading-psychology) · [29](#module-29--algorithmic-trading) · [30](#module-30--quantitative-trading) · [31](#module-31--case-studies)

**Reference Modules:** [32 Daily Analysis](#module-32--daily-market-analysis) · [33 Glossary](#module-33--glossary) · [34 Flashcards](#module-34--flashcards) · [35 CheatSheets](#module-35--cheatsheets) · [36 Quizzes](#module-36--quizzes) · [37 Assessments](#module-37--assessments) · [38 Practice](#module-38--practice) · [39 Projects](#module-39--projects) · [40 Resources](#module-40--resources)

---

## Part 1 — Core Curriculum (Modules 01–31, 270 Lessons)

Each table's **Prerequisites** and **Next** columns link directly to the
cited lesson — this is the same cross-reference chain (`[XX.YY]`) used
throughout the lessons themselves, so following these links reproduces
the curriculum's actual dependency graph (verified cycle-free; see
`AUDIT_REPORT.md`'s "What Was Verified Clean" section).

### Module 01 — Foundation

[Module Index](docs/01_Foundation/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[01.01]` | [What Is a Financial Market](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md) | 🟢 Beginner | 35 min | — | [`[01.02]`](docs/01_Foundation/01.02_What_Is_Trading_vs_Investing.md) |
| `[01.02]` | [What Is Trading vs Investing](docs/01_Foundation/01.02_What_Is_Trading_vs_Investing.md) | 🟢 Beginner | 30 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md) | [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) |
| `[01.03]` | [Asset Classes Overview](docs/01_Foundation/01.03_Asset_Classes_Overview.md) | 🟢 Beginner | 35 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[01.02]`](docs/01_Foundation/01.02_What_Is_Trading_vs_Investing.md) | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) |
| `[01.04]` | [How Stock Exchanges Work](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) | 🟢 Beginner | 35 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) | [`[01.05]`](docs/01_Foundation/01.05_Market_Participants.md) |
| `[01.05]` | [Market Participants](docs/01_Foundation/01.05_Market_Participants.md) | 🟢 Beginner | 35 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) | [`[01.06]`](docs/01_Foundation/01.06_Primary_Market_vs_Secondary_Market.md) |
| `[01.06]` | [Primary Market vs Secondary Market](docs/01_Foundation/01.06_Primary_Market_vs_Secondary_Market.md) | 🟢 Beginner | 30 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) | [`[01.07]`](docs/01_Foundation/01.07_Order_Types_Explained.md) |
| `[01.07]` | [Order Types Explained](docs/01_Foundation/01.07_Order_Types_Explained.md) | 🟢 Beginner | 40 min | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) | [`[01.08]`](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md) |
| `[01.08]` | [How an Order Actually Executes](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md) | 🟢 Beginner | 35 min | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md), [`[01.07]`](docs/01_Foundation/01.07_Order_Types_Explained.md) | [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) |
| `[01.09]` | [Brokers, Depositories & Clearing Corporations](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) | 🟢 Beginner | 35 min | [`[01.08]`](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md) | [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) |
| `[01.10]` | [Reading Your First Stock Quote](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) | 🟢 Beginner | 30 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) | [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) |

### Module 02 — Market Structure

[Module Index](docs/02_Market_Structure/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[02.01]` | [What Is Market Structure](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) | 🟢 Beginner | 35 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) | [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) |
| `[02.02]` | [Trend, Range, and Structure Basics](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | 🟢 Beginner | 35 min | [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) | [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) |
| `[02.03]` | [Higher Highs, Higher Lows, Lower Highs, Lower Lows](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) | 🟢 Beginner | 30 min | [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) |
| `[02.04]` | [Support and Resistance — First Principles](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | 🟢 Beginner | 35 min | [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md), [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) | [`[02.05]`](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md) |
| `[02.05]` | [Break of Structure (BOS) vs Change of Character (CHOCH)](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md) | 🟢 Beginner | 35 min | [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) |
| `[02.06]` | [Liquidity — What It Really Means](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) | 🟢 Beginner | 35 min | [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[02.05]`](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md) | [`[02.07]`](docs/02_Market_Structure/02.07_Swing_Points_and_Fractals.md) |
| `[02.07]` | [Swing Points and Fractals](docs/02_Market_Structure/02.07_Swing_Points_and_Fractals.md) | 🟢 Beginner | 30 min | [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md), [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) | [`[02.08]`](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md) |
| `[02.08]` | [Multi-Timeframe Structure Analysis](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md) | 🟢 Beginner | 35 min | [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md), [`[02.07]`](docs/02_Market_Structure/02.07_Swing_Points_and_Fractals.md) | [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) |

### Module 03 — Indian Market

[Module Index](docs/03_Indian_Market/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[03.01]` | [History of Indian Stock Markets (BSE 1875 to NSE 1992)](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) | 🟢 Beginner | 35 min | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md), [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) | [`[03.02]`](docs/03_Indian_Market/03.02_SEBI_Role_Powers_and_Investor_Protection.md) |
| `[03.02]` | [SEBI — Role, Powers, and Investor Protection](docs/03_Indian_Market/03.02_SEBI_Role_Powers_and_Investor_Protection.md) | 🟢 Beginner | 30 min | [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) | [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) |
| `[03.03]` | [NSE vs BSE — Structure and Indices](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) | 🟢 Beginner | 30 min | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md), [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) | [`[03.04]`](docs/03_Indian_Market/03.04_Nifty_50_and_Sensex_Construction_Methodology.md) |
| `[03.04]` | [Nifty 50 and Sensex — Construction Methodology](docs/03_Indian_Market/03.04_Nifty_50_and_Sensex_Construction_Methodology.md) | 🟢 Beginner | 35 min | [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) | [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) |
| `[03.05]` | [Indian Market Timings, Circuits & Trading Sessions](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) | 🟢 Beginner | 30 min | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md), [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) | [`[03.06]`](docs/03_Indian_Market/03.06_T+1_Settlement_and_the_Indian_Clearing_System.md) |
| `[03.06]` | [T+1 Settlement and the Indian Clearing System](docs/03_Indian_Market/03.06_T+1_Settlement_and_the_Indian_Clearing_System.md) | 🟢 Beginner | 30 min | [`[01.08]`](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md), [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) | [`[03.07]`](docs/03_Indian_Market/03.07_FIIs_DIIs_and_Domestic_Retail_Who_Moves_Nifty.md) |
| `[03.07]` | [FIIs, DIIs & Domestic Retail — Who Moves Nifty](docs/03_Indian_Market/03.07_FIIs_DIIs_and_Domestic_Retail_Who_Moves_Nifty.md) | 🟢 Beginner | 35 min | [`[01.05]`](docs/01_Foundation/01.05_Market_Participants.md), [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) | [`[03.08]`](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md) |
| `[03.08]` | [Indian Derivatives Market (F&O) Overview](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md) | 🟢 Beginner | 35 min | [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md), [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) | [`[03.09]`](docs/03_Indian_Market/03.09_Indian_Market_Regulations_Insider_Trading_Circuit_Filters_Surveillance.md) |
| `[03.09]` | [Indian Market Regulations — Insider Trading, Circuit Filters, Surveillance](docs/03_Indian_Market/03.09_Indian_Market_Regulations_Insider_Trading_Circuit_Filters_Surveillance.md) | 🟢 Beginner | 35 min | [`[03.02]`](docs/03_Indian_Market/03.02_SEBI_Role_Powers_and_Investor_Protection.md), [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) | [`[03.10]`](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md) |
| `[03.10]` | [Union Budget & RBI Policy — Their Effect on Indian Markets](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md) | 🟢 Beginner | 40 min | [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md), [`[03.09]`](docs/03_Indian_Market/03.09_Indian_Market_Regulations_Insider_Trading_Circuit_Filters_Surveillance.md), [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) | [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md) |

### Module 04 — Global Market

[Module Index](docs/04_Global_Market/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[04.01]` | [Major Global Exchanges](docs/04_Global_Market/04.01_Major_Global_Exchanges.md) | 🟢 Beginner | 30 min | [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md), [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) | [`[04.02]`](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) |
| `[04.02]` | [Global Market Trading Hours and Overlaps](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) | 🟢 Beginner | 30 min | [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md), [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) | [`[04.03]`](docs/04_Global_Market/04.03_How_US_Markets_Influence_Indian_Markets.md) |
| `[04.03]` | [How US Markets Influence Indian Markets (SGX Nifty / GIFT Nifty)](docs/04_Global_Market/04.03_How_US_Markets_Influence_Indian_Markets.md) | 🟢 Beginner | 30 min | [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md), [`[04.02]`](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) | [`[04.04]`](docs/04_Global_Market/04.04_Currency_Pairs_and_the_Global_FX_Market.md) |
| `[04.04]` | [Currency Pairs and the Global FX Market](docs/04_Global_Market/04.04_Currency_Pairs_and_the_Global_FX_Market.md) | 🟢 Beginner | 35 min | [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md), [`[04.02]`](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) | [`[04.05]`](docs/04_Global_Market/04.05_Global_Indices_Overview.md) |
| `[04.05]` | [Global Indices Overview (S&P 500, Dow, Nasdaq, DAX, Nikkei)](docs/04_Global_Market/04.05_Global_Indices_Overview.md) | 🟢 Beginner | 30 min | [`[03.04]`](docs/03_Indian_Market/03.04_Nifty_50_and_Sensex_Construction_Methodology.md), [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md) | [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) |
| `[04.06]` | [Correlation Between Global Markets](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) | 🟢 Beginner | 30 min | [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md), [`[04.05]`](docs/04_Global_Market/04.05_Global_Indices_Overview.md) | [`[04.07]`](docs/04_Global_Market/04.07_Emerging_Markets_vs_Developed_Markets.md) |
| `[04.07]` | [Emerging Markets vs Developed Markets](docs/04_Global_Market/04.07_Emerging_Markets_vs_Developed_Markets.md) | 🟢 Beginner | 30 min | [`[03.07]`](docs/03_Indian_Market/03.07_FIIs_DIIs_and_Domestic_Retail_Who_Moves_Nifty.md), [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) | [`[04.08]`](docs/04_Global_Market/04.08_How_to_Read_a_Global_Macro_Calendar.md) |
| `[04.08]` | [How to Read a Global Macro Calendar](docs/04_Global_Market/04.08_How_to_Read_a_Global_Macro_Calendar.md) | 🟢 Beginner | 35 min | [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md), [`[04.07]`](docs/04_Global_Market/04.07_Emerging_Markets_vs_Developed_Markets.md), [`[03.10]`](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md) | [`[05.01]`](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md) |

### Module 05 — Economics

[Module Index](docs/05_Economics/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[05.01]` | [What Is Economics and Why Traders Need It](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md) | 🟢 Beginner | 30 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md) | [`[05.02]`](docs/05_Economics/05.02_Demand_and_Supply_Fundamentals_for_Markets.md) |
| `[05.02]` | [Demand and Supply Fundamentals for Markets](docs/05_Economics/05.02_Demand_and_Supply_Fundamentals_for_Markets.md) | 🟢 Beginner | 30 min | [`[05.01]`](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md), [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) | [`[05.03]`](docs/05_Economics/05.03_Inflation_Causes_Types_and_Measurement.md) |
| `[05.03]` | [Inflation — Causes, Types, and Measurement](docs/05_Economics/05.03_Inflation_Causes_Types_and_Measurement.md) | 🟢 Beginner | 35 min | [`[05.02]`](docs/05_Economics/05.02_Demand_and_Supply_Fundamentals_for_Markets.md) | [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) |
| `[05.04]` | [Interest Rates — What They Are and Why They Move Markets](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) | 🟢 Beginner | 35 min | [`[05.03]`](docs/05_Economics/05.03_Inflation_Causes_Types_and_Measurement.md) | [`[05.05]`](docs/05_Economics/05.05_GDP_and_Economic_Growth_Explained.md) |
| `[05.05]` | [GDP and Economic Growth Explained](docs/05_Economics/05.05_GDP_and_Economic_Growth_Explained.md) | 🟢 Beginner | 30 min | [`[05.01]`](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md) | [`[05.06]`](docs/05_Economics/05.06_Unemployment_and_Labor_Markets.md) |
| `[05.06]` | [Unemployment and Labor Markets](docs/05_Economics/05.06_Unemployment_and_Labor_Markets.md) | 🟢 Beginner | 30 min | [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) | [`[05.07]`](docs/05_Economics/05.07_Fiscal_Policy_vs_Monetary_Policy.md) |
| `[05.07]` | [Fiscal Policy vs Monetary Policy](docs/05_Economics/05.07_Fiscal_Policy_vs_Monetary_Policy.md) | 🟢 Beginner | 30 min | [`[03.10]`](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md), [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) | [`[05.08]`](docs/05_Economics/05.08_Business_Cycles_Expansion_Peak_Recession_Trough.md) |
| `[05.08]` | [Business Cycles — Expansion, Peak, Recession, Trough](docs/05_Economics/05.08_Business_Cycles_Expansion_Peak_Recession_Trough.md) | 🟢 Beginner | 35 min | [`[05.01]`](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md), [`[05.07]`](docs/05_Economics/05.07_Fiscal_Policy_vs_Monetary_Policy.md) | [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md) |

### Module 06 — Macroeconomics

[Module Index](docs/06_Macroeconomics/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[06.01]` | [Central Banks Explained (Federal Reserve, RBI, ECB)](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md) | 🟢 Beginner | 35 min | [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md), [`[05.07]`](docs/05_Economics/05.07_Fiscal_Policy_vs_Monetary_Policy.md) | [`[06.02]`](docs/06_Macroeconomics/06.02_How_Interest_Rate_Decisions_Are_Made.md) |
| `[06.02]` | [How Interest Rate Decisions Are Made](docs/06_Macroeconomics/06.02_How_Interest_Rate_Decisions_Are_Made.md) | 🟢 Beginner | 30 min | [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md) | [`[06.03]`](docs/06_Macroeconomics/06.03_Quantitative_Easing_and_Quantitative_Tightening.md) |
| `[06.03]` | [Quantitative Easing and Quantitative Tightening](docs/06_Macroeconomics/06.03_Quantitative_Easing_and_Quantitative_Tightening.md) | 🟢 Beginner | 35 min | [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md), [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) | [`[06.04]`](docs/06_Macroeconomics/06.04_Currency_Devaluation_and_Exchange_Rate_Regimes.md) |
| `[06.04]` | [Currency Devaluation and Exchange Rate Regimes](docs/06_Macroeconomics/06.04_Currency_Devaluation_and_Exchange_Rate_Regimes.md) | 🟢 Beginner | 30 min | [`[04.04]`](docs/04_Global_Market/04.04_Currency_Pairs_and_the_Global_FX_Market.md), [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md) | [`[06.05]`](docs/06_Macroeconomics/06.05_Balance_of_Payments_and_Current_Account_Deficit.md) |
| `[06.05]` | [Balance of Payments and Current Account Deficit](docs/06_Macroeconomics/06.05_Balance_of_Payments_and_Current_Account_Deficit.md) | 🟢 Beginner | 30 min | [`[06.04]`](docs/06_Macroeconomics/06.04_Currency_Devaluation_and_Exchange_Rate_Regimes.md), [`[04.04]`](docs/04_Global_Market/04.04_Currency_Pairs_and_the_Global_FX_Market.md) | [`[06.06]`](docs/06_Macroeconomics/06.06_Global_Liquidity_Cycles_and_Risk_On_Risk_Off.md) |
| `[06.06]` | [Global Liquidity Cycles and Risk-On/Risk-Off](docs/06_Macroeconomics/06.06_Global_Liquidity_Cycles_and_Risk_On_Risk_Off.md) | 🟢 Beginner | 30 min | [`[06.03]`](docs/06_Macroeconomics/06.03_Quantitative_Easing_and_Quantitative_Tightening.md), [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) | [`[06.07]`](docs/06_Macroeconomics/06.07_Yield_Curves_and_What_Inversion_Means.md) |
| `[06.07]` | [Yield Curves and What Inversion Means](docs/06_Macroeconomics/06.07_Yield_Curves_and_What_Inversion_Means.md) | 🟢 Beginner | 30 min | [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md), [`[05.08]`](docs/05_Economics/05.08_Business_Cycles_Expansion_Peak_Recession_Trough.md) | [`[06.08]`](docs/06_Macroeconomics/06.08_Commodity_Super_Cycles_and_Macro_Trading.md) |
| `[06.08]` | [Commodity Super-Cycles and Macro Trading](docs/06_Macroeconomics/06.08_Commodity_Super_Cycles_and_Macro_Trading.md) | 🟢 Beginner | 30 min | [`[05.02]`](docs/05_Economics/05.02_Demand_and_Supply_Fundamentals_for_Markets.md), [`[06.05]`](docs/06_Macroeconomics/06.05_Balance_of_Payments_and_Current_Account_Deficit.md) | [`[06.09]`](docs/06_Macroeconomics/06.09_Geopolitics_and_Markets.md) |
| `[06.09]` | [Geopolitics and Markets (Wars, Sanctions, Trade Deals)](docs/06_Macroeconomics/06.09_Geopolitics_and_Markets.md) | 🟢 Beginner | 30 min | [`[06.08]`](docs/06_Macroeconomics/06.08_Commodity_Super_Cycles_and_Macro_Trading.md), [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) | [`[06.10]`](docs/06_Macroeconomics/06.10_Indias_Macro_Framework_RBI_Inflation_Targeting.md) |
| `[06.10]` | [India's Macro Framework — RBI's Inflation Targeting Regime](docs/06_Macroeconomics/06.10_Indias_Macro_Framework_RBI_Inflation_Targeting.md) | 🟢 Beginner | 35 min | [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md), [`[06.09]`](docs/06_Macroeconomics/06.09_Geopolitics_and_Markets.md), [`[05.07]`](docs/05_Economics/05.07_Fiscal_Policy_vs_Monetary_Policy.md) | [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md) |

### Module 07 — Financial Statements

[Module Index](docs/07_Financial_Statements/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[07.01]` | [The Three Financial Statements — Overview](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md) | 🟢 Beginner | 35 min | [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md), [`[05.01]`](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md) | [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md) |
| `[07.02]` | [Reading the Income Statement](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md) | 🟢 Beginner | 35 min | [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md) | [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md) |
| `[07.03]` | [Reading the Balance Sheet](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md) | 🟢 Beginner | 35 min | [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md), [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md) | [`[07.04]`](docs/07_Financial_Statements/07.04_Reading_the_Cash_Flow_Statement.md) |
| `[07.04]` | [Reading the Cash Flow Statement](docs/07_Financial_Statements/07.04_Reading_the_Cash_Flow_Statement.md) | 🟢 Beginner | 35 min | [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md), [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md) | [`[07.05]`](docs/07_Financial_Statements/07.05_How_the_Three_Statements_Connect.md) |
| `[07.05]` | [How the Three Statements Connect](docs/07_Financial_Statements/07.05_How_the_Three_Statements_Connect.md) | 🟢 Beginner | 35 min | [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md), [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md), [`[07.04]`](docs/07_Financial_Statements/07.04_Reading_the_Cash_Flow_Statement.md) | [`[07.06]`](docs/07_Financial_Statements/07.06_Revenue_Recognition_and_Earnings_Quality.md) |
| `[07.06]` | [Revenue Recognition and Earnings Quality](docs/07_Financial_Statements/07.06_Revenue_Recognition_and_Earnings_Quality.md) | 🟢 Beginner | 35 min | [`[07.05]`](docs/07_Financial_Statements/07.05_How_the_Three_Statements_Connect.md) | [`[07.07]`](docs/07_Financial_Statements/07.07_Debt_Equity_and_Capital_Structure.md) |
| `[07.07]` | [Debt, Equity & Capital Structure on the Balance Sheet](docs/07_Financial_Statements/07.07_Debt_Equity_and_Capital_Structure.md) | 🟢 Beginner | 30 min | [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md), [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) | [`[07.08]`](docs/07_Financial_Statements/07.08_Depreciation_Amortization_and_Non_Cash_Items.md) |
| `[07.08]` | [Depreciation, Amortization & Non-Cash Items](docs/07_Financial_Statements/07.08_Depreciation_Amortization_and_Non_Cash_Items.md) | 🟢 Beginner | 30 min | [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md), [`[07.04]`](docs/07_Financial_Statements/07.04_Reading_the_Cash_Flow_Statement.md) | [`[07.09]`](docs/07_Financial_Statements/07.09_Reading_an_Indian_Annual_Report.md) |
| `[07.09]` | [Reading an Indian Annual Report (BSE/NSE Filings)](docs/07_Financial_Statements/07.09_Reading_an_Indian_Annual_Report.md) | 🟢 Beginner | 40 min | [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md), [`[07.08]`](docs/07_Financial_Statements/07.08_Depreciation_Amortization_and_Non_Cash_Items.md) | [`[07.10]`](docs/07_Financial_Statements/07.10_Reading_a_US_10K_and_10Q.md) |
| `[07.10]` | [Reading a US 10-K and 10-Q](docs/07_Financial_Statements/07.10_Reading_a_US_10K_and_10Q.md) | 🟢 Beginner | 40 min | [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md), [`[07.09]`](docs/07_Financial_Statements/07.09_Reading_an_Indian_Annual_Report.md), [`[07.09]`](docs/07_Financial_Statements/07.09_Reading_an_Indian_Annual_Report.md) | [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) |

### Module 08 — Fundamental Analysis

[Module Index](docs/08_Fundamental_Analysis/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[08.01]` | [What Is Fundamental Analysis](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) | 🟢 Beginner | 30 min | [`[01.02]`](docs/01_Foundation/01.02_What_Is_Trading_vs_Investing.md) | [`[08.02]`](docs/08_Fundamental_Analysis/08.02_Top_Down_vs_Bottom_Up_Analysis.md) |
| `[08.02]` | [Top-Down vs Bottom-Up Analysis](docs/08_Fundamental_Analysis/08.02_Top_Down_vs_Bottom_Up_Analysis.md) | 🟢 Beginner | 30 min | [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) | [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) |
| `[08.03]` | [Key Financial Ratios — Profitability](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) | 🟢 Beginner | 35 min | [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md), [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md), [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) | [`[08.04]`](docs/08_Fundamental_Analysis/08.04_Key_Financial_Ratios_Liquidity_and_Solvency.md) |
| `[08.04]` | [Key Financial Ratios — Liquidity and Solvency](docs/08_Fundamental_Analysis/08.04_Key_Financial_Ratios_Liquidity_and_Solvency.md) | 🟢 Beginner | 30 min | [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md), [`[07.07]`](docs/07_Financial_Statements/07.07_Debt_Equity_and_Capital_Structure.md) | [`[08.05]`](docs/08_Fundamental_Analysis/08.05_Key_Financial_Ratios_Efficiency.md) |
| `[08.05]` | [Key Financial Ratios — Efficiency](docs/08_Fundamental_Analysis/08.05_Key_Financial_Ratios_Efficiency.md) | 🟢 Beginner | 30 min | [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md), [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md) | [`[08.06]`](docs/08_Fundamental_Analysis/08.06_EPS_PE_and_Growth_Metrics.md) |
| `[08.06]` | [Earnings Per Share, P/E, and Growth Metrics](docs/08_Fundamental_Analysis/08.06_EPS_PE_and_Growth_Metrics.md) | 🟢 Beginner | 35 min | [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md), [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) | [`[08.07]`](docs/08_Fundamental_Analysis/08.07_Competitive_Moats_and_Qualitative_Analysis.md) |
| `[08.07]` | [Competitive Moats and Qualitative Analysis](docs/08_Fundamental_Analysis/08.07_Competitive_Moats_and_Qualitative_Analysis.md) | 🟢 Beginner | 35 min | [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md), [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) | [`[08.08]`](docs/08_Fundamental_Analysis/08.08_Management_Quality_and_Corporate_Governance.md) |
| `[08.08]` | [Management Quality and Corporate Governance](docs/08_Fundamental_Analysis/08.08_Management_Quality_and_Corporate_Governance.md) | 🟢 Beginner | 30 min | [`[08.07]`](docs/08_Fundamental_Analysis/08.07_Competitive_Moats_and_Qualitative_Analysis.md), [`[07.09]`](docs/07_Financial_Statements/07.09_Reading_an_Indian_Annual_Report.md) | [`[08.09]`](docs/08_Fundamental_Analysis/08.09_Industry_and_Sector_Analysis_Framework.md) |
| `[08.09]` | [Industry and Sector Analysis Framework](docs/08_Fundamental_Analysis/08.09_Industry_and_Sector_Analysis_Framework.md) | 🟢 Beginner | 30 min | [`[08.02]`](docs/08_Fundamental_Analysis/08.02_Top_Down_vs_Bottom_Up_Analysis.md), [`[08.07]`](docs/08_Fundamental_Analysis/08.07_Competitive_Moats_and_Qualitative_Analysis.md) | [`[08.10]`](docs/08_Fundamental_Analysis/08.10_Screening_Stocks_Fundamentally.md) |
| `[08.10]` | [Screening Stocks Fundamentally (India & US)](docs/08_Fundamental_Analysis/08.10_Screening_Stocks_Fundamentally.md) | 🟢 Beginner | 40 min | [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md), [`[08.09]`](docs/08_Fundamental_Analysis/08.09_Industry_and_Sector_Analysis_Framework.md) | [`[09.01]`](docs/09_Valuation/09.01_What_Is_Valuation_and_Why_It_Matters.md) |

### Module 09 — Valuation

[Module Index](docs/09_Valuation/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[09.01]` | [What Is Valuation and Why It Matters](docs/09_Valuation/09.01_What_Is_Valuation_and_Why_It_Matters.md) | 🟢 Beginner | 30 min | — | [`[09.02]`](docs/09_Valuation/09.02_Relative_Valuation_PE_PB_EV_EBITDA.md) |
| `[09.02]` | [Relative Valuation — P/E, P/B, EV/EBITDA](docs/09_Valuation/09.02_Relative_Valuation_PE_PB_EV_EBITDA.md) | 🟢 Beginner | 35 min | [`[08.06]`](docs/08_Fundamental_Analysis/08.06_EPS_PE_and_Growth_Metrics.md), [`[07.08]`](docs/07_Financial_Statements/07.08_Depreciation_Amortization_and_Non_Cash_Items.md) | [`[09.03]`](docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md) |
| `[09.03]` | [Discounted Cash Flow (DCF) Fundamentals](docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md) | 🟢 Beginner | 40 min | [`[07.04]`](docs/07_Financial_Statements/07.04_Reading_the_Cash_Flow_Statement.md), [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md), [`[09.01]`](docs/09_Valuation/09.01_What_Is_Valuation_and_Why_It_Matters.md) | [`[09.04]`](docs/09_Valuation/09.04_Dividend_Discount_Model.md) |
| `[09.04]` | [Dividend Discount Model](docs/09_Valuation/09.04_Dividend_Discount_Model.md) | 🟢 Beginner | 30 min | [`[09.03]`](docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md) | [`[09.05]`](docs/09_Valuation/09.05_Valuing_Growth_vs_Value_Stocks.md) |
| `[09.05]` | [Valuing Growth vs Value Stocks](docs/09_Valuation/09.05_Valuing_Growth_vs_Value_Stocks.md) | 🟢 Beginner | 30 min | [`[09.03]`](docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md), [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) | [`[09.06]`](docs/09_Valuation/09.06_Valuation_Traps_and_Common_Mistakes.md) |
| `[09.06]` | [Valuation Traps and Common Mistakes](docs/09_Valuation/09.06_Valuation_Traps_and_Common_Mistakes.md) | 🟢 Beginner | 30 min | [`[09.02]`](docs/09_Valuation/09.02_Relative_Valuation_PE_PB_EV_EBITDA.md), [`[08.09]`](docs/08_Fundamental_Analysis/08.09_Industry_and_Sector_Analysis_Framework.md) | [`[09.07]`](docs/09_Valuation/09.07_Sum_of_the_Parts_Valuation.md) |
| `[09.07]` | [Sum-of-the-Parts Valuation](docs/09_Valuation/09.07_Sum_of_the_Parts_Valuation.md) | 🟢 Beginner | 30 min | [`[09.02]`](docs/09_Valuation/09.02_Relative_Valuation_PE_PB_EV_EBITDA.md), [`[09.03]`](docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md) | [`[09.08]`](docs/09_Valuation/09.08_Valuation_in_Different_Market_Cycles.md) |
| `[09.08]` | [Valuation in Different Market Cycles](docs/09_Valuation/09.08_Valuation_in_Different_Market_Cycles.md) | 🟢 Beginner | 35 min | [`[09.01]`](docs/09_Valuation/09.01_What_Is_Valuation_and_Why_It_Matters.md), [`[09.07]`](docs/09_Valuation/09.07_Sum_of_the_Parts_Valuation.md), [`[05.08]`](docs/05_Economics/05.08_Business_Cycles_Expansion_Peak_Recession_Trough.md) | [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) |

### Module 10 — Technical Analysis

[Module Index](docs/10_Technical_Analysis/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[10.01]` | [What Is Technical Analysis and Does It Work](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) | 🟡 Intermediate | 35 min | [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) | [`[10.02]`](docs/10_Technical_Analysis/10.02_Dow_Theory.md) |
| `[10.02]` | [Dow Theory — The Foundation of TA](docs/10_Technical_Analysis/10.02_Dow_Theory.md) | 🟡 Intermediate | 35 min | [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[10.03]`](docs/10_Technical_Analysis/10.03_Types_of_Charts.md) |
| `[10.03]` | [Types of Charts (Line, Bar, Candlestick, Renko, Heikin-Ashi)](docs/10_Technical_Analysis/10.03_Types_of_Charts.md) | 🟡 Intermediate | 30 min | [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md), [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) | [`[10.04]`](docs/10_Technical_Analysis/10.04_Timeframes_and_How_to_Choose_One.md) |
| `[10.04]` | [Timeframes and How to Choose One](docs/10_Technical_Analysis/10.04_Timeframes_and_How_to_Choose_One.md) | 🟡 Intermediate | 30 min | [`[02.08]`](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md), [`[10.03]`](docs/10_Technical_Analysis/10.03_Types_of_Charts.md) | [`[10.05]`](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md) |
| `[10.05]` | [Trendlines and Channels](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md) | 🟡 Intermediate | 30 min | [`[02.07]`](docs/02_Market_Structure/02.07_Swing_Points_and_Fractals.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | [`[10.06]`](docs/10_Technical_Analysis/10.06_Moving_Averages_SMA_EMA_WMA.md) |
| `[10.06]` | [Moving Averages — SMA, EMA, WMA](docs/10_Technical_Analysis/10.06_Moving_Averages_SMA_EMA_WMA.md) | 🟡 Intermediate | 35 min | [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md), [`[10.05]`](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md) | [`[10.07]`](docs/10_Technical_Analysis/10.07_Momentum_Oscillators_RSI_Stochastic_MACD.md) |
| `[10.07]` | [Momentum Oscillators — RSI, Stochastic, MACD](docs/10_Technical_Analysis/10.07_Momentum_Oscillators_RSI_Stochastic_MACD.md) | 🟡 Intermediate | 35 min | [`[10.06]`](docs/10_Technical_Analysis/10.06_Moving_Averages_SMA_EMA_WMA.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[10.08]`](docs/10_Technical_Analysis/10.08_Volume_as_a_Confirming_Tool.md) |
| `[10.08]` | [Volume as a Confirming Tool](docs/10_Technical_Analysis/10.08_Volume_as_a_Confirming_Tool.md) | 🟡 Intermediate | 30 min | [`[10.02]`](docs/10_Technical_Analysis/10.02_Dow_Theory.md), [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) | [`[10.09]`](docs/10_Technical_Analysis/10.09_Fibonacci_Retracement_and_Extension.md) |
| `[10.09]` | [Fibonacci Retracement and Extension](docs/10_Technical_Analysis/10.09_Fibonacci_Retracement_and_Extension.md) | 🟡 Intermediate | 30 min | [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[10.05]`](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md) | [`[10.10]`](docs/10_Technical_Analysis/10.10_Divergence_Regular_and_Hidden.md) |
| `[10.10]` | [Divergence — Regular and Hidden](docs/10_Technical_Analysis/10.10_Divergence_Regular_and_Hidden.md) | 🟡 Intermediate | 30 min | [`[10.07]`](docs/10_Technical_Analysis/10.07_Momentum_Oscillators_RSI_Stochastic_MACD.md), [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) | [`[10.11]`](docs/10_Technical_Analysis/10.11_Multi_Indicator_Confluence_and_Its_Pitfalls.md) |
| `[10.11]` | [Multi-Indicator Confluence and Its Pitfalls](docs/10_Technical_Analysis/10.11_Multi_Indicator_Confluence_and_Its_Pitfalls.md) | 🟡 Intermediate | 30 min | [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md), [`[10.10]`](docs/10_Technical_Analysis/10.10_Divergence_Regular_and_Hidden.md) | [`[10.12]`](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md) |
| `[10.12]` | [Building a Technical Analysis Checklist](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md) | 🟡 Intermediate | 40 min | [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md), [`[10.11]`](docs/10_Technical_Analysis/10.11_Multi_Indicator_Confluence_and_Its_Pitfalls.md) | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md) |

### Module 11 — Candlesticks

[Module Index](docs/11_Candlesticks/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[11.01]` | [Anatomy of a Candlestick](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md) | 🟡 Intermediate | 30 min | [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md), [`[10.03]`](docs/10_Technical_Analysis/10.03_Types_of_Charts.md) | [`[11.02]`](docs/11_Candlesticks/11.02_Single_Candlestick_Patterns_Doji_Hammer_Shooting_Star.md) |
| `[11.02]` | [Single Candlestick Patterns — Doji, Hammer, Shooting Star](docs/11_Candlesticks/11.02_Single_Candlestick_Patterns_Doji_Hammer_Shooting_Star.md) | 🟡 Intermediate | 35 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | [`[11.03]`](docs/11_Candlesticks/11.03_Single_Candlestick_Patterns_Marubozu_Spinning_Top.md) |
| `[11.03]` | [Single Candlestick Patterns — Marubozu, Spinning Top](docs/11_Candlesticks/11.03_Single_Candlestick_Patterns_Marubozu_Spinning_Top.md) | 🟡 Intermediate | 30 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[11.02]`](docs/11_Candlesticks/11.02_Single_Candlestick_Patterns_Doji_Hammer_Shooting_Star.md) | [`[11.04]`](docs/11_Candlesticks/11.04_Two_Candle_Patterns_Engulfing_Harami.md) |
| `[11.04]` | [Two-Candle Patterns — Engulfing, Harami](docs/11_Candlesticks/11.04_Two_Candle_Patterns_Engulfing_Harami.md) | 🟡 Intermediate | 30 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[11.03]`](docs/11_Candlesticks/11.03_Single_Candlestick_Patterns_Marubozu_Spinning_Top.md) | [`[11.05]`](docs/11_Candlesticks/11.05_Two_Candle_Patterns_Piercing_Line_Dark_Cloud_Cover.md) |
| `[11.05]` | [Two-Candle Patterns — Piercing Line, Dark Cloud Cover](docs/11_Candlesticks/11.05_Two_Candle_Patterns_Piercing_Line_Dark_Cloud_Cover.md) | 🟡 Intermediate | 30 min | [`[11.04]`](docs/11_Candlesticks/11.04_Two_Candle_Patterns_Engulfing_Harami.md) | [`[11.06]`](docs/11_Candlesticks/11.06_Three_Candle_Patterns_Morning_Star_Evening_Star.md) |
| `[11.06]` | [Three-Candle Patterns — Morning Star, Evening Star](docs/11_Candlesticks/11.06_Three_Candle_Patterns_Morning_Star_Evening_Star.md) | 🟡 Intermediate | 30 min | [`[11.04]`](docs/11_Candlesticks/11.04_Two_Candle_Patterns_Engulfing_Harami.md), [`[11.02]`](docs/11_Candlesticks/11.02_Single_Candlestick_Patterns_Doji_Hammer_Shooting_Star.md) | [`[11.07]`](docs/11_Candlesticks/11.07_Three_Candle_Patterns_Three_White_Soldiers_Three_Black_Crows.md) |
| `[11.07]` | [Three-Candle Patterns — Three White Soldiers, Three Black Crows](docs/11_Candlesticks/11.07_Three_Candle_Patterns_Three_White_Soldiers_Three_Black_Crows.md) | 🟡 Intermediate | 30 min | [`[11.06]`](docs/11_Candlesticks/11.06_Three_Candle_Patterns_Morning_Star_Evening_Star.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[11.08]`](docs/11_Candlesticks/11.08_Candlestick_Patterns_in_Context.md) |
| `[11.08]` | [Candlestick Patterns in Context (Why Location Matters More Than Shape)](docs/11_Candlesticks/11.08_Candlestick_Patterns_in_Context.md) | 🟡 Intermediate | 35 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[11.07]`](docs/11_Candlesticks/11.07_Three_Candle_Patterns_Three_White_Soldiers_Three_Black_Crows.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[10.11]`](docs/10_Technical_Analysis/10.11_Multi_Indicator_Confluence_and_Its_Pitfalls.md) | [`[11.09]`](docs/11_Candlesticks/11.09_Japanese_Candlestick_History_Munehisa_Homma.md) |
| `[11.09]` | [Japanese Candlestick History — Munehisa Homma and Rice Trading](docs/11_Candlesticks/11.09_Japanese_Candlestick_History_Munehisa_Homma.md) | 🟡 Intermediate | 30 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) | [`[11.10]`](docs/11_Candlesticks/11.10_Candlestick_Pattern_Reliability.md) |
| `[11.10]` | [Candlestick Pattern Reliability — What Backtests Actually Show](docs/11_Candlesticks/11.10_Candlestick_Pattern_Reliability.md) | 🟡 Intermediate | 35 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[11.09]`](docs/11_Candlesticks/11.09_Japanese_Candlestick_History_Munehisa_Homma.md), [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) | [`[12.01]`](docs/12_Chart_Patterns/12.01_Head_and_Shoulders.md) |

### Module 12 — Chart Patterns

[Module Index](docs/12_Chart_Patterns/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[12.01]` | [Head and Shoulders (and Inverse)](docs/12_Chart_Patterns/12.01_Head_and_Shoulders.md) | 🟡 Intermediate | 35 min | [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md), [`[02.05]`](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md) | [`[12.02]`](docs/12_Chart_Patterns/12.02_Double_Top_and_Double_Bottom.md) |
| `[12.02]` | [Double Top and Double Bottom](docs/12_Chart_Patterns/12.02_Double_Top_and_Double_Bottom.md) | 🟡 Intermediate | 30 min | [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[12.01]`](docs/12_Chart_Patterns/12.01_Head_and_Shoulders.md) | [`[12.03]`](docs/12_Chart_Patterns/12.03_Triple_Top_and_Triple_Bottom.md) |
| `[12.03]` | [Triple Top and Triple Bottom](docs/12_Chart_Patterns/12.03_Triple_Top_and_Triple_Bottom.md) | 🟡 Intermediate | 30 min | [`[12.02]`](docs/12_Chart_Patterns/12.02_Double_Top_and_Double_Bottom.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md) |
| `[12.04]` | [Ascending, Descending, and Symmetrical Triangles](docs/12_Chart_Patterns/12.04_Triangles.md) | 🟡 Intermediate | 30 min | [`[10.05]`](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[12.05]`](docs/12_Chart_Patterns/12.05_Flags_and_Pennants.md) |
| `[12.05]` | [Flags and Pennants](docs/12_Chart_Patterns/12.05_Flags_and_Pennants.md) | 🟡 Intermediate | 30 min | [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md), [`[10.08]`](docs/10_Technical_Analysis/10.08_Volume_as_a_Confirming_Tool.md) | [`[12.06]`](docs/12_Chart_Patterns/12.06_Cup_and_Handle.md) |
| `[12.06]` | [Cup and Handle](docs/12_Chart_Patterns/12.06_Cup_and_Handle.md) | 🟡 Intermediate | 30 min | [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[12.07]`](docs/12_Chart_Patterns/12.07_Wedges_Rising_and_Falling.md) |
| `[12.07]` | [Wedges — Rising and Falling](docs/12_Chart_Patterns/12.07_Wedges_Rising_and_Falling.md) | 🟡 Intermediate | 30 min | [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md), [`[10.05]`](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md) | [`[12.08]`](docs/12_Chart_Patterns/12.08_Rounding_Top_and_Bottom.md) |
| `[12.08]` | [Rounding Top and Bottom](docs/12_Chart_Patterns/12.08_Rounding_Top_and_Bottom.md) | 🟡 Intermediate | 30 min | [`[12.06]`](docs/12_Chart_Patterns/12.06_Cup_and_Handle.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[12.09]`](docs/12_Chart_Patterns/12.09_Broadening_Formations.md) |
| `[12.09]` | [Broadening Formations (Megaphones)](docs/12_Chart_Patterns/12.09_Broadening_Formations.md) | 🟡 Intermediate | 30 min | [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md), [`[23.01]`](docs/23_Volatility/23.01_What_Is_Volatility_Historical_vs_Implied.md) | [`[12.10]`](docs/12_Chart_Patterns/12.10_Pattern_Failures_and_False_Breakouts.md) |
| `[12.10]` | [Pattern Failures and False Breakouts](docs/12_Chart_Patterns/12.10_Pattern_Failures_and_False_Breakouts.md) | 🟡 Intermediate | 40 min | [`[12.01]`](docs/12_Chart_Patterns/12.01_Head_and_Shoulders.md), [`[12.09]`](docs/12_Chart_Patterns/12.09_Broadening_Formations.md), [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) | [`[13.01]`](docs/13_Price_Action/13.01_What_Is_Pure_Price_Action_Trading.md) |

### Module 13 — Price Action

[Module Index](docs/13_Price_Action/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[13.01]` | [What Is Pure Price Action Trading](docs/13_Price_Action/13.01_What_Is_Pure_Price_Action_Trading.md) | 🟡 Intermediate | 30 min | — | [`[13.02]`](docs/13_Price_Action/13.02_Reading_Candle_by_Candle_Behavior.md) |
| `[13.02]` | [Reading Candle-by-Candle Behavior](docs/13_Price_Action/13.02_Reading_Candle_by_Candle_Behavior.md) | 🟡 Intermediate | 30 min | [`[13.01]`](docs/13_Price_Action/13.01_What_Is_Pure_Price_Action_Trading.md), [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md) | [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) |
| `[13.03]` | [Supply and Demand Zones](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) | 🟡 Intermediate | 30 min | [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[13.02]`](docs/13_Price_Action/13.02_Reading_Candle_by_Candle_Behavior.md) | [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md) |
| `[13.04]` | [Breakouts vs Fakeouts](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md) | 🟡 Intermediate | 30 min | [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md), [`[12.10]`](docs/12_Chart_Patterns/12.10_Pattern_Failures_and_False_Breakouts.md), [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) | [`[13.05]`](docs/13_Price_Action/13.05_Pullbacks_and_Retracements_vs_Reversals.md) |
| `[13.05]` | [Pullbacks and Retracements vs Reversals](docs/13_Price_Action/13.05_Pullbacks_and_Retracements_vs_Reversals.md) | 🟡 Intermediate | 30 min | [`[02.05]`](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md), [`[10.09]`](docs/10_Technical_Analysis/10.09_Fibonacci_Retracement_and_Extension.md) | [`[13.06]`](docs/13_Price_Action/13.06_Inside_Bars_and_Outside_Bars.md) |
| `[13.06]` | [Inside Bars and Outside Bars](docs/13_Price_Action/13.06_Inside_Bars_and_Outside_Bars.md) | 🟡 Intermediate | 30 min | [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md), [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md) | [`[13.07]`](docs/13_Price_Action/13.07_Price_Action_at_Key_Levels.md) |
| `[13.07]` | [Price Action at Key Levels (Round Numbers, Prior Day High/Low)](docs/13_Price_Action/13.07_Price_Action_at_Key_Levels.md) | 🟡 Intermediate | 30 min | [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) | [`[13.08]`](docs/13_Price_Action/13.08_Range_Trading_with_Price_Action.md) |
| `[13.08]` | [Range Trading with Price Action](docs/13_Price_Action/13.08_Range_Trading_with_Price_Action.md) | 🟡 Intermediate | 30 min | [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md), [`[13.07]`](docs/13_Price_Action/13.07_Price_Action_at_Key_Levels.md) | [`[13.09]`](docs/13_Price_Action/13.09_Trend_Following_with_Price_Action.md) |
| `[13.09]` | [Trend-Following with Price Action](docs/13_Price_Action/13.09_Trend_Following_with_Price_Action.md) | 🟡 Intermediate | 30 min | [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md), [`[13.08]`](docs/13_Price_Action/13.08_Range_Trading_with_Price_Action.md) | [`[13.10]`](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md) |
| `[13.10]` | [Building a Discretionary Price Action Playbook](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md) | 🟡 Intermediate | 40 min | [`[13.01]`](docs/13_Price_Action/13.01_What_Is_Pure_Price_Action_Trading.md), [`[13.09]`](docs/13_Price_Action/13.09_Trend_Following_with_Price_Action.md), [`[10.12]`](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md) | [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md) |

### Module 14 — Volume

[Module Index](docs/14_Volume/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[14.01]` | [What Volume Really Tells You](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md) | 🟡 Intermediate | 30 min | [`[10.08]`](docs/10_Technical_Analysis/10.08_Volume_as_a_Confirming_Tool.md), [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) | [`[14.02]`](docs/14_Volume/14.02_Volume_Spread_Analysis_Basics.md) |
| `[14.02]` | [Volume Spread Analysis Basics](docs/14_Volume/14.02_Volume_Spread_Analysis_Basics.md) | 🟡 Intermediate | 35 min | [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md), [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md) | [`[14.03]`](docs/14_Volume/14.03_Volume_at_Breakouts_vs_Volume_in_Ranges.md) |
| `[14.03]` | [Volume at Breakouts vs Volume in Ranges](docs/14_Volume/14.03_Volume_at_Breakouts_vs_Volume_in_Ranges.md) | 🟡 Intermediate | 30 min | [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md), [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md) | [`[14.04]`](docs/14_Volume/14.04_Open_Interest_vs_Volume_in_Derivatives.md) |
| `[14.04]` | [Open Interest vs Volume in Derivatives](docs/14_Volume/14.04_Open_Interest_vs_Volume_in_Derivatives.md) | 🟡 Intermediate | 35 min | [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md), [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) | [`[14.05]`](docs/14_Volume/14.05_Climactic_Volume_and_Exhaustion.md) |
| `[14.05]` | [Climactic Volume and Exhaustion](docs/14_Volume/14.05_Climactic_Volume_and_Exhaustion.md) | 🟡 Intermediate | 30 min | [`[14.02]`](docs/14_Volume/14.02_Volume_Spread_Analysis_Basics.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[14.06]`](docs/14_Volume/14.06_Volume_Based_Confirmation_Rules.md) |
| `[14.06]` | [Volume-Based Confirmation Rules](docs/14_Volume/14.06_Volume_Based_Confirmation_Rules.md) | 🟡 Intermediate | 35 min | [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md), [`[14.05]`](docs/14_Volume/14.05_Climactic_Volume_and_Exhaustion.md), [`[10.12]`](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md) | [`[15.01]`](docs/15_Market_Profile/15.01_Introduction_to_Market_Profile.md) |

### Module 15 — Market Profile

[Module Index](docs/15_Market_Profile/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[15.01]` | [Introduction to Market Profile (TPO)](docs/15_Market_Profile/15.01_Introduction_to_Market_Profile.md) | 🟡 Intermediate | 35 min | [`[10.03]`](docs/10_Technical_Analysis/10.03_Types_of_Charts.md), [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md) | [`[15.02]`](docs/15_Market_Profile/15.02_Value_Area_Point_of_Control_and_Range.md) |
| `[15.02]` | [Value Area, Point of Control, and Range](docs/15_Market_Profile/15.02_Value_Area_Point_of_Control_and_Range.md) | 🟡 Intermediate | 30 min | [`[15.01]`](docs/15_Market_Profile/15.01_Introduction_to_Market_Profile.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | [`[15.03]`](docs/15_Market_Profile/15.03_Profile_Shapes.md) |
| `[15.03]` | [Profile Shapes — Normal, P, b, Trend Day](docs/15_Market_Profile/15.03_Profile_Shapes.md) | 🟡 Intermediate | 30 min | [`[15.02]`](docs/15_Market_Profile/15.02_Value_Area_Point_of_Control_and_Range.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[15.04]`](docs/15_Market_Profile/15.04_Initial_Balance_and_Its_Significance.md) |
| `[15.04]` | [Initial Balance and Its Significance](docs/15_Market_Profile/15.04_Initial_Balance_and_Its_Significance.md) | 🟡 Intermediate | 30 min | [`[15.03]`](docs/15_Market_Profile/15.03_Profile_Shapes.md), [`[13.07]`](docs/13_Price_Action/13.07_Price_Action_at_Key_Levels.md) | [`[15.05]`](docs/15_Market_Profile/15.05_Using_Market_Profile_for_Intraday_Bias.md) |
| `[15.05]` | [Using Market Profile for Intraday Bias](docs/15_Market_Profile/15.05_Using_Market_Profile_for_Intraday_Bias.md) | 🟡 Intermediate | 35 min | [`[15.02]`](docs/15_Market_Profile/15.02_Value_Area_Point_of_Control_and_Range.md), [`[15.04]`](docs/15_Market_Profile/15.04_Initial_Balance_and_Its_Significance.md) | [`[15.06]`](docs/15_Market_Profile/15.06_Composite_Profiles_and_Multi_Day_Analysis.md) |
| `[15.06]` | [Composite Profiles and Multi-Day Analysis](docs/15_Market_Profile/15.06_Composite_Profiles_and_Multi_Day_Analysis.md) | 🟡 Intermediate | 35 min | [`[15.01]`](docs/15_Market_Profile/15.01_Introduction_to_Market_Profile.md), [`[15.05]`](docs/15_Market_Profile/15.05_Using_Market_Profile_for_Intraday_Bias.md), [`[02.08]`](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md) | [`[16.01]`](docs/16_Volume_Profile/16.01_Introduction_to_Volume_Profile.md) |

### Module 16 — Volume Profile

[Module Index](docs/16_Volume_Profile/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[16.01]` | [Introduction to Volume Profile](docs/16_Volume_Profile/16.01_Introduction_to_Volume_Profile.md) | 🟡 Intermediate | 30 min | [`[15.01]`](docs/15_Market_Profile/15.01_Introduction_to_Market_Profile.md), [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md) | [`[16.02]`](docs/16_Volume_Profile/16.02_Value_Area_High_Low_POC.md) |
| `[16.02]` | [Value Area High, Value Area Low, POC](docs/16_Volume_Profile/16.02_Value_Area_High_Low_POC.md) | 🟡 Intermediate | 30 min | [`[16.01]`](docs/16_Volume_Profile/16.01_Introduction_to_Volume_Profile.md), [`[15.02]`](docs/15_Market_Profile/15.02_Value_Area_Point_of_Control_and_Range.md) | [`[16.03]`](docs/16_Volume_Profile/16.03_High_Volume_Nodes_vs_Low_Volume_Nodes.md) |
| `[16.03]` | [High Volume Nodes vs Low Volume Nodes](docs/16_Volume_Profile/16.03_High_Volume_Nodes_vs_Low_Volume_Nodes.md) | 🟡 Intermediate | 30 min | [`[16.02]`](docs/16_Volume_Profile/16.02_Value_Area_High_Low_POC.md), [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) | [`[16.04]`](docs/16_Volume_Profile/16.04_Volume_Profile_vs_Market_Profile.md) |
| `[16.04]` | [Volume Profile vs Market Profile — Key Differences](docs/16_Volume_Profile/16.04_Volume_Profile_vs_Market_Profile.md) | 🟡 Intermediate | 30 min | [`[16.01]`](docs/16_Volume_Profile/16.01_Introduction_to_Volume_Profile.md), [`[16.03]`](docs/16_Volume_Profile/16.03_High_Volume_Nodes_vs_Low_Volume_Nodes.md) | [`[16.05]`](docs/16_Volume_Profile/16.05_Session_Composite_and_Fixed_Range_Volume_Profiles.md) |
| `[16.05]` | [Session, Composite, and Fixed Range Volume Profiles](docs/16_Volume_Profile/16.05_Session_Composite_and_Fixed_Range_Volume_Profiles.md) | 🟡 Intermediate | 30 min | [`[16.04]`](docs/16_Volume_Profile/16.04_Volume_Profile_vs_Market_Profile.md), [`[15.06]`](docs/15_Market_Profile/15.06_Composite_Profiles_and_Multi_Day_Analysis.md) | [`[16.06]`](docs/16_Volume_Profile/16.06_Trading_Strategies_Using_Volume_Profile.md) |
| `[16.06]` | [Trading Strategies Using Volume Profile](docs/16_Volume_Profile/16.06_Trading_Strategies_Using_Volume_Profile.md) | 🟡 Intermediate | 40 min | [`[16.01]`](docs/16_Volume_Profile/16.01_Introduction_to_Volume_Profile.md), [`[16.05]`](docs/16_Volume_Profile/16.05_Session_Composite_and_Fixed_Range_Volume_Profiles.md), [`[13.10]`](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md), [`[14.06]`](docs/14_Volume/14.06_Volume_Based_Confirmation_Rules.md) | [`[17.01]`](docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md) |

### Module 17 — Wyckoff

[Module Index](docs/17_Wyckoff/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[17.01]` | [Richard Wyckoff — History and Philosophy](docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md) | 🟡 Intermediate | 30 min | [`[14.05]`](docs/14_Volume/14.05_Climactic_Volume_and_Exhaustion.md), [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) | [`[17.02]`](docs/17_Wyckoff/17.02_The_Three_Laws_of_Wyckoff.md) |
| `[17.02]` | [The Three Laws of Wyckoff](docs/17_Wyckoff/17.02_The_Three_Laws_of_Wyckoff.md) | 🟡 Intermediate | 30 min | [`[17.01]`](docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md), [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md) | [`[17.03]`](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md) |
| `[17.03]` | [Accumulation Schematic — Phases A to E](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md) | 🟡 Intermediate | 40 min | [`[17.02]`](docs/17_Wyckoff/17.02_The_Three_Laws_of_Wyckoff.md), [`[13.08]`](docs/13_Price_Action/13.08_Range_Trading_with_Price_Action.md), [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) | [`[17.04]`](docs/17_Wyckoff/17.04_Distribution_Schematic_Phases_A_to_E.md) |
| `[17.04]` | [Distribution Schematic — Phases A to E](docs/17_Wyckoff/17.04_Distribution_Schematic_Phases_A_to_E.md) | 🟡 Intermediate | 40 min | [`[17.03]`](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md), [`[12.02]`](docs/12_Chart_Patterns/12.02_Double_Top_and_Double_Bottom.md) | [`[17.05]`](docs/17_Wyckoff/17.05_Springs_Upthrusts_and_Tests.md) |
| `[17.05]` | [Springs, Upthrusts, and Tests](docs/17_Wyckoff/17.05_Springs_Upthrusts_and_Tests.md) | 🟡 Intermediate | 35 min | [`[17.03]`](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md), [`[17.04]`](docs/17_Wyckoff/17.04_Distribution_Schematic_Phases_A_to_E.md), [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md) | [`[17.06]`](docs/17_Wyckoff/17.06_Composite_Man_Concept.md) |
| `[17.06]` | [Composite Man Concept](docs/17_Wyckoff/17.06_Composite_Man_Concept.md) | 🟡 Intermediate | 30 min | [`[17.05]`](docs/17_Wyckoff/17.05_Springs_Upthrusts_and_Tests.md), [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) | [`[17.07]`](docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md) |
| `[17.07]` | [Wyckoff in Modern Markets — Does It Still Work](docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md) | 🟡 Intermediate | 30 min | [`[17.06]`](docs/17_Wyckoff/17.06_Composite_Man_Concept.md), [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) | [`[17.08]`](docs/17_Wyckoff/17.08_Wyckoff_Case_Study_on_an_Indian_Stock.md) |
| `[17.08]` | [Wyckoff Case Study on an Indian Stock](docs/17_Wyckoff/17.08_Wyckoff_Case_Study_on_an_Indian_Stock.md) | 🟡 Intermediate | 45 min | [`[17.01]`](docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md), [`[17.07]`](docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md), [`[03.07]`](docs/03_Indian_Market/03.07_FIIs_DIIs_and_Domestic_Retail_Who_Moves_Nifty.md) | [`[18.01]`](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md) |

### Module 18 — Smart Money Concepts

[Module Index](docs/18_Smart_Money/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[18.01]` | [What Are Smart Money Concepts (SMC)](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md) | 🟡 Intermediate | 30 min | [`[17.06]`](docs/17_Wyckoff/17.06_Composite_Man_Concept.md), [`[17.07]`](docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md) | [`[18.02]`](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md) |
| `[18.02]` | [Liquidity Pools — Buy-Side and Sell-Side](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md) | 🟡 Intermediate | 30 min | [`[18.01]`](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md), [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) | [`[18.03]`](docs/18_Smart_Money/18.03_Order_Blocks_Explained.md) |
| `[18.03]` | [Order Blocks Explained](docs/18_Smart_Money/18.03_Order_Blocks_Explained.md) | 🟡 Intermediate | 30 min | [`[18.02]`](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md), [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) | [`[18.04]`](docs/18_Smart_Money/18.04_Fair_Value_Gaps_Imbalances.md) |
| `[18.04]` | [Fair Value Gaps / Imbalances](docs/18_Smart_Money/18.04_Fair_Value_Gaps_Imbalances.md) | 🟡 Intermediate | 30 min | [`[18.03]`](docs/18_Smart_Money/18.03_Order_Blocks_Explained.md), [`[12.09]`](docs/12_Chart_Patterns/12.09_Broadening_Formations.md) | [`[18.05]`](docs/18_Smart_Money/18.05_Mitigation_and_Inducement.md) |
| `[18.05]` | [Mitigation and Inducement](docs/18_Smart_Money/18.05_Mitigation_and_Inducement.md) | 🟡 Intermediate | 30 min | [`[18.04]`](docs/18_Smart_Money/18.04_Fair_Value_Gaps_Imbalances.md), [`[18.02]`](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md) | [`[18.06]`](docs/18_Smart_Money/18.06_Premium_and_Discount_Zones.md) |
| `[18.06]` | [Premium and Discount Zones](docs/18_Smart_Money/18.06_Premium_and_Discount_Zones.md) | 🟡 Intermediate | 30 min | [`[18.05]`](docs/18_Smart_Money/18.05_Mitigation_and_Inducement.md), [`[10.09]`](docs/10_Technical_Analysis/10.09_Fibonacci_Retracement_and_Extension.md) | [`[18.07]`](docs/18_Smart_Money/18.07_SMC_vs_Classical_Technical_Analysis.md) |
| `[18.07]` | [SMC vs Classical Technical Analysis](docs/18_Smart_Money/18.07_SMC_vs_Classical_Technical_Analysis.md) | 🟡 Intermediate | 30 min | [`[18.01]`](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md), [`[18.06]`](docs/18_Smart_Money/18.06_Premium_and_Discount_Zones.md), [`[10.12]`](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md) | [`[18.08]`](docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md) |
| `[18.08]` | [Criticisms and Limitations of SMC](docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md) | 🟡 Intermediate | 40 min | [`[18.01]`](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md), [`[18.07]`](docs/18_Smart_Money/18.07_SMC_vs_Classical_Technical_Analysis.md), [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) | [`[19.01]`](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md) |

### Module 19 — ICT

[Module Index](docs/19_ICT/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[19.01]` | [Introduction to ICT (Inner Circle Trader) Concepts](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md) | 🟡 Intermediate | 30 min | [`[18.08]`](docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md), [`[04.02]`](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) | [`[19.02]`](docs/19_ICT/19.02_Market_Maker_Models.md) |
| `[19.02]` | [Market Maker Models (Buy/Sell Models)](docs/19_ICT/19.02_Market_Maker_Models.md) | 🟡 Intermediate | 30 min | [`[19.01]`](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md), [`[17.03]`](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md) | [`[19.03]`](docs/19_ICT/19.03_Kill_Zones_and_Time_Based_Trading.md) |
| `[19.03]` | [Kill Zones and Time-Based Trading](docs/19_ICT/19.03_Kill_Zones_and_Time_Based_Trading.md) | 🟡 Intermediate | 30 min | [`[19.02]`](docs/19_ICT/19.02_Market_Maker_Models.md), [`[04.02]`](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) | [`[19.04]`](docs/19_ICT/19.04_Optimal_Trade_Entry.md) |
| `[19.04]` | [Optimal Trade Entry (OTE)](docs/19_ICT/19.04_Optimal_Trade_Entry.md) | 🟡 Intermediate | 30 min | [`[19.03]`](docs/19_ICT/19.03_Kill_Zones_and_Time_Based_Trading.md), [`[10.09]`](docs/10_Technical_Analysis/10.09_Fibonacci_Retracement_and_Extension.md) | [`[19.05]`](docs/19_ICT/19.05_Power_of_Three.md) |
| `[19.05]` | [Power of Three (Accumulation, Manipulation, Distribution)](docs/19_ICT/19.05_Power_of_Three.md) | 🟡 Intermediate | 30 min | [`[19.04]`](docs/19_ICT/19.04_Optimal_Trade_Entry.md), [`[17.05]`](docs/17_Wyckoff/17.05_Springs_Upthrusts_and_Tests.md) | [`[19.06]`](docs/19_ICT/19.06_Judas_Swing_Concept.md) |
| `[19.06]` | [Judas Swing Concept](docs/19_ICT/19.06_Judas_Swing_Concept.md) | 🟡 Intermediate | 25 min | [`[19.05]`](docs/19_ICT/19.05_Power_of_Three.md), [`[18.02]`](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md) | [`[19.07]`](docs/19_ICT/19.07_ICT_Applied_to_Indian_Index_Futures.md) |
| `[19.07]` | [ICT Concepts Applied to Indian Index Futures](docs/19_ICT/19.07_ICT_Applied_to_Indian_Index_Futures.md) | 🟡 Intermediate | 35 min | [`[19.01]`](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md), [`[19.06]`](docs/19_ICT/19.06_Judas_Swing_Concept.md), [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) | [`[19.08]`](docs/19_ICT/19.08_Evaluating_ICT.md) |
| `[19.08]` | [Evaluating ICT — Evidence, Skepticism, and Practical Use](docs/19_ICT/19.08_Evaluating_ICT.md) | 🟡 Intermediate | 40 min | [`[19.01]`](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md), [`[19.07]`](docs/19_ICT/19.07_ICT_Applied_to_Indian_Index_Futures.md), [`[18.08]`](docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md) | [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) |

### Module 20 — Futures

[Module Index](docs/20_Futures/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[20.01]` | [What Is a Futures Contract](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) | 🔴 Advanced | 30 min | [`[03.08]`](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md), [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) | [`[20.02]`](docs/20_Futures/20.02_Futures_vs_Forwards_vs_Spot.md) |
| `[20.02]` | [Futures vs Forwards vs Spot](docs/20_Futures/20.02_Futures_vs_Forwards_vs_Spot.md) | 🔴 Advanced | 25 min | [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md), [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) | [`[20.03]`](docs/20_Futures/20.03_Contract_Specifications.md) |
| `[20.03]` | [Contract Specifications — Lot Size, Expiry, Tick Size](docs/20_Futures/20.03_Contract_Specifications.md) | 🔴 Advanced | 30 min | [`[20.02]`](docs/20_Futures/20.02_Futures_vs_Forwards_vs_Spot.md), [`[03.08]`](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md) | [`[20.04]`](docs/20_Futures/20.04_Margin_Mark_to_Market_and_Leverage.md) |
| `[20.04]` | [Margin, Mark-to-Market, and Leverage in Futures](docs/20_Futures/20.04_Margin_Mark_to_Market_and_Leverage.md) | 🔴 Advanced | 35 min | [`[20.03]`](docs/20_Futures/20.03_Contract_Specifications.md), [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) | [`[20.05]`](docs/20_Futures/20.05_Basis_Contango_and_Backwardation.md) |
| `[20.05]` | [Basis, Contango, and Backwardation](docs/20_Futures/20.05_Basis_Contango_and_Backwardation.md) | 🔴 Advanced | 30 min | [`[20.04]`](docs/20_Futures/20.04_Margin_Mark_to_Market_and_Leverage.md), [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) | [`[20.06]`](docs/20_Futures/20.06_Rollover_Mechanics.md) |
| `[20.06]` | [Rollover Mechanics (Indian F&O Expiry Cycle)](docs/20_Futures/20.06_Rollover_Mechanics.md) | 🔴 Advanced | 30 min | [`[20.05]`](docs/20_Futures/20.05_Basis_Contango_and_Backwardation.md), [`[20.03]`](docs/20_Futures/20.03_Contract_Specifications.md) | [`[20.07]`](docs/20_Futures/20.07_Index_Futures_vs_Stock_Futures.md) |
| `[20.07]` | [Index Futures vs Stock Futures](docs/20_Futures/20.07_Index_Futures_vs_Stock_Futures.md) | 🔴 Advanced | 25 min | [`[20.06]`](docs/20_Futures/20.06_Rollover_Mechanics.md), [`[03.08]`](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md) | [`[20.08]`](docs/20_Futures/20.08_Hedging_with_Futures.md) |
| `[20.08]` | [Hedging with Futures](docs/20_Futures/20.08_Hedging_with_Futures.md) | 🔴 Advanced | 30 min | [`[20.07]`](docs/20_Futures/20.07_Index_Futures_vs_Stock_Futures.md), [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) | [`[20.09]`](docs/20_Futures/20.09_Speculation_with_Futures.md) |
| `[20.09]` | [Speculation with Futures — Risk Profile](docs/20_Futures/20.09_Speculation_with_Futures.md) | 🔴 Advanced | 30 min | [`[20.08]`](docs/20_Futures/20.08_Hedging_with_Futures.md), [`[20.04]`](docs/20_Futures/20.04_Margin_Mark_to_Market_and_Leverage.md) | [`[20.10]`](docs/20_Futures/20.10_Commodity_Futures_Basics_MCX.md) |
| `[20.10]` | [Commodity Futures Basics (MCX Overview)](docs/20_Futures/20.10_Commodity_Futures_Basics_MCX.md) | 🔴 Advanced | 35 min | [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md), [`[20.09]`](docs/20_Futures/20.09_Speculation_with_Futures.md), [`[06.08]`](docs/06_Macroeconomics/06.08_Commodity_Super_Cycles_and_Macro_Trading.md) | [`[21.01]`](docs/21_Options/21.01_What_Is_an_Option.md) |

### Module 21 — Options

[Module Index](docs/21_Options/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[21.01]` | [What Is an Option — Calls and Puts Explained](docs/21_Options/21.01_What_Is_an_Option.md) | 🔴 Advanced | 30 min | [`[20.09]`](docs/20_Futures/20.09_Speculation_with_Futures.md), [`[03.08]`](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md) | [`[21.02]`](docs/21_Options/21.02_Option_Buyer_vs_Seller.md) |
| `[21.02]` | [Option Buyer vs Option Seller — Risk Profiles](docs/21_Options/21.02_Option_Buyer_vs_Seller.md) | 🔴 Advanced | 30 min | [`[21.01]`](docs/21_Options/21.01_What_Is_an_Option.md), [`[20.09]`](docs/20_Futures/20.09_Speculation_with_Futures.md) | [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md) |
| `[21.03]` | [Strike Price, Premium, and Moneyness (ITM/ATM/OTM)](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md) | 🔴 Advanced | 30 min | [`[21.02]`](docs/21_Options/21.02_Option_Buyer_vs_Seller.md), [`[21.01]`](docs/21_Options/21.01_What_Is_an_Option.md) | [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) |
| `[21.04]` | [Intrinsic Value vs Time Value](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) | 🔴 Advanced | 30 min | [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md), [`[21.01]`](docs/21_Options/21.01_What_Is_an_Option.md) | [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md) |
| `[21.05]` | [Option Payoff Diagrams — Long Call, Long Put](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md) | 🔴 Advanced | 35 min | [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md), [`[21.02]`](docs/21_Options/21.02_Option_Buyer_vs_Seller.md), [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md) | [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md) |
| `[21.06]` | [Option Payoff Diagrams — Short Call, Short Put](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md) | 🔴 Advanced | 35 min | [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md), [`[21.02]`](docs/21_Options/21.02_Option_Buyer_vs_Seller.md), [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) | [`[21.07]`](docs/21_Options/21.07_Basic_Option_Strategies_Covered_Call_Protective_Put.md) |
| `[21.07]` | [Basic Option Strategies — Covered Call, Protective Put](docs/21_Options/21.07_Basic_Option_Strategies_Covered_Call_Protective_Put.md) | 🔴 Advanced | 35 min | [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md), [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md) | [`[21.08]`](docs/21_Options/21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md) |
| `[21.08]` | [Spreads — Bull Call Spread, Bear Put Spread](docs/21_Options/21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md) | 🔴 Advanced | 35 min | [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md), [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md), [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) | [`[21.09]`](docs/21_Options/21.09_Straddles_and_Strangles.md) |
| `[21.09]` | [Straddles and Strangles](docs/21_Options/21.09_Straddles_and_Strangles.md) | 🔴 Advanced | 35 min | [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md), [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md), [`[21.08]`](docs/21_Options/21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md) | [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) |
| `[21.10]` | [Iron Condor and Iron Butterfly](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) | 🔴 Advanced | 40 min | [`[21.08]`](docs/21_Options/21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md), [`[21.09]`](docs/21_Options/21.09_Straddles_and_Strangles.md), [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md) | [`[21.11]`](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) |
| `[21.11]` | [Option Chain Analysis (India — NSE Option Chain)](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) | 🔴 Advanced | 35 min | [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md), [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md), [`[14.04]`](docs/14_Volume/14.04_Open_Interest_vs_Volume_in_Derivatives.md) | [`[21.12]`](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md) |
| `[21.12]` | [Common Option Buyer Mistakes (Theta Decay Trap)](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md) | 🔴 Advanced | 35 min | [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md), [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md), [`[21.11]`](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) | [`[22.01]`](docs/22_Greeks/22.01_Introduction_to_Option_Greeks.md) |

### Module 22 — Greeks

[Module Index](docs/22_Greeks/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[22.01]` | [Introduction to Option Greeks](docs/22_Greeks/22.01_Introduction_to_Option_Greeks.md) | 🔴 Advanced | 30 min | [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md), [`[21.12]`](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md) | [`[22.02]`](docs/22_Greeks/22.02_Delta_Directional_Sensitivity.md) |
| `[22.02]` | [Delta — Directional Sensitivity](docs/22_Greeks/22.02_Delta_Directional_Sensitivity.md) | 🔴 Advanced | 30 min | [`[22.01]`](docs/22_Greeks/22.01_Introduction_to_Option_Greeks.md), [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md) | [`[22.03]`](docs/22_Greeks/22.03_Gamma_Rate_of_Change_of_Delta.md) |
| `[22.03]` | [Gamma — Rate of Change of Delta](docs/22_Greeks/22.03_Gamma_Rate_of_Change_of_Delta.md) | 🔴 Advanced | 30 min | [`[22.02]`](docs/22_Greeks/22.02_Delta_Directional_Sensitivity.md), [`[22.01]`](docs/22_Greeks/22.01_Introduction_to_Option_Greeks.md) | [`[22.04]`](docs/22_Greeks/22.04_Theta_Time_Decay.md) |
| `[22.04]` | [Theta — Time Decay](docs/22_Greeks/22.04_Theta_Time_Decay.md) | 🔴 Advanced | 30 min | [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md), [`[21.12]`](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md), [`[22.01]`](docs/22_Greeks/22.01_Introduction_to_Option_Greeks.md) | [`[22.05]`](docs/22_Greeks/22.05_Vega_Volatility_Sensitivity.md) |
| `[22.05]` | [Vega — Volatility Sensitivity](docs/22_Greeks/22.05_Vega_Volatility_Sensitivity.md) | 🔴 Advanced | 30 min | [`[22.04]`](docs/22_Greeks/22.04_Theta_Time_Decay.md), [`[21.12]`](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md), [`[21.11]`](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) | [`[22.06]`](docs/22_Greeks/22.06_Rho_and_Second_Order_Greeks.md) |
| `[22.06]` | [Rho and Second-Order Greeks](docs/22_Greeks/22.06_Rho_and_Second_Order_Greeks.md) | 🔴 Advanced | 30 min | [`[22.05]`](docs/22_Greeks/22.05_Vega_Volatility_Sensitivity.md), [`[22.02]`](docs/22_Greeks/22.02_Delta_Directional_Sensitivity.md) | [`[22.07]`](docs/22_Greeks/22.07_Greeks_in_Practice_Managing_a_Position.md) |
| `[22.07]` | [Greeks in Practice — Managing a Position](docs/22_Greeks/22.07_Greeks_in_Practice_Managing_a_Position.md) | 🔴 Advanced | 35 min | [`[22.02]`](docs/22_Greeks/22.02_Delta_Directional_Sensitivity.md), [`[22.06]`](docs/22_Greeks/22.06_Rho_and_Second_Order_Greeks.md), [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) | [`[22.08]`](docs/22_Greeks/22.08_Greeks_Based_Position_Adjustment_Case_Study.md) |
| `[22.08]` | [Greeks-Based Position Adjustment Case Study](docs/22_Greeks/22.08_Greeks_Based_Position_Adjustment_Case_Study.md) | 🔴 Advanced | 40 min | [`[22.07]`](docs/22_Greeks/22.07_Greeks_in_Practice_Managing_a_Position.md), [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) | [`[23.01]`](docs/23_Volatility/23.01_What_Is_Volatility_Historical_vs_Implied.md) |

### Module 23 — Volatility

[Module Index](docs/23_Volatility/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[23.01]` | [What Is Volatility — Historical vs Implied](docs/23_Volatility/23.01_What_Is_Volatility_Historical_vs_Implied.md) | 🔴 Advanced | 30 min | [`[22.05]`](docs/22_Greeks/22.05_Vega_Volatility_Sensitivity.md), [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) | [`[23.02]`](docs/23_Volatility/23.02_India_VIX_Explained.md) |
| `[23.02]` | [India VIX Explained](docs/23_Volatility/23.02_India_VIX_Explained.md) | 🔴 Advanced | 30 min | [`[23.01]`](docs/23_Volatility/23.01_What_Is_Volatility_Historical_vs_Implied.md), [`[03.04]`](docs/03_Indian_Market/03.04_Nifty_50_and_Sensex_Construction_Methodology.md) | [`[23.03]`](docs/23_Volatility/23.03_VIX_US_and_the_Fear_Gauge.md) |
| `[23.03]` | [VIX (US) and the "Fear Gauge"](docs/23_Volatility/23.03_VIX_US_and_the_Fear_Gauge.md) | 🔴 Advanced | 30 min | [`[23.02]`](docs/23_Volatility/23.02_India_VIX_Explained.md), [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) | [`[23.04]`](docs/23_Volatility/23.04_Volatility_Skew_and_Smile.md) |
| `[23.04]` | [Volatility Skew and Smile](docs/23_Volatility/23.04_Volatility_Skew_and_Smile.md) | 🔴 Advanced | 30 min | [`[23.01]`](docs/23_Volatility/23.01_What_Is_Volatility_Historical_vs_Implied.md), [`[21.11]`](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) | [`[23.05]`](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md) |
| `[23.05]` | [Volatility Regimes and Mean Reversion](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md) | 🔴 Advanced | 30 min | [`[23.02]`](docs/23_Volatility/23.02_India_VIX_Explained.md), [`[23.03]`](docs/23_Volatility/23.03_VIX_US_and_the_Fear_Gauge.md) | [`[23.06]`](docs/23_Volatility/23.06_Trading_Volatility_Directly_VIX_Products_Caveats.md) |
| `[23.06]` | [Trading Volatility Directly (VIX Products, Caveats)](docs/23_Volatility/23.06_Trading_Volatility_Directly_VIX_Products_Caveats.md) | 🔴 Advanced | 35 min | [`[23.05]`](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md), [`[20.05]`](docs/20_Futures/20.05_Basis_Contango_and_Backwardation.md) | [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) |

### Module 24 — Trading Strategies

[Module Index](docs/24_Trading_Strategies/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[24.01]` | [What Makes a Trading Strategy "Valid"](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) | 🔴 Advanced | 30 min | [`[10.12]`](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md), [`[13.10]`](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md) | [`[24.02]`](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md) |
| `[24.02]` | [Trend-Following Strategy Framework](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md) | 🔴 Advanced | 30 min | [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md), [`[10.06]`](docs/10_Technical_Analysis/10.06_Moving_Averages_SMA_EMA_WMA.md), [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) | [`[24.03]`](docs/24_Trading_Strategies/24.03_Mean_Reversion_Strategy_Framework.md) |
| `[24.03]` | [Mean-Reversion Strategy Framework](docs/24_Trading_Strategies/24.03_Mean_Reversion_Strategy_Framework.md) | 🔴 Advanced | 30 min | [`[24.02]`](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md), [`[10.07]`](docs/10_Technical_Analysis/10.07_Momentum_Oscillators_RSI_Stochastic_MACD.md) | [`[24.04]`](docs/24_Trading_Strategies/24.04_Breakout_Trading_Strategy.md) |
| `[24.04]` | [Breakout Trading Strategy](docs/24_Trading_Strategies/24.04_Breakout_Trading_Strategy.md) | 🔴 Advanced | 30 min | [`[24.03]`](docs/24_Trading_Strategies/24.03_Mean_Reversion_Strategy_Framework.md), [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md), [`[14.03]`](docs/14_Volume/14.03_Volume_at_Breakouts_vs_Volume_in_Ranges.md) | [`[24.05]`](docs/24_Trading_Strategies/24.05_Gap_Trading_Strategy.md) |
| `[24.05]` | [Gap Trading Strategy](docs/24_Trading_Strategies/24.05_Gap_Trading_Strategy.md) | 🔴 Advanced | 30 min | [`[24.04]`](docs/24_Trading_Strategies/24.04_Breakout_Trading_Strategy.md), [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) | [`[24.06]`](docs/24_Trading_Strategies/24.06_Swing_Trading_Framework.md) |
| `[24.06]` | [Swing Trading Framework](docs/24_Trading_Strategies/24.06_Swing_Trading_Framework.md) | 🔴 Advanced | 30 min | [`[24.04]`](docs/24_Trading_Strategies/24.04_Breakout_Trading_Strategy.md), [`[02.08]`](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md) | [`[24.07]`](docs/24_Trading_Strategies/24.07_Intraday_Scalping_Framework.md) |
| `[24.07]` | [Intraday Scalping Framework](docs/24_Trading_Strategies/24.07_Intraday_Scalping_Framework.md) | 🔴 Advanced | 30 min | [`[24.06]`](docs/24_Trading_Strategies/24.06_Swing_Trading_Framework.md), [`[01.07]`](docs/01_Foundation/01.07_Order_Types_Explained.md) | [`[24.08]`](docs/24_Trading_Strategies/24.08_Positional_Momentum_Investing_Framework.md) |
| `[24.08]` | [Positional/Momentum Investing Framework](docs/24_Trading_Strategies/24.08_Positional_Momentum_Investing_Framework.md) | 🔴 Advanced | 30 min | [`[24.06]`](docs/24_Trading_Strategies/24.06_Swing_Trading_Framework.md), [`[08.10]`](docs/08_Fundamental_Analysis/08.10_Screening_Stocks_Fundamentally.md), [`[10.06]`](docs/10_Technical_Analysis/10.06_Moving_Averages_SMA_EMA_WMA.md) | [`[24.09]`](docs/24_Trading_Strategies/24.09_Options_Income_Strategies_Theta_Selling.md) |
| `[24.09]` | [Options Income Strategies (Theta Selling)](docs/24_Trading_Strategies/24.09_Options_Income_Strategies_Theta_Selling.md) | 🔴 Advanced | 35 min | [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md), [`[22.04]`](docs/22_Greeks/22.04_Theta_Time_Decay.md), [`[23.05]`](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md) | [`[24.10]`](docs/24_Trading_Strategies/24.10_Event_Driven_Trading.md) |
| `[24.10]` | [Event-Driven Trading (Earnings, Budget, Fed Days)](docs/24_Trading_Strategies/24.10_Event_Driven_Trading.md) | 🔴 Advanced | 30 min | [`[24.09]`](docs/24_Trading_Strategies/24.09_Options_Income_Strategies_Theta_Selling.md), [`[21.09]`](docs/21_Options/21.09_Straddles_and_Strangles.md), [`[03.10]`](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md) | [`[24.11]`](docs/24_Trading_Strategies/24.11_Combining_Strategies_into_a_Portfolio_of_Systems.md) |
| `[24.11]` | [Combining Strategies into a Portfolio of Systems](docs/24_Trading_Strategies/24.11_Combining_Strategies_into_a_Portfolio_of_Systems.md) | 🔴 Advanced | 30 min | [`[24.02]`](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md), [`[24.10]`](docs/24_Trading_Strategies/24.10_Event_Driven_Trading.md), [`[27.04]`](docs/27_Portfolio_Management/27.04_Correlation_and_Diversification_in_Practice.md) | [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) |
| `[24.12]` | [Strategy Journaling and Iteration](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) | 🔴 Advanced | 30 min | [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md), [`[24.11]`](docs/24_Trading_Strategies/24.11_Combining_Strategies_into_a_Portfolio_of_Systems.md) | [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md) |

### Module 25 — Risk Management

[Module Index](docs/25_Risk_Management/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[25.01]` | [Why Risk Management Comes Before Returns](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md) | 🔴 Advanced | 30 min | [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md), [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) | [`[25.02]`](docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md) |
| `[25.02]` | [Defining Risk Per Trade (1% Rule and Variants)](docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md) | 🔴 Advanced | 30 min | [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md), [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) | [`[25.03]`](docs/25_Risk_Management/25.03_Stop_Loss_Placement_Methodology.md) |
| `[25.03]` | [Stop-Loss Placement Methodology](docs/25_Risk_Management/25.03_Stop_Loss_Placement_Methodology.md) | 🔴 Advanced | 30 min | [`[25.02]`](docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md), [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) | [`[25.04]`](docs/25_Risk_Management/25.04_Risk_Reward_Ratio_and_Expectancy.md) |
| `[25.04]` | [Risk-Reward Ratio and Expectancy](docs/25_Risk_Management/25.04_Risk_Reward_Ratio_and_Expectancy.md) | 🔴 Advanced | 30 min | [`[25.03]`](docs/25_Risk_Management/25.03_Stop_Loss_Placement_Methodology.md), [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) | [`[25.05]`](docs/25_Risk_Management/25.05_Maximum_Drawdown_and_Why_It_Matters.md) |
| `[25.05]` | [Maximum Drawdown and Why It Matters](docs/25_Risk_Management/25.05_Maximum_Drawdown_and_Why_It_Matters.md) | 🔴 Advanced | 30 min | [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md), [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) | [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md) |
| `[25.06]` | [Correlation Risk Across Positions](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md) | 🔴 Advanced | 30 min | [`[25.05]`](docs/25_Risk_Management/25.05_Maximum_Drawdown_and_Why_It_Matters.md), [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) | [`[25.07]`](docs/25_Risk_Management/25.07_Black_Swan_Events_and_Tail_Risk.md) |
| `[25.07]` | [Black Swan Events and Tail Risk](docs/25_Risk_Management/25.07_Black_Swan_Events_and_Tail_Risk.md) | 🔴 Advanced | 30 min | [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md), [`[25.05]`](docs/25_Risk_Management/25.05_Maximum_Drawdown_and_Why_It_Matters.md) | [`[25.08]`](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md) |
| `[25.08]` | [Building a Personal Risk Management Rulebook](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md) | 🔴 Advanced | 35 min | [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md), [`[25.07]`](docs/25_Risk_Management/25.07_Black_Swan_Events_and_Tail_Risk.md), [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) | [`[26.01]`](docs/26_Position_Sizing/26.01_What_Is_Position_Sizing_and_Why_Its_the_Real_Edge.md) |

### Module 26 — Position Sizing

[Module Index](docs/26_Position_Sizing/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[26.01]` | [What Is Position Sizing and Why It's the Real Edge](docs/26_Position_Sizing/26.01_What_Is_Position_Sizing_and_Why_Its_the_Real_Edge.md) | 🔴 Advanced | 30 min | [`[25.08]`](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md), [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) | [`[26.02]`](docs/26_Position_Sizing/26.02_Fixed_Fractional_Position_Sizing.md) |
| `[26.02]` | [Fixed Fractional Position Sizing](docs/26_Position_Sizing/26.02_Fixed_Fractional_Position_Sizing.md) | 🔴 Advanced | 25 min | [`[26.01]`](docs/26_Position_Sizing/26.01_What_Is_Position_Sizing_and_Why_Its_the_Real_Edge.md), [`[25.02]`](docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md) | [`[26.03]`](docs/26_Position_Sizing/26.03_Volatility_Based_Position_Sizing_ATR_Method.md) |
| `[26.03]` | [Volatility-Based Position Sizing (ATR Method)](docs/26_Position_Sizing/26.03_Volatility_Based_Position_Sizing_ATR_Method.md) | 🔴 Advanced | 25 min | [`[26.02]`](docs/26_Position_Sizing/26.02_Fixed_Fractional_Position_Sizing.md), [`[25.03]`](docs/25_Risk_Management/25.03_Stop_Loss_Placement_Methodology.md) | [`[26.04]`](docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md) |
| `[26.04]` | [The Kelly Criterion Explained Simply](docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md) | 🔴 Advanced | 30 min | [`[26.03]`](docs/26_Position_Sizing/26.03_Volatility_Based_Position_Sizing_ATR_Method.md), [`[25.04]`](docs/25_Risk_Management/25.04_Risk_Reward_Ratio_and_Expectancy.md) | [`[26.05]`](docs/26_Position_Sizing/26.05_Position_Sizing_for_Options.md) |
| `[26.05]` | [Position Sizing for Options (Defined vs Undefined Risk)](docs/26_Position_Sizing/26.05_Position_Sizing_for_Options.md) | 🔴 Advanced | 30 min | [`[26.04]`](docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md), [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md), [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) | [`[26.06]`](docs/26_Position_Sizing/26.06_Scaling_In_and_Scaling_Out.md) |
| `[26.06]` | [Scaling In and Scaling Out](docs/26_Position_Sizing/26.06_Scaling_In_and_Scaling_Out.md) | 🔴 Advanced | 30 min | [`[26.05]`](docs/26_Position_Sizing/26.05_Position_Sizing_for_Options.md), [`[25.03]`](docs/25_Risk_Management/25.03_Stop_Loss_Placement_Methodology.md) | [`[27.01]`](docs/27_Portfolio_Management/27.01_What_Is_a_Portfolio_and_Why_Diversify.md) |

### Module 27 — Portfolio Management

[Module Index](docs/27_Portfolio_Management/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[27.01]` | [What Is a Portfolio and Why Diversify](docs/27_Portfolio_Management/27.01_What_Is_a_Portfolio_and_Why_Diversify.md) | 🔴 Advanced | 30 min | [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md), [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) | [`[27.02]`](docs/27_Portfolio_Management/27.02_Asset_Allocation_Fundamentals.md) |
| `[27.02]` | [Asset Allocation Fundamentals](docs/27_Portfolio_Management/27.02_Asset_Allocation_Fundamentals.md) | 🔴 Advanced | 30 min | [`[27.01]`](docs/27_Portfolio_Management/27.01_What_Is_a_Portfolio_and_Why_Diversify.md), [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) | [`[27.03]`](docs/27_Portfolio_Management/27.03_Modern_Portfolio_Theory_Risk_and_Return.md) |
| `[27.03]` | [Modern Portfolio Theory — Risk and Return](docs/27_Portfolio_Management/27.03_Modern_Portfolio_Theory_Risk_and_Return.md) | 🔴 Advanced | 35 min | [`[27.01]`](docs/27_Portfolio_Management/27.01_What_Is_a_Portfolio_and_Why_Diversify.md), [`[27.02]`](docs/27_Portfolio_Management/27.02_Asset_Allocation_Fundamentals.md) | [`[27.04]`](docs/27_Portfolio_Management/27.04_Correlation_and_Diversification_in_Practice.md) |
| `[27.04]` | [Correlation and Diversification in Practice](docs/27_Portfolio_Management/27.04_Correlation_and_Diversification_in_Practice.md) | 🔴 Advanced | 30 min | [`[27.03]`](docs/27_Portfolio_Management/27.03_Modern_Portfolio_Theory_Risk_and_Return.md), [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md) | [`[27.05]`](docs/27_Portfolio_Management/27.05_Rebalancing_Strategies.md) |
| `[27.05]` | [Rebalancing Strategies](docs/27_Portfolio_Management/27.05_Rebalancing_Strategies.md) | 🔴 Advanced | 30 min | [`[27.02]`](docs/27_Portfolio_Management/27.02_Asset_Allocation_Fundamentals.md), [`[27.04]`](docs/27_Portfolio_Management/27.04_Correlation_and_Diversification_in_Practice.md) | [`[27.06]`](docs/27_Portfolio_Management/27.06_Sector_Rotation_and_Business_Cycle_Investing.md) |
| `[27.06]` | [Sector Rotation and Business Cycle Investing](docs/27_Portfolio_Management/27.06_Sector_Rotation_and_Business_Cycle_Investing.md) | 🔴 Advanced | 30 min | [`[27.05]`](docs/27_Portfolio_Management/27.05_Rebalancing_Strategies.md), [`[05.08]`](docs/05_Economics/05.08_Business_Cycles_Expansion_Peak_Recession_Trough.md) | [`[27.07]`](docs/27_Portfolio_Management/27.07_Building_a_Core_Satellite_Portfolio.md) |
| `[27.07]` | [Building a Core-Satellite Portfolio](docs/27_Portfolio_Management/27.07_Building_a_Core_Satellite_Portfolio.md) | 🔴 Advanced | 30 min | [`[27.06]`](docs/27_Portfolio_Management/27.06_Sector_Rotation_and_Business_Cycle_Investing.md), [`[24.11]`](docs/24_Trading_Strategies/24.11_Combining_Strategies_into_a_Portfolio_of_Systems.md) | [`[27.08]`](docs/27_Portfolio_Management/27.08_Performance_Measurement.md) |
| `[27.08]` | [Performance Measurement (Sharpe, Sortino, Alpha, Beta)](docs/27_Portfolio_Management/27.08_Performance_Measurement.md) | 🔴 Advanced | 35 min | [`[27.07]`](docs/27_Portfolio_Management/27.07_Building_a_Core_Satellite_Portfolio.md), [`[27.03]`](docs/27_Portfolio_Management/27.03_Modern_Portfolio_Theory_Risk_and_Return.md) | [`[28.01]`](docs/28_Trading_Psychology/28.01_Why_Psychology_Determines_Trading_Outcomes.md) |

### Module 28 — Trading Psychology

[Module Index](docs/28_Trading_Psychology/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[28.01]` | [Why Psychology Determines Trading Outcomes](docs/28_Trading_Psychology/28.01_Why_Psychology_Determines_Trading_Outcomes.md) | 🔴 Advanced | 30 min | [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md), [`[25.08]`](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md) | [`[28.02]`](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md) |
| `[28.02]` | [Fear and Greed Cycle](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md) | 🔴 Advanced | 30 min | [`[28.01]`](docs/28_Trading_Psychology/28.01_Why_Psychology_Determines_Trading_Outcomes.md), [`[23.05]`](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md) | [`[28.03]`](docs/28_Trading_Psychology/28.03_Cognitive_Biases_in_Trading.md) |
| `[28.03]` | [Cognitive Biases in Trading (Confirmation, Recency, Loss Aversion)](docs/28_Trading_Psychology/28.03_Cognitive_Biases_in_Trading.md) | 🔴 Advanced | 30 min | [`[28.02]`](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md), [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) | [`[28.04]`](docs/28_Trading_Psychology/28.04_Revenge_Trading_and_Tilt.md) |
| `[28.04]` | [Revenge Trading and Tilt](docs/28_Trading_Psychology/28.04_Revenge_Trading_and_Tilt.md) | 🔴 Advanced | 30 min | [`[28.03]`](docs/28_Trading_Psychology/28.03_Cognitive_Biases_in_Trading.md), [`[26.01]`](docs/26_Position_Sizing/26.01_What_Is_Position_Sizing_and_Why_Its_the_Real_Edge.md) | [`[28.05]`](docs/28_Trading_Psychology/28.05_FOMO_and_Overtrading.md) |
| `[28.05]` | [FOMO and Overtrading](docs/28_Trading_Psychology/28.05_FOMO_and_Overtrading.md) | 🔴 Advanced | 30 min | [`[28.04]`](docs/28_Trading_Psychology/28.04_Revenge_Trading_and_Tilt.md), [`[28.02]`](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md) | [`[28.06]`](docs/28_Trading_Psychology/28.06_Discipline_Rules_and_Trading_Plans.md) |
| `[28.06]` | [Discipline, Rules, and Trading Plans](docs/28_Trading_Psychology/28.06_Discipline_Rules_and_Trading_Plans.md) | 🔴 Advanced | 30 min | [`[28.05]`](docs/28_Trading_Psychology/28.05_FOMO_and_Overtrading.md), [`[25.08]`](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md) | [`[28.07]`](docs/28_Trading_Psychology/28.07_Building_Emotional_Resilience_After_a_Loss.md) |
| `[28.07]` | [Building Emotional Resilience After a Loss](docs/28_Trading_Psychology/28.07_Building_Emotional_Resilience_After_a_Loss.md) | 🔴 Advanced | 30 min | [`[28.06]`](docs/28_Trading_Psychology/28.06_Discipline_Rules_and_Trading_Plans.md), [`[28.04]`](docs/28_Trading_Psychology/28.04_Revenge_Trading_and_Tilt.md) | [`[28.08]`](docs/28_Trading_Psychology/28.08_The_Psychology_of_Professional_vs_Retail_Traders.md) |
| `[28.08]` | [The Psychology of Professional vs Retail Traders](docs/28_Trading_Psychology/28.08_The_Psychology_of_Professional_vs_Retail_Traders.md) | 🔴 Advanced | 35 min | [`[28.01]`](docs/28_Trading_Psychology/28.01_Why_Psychology_Determines_Trading_Outcomes.md), [`[28.07]`](docs/28_Trading_Psychology/28.07_Building_Emotional_Resilience_After_a_Loss.md), [`[25.08]`](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md) | [`[29.01]`](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md) |

### Module 29 — Algorithmic Trading

[Module Index](docs/29_Algorithmic_Trading/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[29.01]` | [What Is Algorithmic Trading](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md) | 🔴 Advanced | 30 min | [`[28.08]`](docs/28_Trading_Psychology/28.08_The_Psychology_of_Professional_vs_Retail_Traders.md), [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) | [`[29.02]`](docs/29_Algorithmic_Trading/29.02_Rule_Based_Systems_vs_Discretionary_Trading.md) |
| `[29.02]` | [Rule-Based Systems vs Discretionary Trading](docs/29_Algorithmic_Trading/29.02_Rule_Based_Systems_vs_Discretionary_Trading.md) | 🔴 Advanced | 30 min | [`[29.01]`](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md), [`[13.10]`](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md) | [`[29.03]`](docs/29_Algorithmic_Trading/29.03_Backtesting_Fundamentals_and_Pitfalls.md) |
| `[29.03]` | [Backtesting Fundamentals and Pitfalls](docs/29_Algorithmic_Trading/29.03_Backtesting_Fundamentals_and_Pitfalls.md) | 🔴 Advanced | 35 min | [`[29.02]`](docs/29_Algorithmic_Trading/29.02_Rule_Based_Systems_vs_Discretionary_Trading.md), [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) | [`[29.04]`](docs/29_Algorithmic_Trading/29.04_Overfitting_and_Curve_Fitting.md) |
| `[29.04]` | [Overfitting and Curve-Fitting](docs/29_Algorithmic_Trading/29.04_Overfitting_and_Curve_Fitting.md) | 🔴 Advanced | 30 min | [`[29.03]`](docs/29_Algorithmic_Trading/29.03_Backtesting_Fundamentals_and_Pitfalls.md), [`[26.04]`](docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md) | [`[29.05]`](docs/29_Algorithmic_Trading/29.05_Order_Execution_Algorithms.md) |
| `[29.05]` | [Order Execution Algorithms (TWAP, VWAP, Iceberg)](docs/29_Algorithmic_Trading/29.05_Order_Execution_Algorithms.md) | 🔴 Advanced | 30 min | [`[29.04]`](docs/29_Algorithmic_Trading/29.04_Overfitting_and_Curve_Fitting.md), [`[01.08]`](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md) | [`[29.06]`](docs/29_Algorithmic_Trading/29.06_Building_a_Simple_Trading_Bot_Architecture_Overview.md) |
| `[29.06]` | [Building a Simple Trading Bot — Architecture Overview](docs/29_Algorithmic_Trading/29.06_Building_a_Simple_Trading_Bot_Architecture_Overview.md) | 🔴 Advanced | 35 min | [`[29.05]`](docs/29_Algorithmic_Trading/29.05_Order_Execution_Algorithms.md), [`[29.03]`](docs/29_Algorithmic_Trading/29.03_Backtesting_Fundamentals_and_Pitfalls.md) | [`[29.07]`](docs/29_Algorithmic_Trading/29.07_Algo_Trading_Regulations_in_India.md) |
| `[29.07]` | [Algo Trading Regulations in India (SEBI API Trading Rules)](docs/29_Algorithmic_Trading/29.07_Algo_Trading_Regulations_in_India.md) | 🔴 Advanced | 30 min | [`[29.06]`](docs/29_Algorithmic_Trading/29.06_Building_a_Simple_Trading_Bot_Architecture_Overview.md), [`[03.02]`](docs/03_Indian_Market/03.02_SEBI_Role_Powers_and_Investor_Protection.md) | [`[29.08]`](docs/29_Algorithmic_Trading/29.08_High_Frequency_Trading_How_It_Actually_Works.md) |
| `[29.08]` | [High-Frequency Trading — How It Actually Works](docs/29_Algorithmic_Trading/29.08_High_Frequency_Trading_How_It_Actually_Works.md) | 🔴 Advanced | 35 min | [`[29.07]`](docs/29_Algorithmic_Trading/29.07_Algo_Trading_Regulations_in_India.md), [`[29.01]`](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md) | [`[30.01]`](docs/30_Quantitative_Trading/30.01_What_Is_Quantitative_Trading.md) |

### Module 30 — Quantitative Trading

[Module Index](docs/30_Quantitative_Trading/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[30.01]` | [What Is Quantitative Trading](docs/30_Quantitative_Trading/30.01_What_Is_Quantitative_Trading.md) | 🔴 Advanced | 30 min | [`[29.01]`](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md), [`[27.08]`](docs/27_Portfolio_Management/27.08_Performance_Measurement.md) | [`[30.02]`](docs/30_Quantitative_Trading/30.02_Statistical_Foundations_for_Traders.md) |
| `[30.02]` | [Statistical Foundations for Traders (Mean, Variance, Distribution)](docs/30_Quantitative_Trading/30.02_Statistical_Foundations_for_Traders.md) | 🔴 Advanced | 30 min | [`[30.01]`](docs/30_Quantitative_Trading/30.01_What_Is_Quantitative_Trading.md), [`[25.07]`](docs/25_Risk_Management/25.07_Black_Swan_Events_and_Tail_Risk.md) | [`[30.03]`](docs/30_Quantitative_Trading/30.03_Correlation_Cointegration_and_Pairs_Trading.md) |
| `[30.03]` | [Correlation, Cointegration, and Pairs Trading](docs/30_Quantitative_Trading/30.03_Correlation_Cointegration_and_Pairs_Trading.md) | 🔴 Advanced | 35 min | [`[30.02]`](docs/30_Quantitative_Trading/30.02_Statistical_Foundations_for_Traders.md), [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md) | [`[30.04]`](docs/30_Quantitative_Trading/30.04_Mean_Reversion_vs_Momentum_A_Quant_View.md) |
| `[30.04]` | [Mean Reversion vs Momentum — A Quant View](docs/30_Quantitative_Trading/30.04_Mean_Reversion_vs_Momentum_A_Quant_View.md) | 🔴 Advanced | 30 min | [`[30.03]`](docs/30_Quantitative_Trading/30.03_Correlation_Cointegration_and_Pairs_Trading.md), [`[24.02]`](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md), [`[24.03]`](docs/24_Trading_Strategies/24.03_Mean_Reversion_Strategy_Framework.md) | [`[30.05]`](docs/30_Quantitative_Trading/30.05_Factor_Investing_Basics.md) |
| `[30.05]` | [Factor Investing Basics (Value, Momentum, Quality, Low-Vol)](docs/30_Quantitative_Trading/30.05_Factor_Investing_Basics.md) | 🔴 Advanced | 30 min | [`[30.04]`](docs/30_Quantitative_Trading/30.04_Mean_Reversion_vs_Momentum_A_Quant_View.md), [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) | [`[30.06]`](docs/30_Quantitative_Trading/30.06_Market_Making_How_Quant_Firms_Provide_Liquidity.md) |
| `[30.06]` | [Market Making — How Quant Firms Provide Liquidity](docs/30_Quantitative_Trading/30.06_Market_Making_How_Quant_Firms_Provide_Liquidity.md) | 🔴 Advanced | 30 min | [`[30.05]`](docs/30_Quantitative_Trading/30.05_Factor_Investing_Basics.md), [`[29.08]`](docs/29_Algorithmic_Trading/29.08_High_Frequency_Trading_How_It_Actually_Works.md) | [`[30.07]`](docs/30_Quantitative_Trading/30.07_Risk_Models_and_Portfolio_Optimization_Basics.md) |
| `[30.07]` | [Risk Models and Portfolio Optimization Basics](docs/30_Quantitative_Trading/30.07_Risk_Models_and_Portfolio_Optimization_Basics.md) | 🔴 Advanced | 35 min | [`[30.06]`](docs/30_Quantitative_Trading/30.06_Market_Making_How_Quant_Firms_Provide_Liquidity.md), [`[27.03]`](docs/27_Portfolio_Management/27.03_Modern_Portfolio_Theory_Risk_and_Return.md) | [`[30.08]`](docs/30_Quantitative_Trading/30.08_Careers_and_Firms_in_Quant_Trading.md) |
| `[30.08]` | [Careers and Firms in Quant Trading (India & Global)](docs/30_Quantitative_Trading/30.08_Careers_and_Firms_in_Quant_Trading.md) | 🔴 Advanced | 30 min | [`[30.07]`](docs/30_Quantitative_Trading/30.07_Risk_Models_and_Portfolio_Optimization_Basics.md), [`[30.01]`](docs/30_Quantitative_Trading/30.01_What_Is_Quantitative_Trading.md) | [`[31.01]`](docs/31_Case_Studies/31.01_2008_Global_Financial_Crisis.md) |

### Module 31 — Case Studies

[Module Index](docs/31_Case_Studies/_Index.md)

| Lesson | Title | Level | Time | Prerequisites | Next |
|---|---|---|---|---|---|
| `[31.01]` | [2008 Global Financial Crisis](docs/31_Case_Studies/31.01_2008_Global_Financial_Crisis.md) | 🔴 Advanced | 40 min | [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md), [`[07.07]`](docs/07_Financial_Statements/07.07_Debt_Equity_and_Capital_Structure.md) | [`[31.02]`](docs/31_Case_Studies/31.02_2020_COVID_Crash_and_V_Shaped_Recovery.md) |
| `[31.02]` | [2020 COVID Crash and V-Shaped Recovery](docs/31_Case_Studies/31.02_2020_COVID_Crash_and_V_Shaped_Recovery.md) | 🔴 Advanced | 35 min | [`[31.01]`](docs/31_Case_Studies/31.01_2008_Global_Financial_Crisis.md), [`[23.05]`](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md) | [`[31.03]`](docs/31_Case_Studies/31.03_Harshad_Mehta_Scam_1992.md) |
| `[31.03]` | [Harshad Mehta Scam (1992) and Indian Market Reform](docs/31_Case_Studies/31.03_Harshad_Mehta_Scam_1992.md) | 🔴 Advanced | 35 min | [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md), [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) | [`[31.04]`](docs/31_Case_Studies/31.04_Ketan_Parekh_Scam_2001.md) |
| `[31.04]` | [Ketan Parekh Scam (2001)](docs/31_Case_Studies/31.04_Ketan_Parekh_Scam_2001.md) | 🔴 Advanced | 30 min | [`[31.03]`](docs/31_Case_Studies/31.03_Harshad_Mehta_Scam_1992.md), [`[03.09]`](docs/03_Indian_Market/03.09_Indian_Market_Regulations_Insider_Trading_Circuit_Filters_Surveillance.md) | [`[31.05]`](docs/31_Case_Studies/31.05_2004_Indian_Election_Result_Crash.md) |
| `[31.05]` | [2004 Indian Election Result Crash](docs/31_Case_Studies/31.05_2004_Indian_Election_Result_Crash.md) | 🔴 Advanced | 30 min | [`[03.10]`](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md), [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) | [`[31.06]`](docs/31_Case_Studies/31.06_May_2022_IndusInd_Bank_Adani_Group_Episodes.md) |
| `[31.06]` | [IndusInd Bank and Adani Group Episodes](docs/31_Case_Studies/31.06_May_2022_IndusInd_Bank_Adani_Group_Episodes.md) | 🔴 Advanced | 30 min | [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md), [`[08.08]`](docs/08_Fundamental_Analysis/08.08_Management_Quality_and_Corporate_Governance.md) | [`[31.07]`](docs/31_Case_Studies/31.07_GameStop_Short_Squeeze_2021.md) |
| `[31.07]` | [GameStop Short Squeeze (2021)](docs/31_Case_Studies/31.07_GameStop_Short_Squeeze_2021.md) | 🔴 Advanced | 35 min | [`[01.05]`](docs/01_Foundation/01.05_Market_Participants.md), [`[28.05]`](docs/28_Trading_Psychology/28.05_FOMO_and_Overtrading.md) | [`[31.08]`](docs/31_Case_Studies/31.08_Long_Term_Capital_Management_Collapse_1998.md) |
| `[31.08]` | [Long-Term Capital Management Collapse (1998)](docs/31_Case_Studies/31.08_Long_Term_Capital_Management_Collapse_1998.md) | 🔴 Advanced | 35 min | [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md), [`[30.03]`](docs/30_Quantitative_Trading/30.03_Correlation_Cointegration_and_Pairs_Trading.md) | [`[31.09]`](docs/31_Case_Studies/31.09_Dot_Com_Bubble_2000.md) |
| `[31.09]` | [Dot-Com Bubble (2000)](docs/31_Case_Studies/31.09_Dot_Com_Bubble_2000.md) | 🔴 Advanced | 35 min | [`[09.01]`](docs/09_Valuation/09.01_What_Is_Valuation_and_Why_It_Matters.md), [`[28.02]`](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md) | [`[31.10]`](docs/31_Case_Studies/31.10_Satyam_Scandal_2009.md) |
| `[31.10]` | [Satyam Scandal (2009) — India's Enron](docs/31_Case_Studies/31.10_Satyam_Scandal_2009.md) | 🔴 Advanced | 35 min | [`[07.06]`](docs/07_Financial_Statements/07.06_Revenue_Recognition_and_Earnings_Quality.md), [`[08.08]`](docs/08_Fundamental_Analysis/08.08_Management_Quality_and_Corporate_Governance.md) | — |

---

## Part 2 — Reference Modules (32–40, 116 Files)

### Module 32 — Daily Market Analysis
[Module Index](docs/32_Daily_Market_Analysis/_Index.md) · ⚪ Reference · A living, extensible module (see `docs/32_Daily_Market_Analysis/_Index.md` for how to add your own entries)

| File | Purpose |
|---|---|
| [Daily Analysis Template](docs/32_Daily_Market_Analysis/DAILY_ANALYSIS_TEMPLATE.md) | Reusable 9-section template for analyzing any trading day |
| [Example 1 — Trend Day](docs/32_Daily_Market_Analysis/Example_01_Trend_Day.md) | Worked example: a clean, confirmed-trend session |
| [Example 2 — Range Day](docs/32_Daily_Market_Analysis/Example_02_Range_Day.md) | Worked example: a range-bound, mean-reversion session |
| [Example 3 — Event-Driven Day](docs/32_Daily_Market_Analysis/Example_03_Event_Driven_Day.md) | Worked example: an RBI policy/event day |

### Module 33 — Glossary
[Module Index](docs/33_Glossary/_Index.md) · ⚪ Reference · **125 terms** across 4 files, each cross-linked to its originating lesson

| File | Range | Terms |
|---|---|---|
| [Glossary A–D](docs/33_Glossary/Glossary_A-D.md) | A – D | 34 |
| [Glossary E–L](docs/33_Glossary/Glossary_E-L.md) | E – L | 34 |
| [Glossary M–R](docs/33_Glossary/Glossary_M-R.md) | M – R | 27 |
| [Glossary S–Z](docs/33_Glossary/Glossary_S-Z.md) | S – Z | 30 |

> **Known gap (tracked in `AUDIT_REPORT.md`, finding AUDIT-001):** the glossary's 125 terms do not yet cover every term taught across the 270 core lessons — Modules 10–19 in particular introduce substantially more specialized vocabulary (candlestick/chart-pattern names, Point of Control, Kill Zone, etc.) than currently has a glossary entry. This index reflects the glossary's *current* state; see the audit report for the full remediation list.

### Module 34 — Flashcards
[Module Index](docs/34_Flashcards/_Index.md) · ⚪ Reference · 10 decks, 20 cards each (200 cards total), mirrors Module 35's cluster grouping

| Deck | Covers |
|---|---|
| [1 — Foundation](docs/34_Flashcards/Deck_01_Foundation.md) | Modules 01–02, 07–09 |
| [2 — Indian Market](docs/34_Flashcards/Deck_02_Indian_Market.md) | Module 03 |
| [3 — Macro](docs/34_Flashcards/Deck_03_Macro.md) | Modules 04–06 |
| [4 — Technical Analysis](docs/34_Flashcards/Deck_04_Technical_Analysis.md) | Modules 10–16 |
| [5 — SMC/ICT/Wyckoff](docs/34_Flashcards/Deck_05_SMC_ICT_Wyckoff.md) | Modules 17–19 |
| [6 — Derivatives](docs/34_Flashcards/Deck_06_Derivatives.md) | Modules 20–23 |
| [7 — Risk & Strategy](docs/34_Flashcards/Deck_07_Risk_and_Strategy.md) | Modules 24–27 |
| [8 — Psychology](docs/34_Flashcards/Deck_08_Psychology.md) | Module 28 |
| [9 — Quant & Algo](docs/34_Flashcards/Deck_09_Quant_and_Algo.md) | Modules 29–30 |
| [10 — Case Studies](docs/34_Flashcards/Deck_10_Case_Studies.md) | Module 31 |

### Module 35 — CheatSheets
[Module Index](docs/35_CheatSheets/_Index.md) · ⚪ Reference · 10 one-page quick-reference sheets, same cluster grouping as Module 34

| Sheet | Covers |
|---|---|
| [1 — Foundation](docs/35_CheatSheets/Sheet_01_Foundation.md) | Modules 01–02, 07–09 |
| [2 — Indian Market](docs/35_CheatSheets/Sheet_02_Indian_Market.md) | Module 03 |
| [3 — Macro](docs/35_CheatSheets/Sheet_03_Macro.md) | Modules 04–06 |
| [4 — Technical Analysis](docs/35_CheatSheets/Sheet_04_Technical_Analysis.md) | Modules 10–16 |
| [5 — SMC/ICT/Wyckoff](docs/35_CheatSheets/Sheet_05_SMC_ICT_Wyckoff.md) | Modules 17–19 |
| [6 — Derivatives](docs/35_CheatSheets/Sheet_06_Derivatives.md) | Modules 20–23 |
| [7 — Risk & Strategy](docs/35_CheatSheets/Sheet_07_Risk_and_Strategy.md) | Modules 24–27 |
| [8 — Psychology](docs/35_CheatSheets/Sheet_08_Psychology.md) | Module 28 |
| [9 — Quant & Algo](docs/35_CheatSheets/Sheet_09_Quant_and_Algo.md) | Modules 29–30 |
| [10 — Case Studies](docs/35_CheatSheets/Sheet_10_Case_Studies.md) | Module 31 |

### Module 36 — Quizzes
[Module Index](docs/36_Quizzes/_Index.md) · ⚪ Reference · 8 consolidated, cross-cluster quizzes (113 questions total) — distinct from the quiz embedded in every individual lesson; use `templates/QUIZ_TEMPLATE.md`'s scoring guide (75%+ to proceed)

| Quiz | Covers | Questions |
|---|---|---|
| [1 — Foundation](docs/36_Quizzes/Quiz_01_Foundation.md) | Modules 01–02, 07–09 | 15 |
| [2 — Indian Market](docs/36_Quizzes/Quiz_02_Indian_Market.md) | Module 03 | 12 |
| [3 — Macro](docs/36_Quizzes/Quiz_03_Macro.md) | Modules 04–06 | 12 |
| [4 — Technical Analysis](docs/36_Quizzes/Quiz_04_Technical_Analysis.md) | Modules 10–16 | 15 |
| [5 — SMC/ICT/Wyckoff](docs/36_Quizzes/Quiz_05_SMC_ICT_Wyckoff.md) | Modules 17–19 | 12 |
| [6 — Derivatives](docs/36_Quizzes/Quiz_06_Derivatives.md) | Modules 20–23 | 15 |
| [7 — Risk & Psychology](docs/36_Quizzes/Quiz_07_Risk_and_Psychology.md) | Modules 24–28 | 18 |
| [8 — Quant & Algo](docs/36_Quizzes/Quiz_08_Quant_and_Algo.md) | Modules 29–30 | 14 |

### Module 37 — Assessments
[Module Index](docs/37_Assessments/_Index.md) · Formal, graded, cumulative exams — take only after completing every module in the stated scope **and** passing the corresponding Module 36 quiz at 75%+

| Assessment | Scope | Level |
|---|---|---|
| [Beginner Certification](docs/37_Assessments/Beginner_Certification.md) | Modules 01–09 | 🟢 Beginner |
| [Intermediate Certification](docs/37_Assessments/Intermediate_Certification.md) | Modules 10–19 | 🟡 Intermediate |
| [Derivatives Proficiency](docs/37_Assessments/Derivatives_Proficiency.md) | Modules 20–23 | 🔴 Advanced |
| [Risk Management Proficiency](docs/37_Assessments/Risk_Management_Proficiency.md) | Modules 25–27 | 🔴 Advanced |
| [Capstone Readiness Exam](docs/37_Assessments/Capstone_Readiness_Exam.md) | Modules 01–28 (cumulative) | 🔴 Advanced |
| [Professional-Track Final Exam](docs/37_Assessments/Professional_Track_Final_Exam.md) | Modules 01–28 (professional depth, 80% bar) | 🔴 Advanced |
| [Quant Track Exam](docs/37_Assessments/Quant_Track_Exam.md) | Modules 29–30 | 🔴 Advanced |
| [Full Academy Final Exam](docs/37_Assessments/Full_Academy_Final_Exam.md) | Modules 01–31 (complete, 31 integrative questions) | 🔴 Advanced |

### Module 38 — Practice
[Module Index](docs/38_Practice/_Index.md) · ⚪ Reference · 8 hands-on drills, each with step-by-step instructions and a fully worked example

| Drill | Focus |
|---|---|
| [1 — Chart Marking: Structure](docs/38_Practice/Drill_01_Chart_Marking_Structure.md) | Market structure annotation (`[02.01]`–`[02.08]`) |
| [2 — Chart Marking: Patterns](docs/38_Practice/Drill_02_Chart_Marking_Patterns.md) | Candlestick/chart pattern identification (`[11]`–`[12]`) |
| [3 — Options Payoff Worksheet](docs/38_Practice/Drill_03_Options_Payoff_Worksheet.md) | Payoff diagram construction by hand (`[21.05]`–`[21.10]`) |
| [4 — Greeks Calculation Worksheet](docs/38_Practice/Drill_04_Greeks_Calculation_Worksheet.md) | Greeks-based position estimation (`[22.02]`–`[22.06]`) |
| [5 — Risk Sizing Calculator](docs/38_Practice/Drill_05_Risk_Sizing_Calculator.md) | Position sizing by hand (`[25.02]`–`[26.04]`) |
| [6 — Journaling Drill](docs/38_Practice/Drill_06_Journaling_Drill.md) | Trade journal construction (`[24.12]`) |
| [7 — Backtesting Drill](docs/38_Practice/Drill_07_Backtesting_Drill.md) | Manual mini-backtest exercise (`[29.03]`–`[29.04]`) |
| [8 — Psychology Self-Audit](docs/38_Practice/Drill_08_Psychology_Self_Audit.md) | Personal bias/discipline audit (`[28.01]`–`[28.08]`) |

### Module 39 — Projects
[Module Index](docs/39_Projects/_Index.md) · 🔴 Advanced (capstone-level) · 6 capstone project briefs — complete `[37]`'s Capstone Readiness Exam first

| Project | Deliverable |
|---|---|
| [1 — Trading Plan](docs/39_Projects/Project_01_Trading_Plan.md) | A complete, personal written trading plan |
| [2 — Stock Screener](docs/39_Projects/Project_02_Stock_Screener.md) | A fundamental/technical stock screening tool |
| [3 — Strategy Backtest](docs/39_Projects/Project_03_Strategy_Backtest.md) | A rigorously backtested simple strategy |
| [4 — Risk Dashboard](docs/39_Projects/Project_04_Risk_Dashboard.md) | A personal portfolio risk monitoring dashboard |
| [5 — Macro Dashboard](docs/39_Projects/Project_05_Macro_Dashboard.md) | A macro/global market context dashboard |
| [6 — Paper-Trade a Quarter](docs/39_Projects/Project_06_Paper_Trade_Quarter.md) | A full quarter of paper-traded results, reported |

### Module 40 — Resources
[Module Index](docs/40_Resources/_Index.md) · ⚪ Reference · Curated further-learning material; usable at any point in the curriculum

| File | Purpose |
|---|---|
| [Recommended Books](docs/40_Resources/Recommended_Books.md) | Curated book list organized by topic |
| [Regulator Resources](docs/40_Resources/Regulator_Resources.md) | Official SEBI/RBI/NSE/BSE/SEC/Fed/CBOE resources |
| [Data Sources](docs/40_Resources/Data_Sources.md) | Market data, charting, and research sources |
| [Keep Learning Guide](docs/40_Resources/Keep_Learning_Guide.md) | How to continue learning after completing this academy |
| [Full Book & Paper Bibliography](docs/40_Resources/Full_Book_Bibliography.md) | Every book/paper cited across Modules 01–31, consolidated |

---

## Part 3 — Special Root Documents

Not part of the numbered module system, but referenced throughout:

| Document | Purpose |
|---|---|
| [README.md](README.md) | Project overview, repository structure, build-progress table |
| [MASTER_SKILL.md](MASTER_SKILL.md) | The teaching constitution — mandatory lesson template, content standards, non-negotiable rules |
| [CURRICULUM.md](CURRICULUM.md) | The full syllabus map (source of truth for planning) |
| [LEARNING_PATH.md](LEARNING_PATH.md) | Recommended student sequencing, with rationale for interleaving (e.g., Psychology alongside Risk) |
| [ROADMAP.md](ROADMAP.md) | Build milestones and their completion status |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Contribution process, including the maintainer checklist |
| [TODO.md](TODO.md) | Live build/maintenance tracker |
| [CHANGELOG.md](CHANGELOG.md) | Dated, most-recent-first change log |
| [AUDIT_REPORT.md](AUDIT_REPORT.md) | Independent pre-publication quality audit (41 findings, 2026-08-05) |
| [progress_tracker/STUDENT_PROGRESS_TEMPLATE.md](progress_tracker/STUDENT_PROGRESS_TEMPLATE.md) | Template for tracking your own progress through the curriculum |
| [market_journal/JOURNAL_TEMPLATE.md](market_journal/JOURNAL_TEMPLATE.md) | Template for a personal market journal |
| [templates/](templates/) | `LESSON_TEMPLATE.md`, `CASE_STUDY_TEMPLATE.md`, `QUIZ_TEMPLATE.md` — the boilerplate every content file in this repo is built from |

---

*This index is generated from source file metadata, not hand-maintained prose — see `CONTRIBUTING.md`'s Maintainer Checklist for how to regenerate it after adding or editing lessons.*
