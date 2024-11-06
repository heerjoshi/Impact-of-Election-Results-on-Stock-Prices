# Impact-of-Election-Results-on-Stock-Prices
This project analyzes the effect of Indian general elections (2014 and 2019) on the stock prices of select companies. Using an event study approach, we assess stock price reactions to significant political events, focusing on how market sentiment and investor behavior shift with election outcomes.

## Project Overview
India's stock market often reacts sensitively to election results, reflecting investor sentiment towards political stability and economic policy changes. This study examines whether the stock prices of key Indian companies exhibit abnormal returns around the 2014 and 2019 election dates. 

Key objectives include:
- Assessing short-term and long-term stock market reactions to election outcomes.
- Evaluating abnormal returns in various sectors such as IT, pharmaceuticals, and banking.
- Examining patterns using event study techniques to understand market efficiency in response to political events.

## Datasets
The datasets for this project include:
1. Daily adjusted closing prices for selected stocks (Wipro, Tata Steel, State Bank of India, etc.) from the NSE.
2. The Nifty 50 index used as a benchmark for broader market trends.

Data Sources:
- [Yahoo Finance](https://finance.yahoo.com/) for stock prices.
- Election event dates: May 16, 2014, and May 23, 2019.

## Methodology
The analysis is based on an **event study** method, employing:
1. **Market Model Estimation**: Using Ordinary Least Squares (OLS) regression to estimate the relationship between stock and market returns.
2. **Abnormal Returns (AR)**: Calculated as deviations from expected returns.
3. **Cumulative Abnormal Returns (CAR)**: Aggregating AR values over the event window.
4. **Statistical Significance Testing**: Using t-tests to assess the significance of abnormal returns.

Please refer to the detailed methodology and statistical analysis in the accompanying Google Colab notebook.

