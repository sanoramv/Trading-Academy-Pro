# ASSET_PLAN.md — Prioritized Visual-Asset Backlog

> **Planning document only. No assets are created here.** Every lesson in
> Trading-Academy-Pro already ships with a text-native ASCII diagram inside
> its own `## Core Concepts` section (per `MASTER_SKILL.md`'s lesson
> template) — this file identifies which lessons would additionally benefit
> from a *produced* graphical asset (an actual illustration, not ASCII art),
> of which kind, and in what order. It is a backlog, not a gallery.

## The 8 Asset Types

| Type | What it is | Best suited to |
|---|---|---|
| **Market Structure Diagram** | Annotated price-structure schematic (highs/lows, ranges, profile shape) | Market Structure, Technical Analysis, Price Action, Market/Volume Profile, Wyckoff, Smart Money, ICT |
| **Option Payoff Diagram** | P&L-vs-underlying-price curve at expiry | Options, Greeks, Portfolio hedging |
| **Candlestick Illustration** | Precisely proportioned candle bodies/wicks for a named pattern | Candlesticks, Price Action, Wyckoff |
| **Order Flow Diagram** | Depth/imbalance/absorption visualization | Order mechanics, Market Structure, Wyckoff/Smart Money/ICT, Algorithmic Trading |
| **Flowchart** | Multi-step process or decision sequence | Order execution, futures/risk processes, algo logic, statement/fundamental analysis steps |
| **Decision Tree** | Branching choice with explicit criteria at each node | Strategy selection, position sizing, options-strategy selection, psychology decision points |
| **Timeline Diagram** | Horizontal sequence-of-events | Case studies, macro cycles, historical examples |
| **Infographic** | Single at-a-glance overview or comparison | "X vs Y" lessons, overviews, participant/type comparisons |

## Methodology

For each of the 270 core lessons (Modules 01-31):

1. **Type scoring** — each of the 8 types gets a score from two signals:
   *module affinity* (does this lesson's module naturally produce this kind
   of content? e.g. Module 21 Options → Option Payoff Diagram) and *title
   cues* (does the lesson title itself contain a strong keyword, e.g.
   "payoff", "candle", "vs", "process"). Both signals are listed per item
   below as **Signal**, so this is auditable, not a black box.
2. **Selection** — the top-scoring type is always kept; a second type is
   kept only if it also scored above zero (most lessons need one asset,
   some genuinely need two — e.g. an options lesson that is also a decision
   point). Lessons matching no type get a low-priority Infographic fallback,
   so every lesson has at least one line item, per the request that every
   lesson be covered.
3. **Priority score** = `type_weight × 10 + downstream_reuse_count × 3 +
   foundational_bonus`. `type_weight` reflects how hard the concept is to
   convey in prose/ASCII (candlesticks, option payoffs, and structure/order-
   flow diagrams score highest — they are inherently graphical; infographics
   score lowest — a well-written comparison table already does most of the
   job). `downstream_reuse_count` is the number of other lessons that list
   this lesson as a prerequisite (same computation as `KNOWLEDGE_GRAPH.md`'s
   "Advanced Topics" column) — a diagram used as a mental model by many
   downstream lessons pays for itself many times over. `foundational_bonus`
   adds weight to Modules 01-02, since errors or gaps there compound
   everywhere else.
4. **Tiering** — items are sorted by score and cut into four tiers by
   quantile (top ~15% P0, next ~25% P1, next ~35% P2, remaining ~25% P3),
   the same Critical/High/Medium/Low convention `AUDIT_REPORT.md` uses.

This produced **393 backlog items** across 270 lessons (some
lessons produced two items, a few produced none from scoring and received
the Infographic fallback).

## Backlog Summary by Asset Type

| Asset Type | P0 | P1 | P2 | P3 | Total |
|---|---|---|---|---|---|
| Market Structure Diagram | 37 | 31 | 0 | 0 | 68 |
| Option Payoff Diagram | 19 | 10 | 0 | 0 | 29 |
| Candlestick Illustration | 14 | 14 | 0 | 0 | 28 |
| Order Flow Diagram | 10 | 13 | 23 | 0 | 46 |
| Flowchart | 1 | 5 | 52 | 12 | 70 |
| Decision Tree | 0 | 2 | 33 | 5 | 40 |
| Timeline Diagram | 0 | 1 | 20 | 13 | 34 |
| Infographic | 0 | 2 | 10 | 66 | 78 |
| **Total** | **81** | **78** | **138** | **96** | **393** |

## How to Use This Backlog

Work top-down within P0 before starting P1, etc. Within a tier, batch by
asset type (the sections below are already grouped that way) so an
illustrator/designer can stay in one visual idiom per session rather than
context-switching between candlestick anatomy and payoff-curve math. No
asset should be produced without checking `KNOWLEDGE_GRAPH.md` first — if a
lesson's Related/Advanced Topics list other lessons needing the *same* asset
type, consider producing one reusable template asset rather than N nearly
identical ones (e.g., one blank option-payoff-diagram template reused with
different strike/premium annotations across Module 21).

---

## P0 — Critical (81 items)

Highest-leverage assets: inherently graphical concepts (payoff curves, candlestick shapes, structure/order-flow) in lessons many other lessons build on.

### P0 — Critical — Market Structure Diagram (37)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) Trend, Range, and Structure Basics | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram; title cue "Structure" | 13 | 94 |
| [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) Support and Resistance — First Principles | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram; title cue "Support" | 13 | 94 |
| [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) What Is Market Structure | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram; title cue "Structure" | 7 | 76 |
| [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) Higher Highs, Higher Lows, Lower Highs, Lower Lows | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram | 6 | 73 |
| [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) What Is Technical Analysis and Does It Work | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 7 | 71 |
| [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) Liquidity — What It Really Means | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram | 4 | 67 |
| [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) NSE vs BSE — Structure and Indices | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | title cue "Structure" | 5 | 65 |
| [`[02.05]`](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md) Break of Structure (BOS) vs Change of Character (CHOCH) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram; title cue "Structure" | 3 | 64 |
| [`[02.08]`](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md) Multi-Timeframe Structure Analysis | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram; title cue "Structure" | 3 | 64 |
| [`[10.05]`](docs/10_Technical_Analysis/10.05_Trendlines_and_Channels.md) Trendlines and Channels | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 4 | 62 |
| [`[10.12]`](docs/10_Technical_Analysis/10.12_Building_a_Technical_Analysis_Checklist.md) Building a Technical Analysis Checklist | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 4 | 62 |
| [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) Supply and Demand Zones | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 4 | 62 |
| [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md) Breakouts vs Fakeouts | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 4 | 62 |
| [`[02.07]`](docs/02_Market_Structure/02.07_Swing_Points_and_Fractals.md) Swing Points and Fractals | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 02 fits Market Structure Diagram; title cue "Swing" | 2 | 61 |
| [`[10.03]`](docs/10_Technical_Analysis/10.03_Types_of_Charts.md) Types of Charts (Line, Bar, Candlestick, Renko, Heikin-Ashi) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 3 | 59 |
| [`[10.06]`](docs/10_Technical_Analysis/10.06_Moving_Averages_SMA_EMA_WMA.md) Moving Averages — SMA, EMA, WMA | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 3 | 59 |
| [`[10.09]`](docs/10_Technical_Analysis/10.09_Fibonacci_Retracement_and_Extension.md) Fibonacci Retracement and Extension | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 3 | 59 |
| [`[13.10]`](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md) Building a Discretionary Price Action Playbook | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 3 | 59 |
| [`[15.01]`](docs/15_Market_Profile/15.01_Introduction_to_Market_Profile.md) Introduction to Market Profile (TPO) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 15 fits Market Structure Diagram; title cue "Profile" | 3 | 59 |
| [`[15.02]`](docs/15_Market_Profile/15.02_Value_Area_Point_of_Control_and_Range.md) Value Area, Point of Control, and Range | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 15 fits Market Structure Diagram; title cue "Range" | 3 | 59 |
| [`[16.01]`](docs/16_Volume_Profile/16.01_Introduction_to_Volume_Profile.md) Introduction to Volume Profile | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 16 fits Market Structure Diagram; title cue "Profile" | 3 | 59 |
| [`[17.03]`](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md) Accumulation Schematic — Phases A to E | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 3 | 59 |
| [`[18.01]`](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md) What Are Smart Money Concepts (SMC) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 3 | 59 |
| [`[18.02]`](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md) Liquidity Pools — Buy-Side and Sell-Side | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 3 | 59 |
| [`[19.01]`](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md) Introduction to ICT (Inner Circle Trader) Concepts | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 3 | 59 |
| [`[07.07]`](docs/07_Financial_Statements/07.07_Debt_Equity_and_Capital_Structure.md) Debt, Equity & Capital Structure on the Balance Sheet | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | title cue "Structure" | 2 | 56 |
| [`[10.07]`](docs/10_Technical_Analysis/10.07_Momentum_Oscillators_RSI_Stochastic_MACD.md) Momentum Oscillators — RSI, Stochastic, MACD | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 2 | 56 |
| [`[10.08]`](docs/10_Technical_Analysis/10.08_Volume_as_a_Confirming_Tool.md) Volume as a Confirming Tool | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 2 | 56 |
| [`[10.11]`](docs/10_Technical_Analysis/10.11_Multi_Indicator_Confluence_and_Its_Pitfalls.md) Multi-Indicator Confluence and Its Pitfalls | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 2 | 56 |
| [`[13.01]`](docs/13_Price_Action/13.01_What_Is_Pure_Price_Action_Trading.md) What Is Pure Price Action Trading | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 2 | 56 |
| [`[13.07]`](docs/13_Price_Action/13.07_Price_Action_at_Key_Levels.md) Price Action at Key Levels (Round Numbers, Prior Day High/Low) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 2 | 56 |
| [`[13.08]`](docs/13_Price_Action/13.08_Range_Trading_with_Price_Action.md) Range Trading with Price Action | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram; title cue "Range" | 2 | 56 |
| [`[17.01]`](docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md) Richard Wyckoff — History and Philosophy | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 2 | 56 |
| [`[17.05]`](docs/17_Wyckoff/17.05_Springs_Upthrusts_and_Tests.md) Springs, Upthrusts, and Tests | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 2 | 56 |
| [`[17.06]`](docs/17_Wyckoff/17.06_Composite_Man_Concept.md) Composite Man Concept | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 2 | 56 |
| [`[17.07]`](docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md) Wyckoff in Modern Markets — Does It Still Work | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 2 | 56 |
| [`[18.08]`](docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md) Criticisms and Limitations of SMC | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 2 | 56 |

### P0 — Critical — Option Payoff Diagram (19)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) Intrinsic Value vs Time Value | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 8 | 74 |
| [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md) Option Payoff Diagrams — Long Call, Long Put | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram; title cue "Payoff" | 5 | 65 |
| [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md) Option Payoff Diagrams — Short Call, Short Put | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram; title cue "Payoff" | 5 | 65 |
| [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md) Strike Price, Premium, and Moneyness (ITM/ATM/OTM) | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram; title cue "Strike" | 4 | 62 |
| [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) Iron Condor and Iron Butterfly | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 4 | 62 |
| [`[21.01]`](docs/21_Options/21.01_What_Is_an_Option.md) What Is an Option — Calls and Puts Explained | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 3 | 59 |
| [`[21.02]`](docs/21_Options/21.02_Option_Buyer_vs_Seller.md) Option Buyer vs Option Seller — Risk Profiles | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 3 | 59 |
| [`[21.11]`](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) Option Chain Analysis (India — NSE Option Chain) | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 3 | 59 |
| [`[21.12]`](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md) Common Option Buyer Mistakes (Theta Decay Trap) | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 3 | 59 |
| [`[22.01]`](docs/22_Greeks/22.01_Introduction_to_Option_Greeks.md) Introduction to Option Greeks | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram; title cue "Greeks" | 3 | 59 |
| [`[22.02]`](docs/22_Greeks/22.02_Delta_Directional_Sensitivity.md) Delta — Directional Sensitivity | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram | 3 | 59 |
| [`[27.03]`](docs/27_Portfolio_Management/27.03_Modern_Portfolio_Theory_Risk_and_Return.md) Modern Portfolio Theory — Risk and Return | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 3 | 59 |
| [`[21.08]`](docs/21_Options/21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md) Spreads — Bull Call Spread, Bear Put Spread | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram; title cue "Spread" | 2 | 56 |
| [`[21.09]`](docs/21_Options/21.09_Straddles_and_Strangles.md) Straddles and Strangles | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram | 2 | 56 |
| [`[22.04]`](docs/22_Greeks/22.04_Theta_Time_Decay.md) Theta — Time Decay | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram | 2 | 56 |
| [`[22.05]`](docs/22_Greeks/22.05_Vega_Volatility_Sensitivity.md) Vega — Volatility Sensitivity | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram | 2 | 56 |
| [`[27.01]`](docs/27_Portfolio_Management/27.01_What_Is_a_Portfolio_and_Why_Diversify.md) What Is a Portfolio and Why Diversify | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 2 | 56 |
| [`[27.02]`](docs/27_Portfolio_Management/27.02_Asset_Allocation_Fundamentals.md) Asset Allocation Fundamentals | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 2 | 56 |
| [`[27.04]`](docs/27_Portfolio_Management/27.04_Correlation_and_Diversification_in_Practice.md) Correlation and Diversification in Practice | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 2 | 56 |

### P0 — Critical — Candlestick Illustration (14)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[11.01]`](docs/11_Candlesticks/11.01_Anatomy_of_a_Candlestick.md) Anatomy of a Candlestick | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 9 | 77 |
| [`[13.03]`](docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md) Supply and Demand Zones | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 4 | 62 |
| [`[13.04]`](docs/13_Price_Action/13.04_Breakouts_vs_Fakeouts.md) Breakouts vs Fakeouts | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 4 | 62 |
| [`[13.10]`](docs/13_Price_Action/13.10_Building_a_Discretionary_Price_Action_Playbook.md) Building a Discretionary Price Action Playbook | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 3 | 59 |
| [`[17.03]`](docs/17_Wyckoff/17.03_Accumulation_Schematic_Phases_A_to_E.md) Accumulation Schematic — Phases A to E | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 3 | 59 |
| [`[11.02]`](docs/11_Candlesticks/11.02_Single_Candlestick_Patterns_Doji_Hammer_Shooting_Star.md) Single Candlestick Patterns — Doji, Hammer, Shooting Star | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 2 | 56 |
| [`[11.04]`](docs/11_Candlesticks/11.04_Two_Candle_Patterns_Engulfing_Harami.md) Two-Candle Patterns — Engulfing, Harami | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 2 | 56 |
| [`[13.01]`](docs/13_Price_Action/13.01_What_Is_Pure_Price_Action_Trading.md) What Is Pure Price Action Trading | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 2 | 56 |
| [`[13.07]`](docs/13_Price_Action/13.07_Price_Action_at_Key_Levels.md) Price Action at Key Levels (Round Numbers, Prior Day High/Low) | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 2 | 56 |
| [`[13.08]`](docs/13_Price_Action/13.08_Range_Trading_with_Price_Action.md) Range Trading with Price Action | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 2 | 56 |
| [`[17.01]`](docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md) Richard Wyckoff — History and Philosophy | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 2 | 56 |
| [`[17.05]`](docs/17_Wyckoff/17.05_Springs_Upthrusts_and_Tests.md) Springs, Upthrusts, and Tests | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 2 | 56 |
| [`[17.06]`](docs/17_Wyckoff/17.06_Composite_Man_Concept.md) Composite Man Concept | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 2 | 56 |
| [`[17.07]`](docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md) Wyckoff in Modern Markets — Does It Still Work | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 2 | 56 |

### P0 — Critical — Order Flow Diagram (10)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[02.02]`](docs/02_Market_Structure/02.02_Trend_Range_and_Structure_Basics.md) Trend, Range, and Structure Basics | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 13 | 84 |
| [`[02.04]`](docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md) Support and Resistance — First Principles | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 13 | 84 |
| [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md) What Is a Financial Market | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 9 | 72 |
| [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) How Stock Exchanges Work | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 9 | 72 |
| [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) Asset Classes Overview | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 7 | 66 |
| [`[02.01]`](docs/02_Market_Structure/02.01_What_Is_Market_Structure.md) What Is Market Structure | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 7 | 66 |
| [`[02.03]`](docs/02_Market_Structure/02.03_Higher_Highs_Higher_Lows_Lower_Highs_Lower_Lows.md) Higher Highs, Higher Lows, Lower Highs, Lower Lows | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 6 | 63 |
| [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) Reading Your First Stock Quote | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 5 | 60 |
| [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) Brokers, Depositories & Clearing Corporations | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 4 | 57 |
| [`[02.06]`](docs/02_Market_Structure/02.06_Liquidity_What_It_Really_Means.md) Liquidity — What It Really Means | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram; title cue "Liquidity" | 4 | 57 |

### P0 — Critical — Flowchart (1)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[01.04]`](docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md) How Stock Exchanges Work | Multi-step process best shown as a decision/process flow rather than prose. | Module 01 fits Flowchart; title cue "How" | 9 | 62 |

## P1 — High (78 items)

Strong visual payoff, somewhat narrower reuse, or a strong module/content fit without the top reuse count.

### P1 — High — Market Structure Diagram (31)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[10.02]`](docs/10_Technical_Analysis/10.02_Dow_Theory.md) Dow Theory — The Foundation of TA | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 1 | 53 |
| [`[10.10]`](docs/10_Technical_Analysis/10.10_Divergence_Regular_and_Hidden.md) Divergence — Regular and Hidden | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 1 | 53 |
| [`[13.02]`](docs/13_Price_Action/13.02_Reading_Candle_by_Candle_Behavior.md) Reading Candle-by-Candle Behavior | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 1 | 53 |
| [`[13.09]`](docs/13_Price_Action/13.09_Trend_Following_with_Price_Action.md) Trend-Following with Price Action | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram; title cue "Trend" | 1 | 53 |
| [`[15.03]`](docs/15_Market_Profile/15.03_Profile_Shapes.md) Profile Shapes — Normal, P, b, Trend Day | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 15 fits Market Structure Diagram; title cue "Trend" | 1 | 53 |
| [`[15.04]`](docs/15_Market_Profile/15.04_Initial_Balance_and_Its_Significance.md) Initial Balance and Its Significance | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 15 fits Market Structure Diagram | 1 | 53 |
| [`[15.05]`](docs/15_Market_Profile/15.05_Using_Market_Profile_for_Intraday_Bias.md) Using Market Profile for Intraday Bias | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 15 fits Market Structure Diagram; title cue "Profile" | 1 | 53 |
| [`[15.06]`](docs/15_Market_Profile/15.06_Composite_Profiles_and_Multi_Day_Analysis.md) Composite Profiles and Multi-Day Analysis | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 15 fits Market Structure Diagram | 1 | 53 |
| [`[16.02]`](docs/16_Volume_Profile/16.02_Value_Area_High_Low_POC.md) Value Area High, Value Area Low, POC | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 16 fits Market Structure Diagram | 1 | 53 |
| [`[16.03]`](docs/16_Volume_Profile/16.03_High_Volume_Nodes_vs_Low_Volume_Nodes.md) High Volume Nodes vs Low Volume Nodes | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 16 fits Market Structure Diagram | 1 | 53 |
| [`[16.04]`](docs/16_Volume_Profile/16.04_Volume_Profile_vs_Market_Profile.md) Volume Profile vs Market Profile — Key Differences | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 16 fits Market Structure Diagram; title cue "Profile" | 1 | 53 |
| [`[16.05]`](docs/16_Volume_Profile/16.05_Session_Composite_and_Fixed_Range_Volume_Profiles.md) Session, Composite, and Fixed Range Volume Profiles | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 16 fits Market Structure Diagram; title cue "Range" | 1 | 53 |
| [`[17.02]`](docs/17_Wyckoff/17.02_The_Three_Laws_of_Wyckoff.md) The Three Laws of Wyckoff | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 1 | 53 |
| [`[17.04]`](docs/17_Wyckoff/17.04_Distribution_Schematic_Phases_A_to_E.md) Distribution Schematic — Phases A to E | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 1 | 53 |
| [`[18.03]`](docs/18_Smart_Money/18.03_Order_Blocks_Explained.md) Order Blocks Explained | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 1 | 53 |
| [`[18.04]`](docs/18_Smart_Money/18.04_Fair_Value_Gaps_Imbalances.md) Fair Value Gaps / Imbalances | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 1 | 53 |
| [`[18.05]`](docs/18_Smart_Money/18.05_Mitigation_and_Inducement.md) Mitigation and Inducement | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 1 | 53 |
| [`[18.06]`](docs/18_Smart_Money/18.06_Premium_and_Discount_Zones.md) Premium and Discount Zones | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 1 | 53 |
| [`[18.07]`](docs/18_Smart_Money/18.07_SMC_vs_Classical_Technical_Analysis.md) SMC vs Classical Technical Analysis | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 18 fits Market Structure Diagram | 1 | 53 |
| [`[19.02]`](docs/19_ICT/19.02_Market_Maker_Models.md) Market Maker Models (Buy/Sell Models) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 1 | 53 |
| [`[19.03]`](docs/19_ICT/19.03_Kill_Zones_and_Time_Based_Trading.md) Kill Zones and Time-Based Trading | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 1 | 53 |
| [`[19.04]`](docs/19_ICT/19.04_Optimal_Trade_Entry.md) Optimal Trade Entry (OTE) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 1 | 53 |
| [`[19.05]`](docs/19_ICT/19.05_Power_of_Three.md) Power of Three (Accumulation, Manipulation, Distribution) | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 1 | 53 |
| [`[19.06]`](docs/19_ICT/19.06_Judas_Swing_Concept.md) Judas Swing Concept | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram; title cue "Swing" | 1 | 53 |
| [`[19.07]`](docs/19_ICT/19.07_ICT_Applied_to_Indian_Index_Futures.md) ICT Concepts Applied to Indian Index Futures | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 1 | 53 |
| [`[10.04]`](docs/10_Technical_Analysis/10.04_Timeframes_and_How_to_Choose_One.md) Timeframes and How to Choose One | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 10 fits Market Structure Diagram | 0 | 50 |
| [`[13.05]`](docs/13_Price_Action/13.05_Pullbacks_and_Retracements_vs_Reversals.md) Pullbacks and Retracements vs Reversals | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 0 | 50 |
| [`[13.06]`](docs/13_Price_Action/13.06_Inside_Bars_and_Outside_Bars.md) Inside Bars and Outside Bars | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 13 fits Market Structure Diagram | 0 | 50 |
| [`[16.06]`](docs/16_Volume_Profile/16.06_Trading_Strategies_Using_Volume_Profile.md) Trading Strategies Using Volume Profile | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 16 fits Market Structure Diagram; title cue "Profile" | 0 | 50 |
| [`[17.08]`](docs/17_Wyckoff/17.08_Wyckoff_Case_Study_on_an_Indian_Stock.md) Wyckoff Case Study on an Indian Stock | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 17 fits Market Structure Diagram | 0 | 50 |
| [`[19.08]`](docs/19_ICT/19.08_Evaluating_ICT.md) Evaluating ICT — Evidence, Skepticism, and Practical Use | Structure concepts (highs/lows/ranges/profile) are chart-shaped by nature. | Module 19 fits Market Structure Diagram | 0 | 50 |

### P1 — High — Option Payoff Diagram (10)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[14.02]`](docs/14_Volume/14.02_Volume_Spread_Analysis_Basics.md) Volume Spread Analysis Basics | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | title cue "Spread" | 1 | 53 |
| [`[22.06]`](docs/22_Greeks/22.06_Rho_and_Second_Order_Greeks.md) Rho and Second-Order Greeks | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram; title cue "Greeks" | 1 | 53 |
| [`[22.07]`](docs/22_Greeks/22.07_Greeks_in_Practice_Managing_a_Position.md) Greeks in Practice — Managing a Position | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram; title cue "Greeks" | 1 | 53 |
| [`[27.05]`](docs/27_Portfolio_Management/27.05_Rebalancing_Strategies.md) Rebalancing Strategies | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 1 | 53 |
| [`[27.06]`](docs/27_Portfolio_Management/27.06_Sector_Rotation_and_Business_Cycle_Investing.md) Sector Rotation and Business Cycle Investing | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 1 | 53 |
| [`[27.07]`](docs/27_Portfolio_Management/27.07_Building_a_Core_Satellite_Portfolio.md) Building a Core-Satellite Portfolio | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 1 | 53 |
| [`[27.08]`](docs/27_Portfolio_Management/27.08_Performance_Measurement.md) Performance Measurement (Sharpe, Sortino, Alpha, Beta) | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 27 fits Option Payoff Diagram | 1 | 53 |
| [`[21.07]`](docs/21_Options/21.07_Basic_Option_Strategies_Covered_Call_Protective_Put.md) Basic Option Strategies — Covered Call, Protective Put | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 21 fits Option Payoff Diagram; title cue "Call" | 0 | 50 |
| [`[22.03]`](docs/22_Greeks/22.03_Gamma_Rate_of_Change_of_Delta.md) Gamma — Rate of Change of Delta | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram | 0 | 50 |
| [`[22.08]`](docs/22_Greeks/22.08_Greeks_Based_Position_Adjustment_Case_Study.md) Greeks-Based Position Adjustment Case Study | Payoff is a mathematical curve — a proper payoff diagram is clearer than a P&L table. | Module 22 fits Option Payoff Diagram; title cue "Greeks" | 0 | 50 |

### P1 — High — Candlestick Illustration (14)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[11.03]`](docs/11_Candlesticks/11.03_Single_Candlestick_Patterns_Marubozu_Spinning_Top.md) Single Candlestick Patterns — Marubozu, Spinning Top | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 1 | 53 |
| [`[11.06]`](docs/11_Candlesticks/11.06_Three_Candle_Patterns_Morning_Star_Evening_Star.md) Three-Candle Patterns — Morning Star, Evening Star | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 1 | 53 |
| [`[11.07]`](docs/11_Candlesticks/11.07_Three_Candle_Patterns_Three_White_Soldiers_Three_Black_Crows.md) Three-Candle Patterns — Three White Soldiers, Three Black Crows | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 1 | 53 |
| [`[11.09]`](docs/11_Candlesticks/11.09_Japanese_Candlestick_History_Munehisa_Homma.md) Japanese Candlestick History — Munehisa Homma and Rice Trading | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 1 | 53 |
| [`[13.02]`](docs/13_Price_Action/13.02_Reading_Candle_by_Candle_Behavior.md) Reading Candle-by-Candle Behavior | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration; title cue "Candle" | 1 | 53 |
| [`[13.09]`](docs/13_Price_Action/13.09_Trend_Following_with_Price_Action.md) Trend-Following with Price Action | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 1 | 53 |
| [`[17.02]`](docs/17_Wyckoff/17.02_The_Three_Laws_of_Wyckoff.md) The Three Laws of Wyckoff | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 1 | 53 |
| [`[17.04]`](docs/17_Wyckoff/17.04_Distribution_Schematic_Phases_A_to_E.md) Distribution Schematic — Phases A to E | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 1 | 53 |
| [`[11.05]`](docs/11_Candlesticks/11.05_Two_Candle_Patterns_Piercing_Line_Dark_Cloud_Cover.md) Two-Candle Patterns — Piercing Line, Dark Cloud Cover | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 0 | 50 |
| [`[11.08]`](docs/11_Candlesticks/11.08_Candlestick_Patterns_in_Context.md) Candlestick Patterns in Context (Why Location Matters More Than Shape) | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 0 | 50 |
| [`[11.10]`](docs/11_Candlesticks/11.10_Candlestick_Pattern_Reliability.md) Candlestick Pattern Reliability — What Backtests Actually Show | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 11 fits Candlestick Illustration; title cue "Candle" | 0 | 50 |
| [`[13.05]`](docs/13_Price_Action/13.05_Pullbacks_and_Retracements_vs_Reversals.md) Pullbacks and Retracements vs Reversals | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 0 | 50 |
| [`[13.06]`](docs/13_Price_Action/13.06_Inside_Bars_and_Outside_Bars.md) Inside Bars and Outside Bars | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 13 fits Candlestick Illustration | 0 | 50 |
| [`[17.08]`](docs/17_Wyckoff/17.08_Wyckoff_Case_Study_on_an_Indian_Stock.md) Wyckoff Case Study on an Indian Stock | Pattern recognition is inherently visual; ASCII candles can't show real wick/body proportion. | Module 17 fits Candlestick Illustration | 0 | 50 |

### P1 — High — Order Flow Diagram (13)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[01.08]`](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md) How an Order Actually Executes | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram; title cue "Order" | 3 | 54 |
| [`[02.05]`](docs/02_Market_Structure/02.05_Break_of_Structure_vs_Change_of_Character.md) Break of Structure (BOS) vs Change of Character (CHOCH) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 3 | 54 |
| [`[02.08]`](docs/02_Market_Structure/02.08_Multi_Timeframe_Structure_Analysis.md) Multi-Timeframe Structure Analysis | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 3 | 54 |
| [`[01.02]`](docs/01_Foundation/01.02_What_Is_Trading_vs_Investing.md) What Is Trading vs Investing | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 2 | 51 |
| [`[01.05]`](docs/01_Foundation/01.05_Market_Participants.md) Market Participants | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 2 | 51 |
| [`[01.07]`](docs/01_Foundation/01.07_Order_Types_Explained.md) Order Types Explained | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram; title cue "Order" | 2 | 51 |
| [`[02.07]`](docs/02_Market_Structure/02.07_Swing_Points_and_Fractals.md) Swing Points and Fractals | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 02 fits Order Flow Diagram | 2 | 51 |
| [`[18.01]`](docs/18_Smart_Money/18.01_What_Are_Smart_Money_Concepts.md) What Are Smart Money Concepts (SMC) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram | 3 | 49 |
| [`[18.02]`](docs/18_Smart_Money/18.02_Liquidity_Pools_Buy_Side_and_Sell_Side.md) Liquidity Pools — Buy-Side and Sell-Side | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram; title cue "Liquidity" | 3 | 49 |
| [`[19.01]`](docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md) Introduction to ICT (Inner Circle Trader) Concepts | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 3 | 49 |
| [`[29.01]`](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md) What Is Algorithmic Trading | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 3 | 49 |
| [`[18.08]`](docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md) Criticisms and Limitations of SMC | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram | 2 | 46 |
| [`[29.03]`](docs/29_Algorithmic_Trading/29.03_Backtesting_Fundamentals_and_Pitfalls.md) Backtesting Fundamentals and Pitfalls | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 2 | 46 |

### P1 — High — Flowchart (5)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) What Makes a Trading Strategy "Valid" | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 8 | 54 |
| [`[10.01]`](docs/10_Technical_Analysis/10.01_What_Is_Technical_Analysis_and_Does_It_Work.md) What Is Technical Analysis and Does It Work | Multi-step process best shown as a decision/process flow rather than prose. | title cue "Work" | 7 | 51 |
| [`[01.10]`](docs/01_Foundation/01.10_Reading_Your_First_Stock_Quote.md) Reading Your First Stock Quote | Multi-step process best shown as a decision/process flow rather than prose. | Module 01 fits Flowchart | 5 | 50 |
| [`[07.02]`](docs/07_Financial_Statements/07.02_Reading_the_Income_Statement.md) Reading the Income Statement | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 6 | 48 |
| [`[01.09]`](docs/01_Foundation/01.09_Brokers_Depositories_Clearing_Corporations.md) Brokers, Depositories & Clearing Corporations | Multi-step process best shown as a decision/process flow rather than prose. | Module 01 fits Flowchart | 4 | 47 |

### P1 — High — Decision Tree (2)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[21.04]`](docs/21_Options/21.04_Intrinsic_Value_vs_Time_Value.md) Intrinsic Value vs Time Value | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 8 | 54 |
| [`[24.01]`](docs/24_Trading_Strategies/24.01_What_Makes_a_Trading_Strategy_Valid.md) What Makes a Trading Strategy "Valid" | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 8 | 54 |

### P1 — High — Timeline Diagram (1)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) History of Indian Stock Markets (BSE 1875 to NSE 1992) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | title cue "History"; title cue "1992" | 6 | 48 |

### P1 — High — Infographic (2)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[01.01]`](docs/01_Foundation/01.01_What_Is_a_Financial_Market.md) What Is a Financial Market | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 01 fits Infographic; title cue "What Is" | 9 | 52 |
| [`[01.03]`](docs/01_Foundation/01.03_Asset_Classes_Overview.md) Asset Classes Overview | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 01 fits Infographic; title cue "Overview" | 7 | 46 |

## P2 — Medium (138 items)

Genuinely useful but lower reuse or a type (flowchart/decision-tree/timeline) that ASCII diagrams already partially cover.

### P2 — Medium — Order Flow Diagram (23)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[01.06]`](docs/01_Foundation/01.06_Primary_Market_vs_Secondary_Market.md) Primary Market vs Secondary Market | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 01 fits Order Flow Diagram | 0 | 45 |
| [`[18.03]`](docs/18_Smart_Money/18.03_Order_Blocks_Explained.md) Order Blocks Explained | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram; title cue "Order" | 1 | 43 |
| [`[18.04]`](docs/18_Smart_Money/18.04_Fair_Value_Gaps_Imbalances.md) Fair Value Gaps / Imbalances | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram | 1 | 43 |
| [`[18.05]`](docs/18_Smart_Money/18.05_Mitigation_and_Inducement.md) Mitigation and Inducement | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram | 1 | 43 |
| [`[18.06]`](docs/18_Smart_Money/18.06_Premium_and_Discount_Zones.md) Premium and Discount Zones | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram | 1 | 43 |
| [`[18.07]`](docs/18_Smart_Money/18.07_SMC_vs_Classical_Technical_Analysis.md) SMC vs Classical Technical Analysis | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 18 fits Order Flow Diagram | 1 | 43 |
| [`[19.02]`](docs/19_ICT/19.02_Market_Maker_Models.md) Market Maker Models (Buy/Sell Models) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 1 | 43 |
| [`[19.03]`](docs/19_ICT/19.03_Kill_Zones_and_Time_Based_Trading.md) Kill Zones and Time-Based Trading | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 1 | 43 |
| [`[19.04]`](docs/19_ICT/19.04_Optimal_Trade_Entry.md) Optimal Trade Entry (OTE) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 1 | 43 |
| [`[19.05]`](docs/19_ICT/19.05_Power_of_Three.md) Power of Three (Accumulation, Manipulation, Distribution) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 1 | 43 |
| [`[19.06]`](docs/19_ICT/19.06_Judas_Swing_Concept.md) Judas Swing Concept | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 1 | 43 |
| [`[19.07]`](docs/19_ICT/19.07_ICT_Applied_to_Indian_Index_Futures.md) ICT Concepts Applied to Indian Index Futures | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 1 | 43 |
| [`[22.06]`](docs/22_Greeks/22.06_Rho_and_Second_Order_Greeks.md) Rho and Second-Order Greeks | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | title cue "Order" | 1 | 43 |
| [`[29.02]`](docs/29_Algorithmic_Trading/29.02_Rule_Based_Systems_vs_Discretionary_Trading.md) Rule-Based Systems vs Discretionary Trading | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 1 | 43 |
| [`[29.04]`](docs/29_Algorithmic_Trading/29.04_Overfitting_and_Curve_Fitting.md) Overfitting and Curve-Fitting | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 1 | 43 |
| [`[29.05]`](docs/29_Algorithmic_Trading/29.05_Order_Execution_Algorithms.md) Order Execution Algorithms (TWAP, VWAP, Iceberg) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram; title cue "Order" | 1 | 43 |
| [`[29.06]`](docs/29_Algorithmic_Trading/29.06_Building_a_Simple_Trading_Bot_Architecture_Overview.md) Building a Simple Trading Bot — Architecture Overview | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 1 | 43 |
| [`[29.07]`](docs/29_Algorithmic_Trading/29.07_Algo_Trading_Regulations_in_India.md) Algo Trading Regulations in India (SEBI API Trading Rules) | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 1 | 43 |
| [`[29.08]`](docs/29_Algorithmic_Trading/29.08_High_Frequency_Trading_How_It_Actually_Works.md) High-Frequency Trading — How It Actually Works | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 29 fits Order Flow Diagram | 1 | 43 |
| [`[30.06]`](docs/30_Quantitative_Trading/30.06_Market_Making_How_Quant_Firms_Provide_Liquidity.md) Market Making — How Quant Firms Provide Liquidity | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | title cue "Liquidity" | 1 | 43 |
| [`[06.06]`](docs/06_Macroeconomics/06.06_Global_Liquidity_Cycles_and_Risk_On_Risk_Off.md) Global Liquidity Cycles and Risk-On/Risk-Off | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | title cue "Liquidity" | 0 | 40 |
| [`[08.04]`](docs/08_Fundamental_Analysis/08.04_Key_Financial_Ratios_Liquidity_and_Solvency.md) Key Financial Ratios — Liquidity and Solvency | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | title cue "Liquidity" | 0 | 40 |
| [`[19.08]`](docs/19_ICT/19.08_Evaluating_ICT.md) Evaluating ICT — Evidence, Skepticism, and Practical Use | Depth/imbalance/absorption concepts are inherently spatial, not linear text. | Module 19 fits Order Flow Diagram | 0 | 40 |

### P2 — Medium — Flowchart (52)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md) The Three Financial Statements — Overview | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 5 | 45 |
| [`[07.03]`](docs/07_Financial_Statements/07.03_Reading_the_Balance_Sheet.md) Reading the Balance Sheet | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 5 | 45 |
| [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) What Is Fundamental Analysis | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 5 | 45 |
| [`[08.03]`](docs/08_Fundamental_Analysis/08.03_Key_Financial_Ratios_Profitability.md) Key Financial Ratios — Profitability | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 5 | 45 |
| [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) What Is a Futures Contract | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 5 | 45 |
| [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) Strategy Journaling and Iteration | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 5 | 45 |
| [`[25.01]`](docs/25_Risk_Management/25.01_Why_Risk_Management_Comes_Before_Returns.md) Why Risk Management Comes Before Returns | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 5 | 45 |
| [`[25.06]`](docs/25_Risk_Management/25.06_Correlation_Risk_Across_Positions.md) Correlation Risk Across Positions | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 5 | 45 |
| [`[01.08]`](docs/01_Foundation/01.08_How_an_Order_Actually_Executes.md) How an Order Actually Executes | Multi-step process best shown as a decision/process flow rather than prose. | Module 01 fits Flowchart; title cue "How" | 3 | 44 |
| [`[25.08]`](docs/25_Risk_Management/25.08_Building_a_Personal_Risk_Management_Rulebook.md) Building a Personal Risk Management Rulebook | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 4 | 42 |
| [`[01.05]`](docs/01_Foundation/01.05_Market_Participants.md) Market Participants | Multi-step process best shown as a decision/process flow rather than prose. | Module 01 fits Flowchart | 2 | 41 |
| [`[07.04]`](docs/07_Financial_Statements/07.04_Reading_the_Cash_Flow_Statement.md) Reading the Cash Flow Statement | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 3 | 39 |
| [`[07.09]`](docs/07_Financial_Statements/07.09_Reading_an_Indian_Annual_Report.md) Reading an Indian Annual Report (BSE/NSE Filings) | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 3 | 39 |
| [`[20.09]`](docs/20_Futures/20.09_Speculation_with_Futures.md) Speculation with Futures — Risk Profile | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 3 | 39 |
| [`[24.02]`](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md) Trend-Following Strategy Framework | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart; title cue "Framework" | 3 | 39 |
| [`[25.03]`](docs/25_Risk_Management/25.03_Stop_Loss_Placement_Methodology.md) Stop-Loss Placement Methodology | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 3 | 39 |
| [`[29.01]`](docs/29_Algorithmic_Trading/29.01_What_Is_Algorithmic_Trading.md) What Is Algorithmic Trading | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart | 3 | 39 |
| [`[07.07]`](docs/07_Financial_Statements/07.07_Debt_Equity_and_Capital_Structure.md) Debt, Equity & Capital Structure on the Balance Sheet | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 2 | 36 |
| [`[07.08]`](docs/07_Financial_Statements/07.08_Depreciation_Amortization_and_Non_Cash_Items.md) Depreciation, Amortization & Non-Cash Items | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 2 | 36 |
| [`[08.07]`](docs/08_Fundamental_Analysis/08.07_Competitive_Moats_and_Qualitative_Analysis.md) Competitive Moats and Qualitative Analysis | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 2 | 36 |
| [`[08.08]`](docs/08_Fundamental_Analysis/08.08_Management_Quality_and_Corporate_Governance.md) Management Quality and Corporate Governance | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 2 | 36 |
| [`[08.09]`](docs/08_Fundamental_Analysis/08.09_Industry_and_Sector_Analysis_Framework.md) Industry and Sector Analysis Framework | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart; title cue "Framework" | 2 | 36 |
| [`[20.03]`](docs/20_Futures/20.03_Contract_Specifications.md) Contract Specifications — Lot Size, Expiry, Tick Size | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 2 | 36 |
| [`[20.04]`](docs/20_Futures/20.04_Margin_Mark_to_Market_and_Leverage.md) Margin, Mark-to-Market, and Leverage in Futures | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 2 | 36 |
| [`[20.05]`](docs/20_Futures/20.05_Basis_Contango_and_Backwardation.md) Basis, Contango, and Backwardation | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 2 | 36 |
| [`[24.03]`](docs/24_Trading_Strategies/24.03_Mean_Reversion_Strategy_Framework.md) Mean-Reversion Strategy Framework | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart; title cue "Framework" | 2 | 36 |
| [`[24.04]`](docs/24_Trading_Strategies/24.04_Breakout_Trading_Strategy.md) Breakout Trading Strategy | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 2 | 36 |
| [`[24.06]`](docs/24_Trading_Strategies/24.06_Swing_Trading_Framework.md) Swing Trading Framework | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart; title cue "Framework" | 2 | 36 |
| [`[24.11]`](docs/24_Trading_Strategies/24.11_Combining_Strategies_into_a_Portfolio_of_Systems.md) Combining Strategies into a Portfolio of Systems | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 2 | 36 |
| [`[25.02]`](docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md) Defining Risk Per Trade (1% Rule and Variants) | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 2 | 36 |
| [`[25.05]`](docs/25_Risk_Management/25.05_Maximum_Drawdown_and_Why_It_Matters.md) Maximum Drawdown and Why It Matters | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 2 | 36 |
| [`[25.07]`](docs/25_Risk_Management/25.07_Black_Swan_Events_and_Tail_Risk.md) Black Swan Events and Tail Risk | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 2 | 36 |
| [`[29.03]`](docs/29_Algorithmic_Trading/29.03_Backtesting_Fundamentals_and_Pitfalls.md) Backtesting Fundamentals and Pitfalls | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart | 2 | 36 |
| [`[07.05]`](docs/07_Financial_Statements/07.05_How_the_Three_Statements_Connect.md) How the Three Statements Connect | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart; title cue "How" | 1 | 33 |
| [`[07.06]`](docs/07_Financial_Statements/07.06_Revenue_Recognition_and_Earnings_Quality.md) Revenue Recognition and Earnings Quality | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 1 | 33 |
| [`[08.02]`](docs/08_Fundamental_Analysis/08.02_Top_Down_vs_Bottom_Up_Analysis.md) Top-Down vs Bottom-Up Analysis | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 1 | 33 |
| [`[08.06]`](docs/08_Fundamental_Analysis/08.06_EPS_PE_and_Growth_Metrics.md) Earnings Per Share, P/E, and Growth Metrics | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 1 | 33 |
| [`[08.10]`](docs/08_Fundamental_Analysis/08.10_Screening_Stocks_Fundamentally.md) Screening Stocks Fundamentally (India & US) | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 1 | 33 |
| [`[20.02]`](docs/20_Futures/20.02_Futures_vs_Forwards_vs_Spot.md) Futures vs Forwards vs Spot | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 1 | 33 |
| [`[20.06]`](docs/20_Futures/20.06_Rollover_Mechanics.md) Rollover Mechanics (Indian F&O Expiry Cycle) | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 1 | 33 |
| [`[20.07]`](docs/20_Futures/20.07_Index_Futures_vs_Stock_Futures.md) Index Futures vs Stock Futures | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 1 | 33 |
| [`[20.08]`](docs/20_Futures/20.08_Hedging_with_Futures.md) Hedging with Futures | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 1 | 33 |
| [`[24.09]`](docs/24_Trading_Strategies/24.09_Options_Income_Strategies_Theta_Selling.md) Options Income Strategies (Theta Selling) | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 1 | 33 |
| [`[24.10]`](docs/24_Trading_Strategies/24.10_Event_Driven_Trading.md) Event-Driven Trading (Earnings, Budget, Fed Days) | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 1 | 33 |
| [`[25.04]`](docs/25_Risk_Management/25.04_Risk_Reward_Ratio_and_Expectancy.md) Risk-Reward Ratio and Expectancy | Multi-step process best shown as a decision/process flow rather than prose. | Module 25 fits Flowchart | 1 | 33 |
| [`[29.02]`](docs/29_Algorithmic_Trading/29.02_Rule_Based_Systems_vs_Discretionary_Trading.md) Rule-Based Systems vs Discretionary Trading | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart | 1 | 33 |
| [`[29.04]`](docs/29_Algorithmic_Trading/29.04_Overfitting_and_Curve_Fitting.md) Overfitting and Curve-Fitting | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart | 1 | 33 |
| [`[29.05]`](docs/29_Algorithmic_Trading/29.05_Order_Execution_Algorithms.md) Order Execution Algorithms (TWAP, VWAP, Iceberg) | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart; title cue "Execut" | 1 | 33 |
| [`[29.06]`](docs/29_Algorithmic_Trading/29.06_Building_a_Simple_Trading_Bot_Architecture_Overview.md) Building a Simple Trading Bot — Architecture Overview | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart | 1 | 33 |
| [`[29.07]`](docs/29_Algorithmic_Trading/29.07_Algo_Trading_Regulations_in_India.md) Algo Trading Regulations in India (SEBI API Trading Rules) | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart | 1 | 33 |
| [`[29.08]`](docs/29_Algorithmic_Trading/29.08_High_Frequency_Trading_How_It_Actually_Works.md) High-Frequency Trading — How It Actually Works | Multi-step process best shown as a decision/process flow rather than prose. | Module 29 fits Flowchart; title cue "How" | 1 | 33 |
| [`[30.06]`](docs/30_Quantitative_Trading/30.06_Market_Making_How_Quant_Firms_Provide_Liquidity.md) Market Making — How Quant Firms Provide Liquidity | Multi-step process best shown as a decision/process flow rather than prose. | title cue "How" | 1 | 33 |

### P2 — Medium — Decision Tree (33)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[21.05]`](docs/21_Options/21.05_Option_Payoff_Diagrams_Long_Call_Long_Put.md) Option Payoff Diagrams — Long Call, Long Put | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 5 | 45 |
| [`[21.06]`](docs/21_Options/21.06_Option_Payoff_Diagrams_Short_Call_Short_Put.md) Option Payoff Diagrams — Short Call, Short Put | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 5 | 45 |
| [`[24.12]`](docs/24_Trading_Strategies/24.12_Strategy_Journaling_and_Iteration.md) Strategy Journaling and Iteration | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 5 | 45 |
| [`[21.03]`](docs/21_Options/21.03_Strike_Price_Premium_and_Moneyness.md) Strike Price, Premium, and Moneyness (ITM/ATM/OTM) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 4 | 42 |
| [`[21.10]`](docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md) Iron Condor and Iron Butterfly | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 4 | 42 |
| [`[21.01]`](docs/21_Options/21.01_What_Is_an_Option.md) What Is an Option — Calls and Puts Explained | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 3 | 39 |
| [`[21.02]`](docs/21_Options/21.02_Option_Buyer_vs_Seller.md) Option Buyer vs Option Seller — Risk Profiles | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 3 | 39 |
| [`[21.11]`](docs/21_Options/21.11_Option_Chain_Analysis_NSE.md) Option Chain Analysis (India — NSE Option Chain) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 3 | 39 |
| [`[21.12]`](docs/21_Options/21.12_Common_Option_Buyer_Mistakes_Theta_Decay_Trap.md) Common Option Buyer Mistakes (Theta Decay Trap) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 3 | 39 |
| [`[24.02]`](docs/24_Trading_Strategies/24.02_Trend_Following_Strategy_Framework.md) Trend-Following Strategy Framework | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 3 | 39 |
| [`[28.02]`](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md) Fear and Greed Cycle | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 3 | 39 |
| [`[21.08]`](docs/21_Options/21.08_Spreads_Bull_Call_Spread_Bear_Put_Spread.md) Spreads — Bull Call Spread, Bear Put Spread | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 2 | 36 |
| [`[21.09]`](docs/21_Options/21.09_Straddles_and_Strangles.md) Straddles and Strangles | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 2 | 36 |
| [`[24.03]`](docs/24_Trading_Strategies/24.03_Mean_Reversion_Strategy_Framework.md) Mean-Reversion Strategy Framework | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 2 | 36 |
| [`[24.04]`](docs/24_Trading_Strategies/24.04_Breakout_Trading_Strategy.md) Breakout Trading Strategy | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 2 | 36 |
| [`[24.06]`](docs/24_Trading_Strategies/24.06_Swing_Trading_Framework.md) Swing Trading Framework | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 2 | 36 |
| [`[24.11]`](docs/24_Trading_Strategies/24.11_Combining_Strategies_into_a_Portfolio_of_Systems.md) Combining Strategies into a Portfolio of Systems | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 2 | 36 |
| [`[25.02]`](docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md) Defining Risk Per Trade (1% Rule and Variants) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | title cue "Rule" | 2 | 36 |
| [`[26.01]`](docs/26_Position_Sizing/26.01_What_Is_Position_Sizing_and_Why_Its_the_Real_Edge.md) What Is Position Sizing and Why It's the Real Edge | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 26 fits Decision Tree; title cue "Sizing" | 2 | 36 |
| [`[26.04]`](docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md) The Kelly Criterion Explained Simply | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 26 fits Decision Tree | 2 | 36 |
| [`[28.01]`](docs/28_Trading_Psychology/28.01_Why_Psychology_Determines_Trading_Outcomes.md) Why Psychology Determines Trading Outcomes | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 2 | 36 |
| [`[28.04]`](docs/28_Trading_Psychology/28.04_Revenge_Trading_and_Tilt.md) Revenge Trading and Tilt | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 2 | 36 |
| [`[28.05]`](docs/28_Trading_Psychology/28.05_FOMO_and_Overtrading.md) FOMO and Overtrading | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 2 | 36 |
| [`[14.06]`](docs/14_Volume/14.06_Volume_Based_Confirmation_Rules.md) Volume-Based Confirmation Rules | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | title cue "Rules" | 1 | 33 |
| [`[24.09]`](docs/24_Trading_Strategies/24.09_Options_Income_Strategies_Theta_Selling.md) Options Income Strategies (Theta Selling) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 1 | 33 |
| [`[24.10]`](docs/24_Trading_Strategies/24.10_Event_Driven_Trading.md) Event-Driven Trading (Earnings, Budget, Fed Days) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 1 | 33 |
| [`[26.02]`](docs/26_Position_Sizing/26.02_Fixed_Fractional_Position_Sizing.md) Fixed Fractional Position Sizing | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 26 fits Decision Tree; title cue "Sizing" | 1 | 33 |
| [`[26.03]`](docs/26_Position_Sizing/26.03_Volatility_Based_Position_Sizing_ATR_Method.md) Volatility-Based Position Sizing (ATR Method) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 26 fits Decision Tree; title cue "Sizing" | 1 | 33 |
| [`[26.05]`](docs/26_Position_Sizing/26.05_Position_Sizing_for_Options.md) Position Sizing for Options (Defined vs Undefined Risk) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 26 fits Decision Tree; title cue "Sizing" | 1 | 33 |
| [`[28.03]`](docs/28_Trading_Psychology/28.03_Cognitive_Biases_in_Trading.md) Cognitive Biases in Trading (Confirmation, Recency, Loss Aversion) | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 1 | 33 |
| [`[28.06]`](docs/28_Trading_Psychology/28.06_Discipline_Rules_and_Trading_Plans.md) Discipline, Rules, and Trading Plans | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree; title cue "Rules" | 1 | 33 |
| [`[28.07]`](docs/28_Trading_Psychology/28.07_Building_Emotional_Resilience_After_a_Loss.md) Building Emotional Resilience After a Loss | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 1 | 33 |
| [`[28.08]`](docs/28_Trading_Psychology/28.08_The_Psychology_of_Professional_vs_Retail_Traders.md) The Psychology of Professional vs Retail Traders | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 28 fits Decision Tree | 1 | 33 |

### P2 — Medium — Timeline Diagram (20)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[20.01]`](docs/20_Futures/20.01_What_Is_a_Futures_Contract.md) What Is a Futures Contract | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 5 | 45 |
| [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md) Central Banks Explained (Federal Reserve, RBI, ECB) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 4 | 42 |
| [`[20.09]`](docs/20_Futures/20.09_Speculation_with_Futures.md) Speculation with Futures — Risk Profile | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 3 | 39 |
| [`[28.02]`](docs/28_Trading_Psychology/28.02_Fear_and_Greed_Cycle.md) Fear and Greed Cycle | Sequence-of-events content — a horizontal timeline clarifies order and duration. | title cue "Cycle" | 3 | 39 |
| [`[06.08]`](docs/06_Macroeconomics/06.08_Commodity_Super_Cycles_and_Macro_Trading.md) Commodity Super-Cycles and Macro Trading | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 2 | 36 |
| [`[20.03]`](docs/20_Futures/20.03_Contract_Specifications.md) Contract Specifications — Lot Size, Expiry, Tick Size | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 2 | 36 |
| [`[20.04]`](docs/20_Futures/20.04_Margin_Mark_to_Market_and_Leverage.md) Margin, Mark-to-Market, and Leverage in Futures | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 2 | 36 |
| [`[20.05]`](docs/20_Futures/20.05_Basis_Contango_and_Backwardation.md) Basis, Contango, and Backwardation | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 2 | 36 |
| [`[06.03]`](docs/06_Macroeconomics/06.03_Quantitative_Easing_and_Quantitative_Tightening.md) Quantitative Easing and Quantitative Tightening | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 1 | 33 |
| [`[06.04]`](docs/06_Macroeconomics/06.04_Currency_Devaluation_and_Exchange_Rate_Regimes.md) Currency Devaluation and Exchange Rate Regimes | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 1 | 33 |
| [`[06.05]`](docs/06_Macroeconomics/06.05_Balance_of_Payments_and_Current_Account_Deficit.md) Balance of Payments and Current Account Deficit | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 1 | 33 |
| [`[06.09]`](docs/06_Macroeconomics/06.09_Geopolitics_and_Markets.md) Geopolitics and Markets (Wars, Sanctions, Trade Deals) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 1 | 33 |
| [`[11.09]`](docs/11_Candlesticks/11.09_Japanese_Candlestick_History_Munehisa_Homma.md) Japanese Candlestick History — Munehisa Homma and Rice Trading | Sequence-of-events content — a horizontal timeline clarifies order and duration. | title cue "History" | 1 | 33 |
| [`[20.02]`](docs/20_Futures/20.02_Futures_vs_Forwards_vs_Spot.md) Futures vs Forwards vs Spot | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 1 | 33 |
| [`[20.06]`](docs/20_Futures/20.06_Rollover_Mechanics.md) Rollover Mechanics (Indian F&O Expiry Cycle) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram; title cue "Cycle" | 1 | 33 |
| [`[20.07]`](docs/20_Futures/20.07_Index_Futures_vs_Stock_Futures.md) Index Futures vs Stock Futures | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 1 | 33 |
| [`[20.08]`](docs/20_Futures/20.08_Hedging_with_Futures.md) Hedging with Futures | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 1 | 33 |
| [`[27.06]`](docs/27_Portfolio_Management/27.06_Sector_Rotation_and_Business_Cycle_Investing.md) Sector Rotation and Business Cycle Investing | Sequence-of-events content — a horizontal timeline clarifies order and duration. | title cue "Cycle" | 1 | 33 |
| [`[31.01]`](docs/31_Case_Studies/31.01_2008_Global_Financial_Crisis.md) 2008 Global Financial Crisis | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2008" | 1 | 33 |
| [`[31.03]`](docs/31_Case_Studies/31.03_Harshad_Mehta_Scam_1992.md) Harshad Mehta Scam (1992) and Indian Market Reform | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "1992" | 1 | 33 |

### P2 — Medium — Infographic (10)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[05.04]`](docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md) Interest Rates — What They Are and Why They Move Markets | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic | 7 | 41 |
| [`[03.01]`](docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md) History of Indian Stock Markets (BSE 1875 to NSE 1992) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 6 | 38 |
| [`[14.01]`](docs/14_Volume/14.01_What_Volume_Really_Tells_You.md) What Volume Really Tells You | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 6 | 38 |
| [`[03.03]`](docs/03_Indian_Market/03.03_NSE_vs_BSE_Structure_and_Indices.md) NSE vs BSE — Structure and Indices | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic; title cue "vs" | 5 | 35 |
| [`[03.05]`](docs/03_Indian_Market/03.05_Indian_Market_Timings_Circuits_and_Trading_Sessions.md) Indian Market Timings, Circuits & Trading Sessions | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 5 | 35 |
| [`[04.01]`](docs/04_Global_Market/04.01_Major_Global_Exchanges.md) Major Global Exchanges | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic | 5 | 35 |
| [`[04.06]`](docs/04_Global_Market/04.06_Correlation_Between_Global_Markets.md) Correlation Between Global Markets | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic | 5 | 35 |
| [`[07.01]`](docs/07_Financial_Statements/07.01_The_Three_Financial_Statements_Overview.md) The Three Financial Statements — Overview | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "Overview" | 5 | 35 |
| [`[08.01]`](docs/08_Fundamental_Analysis/08.01_What_Is_Fundamental_Analysis.md) What Is Fundamental Analysis | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "What Is" | 5 | 35 |
| [`[12.04]`](docs/12_Chart_Patterns/12.04_Triangles.md) Ascending, Descending, and Symmetrical Triangles | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 5 | 35 |

## P3 — Low (96 items)

Nice-to-have polish — infographics/overviews where prose and the existing ASCII diagram are already adequate.

### P3 — Low — Flowchart (12)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[04.03]`](docs/04_Global_Market/04.03_How_US_Markets_Influence_Indian_Markets.md) How US Markets Influence Indian Markets (SGX Nifty / GIFT Nifty) | Multi-step process best shown as a decision/process flow rather than prose. | title cue "How" | 0 | 30 |
| [`[04.08]`](docs/04_Global_Market/04.08_How_to_Read_a_Global_Macro_Calendar.md) How to Read a Global Macro Calendar | Multi-step process best shown as a decision/process flow rather than prose. | title cue "How" | 0 | 30 |
| [`[06.02]`](docs/06_Macroeconomics/06.02_How_Interest_Rate_Decisions_Are_Made.md) How Interest Rate Decisions Are Made | Multi-step process best shown as a decision/process flow rather than prose. | title cue "How" | 0 | 30 |
| [`[06.10]`](docs/06_Macroeconomics/06.10_Indias_Macro_Framework_RBI_Inflation_Targeting.md) India's Macro Framework — RBI's Inflation Targeting Regime | Multi-step process best shown as a decision/process flow rather than prose. | title cue "Framework" | 0 | 30 |
| [`[07.10]`](docs/07_Financial_Statements/07.10_Reading_a_US_10K_and_10Q.md) Reading a US 10-K and 10-Q | Multi-step process best shown as a decision/process flow rather than prose. | Module 07 fits Flowchart | 0 | 30 |
| [`[08.04]`](docs/08_Fundamental_Analysis/08.04_Key_Financial_Ratios_Liquidity_and_Solvency.md) Key Financial Ratios — Liquidity and Solvency | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 0 | 30 |
| [`[08.05]`](docs/08_Fundamental_Analysis/08.05_Key_Financial_Ratios_Efficiency.md) Key Financial Ratios — Efficiency | Multi-step process best shown as a decision/process flow rather than prose. | Module 08 fits Flowchart | 0 | 30 |
| [`[10.04]`](docs/10_Technical_Analysis/10.04_Timeframes_and_How_to_Choose_One.md) Timeframes and How to Choose One | Multi-step process best shown as a decision/process flow rather than prose. | title cue "How" | 0 | 30 |
| [`[20.10]`](docs/20_Futures/20.10_Commodity_Futures_Basics_MCX.md) Commodity Futures Basics (MCX Overview) | Multi-step process best shown as a decision/process flow rather than prose. | Module 20 fits Flowchart | 0 | 30 |
| [`[24.05]`](docs/24_Trading_Strategies/24.05_Gap_Trading_Strategy.md) Gap Trading Strategy | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart | 0 | 30 |
| [`[24.07]`](docs/24_Trading_Strategies/24.07_Intraday_Scalping_Framework.md) Intraday Scalping Framework | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart; title cue "Framework" | 0 | 30 |
| [`[24.08]`](docs/24_Trading_Strategies/24.08_Positional_Momentum_Investing_Framework.md) Positional/Momentum Investing Framework | Multi-step process best shown as a decision/process flow rather than prose. | Module 24 fits Flowchart; title cue "Framework" | 0 | 30 |

### P3 — Low — Decision Tree (5)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[21.07]`](docs/21_Options/21.07_Basic_Option_Strategies_Covered_Call_Protective_Put.md) Basic Option Strategies — Covered Call, Protective Put | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 21 fits Decision Tree | 0 | 30 |
| [`[24.05]`](docs/24_Trading_Strategies/24.05_Gap_Trading_Strategy.md) Gap Trading Strategy | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 0 | 30 |
| [`[24.07]`](docs/24_Trading_Strategies/24.07_Intraday_Scalping_Framework.md) Intraday Scalping Framework | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 0 | 30 |
| [`[24.08]`](docs/24_Trading_Strategies/24.08_Positional_Momentum_Investing_Framework.md) Positional/Momentum Investing Framework | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 24 fits Decision Tree | 0 | 30 |
| [`[26.06]`](docs/26_Position_Sizing/26.06_Scaling_In_and_Scaling_Out.md) Scaling In and Scaling Out | The lesson is fundamentally a branching choice — a decision tree makes the branches explicit. | Module 26 fits Decision Tree | 0 | 30 |

### P3 — Low — Timeline Diagram (13)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[06.02]`](docs/06_Macroeconomics/06.02_How_Interest_Rate_Decisions_Are_Made.md) How Interest Rate Decisions Are Made | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 0 | 30 |
| [`[06.06]`](docs/06_Macroeconomics/06.06_Global_Liquidity_Cycles_and_Risk_On_Risk_Off.md) Global Liquidity Cycles and Risk-On/Risk-Off | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 0 | 30 |
| [`[06.07]`](docs/06_Macroeconomics/06.07_Yield_Curves_and_What_Inversion_Means.md) Yield Curves and What Inversion Means | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 0 | 30 |
| [`[06.10]`](docs/06_Macroeconomics/06.10_Indias_Macro_Framework_RBI_Inflation_Targeting.md) India's Macro Framework — RBI's Inflation Targeting Regime | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 06 fits Timeline Diagram | 0 | 30 |
| [`[20.10]`](docs/20_Futures/20.10_Commodity_Futures_Basics_MCX.md) Commodity Futures Basics (MCX Overview) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 20 fits Timeline Diagram | 0 | 30 |
| [`[31.02]`](docs/31_Case_Studies/31.02_2020_COVID_Crash_and_V_Shaped_Recovery.md) 2020 COVID Crash and V-Shaped Recovery | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2020" | 0 | 30 |
| [`[31.04]`](docs/31_Case_Studies/31.04_Ketan_Parekh_Scam_2001.md) Ketan Parekh Scam (2001) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2001" | 0 | 30 |
| [`[31.05]`](docs/31_Case_Studies/31.05_2004_Indian_Election_Result_Crash.md) 2004 Indian Election Result Crash | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2004" | 0 | 30 |
| [`[31.06]`](docs/31_Case_Studies/31.06_May_2022_IndusInd_Bank_Adani_Group_Episodes.md) Adani Group–Hindenburg Report Episode (January 2023) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram | 0 | 30 |
| [`[31.07]`](docs/31_Case_Studies/31.07_GameStop_Short_Squeeze_2021.md) GameStop Short Squeeze (2021) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2021" | 0 | 30 |
| [`[31.08]`](docs/31_Case_Studies/31.08_Long_Term_Capital_Management_Collapse_1998.md) Long-Term Capital Management Collapse (1998) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "1998" | 0 | 30 |
| [`[31.09]`](docs/31_Case_Studies/31.09_Dot_Com_Bubble_2000.md) Dot-Com Bubble (2000) | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2000" | 0 | 30 |
| [`[31.10]`](docs/31_Case_Studies/31.10_Satyam_Scandal_2009.md) Satyam Scandal (2009) — India's Enron | Sequence-of-events content — a horizontal timeline clarifies order and duration. | Module 31 fits Timeline Diagram; title cue "2009" | 0 | 30 |

### P3 — Low — Infographic (66)

| Lesson | Rationale | Signal | Downstream Reuse | Score |
|---|---|---|---|---|
| [`[03.08]`](docs/03_Indian_Market/03.08_Indian_Derivatives_Market_FO_Overview.md) Indian Derivatives Market (F&O) Overview | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic; title cue "Overview" | 4 | 32 |
| [`[03.10]`](docs/03_Indian_Market/03.10_Union_Budget_and_RBI_Policy_Effect_on_Indian_Markets.md) Union Budget & RBI Policy — Their Effect on Indian Markets | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 4 | 32 |
| [`[04.02]`](docs/04_Global_Market/04.02_Global_Market_Trading_Hours_and_Overlaps.md) Global Market Trading Hours and Overlaps | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic | 4 | 32 |
| [`[05.01]`](docs/05_Economics/05.01_What_Is_Economics_and_Why_Traders_Need_It.md) What Is Economics and Why Traders Need It | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic; title cue "What Is" | 4 | 32 |
| [`[06.01]`](docs/06_Macroeconomics/06.01_Central_Banks_Explained.md) Central Banks Explained (Federal Reserve, RBI, ECB) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "Explained" | 4 | 32 |
| [`[23.05]`](docs/23_Volatility/23.05_Volatility_Regimes_and_Mean_Reversion.md) Volatility Regimes and Mean Reversion | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 4 | 32 |
| [`[01.02]`](docs/01_Foundation/01.02_What_Is_Trading_vs_Investing.md) What Is Trading vs Investing | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 01 fits Infographic; title cue "vs" | 2 | 31 |
| [`[01.07]`](docs/01_Foundation/01.07_Order_Types_Explained.md) Order Types Explained | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 01 fits Infographic; title cue "Explained" | 2 | 31 |
| [`[05.07]`](docs/05_Economics/05.07_Fiscal_Policy_vs_Monetary_Policy.md) Fiscal Policy vs Monetary Policy | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic; title cue "vs" | 3 | 29 |
| [`[05.08]`](docs/05_Economics/05.08_Business_Cycles_Expansion_Peak_Recession_Trough.md) Business Cycles — Expansion, Peak, Recession, Trough | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic | 3 | 29 |
| [`[09.01]`](docs/09_Valuation/09.01_What_Is_Valuation_and_Why_It_Matters.md) What Is Valuation and Why It Matters | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic; title cue "What Is" | 3 | 29 |
| [`[09.03]`](docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md) Discounted Cash Flow (DCF) Fundamentals | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic | 3 | 29 |
| [`[10.03]`](docs/10_Technical_Analysis/10.03_Types_of_Charts.md) Types of Charts (Line, Bar, Candlestick, Renko, Heikin-Ashi) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "Types of" | 3 | 29 |
| [`[23.01]`](docs/23_Volatility/23.01_What_Is_Volatility_Historical_vs_Implied.md) What Is Volatility — Historical vs Implied | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs"; title cue "What Is" | 3 | 29 |
| [`[03.02]`](docs/03_Indian_Market/03.02_SEBI_Role_Powers_and_Investor_Protection.md) SEBI — Role, Powers, and Investor Protection | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 2 | 26 |
| [`[03.04]`](docs/03_Indian_Market/03.04_Nifty_50_and_Sensex_Construction_Methodology.md) Nifty 50 and Sensex — Construction Methodology | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 2 | 26 |
| [`[03.07]`](docs/03_Indian_Market/03.07_FIIs_DIIs_and_Domestic_Retail_Who_Moves_Nifty.md) FIIs, DIIs & Domestic Retail — Who Moves Nifty | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 2 | 26 |
| [`[03.09]`](docs/03_Indian_Market/03.09_Indian_Market_Regulations_Insider_Trading_Circuit_Filters_Surveillance.md) Indian Market Regulations — Insider Trading, Circuit Filters, Surveillance | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 2 | 26 |
| [`[04.04]`](docs/04_Global_Market/04.04_Currency_Pairs_and_the_Global_FX_Market.md) Currency Pairs and the Global FX Market | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic | 2 | 26 |
| [`[05.02]`](docs/05_Economics/05.02_Demand_and_Supply_Fundamentals_for_Markets.md) Demand and Supply Fundamentals for Markets | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic | 2 | 26 |
| [`[09.02]`](docs/09_Valuation/09.02_Relative_Valuation_PE_PB_EV_EBITDA.md) Relative Valuation — P/E, P/B, EV/EBITDA | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic | 2 | 26 |
| [`[12.01]`](docs/12_Chart_Patterns/12.01_Head_and_Shoulders.md) Head and Shoulders (and Inverse) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 2 | 26 |
| [`[12.02]`](docs/12_Chart_Patterns/12.02_Double_Top_and_Double_Bottom.md) Double Top and Double Bottom | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 2 | 26 |
| [`[12.09]`](docs/12_Chart_Patterns/12.09_Broadening_Formations.md) Broadening Formations (Megaphones) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 2 | 26 |
| [`[14.05]`](docs/14_Volume/14.05_Climactic_Volume_and_Exhaustion.md) Climactic Volume and Exhaustion | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 2 | 26 |
| [`[23.02]`](docs/23_Volatility/23.02_India_VIX_Explained.md) India VIX Explained | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "Explained" | 2 | 26 |
| [`[26.01]`](docs/26_Position_Sizing/26.01_What_Is_Position_Sizing_and_Why_Its_the_Real_Edge.md) What Is Position Sizing and Why It's the Real Edge | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "What Is" | 2 | 26 |
| [`[26.04]`](docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md) The Kelly Criterion Explained Simply | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "Explained" | 2 | 26 |
| [`[27.01]`](docs/27_Portfolio_Management/27.01_What_Is_a_Portfolio_and_Why_Diversify.md) What Is a Portfolio and Why Diversify | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "What Is" | 2 | 26 |
| [`[30.01]`](docs/30_Quantitative_Trading/30.01_What_Is_Quantitative_Trading.md) What Is Quantitative Trading | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "What Is" | 2 | 26 |
| [`[30.03]`](docs/30_Quantitative_Trading/30.03_Correlation_Cointegration_and_Pairs_Trading.md) Correlation, Cointegration, and Pairs Trading | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 2 | 26 |
| [`[01.06]`](docs/01_Foundation/01.06_Primary_Market_vs_Secondary_Market.md) Primary Market vs Secondary Market | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 01 fits Infographic; title cue "vs" | 0 | 25 |
| [`[04.05]`](docs/04_Global_Market/04.05_Global_Indices_Overview.md) Global Indices Overview (S&P 500, Dow, Nasdaq, DAX, Nikkei) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic; title cue "Overview" | 1 | 23 |
| [`[04.07]`](docs/04_Global_Market/04.07_Emerging_Markets_vs_Developed_Markets.md) Emerging Markets vs Developed Markets | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic; title cue "vs" | 1 | 23 |
| [`[05.03]`](docs/05_Economics/05.03_Inflation_Causes_Types_and_Measurement.md) Inflation — Causes, Types, and Measurement | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic | 1 | 23 |
| [`[08.02]`](docs/08_Fundamental_Analysis/08.02_Top_Down_vs_Bottom_Up_Analysis.md) Top-Down vs Bottom-Up Analysis | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[09.07]`](docs/09_Valuation/09.07_Sum_of_the_Parts_Valuation.md) Sum-of-the-Parts Valuation | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic | 1 | 23 |
| [`[12.06]`](docs/12_Chart_Patterns/12.06_Cup_and_Handle.md) Cup and Handle | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 1 | 23 |
| [`[12.10]`](docs/12_Chart_Patterns/12.10_Pattern_Failures_and_False_Breakouts.md) Pattern Failures and False Breakouts | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 1 | 23 |
| [`[14.03]`](docs/14_Volume/14.03_Volume_at_Breakouts_vs_Volume_in_Ranges.md) Volume at Breakouts vs Volume in Ranges | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[14.04]`](docs/14_Volume/14.04_Open_Interest_vs_Volume_in_Derivatives.md) Open Interest vs Volume in Derivatives | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[16.03]`](docs/16_Volume_Profile/16.03_High_Volume_Nodes_vs_Low_Volume_Nodes.md) High Volume Nodes vs Low Volume Nodes | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[16.04]`](docs/16_Volume_Profile/16.04_Volume_Profile_vs_Market_Profile.md) Volume Profile vs Market Profile — Key Differences | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[23.03]`](docs/23_Volatility/23.03_VIX_US_and_the_Fear_Gauge.md) VIX (US) and the "Fear Gauge" | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 1 | 23 |
| [`[26.05]`](docs/26_Position_Sizing/26.05_Position_Sizing_for_Options.md) Position Sizing for Options (Defined vs Undefined Risk) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[28.08]`](docs/28_Trading_Psychology/28.08_The_Psychology_of_Professional_vs_Retail_Traders.md) The Psychology of Professional vs Retail Traders | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[30.02]`](docs/30_Quantitative_Trading/30.02_Statistical_Foundations_for_Traders.md) Statistical Foundations for Traders (Mean, Variance, Distribution) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 1 | 23 |
| [`[30.04]`](docs/30_Quantitative_Trading/30.04_Mean_Reversion_vs_Momentum_A_Quant_View.md) Mean Reversion vs Momentum — A Quant View | Overview/comparison content — a single at-a-glance visual beats scanning prose. | title cue "vs" | 1 | 23 |
| [`[30.05]`](docs/30_Quantitative_Trading/30.05_Factor_Investing_Basics.md) Factor Investing Basics (Value, Momentum, Quality, Low-Vol) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 1 | 23 |
| [`[30.07]`](docs/30_Quantitative_Trading/30.07_Risk_Models_and_Portfolio_Optimization_Basics.md) Risk Models and Portfolio Optimization Basics | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 1 | 23 |
| [`[03.06]`](docs/03_Indian_Market/03.06_T+1_Settlement_and_the_Indian_Clearing_System.md) T+1 Settlement and the Indian Clearing System | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 03 fits Infographic | 0 | 20 |
| [`[04.03]`](docs/04_Global_Market/04.03_How_US_Markets_Influence_Indian_Markets.md) How US Markets Influence Indian Markets (SGX Nifty / GIFT Nifty) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic | 0 | 20 |
| [`[04.08]`](docs/04_Global_Market/04.08_How_to_Read_a_Global_Macro_Calendar.md) How to Read a Global Macro Calendar | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 04 fits Infographic | 0 | 20 |
| [`[05.05]`](docs/05_Economics/05.05_GDP_and_Economic_Growth_Explained.md) GDP and Economic Growth Explained | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic; title cue "Explained" | 0 | 20 |
| [`[05.06]`](docs/05_Economics/05.06_Unemployment_and_Labor_Markets.md) Unemployment and Labor Markets | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 05 fits Infographic | 0 | 20 |
| [`[09.04]`](docs/09_Valuation/09.04_Dividend_Discount_Model.md) Dividend Discount Model | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic | 0 | 20 |
| [`[09.05]`](docs/09_Valuation/09.05_Valuing_Growth_vs_Value_Stocks.md) Valuing Growth vs Value Stocks | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic; title cue "vs" | 0 | 20 |
| [`[09.06]`](docs/09_Valuation/09.06_Valuation_Traps_and_Common_Mistakes.md) Valuation Traps and Common Mistakes | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic | 0 | 20 |
| [`[09.08]`](docs/09_Valuation/09.08_Valuation_in_Different_Market_Cycles.md) Valuation in Different Market Cycles | Overview/comparison content — a single at-a-glance visual beats scanning prose. | Module 09 fits Infographic | 0 | 20 |
| [`[12.03]`](docs/12_Chart_Patterns/12.03_Triple_Top_and_Triple_Bottom.md) Triple Top and Triple Bottom | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |
| [`[12.05]`](docs/12_Chart_Patterns/12.05_Flags_and_Pennants.md) Flags and Pennants | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |
| [`[12.07]`](docs/12_Chart_Patterns/12.07_Wedges_Rising_and_Falling.md) Wedges — Rising and Falling | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |
| [`[12.08]`](docs/12_Chart_Patterns/12.08_Rounding_Top_and_Bottom.md) Rounding Top and Bottom | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |
| [`[23.04]`](docs/23_Volatility/23.04_Volatility_Skew_and_Smile.md) Volatility Skew and Smile | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |
| [`[23.06]`](docs/23_Volatility/23.06_Trading_Volatility_Directly_VIX_Products_Caveats.md) Trading Volatility Directly (VIX Products, Caveats) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |
| [`[30.08]`](docs/30_Quantitative_Trading/30.08_Careers_and_Firms_in_Quant_Trading.md) Careers and Firms in Quant Trading (India & Global) | Overview/comparison content — a single at-a-glance visual beats scanning prose. | default fallback — no stronger visual signal found | 0 | 20 |

---

## Explicitly Out of Scope (For Now)

Per the request that generated this file: **no diagrams, illustrations, or
image assets are created here.** This is a backlog only. When work begins on
an item, follow the same maintainer checklist as any other file — check
`KNOWLEDGE_GRAPH.md` for reuse opportunities first, and update this file's
status (a `[ ]`/`[x]` column can be added at that time, mirroring
`TODO.md`'s convention) so the backlog stays a living document rather than a
one-time snapshot.

---

*Generated 2026-08-05 from lesson titles, module membership, and the
prerequisite-graph reuse counts already validated in `KNOWLEDGE_GRAPH.md`.
Educational content only. Not investment advice.*
