# Analyzing Key Factors Influencing U.S. Home Prices: A Data-Driven Approach Using the S&P Case-Schiller Home Price Index

This project explores publicly available data on critical economic and demographic factors impacting U.S. home prices over the past 20 years. Using the S&P Case-Schiller Home Price Index as a proxy for housing prices, we build and evaluate a data science model to uncover how various variables have influenced national home prices.

---

## Data Sources

The data used in this project is sourced from the U.S. Census Bureau and the Federal Reserve Economic Data (FRED).

### Factors Considered

1. **GDP (Gross Domestic Product)**: Reflects the overall economic activity.
2. **GDP per Capita**: Average economic output per person.
3. **Unemployment Rate**: Percentage of the labor force that is jobless and actively seeking employment.
4. **Housing Starts**: Number of new residential construction projects.
5. **Building Permits**: Permits issued for new construction or major renovations.
6. **Population**: Total number of people residing in the country.
7. **Mortgage Rates**: Interest rates charged on home loans.

## Summary of Analysis

- **Data Visualization**: Time series plots and scatter plots were created to visualize the trends and relationships between factors and housing prices.
- **Correlation Analysis**: A heatmap was used to show the correlation coefficients between the factors.
- **Feature Importance**: An ExtraTreesRegressor model was employed to determine the importance of each factor on housing prices.
- **Regression Analysis**: A linear regression model was used to analyze the relationship between mortgage rates and housing prices.

## Key Findings

- **Most Influential Factors**: GDP and GDP per capita had the most significant impact on housing prices.
- **Moderately Influential Factors**: Population, building permits, and unemployment rates showed some level of influence.
- **Least Influential Factors**: Mortgage rates and housing starts were found to have minimal correlation with housing prices.

## Conclusion

This project provides a comprehensive analysis of the economic and demographic factors influencing U.S. home prices, offering valuable insights into their relative importance and impact.
