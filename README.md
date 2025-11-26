# retail-sales-returns-prediction
**Project Objective**
To reduce operational costs and revenue loss by identifying the root causes of product returns and building a predictive model to flag high-risk orders. This project combines advanced machine learning with business intelligence dashboards to provide a holistic view of retail performance.

**Methodology**
Descriptive Analytics: Visualized sales performance across regions and categories to identify high-value segments.

Data Preprocessing: Addressed significant class imbalance in the dataset using the SMOTE (Synthetic Minority Over-sampling Technique) to improve model training stability.

Predictive Modeling: Built and evaluated Logistic Regression and Decision Tree classifiers to predict return probability.

Business Intelligence: Created an interactive Excel Dashboard to track KPIs like "Return Rate by Category" and "Total Sales by Region."

**Tools & Technologies**
Python: Pandas, Scikit-Learn, Imbalanced-Learn (SMOTE), Matplotlib, Seaborn.

Excel: Pivot Tables, Pivot Charts, Slicers for interactive dashboarding.

**Key Outcomes**
Insight: Identified that while "Clothing" is the second-highest sales driver, it is the primary driver of returns, indicating a need for quality control or better sizing guides.

Model Performance: Achieved a baseline model accuracy of 0.83 on the test set using Logistic Regression and Decision Trees.

Strategic Recommendation: Proposed a targeted review of clothing product descriptions to mitigate the high return rate identified in the analysis.

**Files in this Repository**
Midterm_project.ipynb: The Python notebook containing the EDA, data cleaning, and machine learning models.

Retail_Dashboard.xlsx: The Excel file containing the interactive sales and returns dashboard.
