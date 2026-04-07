# Telecom Customer Churn Analysis & Retention Strategy
A data-driven project focused on analyzing customer churn in the telecom industry and uncovering insights that can help reduce churn, improve customer experience, and support strategic decision-making.

## Project Overview

Customer churn is one of the most critical challenges in the telecom industry, directly impacting revenue and long-term growth.

Telecommunications ChurnQuest explores patterns and factors that contribute to customer churn using real customer data. The project analyzes customer behavior and builds a predictive model to identify  **customers at risk of churning**, uncover the **key drivers of churn**, and provide **actionable insights for retention strategies**. 
The project includes 
- Data cleaning 
- Exploratory data analysis
- Data analysis & feature engineering
- Predictive modeling (Logistic Regression)
- Business-driven insights
- The creation of a churn analysis dashboard.

The goal is to help telecom companies identify at-risk customers early and take proactive steps to increase customer retention

---

## Business Objective

* Identify customers likely to churn
* Understand the key factors driving churn
* Quantify potential revenue loss
* Enable proactive customer retention strategies

---

## Dataset Description

The dataset includes customer-level telecom data such as:

* Account information (account length, area code)
* Service usage (day, evening, night, international minutes)
* Billing information (charges across usage types)
* Customer behavior (customer service calls, voicemail usage)
* Target variable: **Churn (1 = Yes, 0 = No)**

---

## Analytical Approach

### 1. Data Preparation

* Cleaned the dataset and handled missing values
* Encoded categorical variables
* Created meaningful features:

  * Total charges
  * Total minutes
  * Service call groups
  * Customer risk segmentation

---

### 2. Exploratory Data Analysis (EDA)

Key patterns identified:

* Customers with **frequent service calls** show significantly higher churn
* **High-usage and high-paying customers** are more likely to churn
* Customers with **international plans** have higher churn rates
* Customers with **voicemail plans** tend to be more retained

---

### 3. Predictive Modeling

A Logistic Regression model was built to predict churn probability.

#### Model Performance:

* Accuracy: **83%**
* ROC-AUC: **0.79**
* Recall (Churn): Improved from **21% → 42% → 87%** (via threshold tuning)

---

### Threshold Optimization (Key Insight)

Instead of using the default 0.5 threshold:

* Lower thresholds significantly improved churn detection
* Optimal range: **0.2 – 0.3**

This increased the model’s ability to identify at-risk customers, enabling earlier intervention.

---

## Key Insights

*  **Customer service interactions are the strongest predictor of churn**
*  **High-value customers are at higher risk of leaving**
*  **International plan users churn more frequently**
*  **Customer dissatisfaction drives churn more than usage alone**

---

## Dashboard Overview (Power BI)

### Page 1: Churn Overview & Drivers

Provides a high-level summary of churn and its causes:

* Churn rate and retention rate
* Revenue at risk
* Churn distribution
* Key drivers:

  * Customer service calls
  * Usage patterns
  * Pricing and plans

---

### Page 2: Customer Risk & Retention Strategy

Focuses on actionable insights:

* Identification of high-risk customers
* High-value vs high-risk segmentation
* Customer-level risk analysis
* Prioritization for retention efforts

---

## Business Recommendations

*  Prioritize customers with **frequent service complaints**
*  Focus retention efforts on **high-value, high-risk customers**
*  Improve customer support experience to reduce dissatisfaction
*  Re-evaluate pricing and value of international plans
*  Use predictive scores to trigger **proactive retention campaigns**

---

## Tools & Technologies

* **Python** (Pandas, NumPy, Scikit-learn)
* **Power BI** (Data visualization & dashboarding)
* **Jupyter Notebook**
* **DAX** (for calculated metrics and KPIs)

---

## Project Impact

This project demonstrates how data analytics can:

* Reduce customer churn through early detection
* Protect revenue by targeting high-risk customers
* Enable data-driven decision-making
* Bridge the gap between data science and business strategy

---

## Author

**[Kaka]**
Data Analyst | Business Intelligence Analyst

---

## Final Note

This project goes beyond predictive modeling by translating data into **actionable business insights and strategic recommendations**, making it highly relevant for real-world telecom operations.


## Dashboard view 
![Dashboard](https://github.com/amieecode/telecommunications_churn_quest/blob/main/Images/Telecom%20Dashboard%201.png)
![Dashboard](https://github.com/amieecode/telecommunications_churn_quest/blob/main/Images/Telecom%20Dashboard%202.png)
