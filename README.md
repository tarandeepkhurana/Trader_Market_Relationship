# Trader Performance vs Market Sentiment Analysis
This project explores the relationship between trader performance and market sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading strategies.

---

## Datasets
1. **Bitcoin Market Sentiment Dataset**
   - Columns: `Date`, `Classification (Fear/Greed)`

2. **Hyperliquid Trader Data**
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, 
     `start position`, `event`, `closedPnL`, `leverage`, etc.

---

## Approach
- **Understanding Business Context** – defined the key objective: link sentiment with trader performance.
- **Data Cleaning & Integration** – aligned sentiment data with trade timestamps.
- **Exploratory Data Analysis (EDA)** – studied PnL, direction, and trade behavior across sentiment categories.
- **Data Visualization** – performed extensive data visualizations to uncover hidden trading patterns.

---

## Notebooks Overview

This repository contains three main Jupyter notebooks, each focusing on a different stage of the analysis:

1. **`sentiment_notebook.ipynb`**  
   - Explores the **Bitcoin Market Sentiment dataset**.  
   - Key tasks: distribution of Fear/Greed over time, sentiment trends, and initial observations.  

2. **`historical_data_notebook.ipynb`**  
   - Focuses on **Historical Trader Data** from Hyperliquid.  
   - Key tasks: trader activity, trade patterns, profit/loss distributions, and risk behavior.  

3. **`trader_behavior_insights_notebook.ipynb`**  
   - Integrates both datasets to study the **relationship between trader performance and market sentiment**.  
   - Key tasks: data merging, exploratory analysis, and multi-dimensional visualizations (PnL vs sentiment, trade size vs sentiment, trade direction vs sentiment, coin vs sentiment, sentiment trend vs profit trend, account-level performance, Size USD vs sentiment, Side vs sentiment, and correlation analysis).

📌 *Each notebook contains clear markdown explanations, insights, and supporting visualizations. It is strongly recommended to go through them in sequence for a complete understanding of the analysis.*  

---
   
