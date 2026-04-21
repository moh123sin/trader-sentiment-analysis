# Trader Performance vs Market Sentiment Analysis

## Overview
In this project, I analyzed how Bitcoin market sentiment (Fear and Greed) affects trader performance and behavior. The goal was to understand whether sentiment influences profitability, trading activity, and risk-taking.

## Dataset
The analysis is based on two datasets:
- Bitcoin Fear & Greed Index (market sentiment)
- Historical trader data from Hyperliquid

## What I Did
- Cleaned and prepared both datasets
- Converted timestamps and aligned them by date
- Merged trader data with sentiment data
- Calculated key metrics like PnL, win rate, and trade size
- Compared performance across different sentiment conditions
- Analyzed trader behavior and activity patterns
- Identified segments like frequent vs infrequent traders

## Key Insights
- Traders tend to perform better during Extreme Greed periods
- Fear periods show higher total PnL but lower consistency
- Extreme Fear conditions lead to weak performance
- Trade size and activity vary based on sentiment

## Strategy Recommendations

- Trade more selectively during Extreme Fear periods, since both win rate and profitability appear weaker in highly negative sentiment.
- During Fear periods, position sizing should be controlled more carefully because larger trade sizes may increase risk even when total PnL is high.
- Extreme Greed periods appear to show stronger average performance, so these conditions may be better for higher-conviction setups.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## How to Run
1. Download the notebook
2. Install required libraries (pandas, numpy, matplotlib)
3. Run all cells in order

## Conclusion
This analysis shows that market sentiment has a noticeable impact on trading performance and behavior. These patterns can be useful for making more informed trading decisions.
