**Title: Feature Engineering for Churn Prediction**

In this Jupyter notebook, the primary objective is to uncover signals within the data, predict churn probability, and evaluate the results. A provided CSV dataset serves as the foundation for this task.
This feature engineering process lays the groundwork for building predictive models focused on churn prediction. The transformations, insights, and considerations provided in the notebook contribute to a robust analysis of the dataset.

1. **Initial Setup:**
   - Download the notebook and accompanying CSV dataset.
   - Execute the notebook cells to initialize and load the dataset.

2. **Feature Engineering:**
   - Introduce features to measure average price changes across periods and the maximum price difference across periods and months.
   - These features aim to capture the variance in prices throughout the year, providing valuable insights into potential fluctuations impacting consumer behavior.

3. **Data Transformation:**
   - Convert date information into months and remove the raw date column.
   - Convert boolean columns into binary values.
   - Convert categorical columns into dummy variables suitable for modeling.

4. **Handling Skewed Columns:**
   - Address skewed distribution observed during exploratory data analysis.
   - Transform columns using the logarithm function to achieve a distribution closer to normal.

5. **Correlation Analysis:**
   - Plot correlations among all columns to identify potential candidates for removal.
   - High correlations between columns may indicate redundancy; considerations for removal are discussed.


