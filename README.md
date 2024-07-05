# Time Series Analysis of Stock Market Prices for Apple, Amazon, Microsoft, and Google

## Overview

This project focuses on the time series analysis of stock market prices for four leading tech companies: Apple, Amazon, Microsoft, and Google. The analysis includes data extraction, cleaning, and various analytical techniques to uncover trends, patterns, and correlations among the stocks.

## Data Extraction and Cleaning

1. **Extract Data**: Stock price data for Apple, Amazon, Microsoft, and Google was obtained from a CSV file.
2. **Data Cleaning**: The extracted data was cleaned by handling missing values, correcting inconsistencies, and ensuring proper date-time formatting for accurate analysis.

## Analysis and Results

### 1. Change in Stock Price Over Time

- **Objective**: To understand how the stock prices of the four companies changed over the years.
- **Result**: 
  - In 2015, Apple achieved its peak stock price, maintaining high values in consecutive years.
  - Amazon, Google, and Microsoft exhibited similar trends over the analyzed period.

### 2. Moving Average of Various Stocks

- **Objective**: To smooth out short-term fluctuations and highlight longer-term trends or cycles in the stock prices.
- **Result**: The moving average analysis revealed the underlying trends in the stock prices, indicating periods of steady growth and occasional dips.

### 3. Analysis of Closing Price Change in Apple Stock

- **Objective**: To identify significant daily changes in Apple's stock price.
- **Result**:
  - The highest daily increment was approximately 8.2% in April 2014.
  - The highest daily decrement was approximately 8% in January 2014.

### 4. Resampling Analysis of Closing Price

- **Objective**: To analyze trends in Apple's stock price on a quarterly basis.
- **Result**: Post-2016, Apple's stock price showed a linear increasing trend every quarter, indicating consistent growth.

### 5. Correlation Analysis of Closing Prices

- **Objective**: To determine if there is a correlation between the closing prices of the tech companies.
- **Result**: 
  - A pair plot analysis indicated a high correlation between Amazon and Microsoft, as evidenced by an almost straight-line trend in the plot.

### 6. Daily Returns Correlation Analysis

- **Objective**: To analyze the correlation of daily changes in closing prices among the stocks.
- **Result**: The analysis revealed a correlation between the daily returns of Amazon and Microsoft stocks.

## Conclusion

The time series analysis of stock market prices for Apple, Amazon, Microsoft, and Google provides valuable insights into their performance and trends over time. Key findings include the significant changes in Apple's stock price, the consistent growth trend post-2016, and the high correlation between Amazon and Microsoft stocks. This analysis can aid investors and analysts in making informed decisions based on historical trends and correlations.

## How to Run the Analysis

1. **Install Dependencies**: Ensure you have Python and necessary libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn` installed.
2. **Load Data**: Load the CSV file containing the stock prices.
3. **Run Analysis**: Execute the provided scripts to perform data cleaning, calculate moving averages, analyze closing price changes, perform resampling analysis, and generate correlation plots.

