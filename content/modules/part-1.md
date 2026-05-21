---
title: "Part 1: Working with Financial Data in Python"
description: "Financial data workflows, Python setup, and preparation for machine learning in finance."
weight: 10
---

Note: The content on this page is subject to change before class starts.

{{< collapse summary="01-01 Setting Things Up" openByDefault=true >}}

Before we start working with financial data, we will set up the tools needed for the course. In this lesson, we will install Visual Studio Code, set up Python, add the required extensions, and run a simple test file to make sure everything works.

### Topics Covered

- Installing Visual Studio Code
- Installing Python
- Setting up Python in VS Code
- Installing required extensions
- Running a simple Python test file

{{< /collapse >}}

{{< collapse summary="01-02 Getting Started with Stock Data in Python" >}}

In this lesson, we will begin working with real stock market data. We will load stock data into Python using Pandas, filter it by date, create simple plots, and then see how an AI agent can help perform the same tasks more efficiently.

### Topics Covered

- Getting familiar with the stock dataset
- Getting started with Pandas
- Loading stock data into Pandas
- Filtering stock prices by date range
- Visualizing stock price trends
- Using an AI agent to read, filter, and plot stock data

{{< /collapse >}}

{{< collapse summary="01-03 Building Multi-Stock Datasets" >}}

In this lesson, we will work with multiple stocks in one DataFrame, slice the data by date and symbol, plot stock prices, and normalize prices for comparison.

### Topics Covered

- Target DataFrame structure
- Reverse date-order issue
- Loading data for multiple stocks
- Date slicing
- Symbol slicing
- Plotting multiple stocks
- Normalizing prices
- Using an AI agent to work with multiple stocks

{{< /collapse >}}

{{< collapse summary="01-04 NumPy for Financial Computing" >}}

In this lesson, we will learn how NumPy supports fast numerical computing in Python and how it connects with Pandas for financial data analysis.

### Topics Covered

- What NumPy is
- How NumPy relates to Pandas
- Why NumPy is useful
- Creating NumPy arrays
- Indexing and slicing arrays
- Processing data with NumPy
- Using NumPy with Pandas
- Using an AI agent to work with NumPy arrays

{{< /collapse >}}

{{< collapse summary="01-05 Time-Series Statistics for Market Data" >}}

In this lesson, we will calculate basic and rolling statistics for stock price data and use Bollinger Bands as a technical indicator example.

### Topics Covered

- Summary statistics for stock data
- Rolling statistics
- Bollinger Bands
- Plotting technical indicators
- Using an AI agent to calculate and plot time-series indicators

### Reading

- *Python for Finance*, Chapter 6: Financial Time Series

{{< /collapse >}}

{{< collapse summary="01-06 Handling Missing Financial Data" >}}

In this lesson, we will examine why missing data appears in financial datasets and how to handle it in Python.

### Topics Covered

- Why financial data can be incomplete
- Identifying missing values
- Dropping missing values
- Filling missing values
- Using an AI agent to detect and handle incomplete data

{{< /collapse >}}

{{< collapse summary="01-07 Visualizing Returns and Stock Relationships" >}}

In this lesson, we will use histograms and scatter plots to analyze daily returns and compare relationships across stocks.

### Topics Covered

- Histograms of daily returns
- Comparing SPY and XOM
- Creating scatter plots
- Understanding why correlation is not slope
- Comparing SPY vs. XOM and SPY vs. GLD
- Using an AI agent to create return plots and scatter plots

{{< /collapse >}}

{{< collapse summary="01-08 Measuring Portfolio Performance" >}}

In this lesson, we will calculate key portfolio statistics, including daily return, volatility, cumulative return, and the Sharpe ratio.

### Topics Covered

- Faster data loading with memoization
- Average daily return
- Daily return volatility
- Cumulative return
- Relationship between daily and cumulative returns
- Sharpe ratio
- Buy-and-hold portfolio modeling
- Using an AI agent to calculate portfolio statistics

{{< /collapse >}}

{{< collapse summary="01-09 Using Optimization to Fit Models" >}}

In this lesson, we will learn what optimizers do and use one to fit a parameterized model to data.

### Topics Covered

- What an optimizer does
- Optimizer syntax
- Inputs, outputs, and assumptions
- Minimizing a function
- Building a parameterized polynomial model
- Using an AI agent to set up and run an optimizer

{{< /collapse >}}

{{< collapse summary="01-10 Portfolio Optimization in Python" >}}

In this lesson, we will use an optimizer to build a portfolio based on objectives, constraints, and allocation ranges.

### Topics Covered

- What portfolio optimization means
- Framing the portfolio optimization problem
- Constraints for portfolio weights
- Allocation ranges for portfolio weights
- Using an AI agent to optimize a portfolio

### Reading

- *Python for Finance*, Chapter 11: Statistics and Portfolio Optimization

{{< /collapse >}}
