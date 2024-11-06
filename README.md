# Impact-of-Election-Results-on-Stock-Prices
This repository examines how Indian general elections impact stock prices. By analyzing stock data from prominent companies around the 2014 and 2019 election dates, we assess market sentiment shifts and investor reactions to political events.

## Project Overview
This project studies the relationship between election outcomes and stock price reactions, focusing on two key election events in India:
1. **May 16, 2014**: General election that saw a pro-business government come to power.
2. **May 23, 2019**: Re-election of the same government, indicating policy continuity.

The study aims to determine if stock prices exhibit **abnormal returns** during election periods, using the **event study methodology** to evaluate price movements before and after the election dates. We look at how sectors such as IT, pharmaceuticals, and banking respond to political changes.

## Datasets
The dataset includes:
1. **Stock Data**: Adjusted closing prices for ten companies listed on the National Stock Exchange (NSE) of India.
    - Companies include Wipro, Tata Steel, Tata Motors, State Bank of India, Sun Pharma, and others.
2. **Market Index**: The Nifty 50 index serves as a benchmark to assess general market trends and isolate election-specific impacts.

### Data Collection
The stock data and Nifty 50 index were retrieved from Yahoo Finance, covering the period from January 1, 2013, to December 31, 2020. This timeframe includes a sufficient estimation and event window to observe the stock price reactions surrounding each election event.

## Methodology
The analysis follows an **event study** approach:
1. **Event Window**: Examines stock price movements from 10 days before to 10 days after each election date.
2. **Market Model**: Uses an Ordinary Least Squares (OLS) regression to estimate expected returns based on historical data.
3. **Abnormal Returns (AR)**: Calculated as the difference between actual and expected stock returns.
4. **Cumulative Abnormal Returns (CAR)**: Aggregates AR across the event window to observe overall election impact.
5. **Statistical Testing**: t-tests assess the statistical significance of abnormal returns to understand if election events cause notable stock price deviations.

## Google Colab Notebook
The Google Colab Notebook titled **"Election_Impact_Stock_Prices_Analysis.ipynb"** contains:
- **Data Preparation**: Imports, cleans, and prepares stock price data for analysis.
- **Event Study Calculation**: Calculates abnormal returns (AR) and cumulative abnormal returns (CAR) for selected stocks.
- **Visualization**: Graphs the AR and CAR for each company to highlight stock reactions.
- **Statistical Analysis**: Conducts t-tests to determine the significance of abnormal returns.

This notebook enables users to replicate the analysis and visualize stock price behavior in response to election outcomes.

## Results
### Key Findings
1. **2014 Election**: 
   - The expectation of a pro-business government increased investor optimism, resulting in positive abnormal returns around the event date, particularly in sectors like infrastructure and energy.
2. **2019 Election**:
   - While market reactions were generally positive, they were less volatile than in 2014. The "re-election" effect contributed to stability, with fewer short-term fluctuations.
   
### Sector-Specific Reactions
- **IT and Pharmaceuticals**: Mixed responses based on global and local industry challenges.
- **Banking and Infrastructure**: Strong positive abnormal returns, reflecting investor confidence in growth-oriented policies.

These findings underscore the importance of political events in shaping investor sentiment, especially for sectors sensitive to policy changes.
