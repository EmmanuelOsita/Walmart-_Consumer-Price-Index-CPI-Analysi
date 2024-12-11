# Walmart-_Consumer-Price-Index-CPI-Analysis



## Project Overview
This project aims to analyze the influence of temperature and fuel price on the Consumer Price Index (CPI) and provide actionable business insights for a multinational retail corporation. The study investigates whether rising temperatures and fuel price correlate with changes in CPI and explores how the corporation can adapt its strategies to respond to this relationship effectively.

This is a pproject I carried out during a One Project/Week Data Challenge. The dataset used in this project is sourced from Kaggle. 
You can find it here: [Walmart Sales Dataset](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)

## Introduction
The Consumer Price Index (CPI) is a critical economic indicator used to measure inflation and changes in the cost of living. CPI impacts business strategies, particularly in the retail industry, where price fluctuations directly affect consumer behavior and profit margins. This study explores the relationship between temperature, fuel price and CPI, focusing on how temperature and fuel price variations might influence pricing trends and business decisions at the retail corporation.

### Objectives
1. To test the correlation between temperature and CPI and determine if temperature increases affect the CPI.

2. To test the correlation between fuel price and CPI and determine if fuel increase affect the CPI

3. To generate actionable business insights for the retail corporation, enabling the company to adjust its pricing, inventory, and marketing strategies based on temperature and fuel price related trends.

## Data Collection
The data collected for this analysis includes:
• Air Temperature (°C): Monthly temperature variations in the region.

• Fuel Cost (USD per gallon): Monthly fuel price data.

•	CPI (Consumer Price Index): The index values reflecting the cost of goods and services.

•	Store: Store number

•	Date: Sales week start date

•	Weekly_Sales: Sales

•	Holiday_Flag: Mark on the presence or absence of a holiday

•	Temperature: Air temperature in the region

•	Unemployment: Unemployment rate
Example of the dataset:
 
![image](https://github.com/user-attachments/assets/c02f36eb-d07b-46d0-bd3c-6764db30bdd8)


## Methodology

The analysis was conducted using a linear regression model to test the relationship between temperature, fuel price (independent variables) and CPI (dependent variable). This model helps determine if temperature, fuel price significantly influences CPI and provides a quantitative measure of the relationship.

### Tools and Libraries Used:
•	Excel
•	Python
•	Pandas
•	Statsmodels
•	Matplotlib (for visualization)

### Steps Taken:
1.	Data Cleaning: The dataset was checked for missing values and outliers.

2.	Exploratory Data Analysis (EDA): Data distributions and correlations were examined visually and statistically.

3.	Regression Analysis: Linear regression was performed to determine the significance of temperature on CPI.

## Results
The regression analysis yielded the following output:

1. The analysis shows that temperature has a measurable impact on CPI (Consumer Price Index). For every 1-degree increase in temperature, CPI increases by 0.38 points. This relationship is statistically significant, meaning it’s unlikely to be due to chance.

2. The regression analysis shows a negative relationship between fuel price and CPI, which could have important strategic implications for the retail’s operations. For every $1 increase in fuel price, CPI decreases by 14.63 points, indicating an inverse relationship.

## Actionable Insights

1.	Dynamic Pricing Adjustments: The retail business should implement a dynamic pricing model that adjusts prices for temperature-sensitive products (e.g., air conditioners, outdoor gear, beverages) as temperature rises. This can help the business maintain profit margins while responding to consumer demand shifts.

2.	Seasonal Stock Planning: Use temperature trends to predict demand spikes for seasonal items like summer clothing, cooling appliances, and outdoor products. Increase inventory levels of these items ahead of temperature increases.

3.	Monitor Fuel Price Trends: Regularly track fuel price movements to anticipate shifts in CPI and adjust operations accordingly.

4.	Dynamic Pricing Models: Leverage this insight to create responsive pricing strategies that align with changes in fuel prices and CPI.

5.	Sustainability Investments: Explore renewable energy options or fuel-efficient technologies to mitigate the impact of volatile fuel prices.



