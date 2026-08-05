# Module 22 — Greeks

> Module 21 built the payoff-at-expiry view of options — what a position
> is worth on the last day. This module introduces the Greeks: the
> mathematical framework for understanding how an option's value changes
> *before* expiry, in response to the underlying's price, time passing,
> and volatility shifting.

## Why This Module Exists
Every strategy in Module 21 was analyzed at expiry, but options are
priced and traded continuously before that — the Greeks quantify exactly
how sensitive a position is to each variable that changes daily,
turning `[21.04]`'s informal "time value erodes" and `[21.05]`'s payoff
diagrams into precise, position-manageable numbers.

## Lessons

| # | Lesson | Status |
|---|---|---|
| 22.01 | [Introduction to Option Greeks](22.01_Introduction_to_Option_Greeks.md) | ✅ |
| 22.02 | [Delta — Directional Sensitivity](22.02_Delta_Directional_Sensitivity.md) | ✅ |
| 22.03 | [Gamma — Rate of Change of Delta](22.03_Gamma_Rate_of_Change_of_Delta.md) | ✅ |
| 22.04 | [Theta — Time Decay](22.04_Theta_Time_Decay.md) | ✅ |
| 22.05 | [Vega — Volatility Sensitivity](22.05_Vega_Volatility_Sensitivity.md) | ✅ |
| 22.06 | [Rho and Second-Order Greeks](22.06_Rho_and_Second_Order_Greeks.md) | ✅ |
| 22.07 | [Greeks in Practice — Managing a Position](22.07_Greeks_in_Practice_Managing_a_Position.md) | ✅ |
| 22.08 | [Greeks-Based Position Adjustment Case Study](22.08_Greeks_Based_Position_Adjustment_Case_Study.md) | ✅ |

## Prerequisites for This Module
- Module 21 — Options (all lessons)

## What Comes After
Per `LEARNING_PATH.md`, this module leads into Module 23 (Volatility),
which develops Vega's underlying driver — implied volatility — in full
depth, including India VIX and the US VIX.

## Module-Level Resources
- New terms accumulate in `docs/33_Glossary/`.
- Flashcard deck and cheat sheet to be added once the module is complete.
