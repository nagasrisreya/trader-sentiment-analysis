# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear vs Greed) impacts trader behavior and performance.

## Methodology
- Cleaned and merged sentiment + trade datasets
- Created features: win rate, leverage proxy, trade frequency
- Performed segmentation:
  - High vs Low exposure
  - Frequent vs Infrequent traders
  - Winners vs Losers

## Key Insights
1. Traders show lower profitability and higher volatility during Fear periods.
2. High exposure traders are more negatively impacted during Fear conditions.
3. Frequent traders tend to overtrade during Greed phases, reducing profitability.

## Strategy Recommendations
1. Reduce position sizes during Fear periods to minimize risk.
2. Avoid excessive trading during Greed phases to prevent overtrading losses.

## How to Run
- Open the notebook in Jupyter/Colab
- Run all cells sequentially
