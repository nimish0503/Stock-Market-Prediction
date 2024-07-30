# Stock-Market-Prediction

## Overview

In this project we utilize python to:
1. **Collect Historical Stock Data:** Download and prepare historical stock data using the yfinance library. The data includes prices and volumes for selected stocks over the past year.
2. **Analyze Stock Performance:** Visualize stock performance through graphs of adjusted close prices, moving averages, and trading volumes. Analyze the distribution of daily returns and calculate correlations between stocks.
3. **Optimize Portfolio:** Apply Modern Portfolio Theory to construct an efficient portfolio. This involves calculating expected returns and volatility, generating random portfolios, and identifying the optimal portfolio with the highest Sharpe ratio.
4. **Visualize Efficient Frontier:** Plot the efficient frontier to showcase the trade-off between risk and return for different portfolio combinations. Identify the portfolio that offers the best risk-adjusted return.

## Data Collection

The script uses the yfinance library to download historical stock market data for a list of stock tickers. The example uses the following tickers:

- RELIANCE.NS (Reliance Industries)
- TCS.NS (Tata Consultancy Services)
- INFY.NS (Infosys)
- HDFCBANK.NS (HDFC Bank)

Data is collected for the past year, with daily price information including Open, High, Low, Close and Volumne.

## Performance Analysis

The script performs several analyses:

1. **Adjusted Close Price Trends:** Plots the adjusted close prices over time for each stock.
2. **Moving Averages:** Calculates and plots 50-day and 200-day moving averages.
3. **Trading Volume:** Plots the volume traded for each stock.
4. **Distribution of Daily Returns:** Analyzes and plots the distribution of daily returns for each stock.
5.**Correlation Matrix:** Computes and plots the correlation matrix of daily returns.

## Portfolio Optimization

Using Modern Portfolio Theory, the cript constructs an efficient portfolio by balancing risk and return. The steps include:

1. **Calculate Expected Returns and Volatility:** Computes the annualized expected returns and volatility for each stock.
2. **Generate Random Portfolios:** Simulates a large number of portfolios to find the efficient frontier.
3. **Optimize Portfolio:** Identifies the portfolio with the maximum Sharpe ratio, representing the best risk-adjusted return.

## Result and Analysis

The script generates plots for:

1. **Efficient Frontier:** Shows the trade-off between risk and return for different portfolios.
2. **Optimal Portfolio Weights:** Displays the stock allocations for the portfolio with the highest Sharpe ratio.

## Example Output

The optmal allocations are:
1. HDFCBANK: 30.85%
2. INFY: 10.59%
3. RELIANCE: 18.02%
4. TCS: 40.53%

These weights are chosen to maximize returns while managing risk effectively.

## Conclusion

This project demonstrates how to leverage Python for stock market portfolio optimization using Modern Portfolio Theory. By analyzing historical stock data, calculating expected returns and volatilities, and optimizing portfolio allocations, investors can make more informed decisions that balance risk and return effectively. The visualizations and analyses provided offer valuable insights into stock performance, including trends, volatility, and correlations. The portfolio optimization process identifies an efficient portfolio that maximizes returns relative to risk, offering a strategic approach to investing.
