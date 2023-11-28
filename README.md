## Portfolio Optimization using MV method (Theory)
<img align="right" alt="Coding" width="400" src="https://d1rwhvwstyk9gu.cloudfront.net/2020/01/Portfolio-Optimization-Methods.png">
While investing in equity markets (stock markets), we often diversify our investments in different stocks to maximize our returns. When investing in multiple stocks, determining the optimal allocation of funds to each stock to minimize risk and maximize returns can be challenging. However, with the help of the portfolio optimization method, we can overcome this issue.

## What is Portfolio Optimization?
Let us first understand what a portfolio is. An investment portfolio refers to a collection of financial assets held by an individual, organization, or entity for the purpose of investment and wealth management. It typically includes a diverse range of investments such as stocks, bonds, mutual funds, exchange-traded funds (ETFs), commodities, and other investment vehicles. The primary objective of a portfolio is to generate returns and grow wealth over time. The composition of an investment portfolio may change over time as market conditions, investment goals, and risk preferences evolve.Portfolio Optimization aims to strike a balance between risk and reward, tailor investments to individual objectives, and increase the likelihood of achieving long-term financial success. Portfolio Optimization acts as a base in mutual funds. However, asset managers incorporate even more complex methods to increase the likelihood of comfortable returns. It is important to note that portfolio optimization is a complex process that may require expertise and professional guidance to implement effectively.

## Markowitz Portfolio Theory
The Markowitz model, also commonly known as Modern Portfolio Theory (MPT), revolutionized portfolio management by introducing the concept of diversification and the trade-off between risk and return. The model suggests that an investor can construct an efficient portfolio by carefully selecting a combination of assets that maximizes returns for a given level of risk or minimizes risk for a desired level of returns.
## Key Terms
Expected Return:
Where we estimate the expected return of each investment in the portfolio based on historical data, financial analysis, or other relevant information.
Risk: 
Risk is measured by the variance or standard deviation of an asset’s returns. Markowitz emphasizes that we should consider the overall portfolio’s risk, considering the correlation or covariance between different assets.
Diversification: 
Markowitz highlights the benefits of diversification in reducing portfolio risk. By combining assets with low or negative correlations, we can potentially achieve a more efficient risk-return trade-off.
Efficient Frontier:
The efficient frontier represents a set of optimal portfolios that offer the highest expected return for each level of risk or the lowest risk for a given level of expected return. The goal is to identify the portfolio that lies on the efficient frontier, providing the best risk-return profile.
Markowitz’s contribution has been significant to the portfolio theory. However, investment practices have evolved over the years, and various enhancements to the original model have been proposed.

While investing in equity markets (stock markets), we often diversify our investments in different stocks to maximize our returns. When investing in multiple stocks, determining the optimal allocation of funds to each stock to minimize risk and maximize returns can be challenging. However, with the help of the portfolio optimization method, we can overcome this issue. In this article, we will try to understand what portfolio optimization is, how to download historical stock price data from Yahoo Finance, and how to build a portfolio optimization code using mean variance method in Python.

## Markowitz Portfolio Theory
The Markowitz model, also commonly known as Modern Portfolio Theory (MPT), revolutionized portfolio management by introducing the concept of diversification and the trade-off between risk and return. The model suggests that an investor can construct an efficient portfolio by carefully selecting a combination of assets that maximizes returns for a given level of risk or minimizes risk for a desired level of returns.

**Expected Return:** 
Where we estimate the expected return of each investment in the portfolio based on historical data, financial analysis, or other relevant information.
**Risk:**
Risk is measured by the variance or standard deviation of an asset’s returns. Markowitz emphasizes that we should consider the overall portfolio’s risk, considering the correlation or covariance between different assets.
**Diversification:** 
Markowitz highlights the benefits of diversification in reducing portfolio risk. By combining assets with low or negative correlations, we can potentially achieve a more efficient risk-return trade-off.
**Efficient Frontier:**
The efficient frontier represents a set of optimal portfolios that offer the highest expected return for each level of risk or the lowest risk for a given level of expected return. The goal is to identify the portfolio that lies on the efficient frontier, providing the best risk-return profile.
Markowitz’s contribution has been significant to the portfolio theory. However, investment practices have evolved over the years, and various enhancements to the original model have been proposed.

## Sharpe Ratio
To determine how much return is expected for the risk we are willing to take, we try to maximize the Sharpe ratio of the portfolio. The Sharpe ratio is a measure used to evaluate the risk-adjusted return of an investment or portfolio. It quantifies the excess return generated per unit of risk taken. The ratio is calculated by subtracting the risk-free rate of return from the investment’s average return and dividing the result by the standard deviation of the investment’s returns. A higher Sharpe ratio indicates better risk-adjusted performance, reflecting higher returns relative to volatility. It helps us compare different investment opportunities and determine whether the potential returns adequately compensate for the level of risk involved. Usually, the government bond yield is considered the risk-free rate of return.
