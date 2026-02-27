Summary MarkDown

Methodology

Two datasets were analyzed: a daily Bitcoin market sentiment dataset (Fear/Greed) and historical trade-level data from the Hyperliquid platform.
Data quality checks confirmed the absence of missing values and duplicates. Timestamps were converted and aligned at a daily level to ensure consistency across datasets.

Trade-level data was aggregated into daily trader metrics, including daily PnL, trade count, win rate, average trade size, and long/short ratio. These metrics were then merged with daily market sentiment labels. Performance and behavioral patterns were compared across Fear and Greed regimes. Additionally, a simple predictive model was built to assess whether trader behavior and sentiment could predict next-day profitability.

Key Insights

Market sentiment significantly influences trader behavior and performance.
Fear days are associated with lower win rates and higher PnL volatility, particularly for high-activity traders.

Greed regimes encourage increased participation and long bias.
Traders tend to execute more trades during Greed periods, with disciplined active traders achieving better performance.

Conservative traders demonstrate stable performance across regimes.
Low-activity traders are less affected by sentiment-driven volatility and maintain relatively consistent results.

Strategy Recommendations

Reduce risk during Fear regimes: Traders should lower trade frequency and avoid aggressive positioning during Fear periods to limit drawdowns.

Adopt selective aggression during Greed regimes: Increased participation during Greed periods should be limited to historically profitable and disciplined traders, with controlled position sizing.

Maintain consistency for conservative strategies: Traders with a low-activity approach should prioritize capital preservation and avoid sentiment-driven overreaction.

Conclusion

This analysis highlights the importance of sentiment-aware trading strategies. By aligning trading behavior with market sentiment conditions, traders and platforms can improve risk management, reduce unnecessary losses, and enhance overall performance.
