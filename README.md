
# Analysis of US Unemployment vs Labor Participation

## Overview
This repository contains a Jupyter Notebook analysis of the US unemployment rates versus labor market participation. It includes a series of graphs that provide visual insights into these economic indicators over time and across different US states.

## Methodology
The analysis is conducted using Python with the following methodology:

1. **Data Collection**: Data is sourced from the FRED (Federal Reserve Economic Data) API, ensuring reliable and up-to-date economic data.
2. **Data Processing**: The data is cleaned and structured for analysis. This includes handling missing values, parsing dates, and normalizing data where necessary.
3. **Time Series Analysis**: We perform a time series analysis to understand trends and patterns over time.
4. **Comparative Analysis**: Comparisons are made between different states to identify regional disparities and trends.
5. **Correlation Analysis**: We investigate the relationship between unemployment rates and labor market participation to understand how these two metrics interact with each other.

## Insights from Graphs

### S&P 500 (S&P500.png)
This graph tracks the S&P 500 index over time, illustrating the overall health of the stock market and, indirectly, the economy. Observing the trend, one can infer periods of growth and recession, which often correlate with labor market conditions.

### Annual National Unemployment Rate (Annual_National_Unemployment_Rate.png)
Displays the national unemployment rate from 1949 onwards. The spikes correlate with known economic downturns, such as the early 1980s recession, the dot-com bubble burst, the 2008 financial crisis, and the COVID-19 pandemic.

### Unemployment Rate by State, April 2020 (Unemployment_rate_Per_State_for_April_2020.png)
This bar chart provides a snapshot of how the COVID-19 pandemic affected each state differently, with states like Nevada and Hawaii experiencing higher rates likely due to their reliance on tourism.

### Annual Unemployment Rate Per State (Annula_Unemployment_Rate_Per_State.png)
A multi-line chart showing unemployment trends across various states. This highlights regional economic variations and can be used to compare the impact of national economic trends on individual states.

### Annual Participation Rate Per State (Annula_Participation_Rate_Per_State.png)
Similar to the previous graph but focusing on labor force participation. Comparing this graph with the unemployment rate can reveal if a decrease in unemployment is due to job creation or a shrinking labor force.

### Participation vs Unemployment Per State After 2020 (Participation_Vs_Unemployment_Per_State_After_2020.png)
This set of graphs compares the labor force participation rate and unemployment rate for each state post-2020. It can be inferred that while some states recovered quickly from the pandemic's impact, others continued to struggle.

## Repository Structure
- `US Unemployment vs Participation.ipynb`: Main Jupyter notebook with the analysis code and comments.
- `S&P500.png`: Graph showing the S&P 500 index over time.
- `Annual_National_Unemployment_Rate.png`: Graph of the national unemployment rate from 1949 to present.
- `Unemployment_rate_Per_State_for_April_2020.png`: Bar chart of unemployment rates by state for April 2020.
- `Annula_Unemployment_Rate_Per_State.png`: Multi-line chart of annual unemployment rates per state.
- `Annula_Participation_Rate_Per_State.png`: Multi-line chart of annual participation rates per state.
- `Participation_Vs_Unemployment_Per_State_After_2020.png`: Comparative line graphs of participation vs. unemployment rates per state post-2020.

## Requirements
- Python 3
- Jupyter Notebook
- Libraries: `pandas`, `matplotlib`, `numpy`, `fredapi`

## Usage
To run the analysis, you'll need an API key from FRED. Set up the API key in your environment and execute the Jupyter Notebook cell by cell.

## Contributing
Contributions are welcome. Please open an issue first to discuss what you would like to change or add.
