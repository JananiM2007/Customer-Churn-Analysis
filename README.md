# Customer Churn Analysis

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Understanding why customers leave helps organizations improve customer satisfaction, increase retention, and reduce revenue loss.

This project analyzes customer behavior using the Telco Customer Churn dataset to identify the major factors contributing to customer churn. The project includes data cleaning, exploratory data analysis (EDA), visualization, business insights, and a Logistic Regression model to predict customer churn.

---

## Objectives

* Analyze customer demographics and subscription details.
* Identify patterns behind customer churn.
* Explore the relationship between customer behavior and churn.
* Build a machine learning model to predict customer churn.
* Provide business recommendations to improve customer retention.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, subscription details, billing information, and churn status.

### Features include:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure Months
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn Label (Target)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Exploratory Data Analysis

The analysis includes:

* Customer churn distribution
* Gender vs Churn
* Senior Citizen vs Churn
* Contract Type vs Churn
* Internet Service vs Churn
* Payment Method vs Churn
* Monthly Charges Distribution
* Total Charges Distribution
* Tenure Analysis
* Correlation Heatmap
* Feature Importance Analysis

---

##  Machine Learning

**Model Used**

* Logistic Regression

### Workflow

* Data Cleaning
* Handling Missing Values
* Feature Encoding
* Train-Test Split
* Model Training
* Model Evaluation

### Evaluation Metrics

* Accuracy
* Confusion Matrix
* Classification Report

---

##  Key Findings

* Customers with month-to-month contracts have the highest churn rate.
* Customers with shorter tenure are more likely to cancel their subscriptions.
* Higher monthly charges are associated with increased churn.
* Customers without Online Security and Tech Support services tend to churn more frequently.
* Long-term customers demonstrate significantly higher retention.

---

## Business Recommendations

* Encourage customers to switch to yearly or two-year contracts through promotional offers.
* Improve onboarding and engagement for new customers during their initial months.
* Provide personalized retention offers for customers with higher monthly charges.
* Promote Online Security and Tech Support services to increase customer loyalty.
* Develop targeted retention campaigns for high-risk customer segments.

---

##  Results

The Logistic Regression model achieved approximately **80% accuracy**, demonstrating good performance in identifying customers who are likely to churn.

---

## Future Improvements

* Compare additional machine learning models such as Random Forest, XGBoost, and LightGBM.
* Perform hyperparameter tuning to improve model performance.
* Develop an interactive dashboard using Power BI or Tableau.
* Deploy the churn prediction model as a web application using Streamlit.

---

## Conclusion

This project demonstrates how data analytics and machine learning can be used to understand customer behavior and predict churn. The insights generated from the analysis can help businesses implement effective customer retention strategies, improve customer satisfaction, and reduce subscription cancellations.

If you found this project useful, consider giving the repository a ⭐.
