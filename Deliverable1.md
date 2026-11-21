#### MSCS 634 – Data Mining Project

### Deliverable 1: Data Collection, Cleaning, and Exploration

1. Dataset Summary and Key Insights

The Bank Marketing Dataset was obtained from the UCI Machine Learning Repository. It contains 45,211 records and 17 attributes, including customer demographics, financial information, and marketing campaign outcomes. Exploratory analysis revealed that most customers were aged 30–50, while only 11.7% subscribed to term deposits. Account balances showed potential outliers, and most numerical variables exhibited weak correlations.

2. Data Cleaning and Exploration

The dataset was loaded using Pandas and examined for missing values, duplicates, and inconsistencies. No standard missing values or exact duplicates were identified. Unknown categorical values were retained to prevent unnecessary data loss. Exploratory analysis included an age histogram, subscription count plot, account balance boxplot, and correlation heatmap to identify distributions, outliers, and feature relationships.

3. Challenges and Solutions

Challenge 1: Unknown Categorical Values
Several attributes contained unknown categories.
Solution: These values were retained because removing them could lead to unnecessary information loss.

Challenge 2: Potential Outliers
Some numerical variables contained extreme values.
Solution: Outliers were examined using descriptive statistics and boxplots. Plausible observations were retained for further analysis.

Challenge 3: Imbalanced Target Variable
The number of customers who subscribed was significantly lower than the number who did not.
Solution: Class imbalance was identified as an important consideration for future classification modeling.

4. Key Insights
- Most customers belong to middle-age groups.
- The subscription target variable is highly imbalanced.
- Account balances show substantial variation and potential outliers.
- Most numerical features have weak linear correlations.
- Data preprocessing and feature selection will be important for future modeling.

5. Conclusion

The analysis provided insights into customer characteristics, subscription patterns, and data quality. These findings will guide feature engineering and predictive modeling in subsequent deliverables.