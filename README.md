Trader Beaviour Analysis Based on Market Sentiment

📌 Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

The objective is to understand how market psychology influences trader profitability, win rate, and risk-taking behavior, and to derive insights that can support smarter trading strategies.


📂 Datasets Used

1. Bitcoin Market Sentiment Dataset
   - Date : Calendar date
   - Classification : Market Sentiment
       - Fear
       - Extreme Fear
       - Greed
       - Extreme Greed
       - Neutral
    
2. Historical Trader Data
   - account : trader identifier
   - coin : traded assest
   - execution_price : trade execution price
   - size_tokens, size_usd : trade size
   - side : buy/sell
   - timestamp : trade time
   - closed_pnl : profit or loss per trade


🛠️ Tools & Technologies

- Python
- Pandas : Data cleaning and analysis
- Matplotlib and Seaborn : Visualization
- Jupyter Notebook


🔄 Data Processing Steps

1. Cleaned and standardized column names

2. Converted Unix timestamps to readable datetime format

3. Extracted date for merging datasets

4. Merged trader data with market sentiment data

5. Handled missing sentiment values

6. Created derived features such as trade win flag


📈 Analysis Performed

- PnL Distribution Analysis
    - Compared profit and loss distributions across different market sentiments

- Win Rate Analysis
    - Measured the percentage of profitable trades under each sentiment regime

- Risk Behavior Analysis
    - Used trade size (USD) as a proxy for risk exposure due to absence of leverage data


🔍 Key Insights

- Trader performance varies significantly across market sentiment regimes

- Extreme Greed periods show the highest trade win rates, indicating momentum-driven opportunities

- Fear phases exhibit high volatility, producing both large gains and losses

- Neutral sentiment results in the lowest win rates, reflecting unclear market direction

- Risk-taking behavior increases during Greed phases, leading to higher PnL variability


 📌 Conclusion

Market sentiment plays a meaningful role in shaping trader behavior and performance.
The analysis suggests that sentiment-aware risk management—such as moderating exposure during Greed and maintaining discipline during Fear—can improve trading consistency.

🔍 Data Availability

The datasets used in this project were provided as part of an assignment and are not included in this repository.
