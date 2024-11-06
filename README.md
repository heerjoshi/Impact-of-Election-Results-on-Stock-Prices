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
The analysis employs a rigorous **event study** approach with statistical tests to evaluate the stock market's reaction to the election events.

1. **Event Window**: Observes stock price changes 10 days before and after each election date to capture the full effect.
2. **Market Model**: Uses an Ordinary Least Squares (OLS) regression to model expected stock returns, accounting for general market movements.
3. **Abnormal Returns (AR)**: Measures deviations between actual and expected returns during the event window.
4. **Cumulative Abnormal Returns (CAR)**: Aggregates AR values over the event window to assess the overall election impact.
5. **Statistical Testing**:
   - **t-tests**: Test the significance of AR and CAR values to determine if the observed stock price changes are statistically significant.
   - **Paired t-tests**: Analyze differences in returns before and after each election event, focusing on any significant shifts in stock price behavior.
   - **Variance Analysis**: Examines return volatility to assess how election events may influence market stability or risk.
   - **Correlation Analysis**: Investigates correlations between election events and stock returns across different sectors, providing insights into sector-specific sensitivities.

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
   - A significant positive reaction in sectors like infrastructure and energy, suggesting investor confidence in a pro-business government.
   - t-tests confirmed statistically significant abnormal returns for several companies, reflecting heightened investor optimism.
   
2. **2019 Election**:
   - More muted market response compared to 2014. The continuity of the ruling party led to less volatility and stable returns across most sectors.
   - Paired t-tests indicated fewer significant changes in AR and CAR, consistent with investor expectations of policy stability.

These results highlight how political events impact market sentiment and emphasize the need for investors to consider both statistical significance and market expectations when interpreting stock price movements.
   
### Sector-Specific Reactions
- **IT and Pharmaceuticals**: Mixed responses based on global and local industry challenges.
- **Banking and Infrastructure**: Strong positive abnormal returns, reflecting investor confidence in growth-oriented policies.

These findings underscore the importance of political events in shaping investor sentiment, especially for sectors sensitive to policy changes.

## Authors
This project was conducted as part of an M.Sc. (Economics) course.
- **Heer Joshi**
- **Shubham Prakash** 
