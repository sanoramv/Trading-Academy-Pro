# CheatSheet 7 — Strategy, Risk, Sizing & Portfolio

> Covers Modules 24-27. Part of Module 35.

## Expectancy Formula (`[24.01]`)
```
Expectancy = (Win Rate x Avg Win) - (Loss Rate x Avg Loss)
```

## Position Sizing Formula (`[25.02]`, `[26.02]`)
```
Position Size = Risk Per Trade (currency) / Stop Distance (currency)
Risk Per Trade = Account Equity x Fixed % (commonly 1%)
```

## Breakeven Win Rate (`[25.04]`)
```
Breakeven Win Rate = Risk / (Risk + Reward)
  1:1 -> 50%    1:2 -> 33%    1:3 -> 25%
```

## Recovery Math (`[25.01]`)
```
Gain Needed to Recover = Loss / (1 - Loss)
  10% loss -> 11% gain    50% loss -> 100% gain    90% loss -> 900% gain
```

## Kelly Criterion (`[26.04]`)
```
Kelly % = W - [(1-W)/R]
  W = win rate, R = payoff ratio (avg win / avg loss)
  ALWAYS use a FRACTION (1/4 to 1/2) of full Kelly in practice
```

## Strategy Framework Quick Map (Module 24)
| Framework | Condition Fit |
|---|---|
| Trend-Following `[24.02]` | Trending markets |
| Mean-Reversion `[24.03]` | Range-bound markets |
| Breakout `[24.04]` | Range → new trend transition |
| Theta-Selling `[24.09]` | Elevated/normal IV, range-bound |

## Portfolio Metrics (`[27.08]`)
```
Sharpe Ratio  = (Return - Risk-Free Rate) / Std Deviation
Sortino Ratio = (Return - Risk-Free Rate) / DOWNSIDE Deviation only
```

## Personal Risk Rulebook Checklist (`[25.08]`)
1. Per-trade risk limit (%)
2. Stop-loss methodology
3. Minimum risk-reward ratio
4. Max drawdown response trigger
5. Correlation/cluster limit
6. Tail-risk safeguards (leverage cap, cash reserve)

---
*Educational content only. Not investment advice.*
