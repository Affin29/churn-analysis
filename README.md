*Project Overview
Customer churn refers to when customers stop doing business with a company. This project aims to analyze customer behavior, identify key factors influencing churn, and build insights to help improve customer retention strategies.
By using Exploratory Data Analysis (EDA) and Machine Learning, we identify the main reasons for churn and provide actionable insights to reduce it.

*Objectives
Understand the data and perform cleaning and preprocessing.Analyze churn distribution and key patterns.Visualize customer demographics and service usage behavior.Build predictive models to identify high-risk churn customers.Provide data-driven recommendations to improve retention

*Dataset
Dataset Source: Telco Customer Churn Dataset (Kaggle)
Rows: 7043
Columns: 21

*Key Features:
customerID – Unique ID for each customer
gender, SeniorCitizen, Partner, Dependents
tenure, Contract, PaymentMethod, MonthlyCharges, TotalCharges
Churn – Target variable (Yes/No)

*Data Cleaning
Handled missing values and inconsistent data types
Converted categorical variables using encoding
Scaled numerical features for analysis
Removed duplicates and outliers

*Exploratory Data Analysis (EDA)
Churn distribution visualization
Contract type vs churn rate
Tenure vs churn rate
Monthly charges and total charges correlation
Heatmap of numerical features

*Sample Visuals:

sns.countplot(x='Churn', data=df)
sns.boxplot(x='Churn', y='MonthlyCharges', data=df)
sns.heatmap(df.corr(numeric_only=True), annot=True, cmap='coolwarm')

*Insights
Customers with Month-to-Month contracts are more likely to churn
Higher MonthlyCharges correlates with higher churn probability
Long-term customers (high tenure) have a lower churn rate
Customers using Electronic Check as payment method churn more frequently

* Author

AFFIN LEO
📧 leoprincess1996@gmail.com

