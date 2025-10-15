# Task
Objective

To explore and quantify the relationship between trader performance and market sentiment,
and to determine whether emotional market conditions influence profitability and trading style.

Data Cleaning & Preparation

Handled missing and duplicate records

Standardized date/time formats

Merged sentiment and trading datasets by date

Feature Engineering

Computed per-day metrics:

total_pnl — total daily profit/loss

win_rate — percentage of profitable trades

avg_leverage — average leverage used

num_trades — number of trades executed

Exploratory Data Analysis (EDA)

Compared trader performance during Fear vs Greed phases

Examined sentiment trends and volatility

Identified behavioral shifts in trading volume and leverage

Correlation Analysis

Used Pearson and Spearman coefficients to measure relationships between sentiment value and PnL/win rate.

Predictive Modeling

Built Logistic Regression Model



Visualization Dashboard

Built rich, intuitive plots using matplotlib and seaborn:

Sentiment trends

PnL distribution under Fear vs Greed

Correlation heatmaps

Win rate vs sentiment over time

Trader cluster analysis
