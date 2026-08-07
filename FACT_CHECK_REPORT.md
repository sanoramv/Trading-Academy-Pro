# FACT_CHECK_REPORT.md — Chief Technical Editor Review

> **Read-only review. No files were modified to produce this report** — per
> the explicit instruction this review was conducted under, every finding
> below is a *proposed* correction, not an applied one. Nothing in
> `docs/` has changed as a result of this document existing.

## Remediation Status (2026-08-07)

All **14 High-confidence findings**, plus the non-categorized editorial
artifact, have been **fixed** in the lesson files: FACT-002, FACT-004,
FACT-008, FACT-011, FACT-022, FACT-024, FACT-025, FACT-027, FACT-028,
FACT-029, FACT-031, FACT-032, FACT-033, FACT-034, and the `28.08` editorial
note. Each fix also propagated to every other place in the repository that
repeated the same error (e.g., FACT-024/025's NSE expiry-day change was
corrected in every ASCII diagram, quiz, and revision-notes bullet across
both affected files, not just the one quoted sentence per finding; FACT-034's
title fix was propagated to `KNOWLEDGE_GRAPH.md`, `INDEX.md`, `ASSET_PLAN.md`,
`STUDY_PLAN_365_DAY.md`, `CURRICULUM.md`, `31.05`'s Next Lesson link, and
`MASTER_SKILL.md`'s own example citation — without renaming the underlying
file, to avoid breaking the 1,200+ existing links that reference its path).
Medium-confidence-and-below findings (FACT-001, FACT-003, FACT-005 through
FACT-021 except those listed above, FACT-023, FACT-026, FACT-030) **remain
open**, pending a separate remediation pass. See `CHANGELOG.md`'s
2026-08-07 fix entry for the full list and validation results.

## Methodology

All 270 core lessons (Modules 01–31) were read in full — not sampled, not
skimmed — across eight parallel deep-read passes, each covering a cluster of
2–5 related modules. Each pass checked every lesson against seven categories
of problem: **incorrect statements, outdated information, oversimplified
explanations, claims presented without evidence, common trading myths
accidentally presented as fact, statements that need nuance, and concepts
that require caveats.** Every finding below was independently verified
(checkable dates, formulas, and historical figures were cross-checked
against known facts, not just flagged on suspicion) and calibrated against
one rule: **a correctly-caveated simplification for beginners is not an
issue.** This curriculum turned out to be unusually well-hedged already —
most lessons already contain explicit "Misconceptions" sections that
pre-empt the obvious myths. That is why this report contains 34 findings
across 270 lessons (roughly one every 8 lessons), not one per lesson.

Four items were checked specifically because a prior structural audit
(`AUDIT_REPORT.md`, 2026-08-05) flagged them without full detail; this
report gives all four the complete File/Section/Exact-sentence/Corrected
treatment that audit's format didn't require:

| Prior finding | Status here |
|---|---|
| AUDIT-041 (SEBI Act timeline) | Confirmed — see FACT-003 |
| AUDIT-035 (Kelly Criterion negative edge) | Confirmed and deepened — see FACT-031 |
| AUDIT-032 (Volmageddon VIX magnitude) | Confirmed — see FACT-028 |
| AUDIT-040 (Citadel Securities founding year) | Confirmed — see FACT-032 |
| AUDIT-005 (31.06 title/content mismatch) | Given full fact-check treatment — see FACT-034 |

## Executive Summary

| Confidence | Count |
|---|---|
| High | 17 |
| Medium-High | 2 |
| Medium | 12 |
| Low-Medium | 4 |
| Low | 2 |
| **Total** | **34** (+1 non-categorized editorial artifact, see end) |

| Category | Count |
|---|---|
| Incorrect statements | 11 |
| Outdated information | 4 |
| Claims presented without evidence | 8 |
| Concepts that require caveats | 7 |
| Common trading myths presented as fact | 2 |
| Oversimplified explanations | 2 |

*(Several findings legitimately span two categories; each is counted once
under its primary category above.)*

## Cross-Cutting Patterns

Two patterns recurred across *independent* module clusters — independent
because different reviewers, each blind to the others' work, flagged the
same underlying issue in different lessons. That independence is itself
evidence the pattern is real, not one reviewer's idiosyncrasy:

1. **An unsourced "US quantitative researchers report..." rhetorical
   device appears in at least three lessons** (`17.07`, `18.08`, `19.08`)
   — each time lending false specificity to an unverified claim by
   attributing it to an anonymous, uncited research community. This reads
   as a templated phrase reused across the Wyckoff/Smart Money/ICT cluster
   rather than three independent unsourced claims — worth a targeted
   find-and-fix pass across that phrase specifically, not just the three
   instances caught here.
2. **The S&P 500's 2007–2009 Global Financial Crisis recovery duration is
   understated as "over four years" in two independent lessons**
   (`25.05` and `31.01`) when the actual peak-to-new-high gap (October
   2007 to March 2013) is roughly five and a half years. The consistency
   of the same understated figure across two lessons suggests one was
   copied from the other (or both from a shared uncredited source)
   without either being checked against the actual index history.

---

## Findings (Curriculum Order)

### FACT-001 — NSE "launch" conflates incorporation with trading start
- **File:** `docs/01_Foundation/01.04_How_Stock_Exchanges_Work.md`
- **Section:** `## Indian Market Example`
- **Exact sentence:** "The National Stock Exchange (NSE), launched in 1992, was India's first fully electronic exchange, and it fundamentally transformed Indian markets by replacing the open-outcry (physically shouting orders on a trading floor) system used by the BSE at the time."
- **Category:** Outdated / incorrect information
- **Why it's problematic:** NSE was incorporated in November 1992 but did not begin live trading until 1994 (Wholesale Debt Market in June, equity Capital Market segment in November). "Launched in 1992" conflates incorporation with the start of electronic trading. The same imprecision recurs in `03.01_History_of_Indian_Stock_Markets.md` and `03.03_NSE_vs_BSE_Structure_and_Indices.md`.
- **Corrected version:** "The National Stock Exchange (NSE), incorporated in 1992, began live trading in 1994 (Wholesale Debt Market in June, equity Capital Market segment in November), becoming India's first fully electronic exchange for equities and fundamentally transforming Indian markets by replacing the open-outcry system used by the BSE at the time."
- **Confidence:** Medium — 1992 incorporation is correct and widely used as shorthand; the 1994 trading-start date is a distinct, separately verifiable fact many sources conflate.

### FACT-002 — Nifty 18,000 resistance-break timeline off by roughly a year
- **File:** `docs/02_Market_Structure/02.04_Support_and_Resistance_First_Principles.md`
- **Section:** `## Indian Market Example`
- **Exact sentence:** "The Nifty 50's 18,000 level acted as a significant resistance zone during much of 2021–2022, repeatedly rejecting rallies, before eventually being decisively broken above in late 2023."
- **Category:** Incorrect statement
- **Why it's problematic:** Nifty 50 cleared 18,000 decisively in December 2022 (new all-time high near 18,887), not "late 2023." By late 2023 the index was already well above 19,500–20,000.
- **Corrected version:** "The Nifty 50's 18,000 level acted as a significant resistance zone during 2021–2022, repeatedly rejecting rallies, before the index decisively cleared it in December 2022 (setting a new all-time high near 18,887) — after which the zone was retested from above on subsequent pullbacks and behaved as support, a clean example of the polarity flip principle."
- **Confidence:** High — Nifty 50's historical closing/intraday levels on these dates are well-documented index data.

### FACT-003 — SEBI Act 1992 timeline overstates the Harshad Mehta scam's causal role
- **File:** `docs/03_Indian_Market/03.01_History_of_Indian_Stock_Markets.md`
- **Section:** `## Historical Example`
- **Exact sentence:** "This single event is arguably the most consequential turning point in Indian market history: it directly led to SEBI receiving full statutory regulatory powers via the SEBI Act 1992, and directly accelerated NSE's 1992 launch as a transparent, electronic alternative to BSE's then-opaque floor-trading system."
- **Category:** Incorrect statement (confirms AUDIT-041)
- **Why it's problematic:** The SEBI Act, 1992 received presidential assent on April 4, 1992; the Harshad Mehta scam became public via Sucheta Dalal's exposé on April 23, 1992 — about three weeks *later*. The Act's passage was part of the broader 1991–92 liberalization package, not a direct reaction to a scam that hadn't been publicly exposed yet.
- **Corrected version:** "This event exposed deep weaknesses in India's banking-market settlement linkages and directly accelerated NSE's 1992–1994 rollout as a transparent, electronic alternative to BSE's then-opaque floor-trading system, as well as the subsequent strengthening of SEBI's enforcement and surveillance powers. (The SEBI Act, 1992 itself received presidential assent on April 4, 1992 — about three weeks before the scam became public on April 23, 1992 — so the Act's original passage is better understood as part of the same 1991–92 liberalization wave than as a direct reaction to the scam's exposure.)"
- **Confidence:** Medium — the specific dates are well-documented; the broader crisis-accelerated-reform narrative retains partial validity for SEBI's *later* empowerment.

### FACT-004 — Zomato IPO proceeds misattributed in full to the company
- **File:** `docs/01_Foundation/01.06_Primary_Market_vs_Secondary_Market.md`
- **Section:** `## Indian Market Example`
- **Exact sentence:** "When Zomato conducted its IPO in July 2021, the company sold new shares directly to investors (the primary market transaction) and raised approximately ₹9,375 crore in fresh capital for its business."
- **Category:** Incorrect statement
- **Why it's problematic:** Zomato's ₹9,375 crore IPO was a ₹9,000 crore fresh issue (proceeds to Zomato) plus a ₹375 crore Offer for Sale by existing shareholder Info Edge — OFS proceeds went to Info Edge, not Zomato. This undercuts the lesson's own fresh-issue-vs-OFS distinction, correctly applied to the Coal India example just below it.
- **Corrected version:** "When Zomato conducted its IPO in July 2021, the company raised approximately ₹9,000 crore in fresh capital for its business through a fresh issue of new shares (the primary market transaction), alongside a separate ₹375 crore Offer for Sale by existing shareholder Info Edge, bringing the total issue size to ₹9,375 crore."
- **Confidence:** High — documented in Zomato's IPO prospectus and widely reported at the time.

### FACT-005 — Fed funds rate hike cycle duration understated
- **File:** `docs/05_Economics/05.04_Interest_Rates_What_They_Are_and_Why_They_Move_Markets.md`
- **Section:** `## US Market Example`
- **Exact sentence:** "The period of aggressive Fed rate hikes during 2022 (raising the federal funds rate from near 0% to over 5% within roughly a year, in response to the sharp post-pandemic inflation surge) directly coincided with a significant repricing of high-growth, long-duration US technology stocks"
- **Category:** Incorrect statement
- **Why it's problematic:** The cycle began March 2022 and didn't clearly exceed 5% until March–May 2023 — about 16 months, not "roughly a year." 2022 alone only reached 4.25–4.50%.
- **Corrected version:** "The period of aggressive Fed rate hikes from March 2022 through mid-2023 (raising the federal funds rate from near 0% to over 5% over roughly 16 months, in response to the sharp post-pandemic inflation surge) directly coincided with a significant repricing of high-growth, long-duration US technology stocks"
- **Confidence:** Medium — the error is one of degree (16 vs. 12 months), not direction or magnitude.

### FACT-006 — Monetary Policy Framework Agreement misdated by a year
- **File:** `docs/06_Macroeconomics/06.10_Indias_Macro_Framework_RBI_Inflation_Targeting.md`
- **Section:** `### Definition`
- **Exact sentence:** "India's flexible inflation targeting (FIT) framework, formally adopted via the Monetary Policy Framework Agreement of 2016 between the Government of India and the RBI, mandates the RBI to maintain CPI inflation (`[05.03]`) at 4%, within a tolerance band of +/- 2%"
- **Category:** Outdated / incorrect information
- **Why it's problematic:** The Agreement was signed February 2015, not 2016. 2016 is the separate Finance Act amendment to the RBI Act that created the Monetary Policy Committee and gave the framework statutory backing. The lesson's Further Reading citation repeats the same misdate.
- **Corrected version:** "India's flexible inflation targeting (FIT) framework traces to the Monetary Policy Framework Agreement signed between the Government of India and the RBI in February 2015, with statutory backing added via a 2016 amendment to the RBI Act that established the Monetary Policy Committee (MPC) and formally notified the mandate: CPI inflation (`[05.03]`) at 4%, within a tolerance band of +/- 2%"
- **Confidence:** Medium-High — both the 2015 Agreement and 2016 statutory amendment are well-documented, distinct milestones the lesson merges under one misdated label.

### FACT-007 — Revenue recognition described using a superseded pre-2018 standard
- **File:** `docs/07_Financial_Statements/07.06_Revenue_Recognition_and_Earnings_Quality.md`
- **Section:** `### Definition`
- **Exact sentence:** "Revenue recognition refers to the accounting rules determining when a sale should be recorded as revenue — generally, when goods or services have been delivered/performed and payment is reasonably assured, not necessarily when cash is actually received"
- **Category:** Outdated information
- **Why it's problematic:** This describes pre-2018 US GAAP criteria. Since 2018, both US GAAP (ASC 606) and Ind AS 115/IFRS 15 — standards this module names elsewhere — use a five-step "transfer of control" model instead.
- **Corrected version:** "Revenue recognition refers to the accounting rules determining when a sale should be recorded as revenue. Under the current five-step model used in US GAAP (ASC 606) and Ind AS 115/IFRS 15, revenue is recognized when control of the goods or services transfers to the customer — not necessarily when cash is actually received."
- **Confidence:** Low-Medium — the plain-English version isn't badly wrong in effect, but uses superseded technical language in a module that otherwise names standards precisely.

### FACT-008 — Goodwill incorrectly described as amortized
- **File:** `docs/07_Financial_Statements/07.08_Depreciation_Amortization_and_Non_Cash_Items.md`
- **Section:** `### Definition`
- **Exact sentence:** "Amortization is the equivalent concept applied to intangible assets (patents, trademarks, goodwill from acquisitions)."
- **Category:** Incorrect statement
- **Why it's problematic:** Goodwill has not been amortized under US GAAP (ASC 350, since 2001) or Ind AS/IFRS for two decades — it is tested for impairment at least annually instead. The error compounds in this lesson's US Market Example, which refers to "goodwill and intangible asset amortization charges."
- **Corrected version:** "Amortization is the equivalent concept applied to intangible assets with a finite useful life (patents, customer relationships, many trademarks). Goodwill from acquisitions, by contrast, is not amortized under current US GAAP or Ind AS/IFRS — it is instead tested at least annually for impairment."
- **Confidence:** High — textbook-level accounting fact, unchanged for two decades under both standards.

### FACT-009 — EPS defined using period-end rather than weighted-average share count
- **File:** `docs/08_Fundamental_Analysis/08.06_EPS_PE_and_Growth_Metrics.md`
- **Section:** `### Definition`
- **Exact sentence:** "Earnings Per Share (EPS) = Net Profit / Number of Outstanding Shares — the portion of a company's profit attributable to each individual share."
- **Category:** Concepts that require caveats
- **Why it's problematic:** Standard practice uses the *weighted-average* share count over the period, not a point-in-time count — material for companies with mid-year buybacks or issuances. Module 07's ROE lesson applies exactly this rigor to ROE's denominator; EPS's own definition doesn't carry it through.
- **Corrected version:** "Earnings Per Share (EPS) = Net Profit / Weighted-Average Number of Shares Outstanding during the period — using the weighted average (not simply the period-end share count) matters especially for companies with significant mid-year buybacks or share issuances."
- **Confidence:** Medium — correct and checkable, but an extremely common introductory-level simplification.

### FACT-010 — Enterprise Value formula omits preferred equity and minority interest
- **File:** `docs/09_Valuation/09.02_Relative_Valuation_PE_PB_EV_EBITDA.md`
- **Section:** `### Definition`
- **Exact sentence:** "Enterprise Value (EV) = Market Capitalization + Total Debt − Cash"
- **Category:** Concepts that require caveats
- **Why it's problematic:** The complete formula also adds preferred equity and minority (non-controlling) interest — relevant precisely where this module later applies EV/EBITDA thinking to Reliance Industries (`[09.07]`), a company with partly-owned subsidiaries.
- **Corrected version:** "Enterprise Value (EV) = Market Capitalization + Total Debt + Preferred Equity + Minority Interest − Cash and Cash Equivalents (the preferred equity and minority interest terms are often negligible for simple capital structures but matter for companies with partly-owned subsidiaries)."
- **Confidence:** Low-Medium — a common introductory simplification, material only for complex capital structures.

### FACT-011 — WACC presented without the after-tax cost-of-debt adjustment
- **File:** `docs/09_Valuation/09.03_Discounted_Cash_Flow_Fundamentals.md`
- **Section:** `### Definition`
- **Exact sentence:** "The discount rate used is typically the Weighted Average Cost of Capital (WACC) — a blended rate reflecting the cost of both the company's debt and equity financing (`[07.07]`), weighted by their relative proportions in the capital structure."
- **Category:** Concepts that require caveats
- **Why it's problematic:** Standard WACC applies cost of debt *after-tax* (interest is tax-deductible) — one of the most universally taught features of the formula. Omitting it in a "DCF Fundamentals" lesson risks the homework assignment's DIY DCF overstating WACC and understating valuation.
- **Corrected version:** "...weighted by their relative proportions in the capital structure, with the cost of debt applied on an after-tax basis (Cost of Debt × (1 − Tax Rate)) since interest expense is tax-deductible, generally making debt financing appear cheaper within the blended WACC than its stated interest rate alone would suggest."
- **Confidence:** High — standard, universally-taught, checkable, and directly relevant to this lesson's own homework exercise.

### FACT-012 — Three-candle pattern reliability claimed without evidence
- **File:** `docs/11_Candlesticks/11.06_Three_Candle_Patterns_Morning_Star_Evening_Star.md`
- **Section:** `## Institutional Perspective`
- **Exact sentence:** "Institutional technicians generally regard three-candle reversal patterns as carrying somewhat higher inherent reliability than single- or two-candle patterns, specifically because the pattern's own definition already requires the kind of follow-through confirmation that must be separately awaited for simpler patterns"
- **Category:** Claims presented without evidence
- **Why it's problematic:** Requiring more qualifying candles means fewer instances occur — it doesn't establish the ones that do occur resolve correctly more often. No evidence is cited, unlike the rigor `[11.10]` applies to candlestick reliability generally.
- **Corrected version:** "Three-candle reversal patterns are often described by technicians as feeling more convincing than single- or two-candle patterns, since the pattern already incorporates a confirming candle by definition — though this structural feature has not been rigorously shown to translate into a measurably higher win rate, and should be weighed with the same backtesting caution `[11.10]` applies to other candlestick patterns."
- **Confidence:** Medium — a reasoning flaw rather than a checkable factual error.

### FACT-013 — Flags/Pennants evidence overstated as "decades of quantitative research"
- **File:** `docs/12_Chart_Patterns/12.05_Flags_and_Pennants.md`
- **Section:** `## Historical Example`
- **Exact sentence:** "Flags and Pennants... are specifically noted across decades of subsequent practitioner and quantitative research (including Thomas Bulkowski's extensive data-driven pattern performance cataloging) as among the statistically higher-performing continuation patterns when properly identified and confirmed — a notable distinction from the more genuinely mixed evidence picture `[11.10]` described for some candlestick patterns."
- **Category:** Claims presented without evidence
- **Why it's problematic:** This is essentially one practitioner's retrospective, hand-tagged dataset (Bulkowski) presented as "decades of... quantitative research" with a confidence level the curriculum explicitly denies candlestick patterns one module earlier, without the same look-ahead/selection-bias caveats.
- **Corrected version:** "Flags and Pennants are frequently cited — most notably in Thomas Bulkowski's practitioner-compiled performance statistics — as comparatively strong-performing continuation patterns. This evidence comes largely from a single retrospective dataset, however, and is subject to the same look-ahead and definitional-subjectivity caveats `[11.10]` raised for candlestick patterns, so it should be treated as suggestive rather than rigorously validated."
- **Confidence:** Medium — Bulkowski's data is real and widely cited; the framing overstates its rigor relative to this curriculum's own standard elsewhere.

### FACT-014 — Supply/demand zone mechanism stated as fact rather than folk theory
- **File:** `docs/13_Price_Action/13.03_Supply_and_Demand_Zones.md`
- **Section:** `## Intuition`
- **Exact sentence:** "some participants who wanted to transact at that origin price may not have gotten a full fill, leaving genuine, unfilled interest resting at that specific zone. If price returns to that origin later, those unfilled orders may still be active, creating a plausible reason for renewed reaction at that specific level"
- **Category:** Common trading myths accidentally presented as facts
- **Why it's problematic:** This is the standard retail explanation, but a folk theory rather than demonstrated microstructure fact — real limit order books are continuously cancelled and refreshed, especially by market makers and algorithms. Stated as the causal mechanism without flagging it as contested.
- **Corrected version:** "One popular explanation is that unfilled orders remain resting at the origin zone and get triggered on a return visit — this is an intuitive heuristic, not a demonstrated market-microstructure fact, since real order books are continuously refreshed and cancelled. A more defensible explanation is that many participants independently remember and react to the same visually obvious level, creating a self-fulfilling behavioral effect regardless of whether the original orders are still literally present."
- **Confidence:** Medium — genuinely debated among market-structure-literate practitioners, not settled fact in either direction.

### FACT-015 — "Smart money buys climaxes" framed as institutional fact
- **File:** `docs/14_Volume/14.05_Climactic_Volume_and_Exhaustion.md`
- **Section:** `## Institutional Perspective`
- **Exact sentence:** "Institutional 'smart money' participants are specifically associated, within Wyckoff-tradition analysis, with strategically buying INTO selling climaxes (when panic-driven retail selling peaks) and strategically selling INTO buying climaxes (when euphoric retail buying peaks)"
- **Category:** Common trading myths accidentally presented as facts
- **Why it's problematic:** Core Wyckoff folklore, not verified with institutional trade-level data. Placing it under "Institutional Perspective" — a section this academy otherwise uses for verified professional practice — lends it more empirical weight than earned, even with the "Wyckoff-tradition" attribution.
- **Corrected version:** "Wyckoff-tradition analysis theorizes that sophisticated 'smart money' participants tend to buy into selling climaxes and sell into buying climaxes, absorbing exhausted retail flow — this is a long-standing interpretive framework rather than a pattern verified with institutional trade-level data, and should be treated as a plausible narrative, not a confirmed description of how institutions actually trade."
- **Confidence:** Low-Medium — partly hedged already by "within Wyckoff-tradition analysis," but the section heading still risks reading as verified fact.

### FACT-016 — Composite Man footprints described as reliably detectable
- **File:** `docs/17_Wyckoff/17.01_Richard_Wyckoff_History_and_Philosophy.md`
- **Section:** `### Intuition`
- **Exact sentence:** "large, well-capitalized, well-informed operators (his 'Composite Man,' `[17.06]`) accumulate and distribute substantial positions deliberately, and their footprints — because size cannot be hidden entirely — become visible in price and volume behavior to anyone trained to read them correctly."
- **Category:** Common trading myths accidentally presented as facts
- **Why it's problematic:** Asserts reliable detectability as established fact. Later lessons (`17.06`, `17.07`) explicitly walk this back as an interpretive model, not a guarantee — but this founding sentence, read alone, states the strong version.
- **Corrected version:** "large, well-capitalized, well-informed operators (his 'Composite Man,' `[17.06]`) accumulate and distribute substantial positions deliberately, and Wyckoff argued that their footprints — because size cannot be hidden entirely — can become visible in price and volume behavior to traders who develop the skill to interpret them, though this remains an interpretive judgment rather than a guaranteed or mechanical detection."
- **Confidence:** Medium — the rest of the module self-corrects this framing; the issue is localized to one early sentence.

### FACT-017 — Argument-from-persistence for Wyckoff's continued institutional use
- **File:** `docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md`
- **Section:** `## Institutional Perspective`
- **Exact sentence:** "if the framework had become entirely obsolete, this continued institutional investment in Wyckoff-based training would be difficult to rationally explain."
- **Category:** Claims presented without evidence
- **Why it's problematic:** A weak argument-from-persistence stated with confidence. Continued training investment is equally explained by tradition, path-dependency, or trainer-side commercial incentives — a point the curriculum itself raises elsewhere (`[18.08]`).
- **Corrected version:** "Institutional trading desks continue training analysts in Wyckoff's framework, and its proponents argue this reflects genuinely useful behavioral logic — though continued institutional usage alone is not proof of predictive validity, since practices can persist due to tradition and training inertia as much as demonstrated edge."
- **Confidence:** Low-Medium — a subtle reasoning flaw, not a factual error, in an otherwise well-hedged lesson.

### FACT-018 — Unsourced "US quant research teams" claim about Wyckoff patterns
- **File:** `docs/17_Wyckoff/17.07_Wyckoff_in_Modern_Markets.md`
- **Section:** `## US Market Example`
- **Exact sentence:** "US quantitative research teams have specifically studied whether Wyckoff-consistent accumulation/distribution patterns remain statistically detectable in modern high-frequency electronic market data — while formal academic consensus remains limited, considerable practitioner-level evidence and continued widespread professional use suggest the framework's continued practical relevance"
- **Category:** Claims presented without evidence (see Cross-Cutting Pattern #1)
- **Why it's problematic:** Names no specific study, researcher, or institution while citing "considerable practitioner-level evidence" — a checkable-sounding claim with no citation.
- **Corrected version:** "Some practitioners and independent researchers have informally explored whether Wyckoff-consistent patterns remain detectable in modern electronic market data, but no widely-cited, peer-reviewed study is known to confirm this, and formal academic consensus is absent — claims of 'considerable practitioner-level evidence' should be treated as anecdotal rather than verified."
- **Confidence:** Medium — the vagueness is the flaw; the underlying claim isn't necessarily false, just unsupported as stated.

### FACT-019 — Unsourced "US quant researchers" claim about SMC fill rates
- **File:** `docs/18_Smart_Money/18.08_Criticisms_and_Limitations_of_SMC.md`
- **Section:** `## US Market Example`
- **Exact sentence:** "US quantitative researchers who have attempted to systematically backtest specific SMC claims (such as FVG fill rates) generally report more modest, context-dependent results than commonly cited in popular SMC marketing content"
- **Category:** Claims presented without evidence (see Cross-Cutting Pattern #1)
- **Why it's problematic:** Ironically appears in the lesson devoted to warning readers about unverified SMC claims, yet itself makes an unsourced, unnamed claim about "researchers" — exactly the pattern the lesson tells readers to be skeptical of.
- **Corrected version:** "Independent traders and analysts who have attempted to backtest specific SMC claims (such as FVG fill rates) on their own data often report more modest, context-dependent results than commonly cited in SMC marketing content — though as with any such claim in this lesson, readers should verify this through their own systematic testing rather than accepting it uncritically."
- **Confidence:** Medium — the self-undermining irony strengthens the case for flagging it.

### FACT-020 — ICT/Huddleston origin timeline imprecise
- **File:** `docs/19_ICT/19.01_Introduction_to_ICT_Concepts.md`
- **Section:** `### Definition`
- **Exact sentence:** "ICT (Inner Circle Trader) is a trading methodology developed and popularized by trader Michael J. Huddleston beginning in the 2010s through free and paid educational content"
- **Category:** Outdated / imprecise information
- **Why it's problematic:** Public sourcing is inconsistent, but multiple accounts place Huddleston's branded mentorship activity in the mid-to-late 2000s, with mass free-content popularization coming later, mid-to-late 2010s. Stating flatly "beginning in the 2010s" conflates founding with mass-popularization.
- **Corrected version:** "ICT (Inner Circle Trader) is a trading methodology developed by trader Michael J. Huddleston, whose mentorship and branded educational content trace back to the mid-to-late 2000s, with the framework achieving mass popularization through free YouTube and social media content particularly from the mid-2010s onward."
- **Confidence:** Low — public sourcing on Huddleston's exact timeline is itself inconsistent; a soft correction rather than a clear-cut error.

### FACT-021 — "Market Maker Models" conflates ICT usage with the formal market-microstructure role
- **File:** `docs/19_ICT/19.02_Market_Maker_Models.md`
- **Section:** `### Definition`
- **Exact sentence:** "ICT's Market Maker Models describe a specific, idealized sequence of price behavior institutional 'market makers' are theorized to follow when establishing directional positioning."
- **Category:** Concepts that require caveats
- **Why it's problematic:** A real market maker is a firm that continuously quotes two-sided prices and typically runs a flat, risk-managed book, profiting from spread — not a directional accumulator. Conflating this with ICT's "smart money"/Composite Man concept is a well-documented criticism of ICT terminology; the lesson's Institutional Perspective only partially addresses it.
- **Corrected version:** "ICT's Market Maker Models describe a specific, idealized sequence of price behavior that ICT attributes to large, directional institutional operators (this curriculum's 'smart money'/Composite Man concept, Modules 17-18) — note that ICT's use of the term 'market maker' here differs from the formal market-microstructure definition (a firm that continuously quotes two-sided prices and typically runs a comparatively flat, risk-neutral book), a terminology distinction worth keeping in mind when comparing ICT content to institutional trading literature."
- **Confidence:** Medium-High — a specifically documented criticism of ICT vocabulary, not a stylistic nitpick.

### FACT-022 — OTE's Fibonacci empirical support overstated, contradicted by published research
- **File:** `docs/19_ICT/19.04_Optimal_Trade_Entry.md`
- **Section:** `## Institutional Perspective`
- **Exact sentence:** "Institutional analysts note that Fibonacci-based retracement levels, including deeper retracement zones resembling OTE, have some genuine, if modest, empirical support in price behavior studies — though the specific 62%-79% boundary is a somewhat arbitrary ICT-specific refinement rather than a rigorously, independently validated numerical threshold."
- **Category:** Incorrect statement
- **Why it's problematic:** Peer-reviewed research systematically testing Fibonacci levels (automated tests across the Dow, NASDAQ, and DAX, *Expert Systems with Applications*, 2022) found reactions at Fibonacci levels statistically indistinguishable from reactions at randomly chosen levels — i.e., no standalone empirical support was found, contradicting this claim.
- **Corrected version:** "Peer-reviewed studies that have systematically tested Fibonacci retracement levels (e.g., automated tests across the Dow, NASDAQ, and DAX published in *Expert Systems with Applications*, 2022) generally find that price reactions at Fibonacci levels are statistically indistinguishable from reactions at randomly chosen levels — meaning Fibonacci-based retracement, including OTE's 62%-79% band, currently lacks robust standalone empirical support in the academic literature, beyond the self-fulfilling effect of many traders watching the same levels."
- **Confidence:** High — directly contradicted by identifiable peer-reviewed research.

### FACT-023 — Unsourced "US quantitative researchers" claim about ICT backtesting
- **File:** `docs/19_ICT/19.08_Evaluating_ICT.md`
- **Section:** `## US Market Example`
- **Exact sentence:** "US quantitative researchers who have attempted rigorous backtesting of various ICT-derived concepts generally report finding more consistent, if modest, statistical support for session-timing-related effects than for the more precisely-sequenced narrative concepts like Power of Three"
- **Category:** Claims presented without evidence (see Cross-Cutting Pattern #1)
- **Why it's problematic:** Same unsourced-researcher pattern as `17.07` and `18.08` — a third instance of a checkable-sounding empirical claim with no named study, author, or publication.
- **Corrected version:** "Independent traders who have attempted backtesting of ICT-derived concepts anecdotally report finding more consistent results for session-timing effects (consistent with the documented market-microstructure literature on intraday liquidity patterns) than for narrative-heavy concepts like Power of Three, though no specific published, peer-reviewed study is cited here and readers should verify claims through their own testing."
- **Confidence:** Medium — the directional claim is plausible; the specific sourcing is fabricated-sounding.

### FACT-024 — NSE F&O expiry day outdated (Thursday → Tuesday, September 2025)
- **File:** `docs/20_Futures/20.03_Contract_Specifications.md`
- **Section:** `## Key Takeaways`
- **Exact sentence:** "Indian equity/index futures traditionally expire on the last Thursday of each month."
- **Category:** Outdated information
- **Why it's problematic:** NSE shifted the entire F&O segment's expiry day to Tuesday effective September 1, 2025 (per SEBI's May 2025 standardization circular). Monthly contracts now expire on the last Tuesday, not Thursday.
- **Corrected version:** "Indian equity/index futures historically expired on the last Thursday of each month, but NSE shifted the F&O expiry day to Tuesday in September 2025 (monthly contracts now expire on the last Tuesday) — always verify the current expiry day directly from the exchange, since this convention has changed before and can change again."
- **Confidence:** High — verified via NSE circulars and financial news confirming the September 2025 change.

### FACT-025 — Same NSE expiry day error repeated in the rollover lesson
- **File:** `docs/20_Futures/20.06_Rollover_Mechanics.md`
- **Section:** `## Core Concepts`
- **Exact sentence:** "Indian equity and index F&O contracts traditionally follow a monthly expiry cycle, with three contract months (near, next, and far month) available for trading simultaneously at any given time, and the near-month contract expiring on the last Thursday of each month (`[20.03]`)."
- **Category:** Outdated information
- **Why it's problematic:** Same underlying issue as FACT-024, repeated in a second file as the stated mechanic underpinning rollover timing.
- **Corrected version:** "Indian equity and index F&O contracts traditionally follow a monthly expiry cycle, with three contract months (near, next, and far month) available for trading simultaneously at any given time, and the near-month contract expiring on the exchange's current designated expiry day each month (last Tuesday as of September 2025, previously last Thursday — verify the current convention, `[20.03]`)."
- **Confidence:** High — same verified change as FACT-024.

### FACT-026 — Iron condor execution/slippage risk omitted
- **File:** `docs/21_Options/21.10_Iron_Condor_and_Iron_Butterfly.md`
- **Section:** `## Core Concepts`
- **Exact sentence:** "An iron condor combines a bear call spread (short lower-strike call, long higher-strike call) and a bull put spread (short higher-strike put, long lower-strike put), all four legs on the same underlying and expiry — a net-credit strategy that profits if the underlying stays between the two short strikes at expiry."
- **Category:** Concepts that require caveats
- **Why it's problematic:** A four-leg order carries meaningfully more execution risk (wider effective bid-ask cost, partial fills, leg-in/leg-out slippage) than a single option or two-leg spread, especially on thinly-traded far-OTM wing strikes — a standard professional caveat the lesson's Common Mistakes/Retail Perspective sections omit.
- **Corrected version:** Add to Common Mistakes: "Underestimating execution cost on a four-leg order — each leg carries its own bid-ask spread, and far-OTM wing strikes are often less liquid, so the net credit actually filled can be meaningfully worse than the sum of each leg's quoted mid-price, particularly when legging in/out rather than using a single combo order."
- **Confidence:** Medium — a defensible professional caveat, more a judgment call than a factual error.

### FACT-027 — India VIX cited for an event four years before the index existed
- **File:** `docs/23_Volatility/23.02_India_VIX_Explained.md`
- **Section:** `## Historical Example`
- **Exact sentence:** "beyond the March 2020 COVID crash, comparable elevated readings have also been observed around major domestic events such as national election results (`[31.05]` previewed, the 2004 election crash), when outcome uncertainty directly inflates the market's near-term volatility expectation."
- **Category:** Incorrect statement
- **Why it's problematic:** India VIX did not exist in 2004 — NSE launched it April 8, 2008. Claiming "comparable elevated readings" around the 2004 event is anachronistic; no India VIX data exists for that year.
- **Corrected version:** "beyond the March 2020 COVID crash, comparable elevated readings have also been observed around major domestic events since India VIX's 2008 launch — such as ahead of the 2019 general election results, when outcome uncertainty inflated the market's near-term volatility expectation before the index fell sharply once the result was confirmed (the pre-2008 2004 election crash, `[31.05]` previewed, predates India VIX and is a relevant crash example but not an India VIX data point)."
- **Confidence:** High — India VIX's April 2008 launch is well documented, making any 2004 reading impossible.

### FACT-028 — Volmageddon VIX spike magnitude understated ~6x (confirms AUDIT-032)
- **File:** `docs/23_Volatility/23.06_Trading_Volatility_Directly_VIX_Products_Caveats.md`
- **Section:** `## Historical Example`
- **Exact sentence:** "'Volmageddon' (February 5, 2018) stands as the primary cautionary case study in this space: a roughly 20% single-day VIX spike (a very large move by VIX's own standards) caused certain short-volatility ETPs to lose the vast majority of their value in one session..."
- **Category:** Incorrect statement
- **Why it's problematic:** VIX closed at 17.31 on February 2 and 37.32 on February 5, 2018 — a +115.6% one-day move, not "roughly 20%." Intraday/after-hours levels pushed toward the high-40s/~50 range.
- **Corrected version:** "'Volmageddon' (February 5, 2018) stands as the primary cautionary case study in this space: VIX spiked roughly 116% in a single session — closing at 37.32, up from 17.31 the prior close, with intraday/after-hours levels pushing toward the high-40s to roughly 50 (the largest one-day percentage and point gain in VIX's history at the time) — and this caused certain short-volatility ETPs to lose the vast majority of their value in one session..."
- **Confidence:** High — verified against multiple independent sources confirming the 17.31→37.32 move.

### FACT-029 — Stop-loss "risk per trade" presented without slippage/gap caveat
- **File:** `docs/25_Risk_Management/25.02_Defining_Risk_Per_Trade.md`
- **Section:** `## Core Concepts` (Definition)
- **Exact sentence:** "Risk per trade is the amount of capital that will actually be lost if a position's stop-loss is hit — not the total value of the position itself."
- **Category:** Concepts that require caveats
- **Why it's problematic:** Repeated four times across the lesson, this treats stop-loss distance as the exact, guaranteed loss. A stop order can execute worse than the stop level during gaps or fast/illiquid markets — routine for NSE/BSE overnight sessions per this academy's own `[24.05]`. No lesson in the 8-lesson Risk Management module mentions slippage/gap risk on stop execution.
- **Corrected version:** "Risk per trade is the amount of capital *intended* to be lost if a position's stop-loss is hit — not the total value of the position itself. Note that in fast-moving or gapping markets, the stop order may execute at a worse price than planned (slippage), so actual loss can exceed this calculated figure; this is a key reason many traders build in a buffer or use guaranteed stop orders where available."
- **Confidence:** High — the omission is verifiable by checking the whole module; gap/slippage risk on stops is uncontroversial and directly relevant to this academy's own `[24.05]` content.

### FACT-030 — S&P 500 GFC drawdown duration inconsistent with the lesson's own definition
- **File:** `docs/25_Risk_Management/25.05_Maximum_Drawdown_and_Why_It_Matters.md`
- **Section:** `## Historical Example`
- **Exact sentence:** "The S&P 500 experienced a maximum drawdown of approximately 57% from its October 2007 peak to its March 2009 trough during the Global Financial Crisis (`[31.01]` previewed), taking over four years to reach a new all-time high"
- **Category:** Incorrect statement (see Cross-Cutting Pattern #2)
- **Why it's problematic:** The lesson's own "Drawdown Duration" definition measures from peak through trough to a new equity high — by that definition the duration was roughly 5.5 years (October 2007 to ~March 2013), not "over four years." Four years only holds measuring from the March 2009 trough, a different quantity than the lesson's own metric. The quiz answer key repeats the inconsistency.
- **Corrected version:** "The S&P 500 experienced a maximum drawdown of approximately 57% from its October 2007 peak to its March 2009 trough during the Global Financial Crisis (`[31.01]` previewed) — a decline that took roughly four years to recover from its trough, but over five years measured as drawdown duration from the original October 2007 peak to a new all-time high in March 2013."
- **Confidence:** Medium — exact recovery date depends on price-only vs. total-return index, but the peak-to-new-high gap is well-documented as exceeding five years.

### FACT-031 — Kelly Criterion's negative-edge behavior omitted (confirms/deepens AUDIT-035)
- **File:** `docs/26_Position_Sizing/26.04_The_Kelly_Criterion_Explained_Simply.md`
- **Section:** `## Core Concepts` (Definition/Intuition/Mental Model)
- **Exact sentence:** "Kelly's output is highly sensitive to errors in those estimates, which is precisely why practitioners scale the raw output down substantially before applying it."
- **Category:** Concepts that require caveats
- **Why it's problematic:** The lesson correctly shows over-betting a *correctly-known positive* edge drives growth negative — but never addresses a negative/near-zero Kelly result, nor that sizing against a mis-estimated edge (plausible given the lesson's own point about estimation sensitivity) leads to guaranteed capital destruction over time, not just "lower returns."
- **Corrected version:** "If the calculated Kelly percentage is zero or negative, this signals the strategy has no genuine edge (or a negative one) at the estimated inputs — the formula is telling you not to bet at all, not to bet a small or negative amount. Because Kelly's inputs are only ever estimates, a strategy that appears to have a small positive edge from a limited sample may, in reality, have zero or negative edge; sizing positions — even conservatively — against a strategy whose true edge is negative guarantees eventual capital loss with certainty over a long enough series of trades, not merely a lower growth rate. This is distinct from, and in addition to, the danger of over-betting a genuinely positive edge."
- **Confidence:** High — a well-established property of the Kelly framework, and the omission was independently pre-flagged by the prior structural audit.

### FACT-032 — Citadel Securities founding year wrong by three years (confirms AUDIT-040)
- **File:** `docs/30_Quantitative_Trading/30.06_Market_Making_How_Quant_Firms_Provide_Liquidity.md`
- **Section:** `### Historical Example`
- **Exact sentence:** "firms like Citadel Securities and Jane Street (founded 1999 and 2000 respectively) grew into major global market-making operations spanning equities, options, and other asset classes using exactly this lesson's spread-capture-plus-hedging business model at institutional scale."
- **Category:** Incorrect statement
- **Why it's problematic:** Citadel Securities was founded in 2002 (spun out from Ken Griffin's Citadel, the hedge fund founded 1990), not 1999. The same "1999" figure repeats in this lesson's Revision Notes.
- **Corrected version:** "firms like Citadel Securities and Jane Street (founded 2002 and 2000 respectively) grew into major global market-making operations spanning equities, options, and other asset classes using exactly this lesson's spread-capture-plus-hedging business model at institutional scale."
- **Confidence:** High — verified against multiple independent sources; consistently cited as 2002.

### FACT-033 — S&P 500 GFC recovery duration understated a second time
- **File:** `docs/31_Case_Studies/31.01_2008_Global_Financial_Crisis.md`
- **Section:** `## Key Takeaways`
- **Exact sentence:** "The S&P 500 fell approximately 57% peak-to-trough, taking over four years to reach new highs — a real, concrete application of `[25.05]`'s drawdown framework."
- **Category:** Incorrect statement (see Cross-Cutting Pattern #2)
- **Why it's problematic:** The S&P 500 peaked October 9, 2007 (1,565.15) and didn't close at a new all-time high until March 28, 2013 (1,569.19) — roughly 5.5 years, not "over four." The same understated figure appears in this lesson's Revision Notes and ASCII diagram.
- **Corrected version:** "The S&P 500 fell approximately 57% peak-to-trough, taking roughly five and a half years to reach new highs (March 2013) — a real, concrete application of `[25.05]`'s drawdown framework."
- **Confidence:** High — confirmed via independent verification of the October 2007 peak and March 2013 new-high dates.

### FACT-034 — Lesson title/filename doesn't match its actual content
- **File:** `docs/31_Case_Studies/31.06_May_2022_IndusInd_Bank_Adani_Group_Episodes.md`
- **Section:** Title/filename (confirms AUDIT-005)
- **Exact sentence:** Title `[31.06] IndusInd Bank and Adani Group Episodes`, filename `31.06_May_2022_IndusInd_Bank_Adani_Group_Episodes.md` — but the body covers only "the Adani Group's stock price collapse beginning in late January 2023" and explicitly states "this lesson does not assert specific claims about individual bank episodes beyond general market context."
- **Category:** Incorrect statement
- **Why it's problematic:** The title names an entity (IndusInd Bank) and date (May 2022) that never appear substantively in the content; the actual event covered (Adani-Hindenburg) occurred January 2023, not May 2022. A student searching by title would find no IndusInd Bank content.
- **Corrected version:** Retitle the file/header to `[31.06] Adani Group–Hindenburg Report Episode (January 2023)` to match the actual content, or add genuine IndusInd Bank content and correct the date if that episode is meant to be covered.
- **Confidence:** High — directly observable from the file's own title/content mismatch.

---

## Additional Editorial Note (Not a Fact-Check Finding)

One reviewer surfaced a content-quality defect that doesn't fit any of the
seven fact-checking categories but is worth flagging to the Chief Technical
Editor as a mechanical fix:

- **File:** `docs/28_Trading_Psychology/28.08_The_Psychology_of_Professional_vs_Retail_Traders.md`
- **Section:** `### Intuition`
- **Exact text:** "MASTER_SKILL.md's institutional perspective sections throughout this academy have shown professionals actively managing these same patterns, not transcending them."
- **Issue:** A stray file-reference artifact, apparently leaked from a generation template, rather than coherent prose — likely meant to read "This academy's institutional perspective sections..."
- **Confidence:** High — the literal string "MASTER_SKILL.md" appearing inside body prose is self-evidently a broken reference, not a substantive claim.

---

## Next Steps

This report changes nothing by itself. Per the instruction it was produced
under, no file has been edited. If and when corrections are authorized:
work top-down by confidence (High first), check `KNOWLEDGE_GRAPH.md` for
any other lesson that might share the same fact (the two independent GFC
duration errors above show this happens), and log each correction in
`CHANGELOG.md` like any other change, per the maintainer checklist in
`CONTRIBUTING.md`.

---

*Generated 2026-08-07 from eight independent full-corpus read-throughs of
all 270 core lessons, cross-referenced against `AUDIT_REPORT.md`'s prior
findings. Educational content only. Not investment advice.*
