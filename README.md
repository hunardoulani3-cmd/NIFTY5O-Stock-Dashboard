# NIFTY5O-Stock-Dashboard
A python script that pulls the current NIFTY 50 constituent list from NSE; fetches live price data for the stocks using the yfinance library- current price, previous close, day's change (₹ and %), market cap, and volume; displays this as a clean table, exports it to CSV and PNG; plots a 1-year price chart for chosen stock, with monthly markers 
As someone with a keen interest in finance, I've been trying to connect the theoretical side of equity analysis with practical, hands-on tools. This small project was a step in that direction.

I built a Python script that:
1. Pulls the current NIFTY 50 constituent list directly from NSE (so the list of companies tracked stays up to date automatically, rather than being hardcoded)
2. Fetches live price data for all 50 stocks using the yfinance library — current price, previous close, day's change (₹ and %), market cap, and volume
3. Sorts and displays this as a clean table, and exports it to CSV and PNG for further use
4. Plots a 1-year price chart for any chosen stock, with monthly markers on the x-axis for easier trend-reading

Working with this dataset gave me a more concrete feel for how market cap, daily price movement, and trading volume relate to each other across sectors. However, this is a fairly basic dashboard. It only captures a daily snapshot without any historical trend analysis across all 50 stocks, sector-wise grouping, or valuation ratios (P/E, P/B, etc.) yet, which would be the natural next step. The NSE data source can also be unreliable at times due to access restrictions, so the script doesn't yet have a fallback for that.

For someone early in their Fintech journey, I think there's real value in building small tools like this as they force you to think about data sourcing, structure, and what numbers actually mean in context, rather than just consuming pre-made dashboards.
Open to feedback from anyone who has worked on similar projects particularly on how to extend this toward more meaningful fundamental analysis.
