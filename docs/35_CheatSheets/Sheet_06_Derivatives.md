# CheatSheet 6 — Derivatives (Futures, Options, Greeks, Volatility)

> Covers Modules 20-23. Part of Module 35.

## Option Payoff Formulas (`[21.05]`, `[21.06]`)
```
LONG CALL payoff  = max(0, Underlying - Strike) - Premium Paid
LONG PUT payoff   = max(0, Strike - Underlying) - Premium Paid
SHORT CALL payoff = Premium - max(0, Underlying - Strike)
SHORT PUT payoff  = Premium - max(0, Strike - Underlying)
```

## Max Loss / Max Profit Quick Table
| Position | Max Loss | Max Profit |
|---|---|---|
| Long Call | Premium paid | Unlimited |
| Long Put | Premium paid | Large (capped, floor=0) |
| Short Call | Unlimited | Premium received |
| Short Put | Large (capped) | Premium received |
| Iron Condor | Wing width − Net Credit | Net Credit |

## The Greeks (`[22.02]`-`[22.06]`)
| Greek | Measures | 
|---|---|
| Delta | Premium sensitivity to underlying price |
| Gamma | Rate of change of Delta |
| Theta | Premium sensitivity to time (decay) |
| Vega | Premium sensitivity to implied volatility |
| Rho | Premium sensitivity to interest rates |

## Volatility Quick Reference (`[23.01]`-`[23.04]`)
```
Historical Vol = backward-looking (actual past movement)
Implied Vol    = forward-looking (from option prices)

Equity Skew: OTM Puts typically carry HIGHER IV than OTM Calls
```

## Futures Curve (`[20.05]`)
```
CONTANGO:      Futures Price > Spot Price
BACKWARDATION: Futures Price < Spot Price
```

## Strategy Quick Map (Module 21)
| Bias | Structure |
|---|---|
| Bullish, defined risk | Bull Call Spread `[21.08]` |
| Bearish, defined risk | Bear Put Spread `[21.08]` |
| Big move, either direction | Straddle/Strangle `[21.09]` |
| Range-bound | Iron Condor `[21.10]` |

---
*Educational content only. Not investment advice.*
