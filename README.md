# Project Overview
• Seek insight from the dataset with Exploratory Data Analysis
• Performed data processing, data engineering to prepare data before modeling
• Built a model to predict Insurance Cost based on the features

# Data Processing
• Check missing value - there are none
• Check duplicate value - there are 1 duplicate, will be remove
• Feature engineering - make a new column weight_status based on BMI score
• Feature transformation
Encoding sex, region, & weight_status
Ordinal encoding smoker
• Modeling
Separating target & features
Splitting train & test data
Modeling using Linear Regression, Random Forest, Decision Tree, Ridge, & Lasso algorithm

# Conclusion
Based on the predictive modeling, Linear Regression algorithm has the best score compared to the others, with MAE Score 4305.20, RMSE Score 6209.88, & R2 Score 0.69. Linear Regression algorithm is fit based on the train & test accuracy.
