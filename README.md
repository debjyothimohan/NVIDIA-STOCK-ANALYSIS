# NVIDIA-STOCK-ANALYSIS
# NVIDIA (NVDA) Stock Data Analysis



## Project Overview

This project conducts a comprehensive **Exploratory Data Analysis (EDA)** on NVIDIA Corporation's stock data (NVDA). The analysis spans from NVIDIA's IPO in January 1999 to projected dates in mid-2025, providing deep insights into one of the most significant tech stock success stories.

The project includes extensive data cleaning, preprocessing, statistical analysis, and visualization to uncover trends, patterns, and insights into NVIDIA's remarkable stock performance over more than two decades.

## Key Findings & Insights

Our analysis reveals several critical characteristics of NVIDIA's stock performance:

- **Exponential Growth**: Stock price remained relatively stable for ~15 years before experiencing dramatic surge from 2020 onwards
- **High Price Correlation**: OHLC prices show near-perfect correlation (>0.999), typical for daily stock data
- **Future Data**: Dataset includes 2025 projections - important consideration for predictive modeling
- **Volatility Patterns**: 30-day rolling volatility highlights major market events including dot-com bubble, 2008 crisis, and AI boom
- **Volume Spikes**: Significant trading volume increases correspond to earnings, product launches, and stock splits

## Dataset Information

| Attribute | Details |
|-----------|---------|
| **File** | `Nvidia_stock_data.csv` |
| **Date Range** | 1999-01-22 to 2025-06-10 |
| **Columns** | Date, Open, High, Low, Close, Volume |
| **Format** | Standard OHLCV time-series data |

### Column Descriptions
- **Date**: Trading date (datetime index)
- **Open**: Opening price for the trading day
- **High**: Highest price achieved during the day
- **Low**: Lowest price achieved during the day
- **Close**: Final trading price for the day
- **Volume**: Number of shares traded

## Analysis Performed

### Data Cleaning & Preprocessing
- **Data Loading**: CSV import with proper pandas DataFrame structure
- **Date Conversion**: DateTime indexing for time-series analysis
- **Integrity Checks**: 
  - Zero missing values confirmed
  - No duplicate entries found
- **Standardization**: OHLCV column ordering
- **Type Conversion**: Numeric data type validation

### Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Distribution analysis and summary metrics
- **Correlation Analysis**: Relationship mapping with heatmap visualization
- **Time-Series Analysis**:
  - Daily closing price trends
  - Trading volume patterns
- **Technical Analysis**:
  - 7-day and 30-day moving averages
  - 30-day rolling volatility calculations
- **Return Analysis**: Daily percentage change distribution
- **Temporal Aggregation**: Monthly and yearly performance patterns
- **Event Analysis**: High-volume trading day identification

## Visualizations

The project generates comprehensive visual analysis including:

| Visualization Type | Description |
|-------------------|-------------|
| **Price Distribution** | Histogram showing closing price frequency |
| **Time-Series Plots** | Historical price and volume trends |
| **Moving Averages** | Short-term vs long-term trend analysis |
| **Volatility Charts** | Risk assessment over time |
| **Return Distribution** | Daily percentage change patterns |
| **Correlation Heatmap** | Inter-variable relationship matrix |
| **Temporal Analysis** | Monthly/yearly aggregated performance |


## Technical Stack

- **Language**: Python 3.12
- **Data Analysis**: pandas, numpy
- **Visualization**: matplotlib
- **Environment**: Jupyter Notebook/Lab

## Future Work & Extensions

This EDA provides a solid foundation for advanced analysis:

### Predictive Modeling
- **Time-Series Forecasting**: ARIMA, SARIMA, LSTM models
- **Machine Learning**: Feature engineering for price prediction

### Quantitative Analysis
- **Trading Strategies**: Moving Average Crossovers, RSI, MACD
- **Backtesting**: Strategy performance evaluation
- **Risk Management**: Portfolio optimization techniques

### Comparative Analysis
- **Sector Comparison**: AMD, Intel, semiconductor industry
- **Market Benchmarking**: S&P 500, NASDAQ correlation

### Interactive Tools
- **Dashboard Development**: Streamlit/Dash implementations
- **Real-time Updates**: Live data integration
- **User Interface**: Dynamic exploration capabilities

## Key Metrics Summary

| Metric | Value |
|--------|-------|
| **Analysis Period** | 26+ years |
| **Data Points** | 6,000+ daily records |
| **Price Correlation** | >99.9% (OHLC) |
| **Volatility Periods** | 3+ major events identified |
| **Growth Pattern** | Exponential (2020+) |



## Disclaimer

This analysis is for educational and research purposes only. It should not be considered as financial advice for investment decisions. Always consult with qualified financial advisors before making investment choices.

---

