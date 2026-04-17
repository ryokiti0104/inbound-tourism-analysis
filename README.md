# Exchange Rates and Inbound Tourism in Japan: Effects on Visitor Arrivals and Spending

## Overview
This project analyzes the relationship between the Japanese yen exchange rate and inbound tourism demand in Japan using official statistical data.

## Data Sources
#### JNTO (Foreign Visitors to Japan, Tourism Consumption)
- foreign_visitors_yearly.csv: https://statistics.jnto.go.jp/graph/#graph--inbound--travelers--transition
- expenditure_per_foreign_tourist.csv: https://statistics.jnto.go.jp/graph/#graph--inbound--consumption--transition
#### Bank of Japan (Exchange Rate)
- exchange_rate_monthly.csv: https://www.stat-search.boj.or.jp/ssi/cgi-bin/famecgi2?cgi=$graphwnd
##### Note: Data for 2020–2022 were excluded because tourism consumption data were not available for those years due to the COVID-19 pandemic.

## Key Findings
- The exchange rate shows a relatively strong correlation with inbound tourism.
- Visitor arrivals and tourism consumption are moderately correlated.
- However, it is not the sole factor affecting tourism demand.

## Visualization
Scatter plot showing the relationship between the exchange rate (JPY/USD) and inbound visitor arrivals in Japan.  
The regression line indicates a positive relationship between a weaker yen and visitor arrivals.
### Exchange Rate vs Visitor Arrivals
![Exchange vs Visitors](images/exchange_vs_visitors.png)

## Regression Analysis
An OLS regression was conducted to examine the relationship between the exchange rate (JPY/USD) and inbound visitor arrivals.
The results suggest a positive relationship between the exchange rate and inbound tourism demand. A weaker yen is associated with higher visitor arrivals.
However, due to the small sample size and external shocks such as COVID-19, the results should be interpreted with caution. The observed relationship may partly reflect broader time trends or other omitted variables rather than a purely causal effect.

## Tourism Demand Structure
### Visitor Arrivals vs Tourism Consumption
![Visitor vs Consumption](images/visitors_vs_consumption.png)


Analysis (one sentence):
Tourism consumption per visitor shows a general upward trend over time, with a temporary dip after 2015 followed by a strong increase toward 2024.

Note on missing data:
Data for the COVID-19 period (2020–2022) are not included, which may limit the interpretation of short-term fluctuations during that time.

## Conclusion
The analysis suggests that exchange rates have a statistically significant relationship with inbound tourism demand in Japan.
A weaker yen is associated with higher visitor arrivals.
Furthermore, visitor arrivals show a strong relationship with tourism consumption, suggesting that increasing inbound tourism contributes to higher tourism revenue.
However, exchange rates are not the sole driver of inbound tourism demand. Other factors such as visa policies, airline capacity, and global travel conditions may also play important roles.
