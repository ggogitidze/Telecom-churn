# Telecom Customer Churn Analysis

## Project Overview

As part of our effort to understand and reduce customer churn, we have conducted an in-depth analysis of customer behavior and service usage patterns using the [`telecom_churn.csv`](https://www.kaggle.com/datasets/barun2104/telecom-churn/data) dataset. This analysis aims to identify key factors correlated with customer churn, understand how usage patterns and service interactions influence churn, and identify high-risk customer segments for targeted marketing and retention strategies.

## Business Questions:
1. What are the key factors correlated with customer churn?
2. How do customer usage patterns and service interactions correlate with the likelihood of churn?
3. Which customer segments have the highest churn rates, and what are their characteristics?

## Data Collection and Preparation

### Data Sources

The primary data source for this analysis is the [`telecom_churn.csv`](https://www.kaggle.com/datasets/barun2104/telecom-churn/data) dataset. 

### Data Cleaning

Ensured the data is clean, consistent, and complete for analysis. Focused on key features such as customer demographics, account information, and service usage metrics.

## Data Analysis

### A. [Descriptive Analysis](DescriptiveAnalysis.ipynb)

- **Summary Statistics:** Computed summary statistics (mean, median, standard deviation) for key variables to get an overall understanding of the data.
- **Churn Rate Calculation:** Calculated the overall churn rate and churn rate by different categories (e.g., `Contract Renewal`, `Data Plan`).

### B. [Trend Analysis](TrendAnalysis.ipynb)

- **Churn Over Time:** Analyzed churn trends over time using the `AccountWeeks` feature to identify any patterns or effects.
- **Service Usage Trends:** Analyzed trends in service usage (e.g., data usage, customer service calls) over time for churned vs. retained customers.

### C. [Distribution Analysis](DistributionAnalysis.ipynb)

- **Customer Demographics:** Analyzed the distribution of customer demographics (e.g., `Contract Renewal`, `Data Plan`) and their correlation with churn.
- **Service Usage Patterns:** Analyzed the distribution of service usage metrics (e.g., data usage, customer service calls) for churned vs. retained customers.

### D. [Customer Segmentation](Segmentation.ipynb)

- **Segmentation Criteria:** Segmented customers based on key features such as service plan, data usage, and customer service interactions.
- **Churn Rate by Segment:** Calculated and analyzed churn rates for each customer segment.

## Insights and Recommendations

### A. Key Factors Correlated with Churn

- **Contract Renewal:** Customers who do not renew their contracts are more likely to churn. Strategies to encourage contract renewal could help reduce churn.
- **Customer Service Calls:** High numbers of customer service calls are correlated with higher churn rates, suggesting that improving customer service quality could help retain customers.
- **Monthly Charges:** Higher monthly charges are associated with higher churn rates. Reviewing pricing strategies or offering more value could help retain high-paying customers.
- **Day Minutes Usage:** High usage of day minutes is correlated with higher churn rates. Understanding the needs of these high-usage customers and addressing their concerns could help in reducing churn.

- ![Data Usage and Monthly Charges](images/TableauVisualizations/DataUsageMonthlyCharge.png)

### B. Correlation of Usage Patterns and Service Interactions
 
- **Data Usage:** Inconsistent or high data usage correlates with higher churn rates, suggesting that customers with such patterns may be at risk.
- **Customer Service Calls:** High frequency of customer service interactions is correlated with higher churn rates, indicating potential unresolved issues or dissatisfaction.
- ![Customer Service By Churn Status](images/DescriptiveAnalysis/CustomerServiceCalls.png)
- **Monthly Charges:** Higher monthly charges are correlated with higher churn rates, highlighting the need to address value perception and pricing strategies.
- ![Monthly Charge by Churn Status](images/DescriptiveAnalysis/MonthlyChargesByChurn.png)

### C. Customer Segmentation and Targeted Strategies

- **High-Risk Segments:** Identified customer segments with the highest churn rates and underlined characteristics of the groups.
- ![Customer Segments](images/Segmentation/Segments.png)

- ![Segmentation Results](images/TableauVisualizations/Segmentation.png)



