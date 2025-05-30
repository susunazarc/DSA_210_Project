# DSA_210_Project – Lipstick Index Analysis in Turkey

## Project Idea

In this project, I analyze how cosmetic sales trends correlate with financial growth and economic downturns. The goal is to determine whether the “Lipstick Index” phenomenon holds true — that is, whether consumers shift toward smaller luxury purchases, such as cosmetics, during financial crises. By comparing cosmetic sales data with economic indicators like GDP growth and stock market performance, I aim to identify patterns reflecting consumer behavior during different financial conditions.

If a clear relationship exists, this analysis could provide insights into how economic uncertainty influences spending habits on affordable luxuries.

## Datasets

### 1. Beauty Product Retail Sales in Istanbul (2021–2023)

- Yearly retail sales data for beauty products in Istanbul
- Helps identify trends in cosmetic spending over time
- Source: https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset
- `customer_shopping_data.csv`

### 2. Turkey’s GDP, CPI and CCI Data (2021–2023)

- Provides Turkey’s GDP, Consumer Price Index (CPI), and Consumer Confidence Index (CCI)
- Used to assess economic health and identify downturns
- Sources:
  - https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=TR
  - https://fred.stlouisfed.org/series/TURCPALTT01IXNBM
  - https://data.tuik.gov.tr/Bulten/Index?p=Consumer-Confidence-Index-August-2023-49440&dil=2
  - `API_NY.GDP.MKTP.CD_DS2_en_csv_v2_19294.csv`
  - `TURCPALTT01IXNBM.csv`

Turkey’s economic data is analyzed alongside beauty retail sales in Istanbul malls to determine whether economic shifts influence cosmetic consumption, as the Lipstick Index suggests.

## Methods I’ve Used

1. **Data Cleaning & Transformation**  
   - Filtered cosmetic sales data  
   - Converted date formats and calculated total sales  
   - Processed GDP and CPI data for consistency

2. **Exploratory Data Analysis (EDA)**  
   - Visualized trends in cosmetic sales, GDP, and CPI  
   - Generated a correlation matrix

3. **Hypothesis Testing**  
   - Pearson correlation between GDP and cosmetic sales

4. **Machine Learning**  
   - Linear Regression model using GDP and CPI to predict cosmetic sales

## Key Findings

### Correlation Analysis
- Correlation between GDP and cosmetic sales: -0.353  
- P-value: 0.071 (not statistically significant at α = 0.05)

### Machine Learning Model
- RMSE: ~19,594  
- R² Score: -0.14 (indicates poor model fit)

## My Insights and Conclusion

The observed Pearson correlation coefficient between GDP and cosmetic sales was moderate (-0.353), with a p-value of 0.071 — above the conventional significance threshold of 0.05. Additionally, the R² value from our linear regression model was negative, indicating poor predictive power. These metrics suggest that while there may be trends worth exploring, the current data from Turkey alone does not provide conclusive support for the Lipstick Index.

This analysis offered me valuable insight into the relationship between cosmetic sales and macroeconomic indicators in Turkey. While GDP and CPI alone did not strongly predict cosmetic spending in this dataset, the findings suggest that consumer behavior during economic shifts is complex and influenced by multiple factors. The project highlights the potential of expanding the model with additional features — such as unemployment rates, consumer sentiment, or stock market trends — to further investigate the "Lipstick Index" in a more holistic framework.

This also shows that in Turkey, cosmetics are not seen as recession-proof essentials or symbolic comfort goods to the same extent as the Lipstick Index suggests, possibly due to different cultural spending habits.




