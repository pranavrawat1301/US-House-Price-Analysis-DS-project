## Analyzing Key Factors Influencing U.S. Home Prices

### Project Overview

This project investigates the key factors influencing U.S. home prices over the past 20 years using publicly available economic and demographic data. The S&P Case-Schiller Home Price Index was used as a proxy for housing prices. The goal was to understand how variables such as GDP, GDP per capita, unemployment rate, housing starts, building permits, population, and mortgage rates affect U.S. home prices.

### Key Factors Analyzed

1. **GDP (Gross Domestic Product)**: Represents the total market value of all goods and services produced in the country.
2. **GDP per Capita**: Measures the average economic output per person.
3. **Unemployment Rate**: The percentage of the labor force that is jobless and actively seeking employment.
4. **Housing Starts**: The number of new residential construction projects that have begun.
5. **Building Permits**: The number of permits issued for new construction or major renovations.
6. **Population**: The total number of people residing in the country.
7. **Mortgage Rates**: The interest rates charged on home loans.

### Methodology

- **Data Import**: The project begins by importing and preprocessing datasets related to the factors mentioned above.
- **Visualization**: Various factors were plotted against home prices to observe trends and correlations.
- **Feature Importance**: An Extra Trees Regressor was used to determine the importance of each factor in predicting home prices.
- **Cross-Correlation Analysis**: Explored the relationship between home prices and other factors at different lags.
- **Granger Causality Tests**: Used to determine whether past values of a factor can predict future values of home prices.

### Key Findings

- **GDP and GDP per Capita**: These factors were found to have the most significant impact on home prices.
- **Population, Building Permits, and Unemployment Rates**: These factors also showed some level of influence on home prices.
- **Mortgage Rates and Housing Starts**: These were less related to housing prices compared to other factors.

### Conclusion

- **Significant Influences**: GDP and GDP per Capita are the most influential factors affecting home prices. Population, Building Permits, and Unemployment Rates also contribute to some extent.
- **Minimal Impact**: Mortgage Rates and Housing Starts showed limited correlation with housing prices, suggesting that their direct impact is less significant.

This analysis provides valuable insights into the economic and demographic factors that impact U.S. home prices, helping in understanding market dynamics and making informed decisions.

### Files Included

- `house_price.csv`: S&P Case-Schiller Home Price Index data.
- `GDP.csv`: GDP data.
- `GDP Per Capita.csv`: GDP per capita data.
- `Unemployement rate.csv`: Unemployment rate data.
- `MORTGAGE.csv`: Mortgage rates data.
- `HOUSING STARTS.csv`: Housing starts data.
- `PERMIT.csv`: Building permits data.
- `Population.csv`: Population data.

### Dependencies

- Pandas
- Matplotlib
- Seaborn
- NumPy
- Scikit-learn
- Statsmodels
