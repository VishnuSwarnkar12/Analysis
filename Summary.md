# Project Summary

## Methodology

The analysis began by loading the historical trading dataset and the Fear & Greed Index dataset into Python using Pandas.
Missing values and duplicate records were inspected before converting timestamps into a common daily format.
The two datasets were merged on the trading date to associate each trading day with its corresponding market sentiment.
Additional features including daily PnL, win rate, average trade size, trade frequency, long/short ratio, and trader-level statistics were generated.

Trader segmentation was performed based on trading frequency, average trade size, and historical win rate. Multiple visualizations were created to compare trader behavior across different market sentiment conditions.

---

## Key Insights

- Extreme Fear periods produced the highest average daily profits among all sentiment categories.

- High-frequency traders achieved substantially higher total profits than medium- and low-frequency traders.

- Traders with consistently higher win rates were generally more active and executed a larger number of trades.

---

## Strategy Recommendations

### Strategy 1

During Fear and Extreme Fear market conditions, traders should prioritize disciplined participation while maintaining appropriate risk management, as these periods demonstrated stronger average profitability.

### Strategy 2

Instead of increasing trade size aggressively, traders may benefit more from identifying a larger number of high-quality trading opportunities while maintaining consistent execution.
