# DSA_210_Project


Project Idea:
In this project, I will analyze how cosmetic sales trends correlate with financial growth and economic downturns. My goal is to determine whether the “Lipstick Index” phenomenon holds true by examining whether consumers shift toward smaller luxury purchases, such as cosmetics, during financial crises. I plan on doing this by comparing cosmetic sales data with economic indicators like GDP growth and stock market performance to identify patterns that reflect consumer behavior during different financial conditions. If a clear relationship exists, this analysis could provide insights into how economic uncertainty influences spending habits on affordable luxuries. 

Datasets:

1. Beauty Product Retail Sales in Istanbul (2021–2023)
This dataset contains yearly retail sales data for beauty products in Istanbul, Turkey.
It will help identify trends in consumer spending on cosmetics over time.
Data will be systematically organized to detect patterns, seasonal variations, and potential economic influences on beauty product sales.

https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset
(customer_shopping_data.csv.)


2. Turkey’s GDP, CPI and CCI Data (2021–2023)
These datasets provide Turkey’s Gross Domestic Product (GDP), Consumer Price Index (CPI), and Consumer Confidence Index (CCI) figures from 2021 to 2023.
It will be used to assess the country’s economic growth and identify potential periods of economic downturns or crisises.

https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=TR
https://fred.stlouisfed.org/series/TURCPALTT01IXNBM
https://data.tuik.gov.tr/Bulten/Index?p=Consumer-Confidence-Index-August-2023-49440&dil=2

(API_NY.GDP.MKTP.CD_DS2_en_csv_v2_19294.csv)
(TURCPALTT01IXNBM.csv)

Turkey’s economic data will be analyzed alongside beauty retail sales in İstanbul malls to determine whether economic shifts have some kind of influence on consumer spending on cosmetics like the Lipstick Index phenomenon suggests. 

Methods I’ve Used:

Data Cleaning & Transformation:
	- Filtered the “Beauty Product Retail Sales in Istanbul (2021–2023)” cosmetic sales data.
	- Converted date formats and calculated total sales.
	- Processed GDP and CPI data for consistency.
Exploratory Data Analysis (EDA):
	- Visualized trends in cosmetic sales, GDP, and CPI over time.
	- Generated a correlation matrix to assess relationships between variables.
Hypothesis Testing:
	- Conducted Pearson correlation tests to evaluate the relationship between GDP and cosmetic sales.
Machine Learning:
	- Implemented a Linear Regression model using scaled GDP and CPI as predictors for cosmetic sales.

Key Findings:

Correlation Analysis:
- Correlation between GDP and cosmetic sales: -0.353.
- P-value: 0.071 (not statistically significant at α = 0.05).

Machine Learning Model:
- Root Mean Square Error (RMSE): ~19,594
- R² Score: -0.14 (indicates poor model fit).

My Insights and Conclusion: 

The observed Pearson correlation coefficient between GDP and cosmetic sales was moderate (−0.353), with a p-value of 0.071 — above the conventional significance threshold of 0.05. Additionally, the R² value from our linear regression model was negative, indicating poor predictive power. These metrics suggest that while there may be trends worth exploring, the current data from Turkey alone does not provide conclusive support for the Lipstick Index.

This analysis offered me new valuable evidences and insights on the relationship between cosmetic sales and macroeconomic indicators in Turkey. While GDP and CPI alone did not strongly predict cosmetic spending in this dataset, the findings suggest that consumer behavior during economic shifts is more complex than we think and it is influenced by multiple factors. The project demonstrates the importance of affordable luxuries in economic analysis and highlights the potential of expanding the model with additional features — such as unemployment rates, consumer sentiment, or stock market trends — to further investigate the "Lipstick Index" in a more holistic framework.

This may conclude that in Turkey, cosmetics are not seen as recession-proof essentials or comfort goods to the same extent as the Lipstick Insex suggests, possibly due to different cultural spending habits.



