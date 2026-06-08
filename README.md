# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using:

* Historical Trader Data (Hyperliquid)
* Bitcoin Fear & Greed Index

The objective is to determine how market sentiment influences profitability, win rate, and trading behavior.

---

## Dataset Description

### Historical Trader Data

Contains:

* Trade Timestamp
* Account Information
* Position Details
* Closed PnL
* Leverage
* Trading Side

### Fear & Greed Index

Contains:

* Date
* Sentiment Classification

  * Extreme Fear
  * Fear
  * Neutral
  * Greed
  * Extreme Greed

---

The datasets used in this project exceed GitHub web upload limits and are therefore not included in the repository.

Historical Trader Data:
- Hyperliquid Trading Dataset

Fear & Greed Data:
- Bitcoin Fear & Greed Index

Please place the datasets inside the `data/` folder before running the notebook.

## Methodology

1. Data Loading
2. Data Cleaning
3. Date Conversion
4. Dataset Merging
5. Profitability Analysis
6. Win Rate Analysis
7. Visualization
8. Insight Generation

---

## Key Findings

### Average Profitability

Greed periods generated the highest average profit per trade.

### Win Rate

Extreme Greed periods showed the highest percentage of profitable trades.

### Trading Activity

Fear periods generated the highest cumulative profit because of increased trading activity.

### Market Behavior

Neutral sentiment resulted in the weakest performance.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Results

The study demonstrates a measurable relationship between Bitcoin market sentiment and trader performance. Sentiment indicators can be incorporated into trading strategies to improve decision-making and risk management.

---

## Author

Nawneet Chaubey
B.Tech CSE (AI & Data Science)
