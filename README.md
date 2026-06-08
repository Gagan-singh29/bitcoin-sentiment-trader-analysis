# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between cryptocurrency market sentiment and trader performance using:

1. Bitcoin Fear & Greed Index Dataset
2. Historical Hyperliquid Trader Dataset

The objective is to determine how market sentiment influences trading activity, profitability, win rates, trading volume, and trading strategy performance.


## Datasets

### Fear & Greed Index Dataset

Contains daily market sentiment classifications:

* Extreme Fear
* Fear
* Neutral
* Greed
* Extreme Greed

Columns used:

* Date
* Value
* Classification

### Historical Trader Dataset

Contains detailed trade-level information including:

* Account
* Coin
* Execution Price
* Size USD
* Direction
* Closed PnL
* Timestamp


## Methodology

1. Data Cleaning

   * Checked missing values
   * Checked duplicates
   * Converted date columns

2. Data Integration

   * Merged both datasets using the date field

3. Exploratory Data Analysis

   * Trade activity analysis
   * Profitability analysis
   * Win rate analysis
   * Trading volume analysis
   * Long vs Short performance analysis
   * Coin preference analysis

4. Visualization

   * Trades by sentiment
   * Average PnL by sentiment
   * Win rate by sentiment
   * Trading volume by sentiment
   * Coin preference by sentiment


## Key Findings

### Trading Activity

* Fear recorded the highest number of trades (61,837).
* Extreme Fear recorded the lowest trading activity.

### Profitability

* Extreme Greed produced the highest average profit per trade (67.89).
* Fear generated the highest total profit due to higher trading activity.

### Win Rate

* Extreme Greed achieved the highest win rate (46.49%).
* Extreme Fear recorded the lowest win rate (37.06%).

### Trading Volume

* Fear attracted the highest trading volume ($483.3M).

### Long vs Short Performance

* Short positions performed better during Fear and Extreme Fear.
* Long positions performed better during Greed and Extreme Greed.

### Coin Preference

* HYPE dominated trading activity during Fear, Extreme Fear, and Neutral conditions.
* @107 dominated trading activity during Greed and Extreme Greed conditions.


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
