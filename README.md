# Trading-

Crypto Sentiment & Trader Performance Analysis - 

This project explores the correlation between Bitcoin Market Sentiment (Fear & Greed Index) and on-chain trader performance on the Hyperliquid DEX. By merging historical trade executions with daily sentiment classifications, we uncover how market psychology influences profitability, win rates, and directional bias (Long vs. Short).

Project Objective - 

The goal is to move beyond "gut feeling" and use data to answer:

   1) Do traders perform better during periods of "Extreme Fear" or "Extreme Greed"?

   2) Which sentiment environments yield the highest Win Rate for Long vs. Short positions?

   3) Is there a statistically significant correlation between the Fear & Greed Index value and aggregate PnL?

Datasets Used - 
1) Bitcoin Market Sentiment Dataset:

   Source: Fear & Greed Index API.

   Data: Daily timestamps, Index Values (0-100), and Classifications (Extreme Fear to Extreme Greed).

2) Historical Trader Data (Hyperliquid):

   Source: Hyperliquid L1 Blockchain.

   Data: Account addresses, symbols, execution prices, trade sizes, side (Buy/Sell), closed PnL, and timestamps.

Tech Stack - 
   Language: Python 3.x

   Data Manipulation: Pandas, NumPy

   Visualization: Matplotlib, Seaborn

   Environment: Jupyter Notebook / Python IDE

Key Insights - 

   1) The "Fear" Alpha: While "Greed" markets attract the most retail volume, the highest aggregate PnL in the dataset was captured during "Fear" periods, likely due to volatility-driven short opportunities.

   2) Win Rate vs. Sentiment: Win rates for Long positions peaked at >90% during "Extreme Greed," confirming a "rising tide lifts all boats" effect, whereas "Extreme Fear" periods saw the highest average profit per             individual Short trade.

   3) Sentiment Lag: Historical data suggests that trader activity (volume) spikes significantly 24–48 hours after a major sentiment shift.
