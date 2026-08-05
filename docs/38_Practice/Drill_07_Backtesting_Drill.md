# Drill 7 — Manual Mini-Backtest Drill

> Builds `[29.03]`-`[29.04]`'s backtesting discipline through a small, hand-run exercise.

## Instructions
1. Choose one simple, precisely-defined rule from Module 24 (e.g.,
   `[24.02]`'s "price closes above the rising 20-day EMA, enter long on
   the next pullback-and-resume").
2. Manually scan 40-60 historical daily bars of any instrument you have
   chart access to, marking every point the rule would have triggered.
3. For each signal, manually record: entry price, a reasonable
   structural stop (`[25.03]`), and outcome (did the stop or a
   reasonable target hit first?).
4. Calculate win rate, average win, average loss, and expectancy from
   your sample.
5. Explicitly check your work against `[29.03]`'s pitfall checklist:
   did you use only information available AT the signal date (no
   look-ahead), and did you include the full available price history (no survivorship bias)?

## Worked Example (Hypothetical, 6 signals from a 60-bar sample)
```
Signal 1: Entry 100, Stop 96, Target 108 -> Target hit: +8 (Win)
Signal 2: Entry 105, Stop 101, Target 113 -> Stop hit: -4 (Loss)
Signal 3: Entry 98, Stop 94, Target 106 -> Target hit: +8 (Win)
Signal 4: Entry 110, Stop 106, Target 118 -> Stop hit: -4 (Loss)
Signal 5: Entry 103, Stop 99, Target 111 -> Target hit: +8 (Win)
Signal 6: Entry 107, Stop 103, Target 115 -> Stop hit: -4 (Loss)

Win Rate = 3/6 = 50%. Avg Win = 8. Avg Loss = 4.
Expectancy = (0.5 x 8) - (0.5 x 4) = 4 - 2 = +2 per trade (POSITIVE
in this small, illustrative sample)

CAVEAT (per [29.03]/[24.01]): 6 trades is FAR too small a sample to
draw genuine conclusions -- this drill demonstrates the CALCULATION
PROCESS, not a validated strategy. A real backtest requires many more
signals across multiple market regimes, [23.05], before any live
deployment decision.
```

## Self-Check Questions
- Did you record EVERY signal the rule generated, including ones that later looked "obviously bad," avoiding selective/biased recording?
- Did you use only data that would have been genuinely known at each signal's date?
- What is the minimum sample size you'd want before trusting this expectancy figure, per `[29.03]`'s discipline?

---
*Educational content only. Not investment advice.*
