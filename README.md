# 📊 Customer Lifetime Value (CLTV) Analytics Project

## 1. Project Overview

Customer Lifetime Value (CLTV) is a core pillar of **Customer Value Management (CVM)**. This project demonstrates how data-driven CLTV analysis can be used to **identify high-value customer segments**, **predict future value**, and **support retention & monetization decisions**.

The project is designed from a **telecom / subscription-business perspective**, aligned with real-world CVM use cases in companies such as Orange or Vodafone.

---

## 2. Business Problem

Customer bases are heterogeneous: not all customers contribute equally to revenue or profitability.

**Key business questions addressed:**

* Which customers generate the highest long-term value?
* How can we segment customers based on behavioral and monetary patterns?
* Can we predict future customer value to support targeted retention strategies?
* How can CLTV insights be translated into actionable CVM decisions?

---

## 3. Dataset Description

The dataset represents customer-level transactional and behavioral data, including:

* Customer ID
* Transaction dates
* Revenue / monetary value
* Frequency of interactions or purchases
* Recency metrics

> The dataset structure enables both **historical CLTV calculation** and **predictive modeling**.

---

## 4. Methodology

### 4.1 Data Preparation

* Data cleaning and validation
* Handling missing values and duplicates
* Feature engineering for recency, frequency, and monetary value

### 4.2 Exploratory Data Analysis (EDA)

* Revenue distribution analysis
* Customer activity patterns
* Identification of skewness and high-value outliers

### 4.3 CLTV Calculation

CLTV was calculated using a structured approach based on:

> **CLTV = Average Monetary Value × Purchase Frequency × Expected Customer Lifetime**

This provides a baseline measure of historical customer value.

### 4.4 Customer Segmentation (RFM)

Customers were segmented using **RFM analysis**:

* **Recency**: How recently a customer was active
* **Frequency**: How often the customer engages
* **Monetary**: How much revenue the customer generates

Segments were analyzed to identify:

* High-value loyal customers
* At-risk but valuable customers
* Low-value / low-engagement customers

### 4.5 Predictive Modeling

A supervised learning model was developed to predict **future CLTV**, using:

* Behavioral features
* Historical revenue patterns

The model enables proactive CVM actions rather than reactive analysis.

---

## 5. Key Insights

* A small percentage of customers contributes a disproportionately large share of total CLTV.
* RFM segmentation clearly distinguishes **high-potential** vs **churn-risk** customers.
* Predictive CLTV enables prioritization of retention efforts toward customers with the highest expected future value.

---

## 6. Business Impact & CVM Use Cases

This project supports multiple CVM initiatives:

* 🎯 Targeted retention campaigns for high-CLTV, high-churn-risk customers
* 💰 Personalized offers for high-value segments
* 📉 Reduced churn through early identification of declining engagement
* 📈 Revenue optimization via value-based customer prioritization

---

## 7. Tools & Technologies

* **Python** (Pandas, NumPy, Scikit-learn)
* **Data Visualization** (Matplotlib / Seaborn or Power BI)
* **Jupyter Notebook** for analysis and modeling

---

## 8. Limitations & Future Improvements

* Incorporate churn probability explicitly into CLTV calculation
* Extend modelling with survival analysis or probabilistic CLTV models
* Integrate campaign response data to measure uplift

---

## 9. Conclusion

This CLTV project demonstrates an **end-to-end CVM analytics workflow**, from raw data to business-ready insights.

It highlights how data science can directly support **customer-centric decision-making**, revenue growth, and long-term value optimisation.

---

## 10. Author

**Doaa Ahmed**
Applied Data Scientist – CVM & Marketing Analytics Focus







# Customer-lifetime-value
Step-by-step machine learning project covering data preprocessing, feature engineering, isolation forest, XGBoost, K-means, SHAP, and deployment using Flask and Ngrok in Colab.

    All Customers Are Not Equal. Mark Jeffery

As almost 20 percent of customers generate 80 percent of the revenue.

## What is Customer Lifetime Value?

    In marketing, customer lifetime value is a prognostication of the net profit contributed to the whole future relationship with a customer. wiki

Tailor effective Value-based marketing strategies can help you retain your loyal customers for as long as possible.

There are many ways to calculate CLTV, but the most recommended formula by data scientists like Barış Karaman is:

### Lifetime Value = Total Gross Revenue — Total Cost

The main objective of this project is to develop an Xgboost model to predict customer lifetime value (CLTV) and use this prediction to determine which cluster the customer belongs to.

For this project, we will analyse historical transactional data and perform feature engineering to predict the customer lifetime value (CLTV) over the next 90 days.

### Our Project Steps: 
    Knowing the Dataset.
    Data Preprocessing and Analysis.
    Building Xgboost and performing shap values.
    Building PCA and K-Means.
    Deployment using Flask and Ngrok.
    References

## Final Application


![alt text](https://github.com/doaa450/Customer-lifetime-value/blob/main/88.PNG)


## render this result
![alt text](https://github.com/doaa450/Customer-lifetime-value/blob/main/8.PNG)


[App Link](https://f71dd6122a60.ngrok-free.app/)



[Medium Article](https://medium.com/@DoaaA/end-to-end-machine-learning-project-customer-lifetime-value-prediction-and-segmentation-80fea7730cb1).



