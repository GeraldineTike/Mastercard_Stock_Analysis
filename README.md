MASTERCARD STOCK HOSTORY- EXPLORATORY DATA ANALYSIS

![OIP (5)](https://github.com/user-attachments/assets/edc45990-0372-4f0b-a6bb-665f480d6202)

Description

This project analyzes the historical stock data of Mastercard to uncover trends, patterns, and insights. It focuses on performing Exploratory Data Analysis (EDA) to understand the stock's behavior over time and identify key characteristics related to price fluctuations, trading volume, dividends, and stock splits.

Dataset Overview

Total Records: 3872
Date Range: From the earliest recorded date (2006-05-25).

Columns
Date: Trading day.
Open: Price at market opening.
High: Highest price reached during the day.
Low: Lowest price reached during the day.
Close: Price at market closing.
Volume: Total shares traded.
Dividends: Dividend payouts on specific dates.
Stock Splits: Information about stock split events.

Objectives

1. Preprocessing:
Ensure the Date column is properly formatted as a datetime object.
Handle outliers or anomalous values in numeric fields.

2. Analysis:
Trend analysis of opening and closing prices over time.
Correlation between Volume, High, Low, and Close.
Impact of dividends and stock splits on trading volume and prices.
Seasonal patterns or periodic fluctuations in stock performance.

3.Visualizations:
Line charts for price trends.
Histograms and box plots for price and volume distributions.
Heatmaps to identify correlations.
Event markers (e.g., stock splits and dividends) on price trend charts.

Dependencies:

Python Libraries:

pandas: For data manipulation.
matplotlib/seaborn: For visualizations.
numpy: For numerical operations.
datetime: For handling date fields.
