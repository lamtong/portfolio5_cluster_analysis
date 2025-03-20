# Customer Segmentation Analysis for a UK Bank

Refer to [portfolio_task5.ipynb](./portfolio_task5.ipynb) or [portfolio_task5.html](./portfolio_task5.html) for a detailed report of the analysis.


## Introduction
This study aims to segment customers of a UK bank based on demographic and financial data. The goal is to identify distinct customer groups that can inform the development of targeted financial products and marketing strategies. The dataset includes information on customer demographics, financial behavior, and credit risk.

## Methodology

### Data Preparation
- The dataset was examined for missing values and outliers, and necessary transformations were applied.
- Categorical variables, such as marital status and homeownership, were encoded for analysis.
- Data normalization was performed to ensure comparability across numerical features like account balances and employment duration.

### Feature Selection
- Key variables influencing financial behavior were selected, including savings and current account balances, employment duration, and credit risk.
- A correlation analysis was conducted to ensure non-redundant features were included.

### Clustering Algorithm
Hierarchical Clustering was selected as the most effective clustering technique for targeting financial products and promotions. This method provided clearer segmentation of customer groups based on their financial profiles and demographic characteristics.

### Model Evaluation
- The **Silhouette Score** was used to assess the quality of clustering.
- **Cluster interpretation** was conducted by analyzing the distribution of demographic and financial variables within each cluster.

## Key Findings
The analysis identified **two distinct customer clusters** with varying financial profiles and product needs:

### Cluster 0: Older, High-Savings Customers
- This cluster consists of older customers with high savings, long-term employment, and a higher percentage in management positions.
- Their financial stability and long-term outlook make them more inclined towards long-term investment products like bonds, stocks, and mutual funds.
- Additionally, they are likely to be interested in life insurance or property insurance products, given their focus on securing their financial future and wealth preservation.

### Cluster 1: Younger, Low-Savings Customers
- This majority customer group represents younger customers with lower savings, higher balances in their current accounts for day-to-day spending, and limited work experience.
- Due to their current financial situation, this cluster is more suited for credit cards, unsecured small loans, and short-term financial products.
- However, they may also have an interest in exploring more flexible savings or investment options that help them build a foundation for future financial growth.

## Conclusion & Recommendations
- **Cluster 0 customers** should be targeted with **long-term financial products**, including investment plans, retirement savings options, and insurance products.
- **Cluster 1 customers** would benefit from **short-term financial solutions**, such as credit products, flexible savings plans, and financial advisory services to support their financial growth.
- Future analysis could incorporate additional behavioral variables to refine segmentation and enhance targeting strategies.


 
