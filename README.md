# Stock Price Time Series Analysis Using Python

## Project Overview

This project was completed as part of the Codveda Technologies Data Analysis Internship – Level 2 (Intermediate).

The objective of this project was to perform time series analysis on historical stock price data to identify trends, seasonal patterns, and irregular fluctuations. The project also applied moving average smoothing techniques to better understand the underlying behavior of stock prices over time.

Time series analysis is widely used in finance, economics, forecasting, and business intelligence to uncover patterns within time-dependent data.

---

## Project Objectives

The following tasks were completed:

* Plot time series data and identify patterns
* Analyze stock price trends over time
* Decompose the time series into:

  * Trend
  * Seasonal Component
  * Residual Component
* Apply Moving Average Smoothing
* Visualize smoothed and original series
* Interpret findings and business insights

---

## Dataset Information

The dataset contains historical stock market data including:

* Stock Symbol
* Date
* Opening Price
* Highest Price
* Lowest Price
* Closing Price
* Trading Volume

For this analysis, Apple Inc. (**AAPL**) stock data was selected and analyzed.

---

## Tools and Technologies Used

* Python
* Pandas
* Matplotlib
* Statsmodels
* Google Colab

---

## Project Workflow

### 1. Data Preparation

* Loaded stock price dataset
* Filtered data for AAPL stock
* Converted date column to datetime format
* Set date as the index

### 2. Time Series Visualization

A line chart was created to visualize stock closing prices over time and identify long-term patterns and fluctuations.

### 3. Time Series Decomposition

The stock price series was decomposed into:

#### Trend Component

Represents the long-term movement of stock prices.

#### Seasonal Component

Represents recurring patterns observed within the series.

#### Residual Component

Represents random variations not explained by trend or seasonality.

### 4. Moving Average Smoothing

A 30-day moving average was calculated to smooth daily price fluctuations and highlight the underlying trend.

---

## Key Findings

### Trend Analysis

The stock price series exhibited noticeable fluctuations over time while maintaining a clear long-term trend.

### Seasonality

Recurring patterns were identified through decomposition, providing insight into cyclical behavior within the dataset.

### Residual Analysis

Residual fluctuations captured irregular market movements that were not explained by trend or seasonal components.

### Moving Average Insights

The 30-day moving average reduced short-term volatility and provided a clearer representation of the stock's overall direction.

---

## Visualizations

### Stock Closing Price Over Time

![Time Series Plot](images/AAPL_TimeSeries.png)

### 30-Day Moving Average

![Moving Average Plot](images/AAPL_MovingAverage.png)

### Time Series Decomposition

![Time Series Decomposition](images/AAPL_Decomposition.png)

---

## Project Structure

```text
Level2-Project1-Time-Series-Analysis
│
├── Stock_TimeSeries_Analysis.ipynb
├── README.md
├── images
│   ├── AAPL_TimeSeries.png
│   ├── AAPL_MovingAverage.png
│   └── AAPL_Decomposition.png
└── stock_data.csv
```

## Skills Demonstrated

* Time Series Analysis
* Data Visualization
* Trend Analysis
* Seasonal Decomposition
* Moving Average Smoothing
* Financial Data Analysis
* Python Programming
* Statistical Analysis
* Google Colab

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Working with time-indexed datasets
* Visualizing stock market trends
* Applying decomposition techniques
* Identifying seasonal and residual patterns
* Using moving averages for data smoothing
* Interpreting financial time series data

---

## Conclusion

This project demonstrates the practical application of time series analysis techniques to historical stock price data. By combining visualization, decomposition, and smoothing methods, valuable insights were extracted regarding stock market behavior and long-term trends.

The techniques used in this project form a foundation for more advanced forecasting, predictive analytics, and financial modeling applications.

---

## Author

Adeyemi Victor

Data Analyst | Python | SQL | Power BI | Excel

Completed as part of the Codveda Technologies Data Analysis Internship Program.
