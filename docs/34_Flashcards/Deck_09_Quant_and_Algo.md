# Flashcard Deck 9 — Algorithmic & Quantitative Trading

> Covers Modules 29 (Algorithmic Trading), 30 (Quantitative Trading). Part of Module 34.

| Front | Back |
|---|---|
| What is algorithmic trading? | Computer programs executing trading decisions according to predefined rules, without manual order placement. `[29.01]` |
| Is HFT synonymous with algorithmic trading? | No — HFT is one extreme category within the much broader algo trading spectrum. `[29.01]`, `[29.08]` |
| What distinguishes rule-based systems from discretionary trading? | Rule-based uses precisely defined, codeable criteria; discretionary relies on subjective judgment. `[29.02]` |
| What is look-ahead bias? | Using information in a backtest that wouldn't have been available at the actual simulated trade moment. `[29.03]` |
| What is survivorship bias in backtesting? | Testing only currently-existing instruments, excluding delisted/failed ones. `[29.03]` |
| What is overfitting (curve-fitting)? | Tuning a strategy too precisely to historical noise rather than a genuine, persistent pattern. `[29.04]` |
| What is walk-forward testing? | Sequentially optimizing on one window and testing on the next, genuinely unseen window. `[29.04]` |
| What does TWAP do? | Splits a large order evenly across a specified time period. `[29.05]` |
| What does VWAP do? | Splits a large order to match the market's typical volume pattern. `[29.05]` |
| Why should risk management be architecturally independent from strategy logic in a trading bot? | So a bug in signal logic cannot bypass risk limits. `[29.06]` |
| What real incident illustrates the danger of inadequate automated risk gates? | Knight Capital's August 2012 trading error (~$440 million loss). `[29.06]` |
| When did SEBI first formally permit institutional algorithmic trading/DMA? | Around 2008. `[29.07]` |
| What infrastructure investment is central to HFT's speed edge? | Co-location and low-latency networks. `[29.08]` |
| What is quantitative trading? | Deriving trading strategy ideas from rigorous statistical/mathematical analysis of data. `[30.01]` |
| What does standard deviation measure? | The spread of values around the mean — identical to "volatility." `[30.02]` |
| How does cointegration differ from correlation? | Cointegration measures a stable relationship between price levels; correlation measures co-movement of returns. `[30.03]` |
| What does positive autocorrelation indicate? | Momentum — returns tend to continue in the same direction. `[30.04]` |
| Name the four classic investing factors. | Value, momentum, quality, and low-volatility. `[30.05]` |
| What is market making's primary profit source? | Capturing the bid-ask spread repeatedly across high trading volume. `[30.06]` |
| What does VaR estimate, and what is its key limitation? | Maximum expected loss at a given confidence level — says little about severity beyond that threshold. `[30.07]` |

---
*Educational content only. Not investment advice.*
