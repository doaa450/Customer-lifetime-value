# 📊 Customer Lifetime Value (CLTV) Analytics Project

## 1. Project Overview

Customer Lifetime Value (CLTV) is a core pillar of **Customer Value Management (CVM)**. This project demonstrates how data-driven CLTV analysis can be used to **identify high-value customer segments**, **predict future value**, and **support retention & monetization decisions**.

---

## 2. Business Problem

Customer bases are heterogeneous: not all customers contribute equally to revenue or profitability, and tailoring effective Value-based marketing strategies leads to retaining your loyal customers for as long as possible.


**Key business questions addressed:**

* Which customers generate the highest value?
* How can we segment customers based on behavioural and monetary patterns?
* Can we predict future customer value to support targeted retention strategies?
* How can CLTV insights be translated into actionable CVM decisions?

---

## 3. Dataset Description

This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers

The dataset represents customer-level transactional including:

* InvoiceNo
* StockCode
* Description
* Quantity
* InvoiceDate
* UnitPrice
* CustomerID
* Country
---

## 4. Methodology

### 4.1 Data Preparation

* Data cleaning and validation
* Handling missing values and duplicates
* Feature engineering

### 4.2 Exploratory Data Analysis (EDA)

* 
* 
* 

### 4.3 CLTV Calculation

CLTV was calculated using a structured approach based on:

> **CLTV = Total Gross Revenue — Total Cost**

This provides a baseline measure of historical customer value.

### 4.4 Customer Segmentation (RFM)

Customers were segmented using **RFM analysis**:

* **Recency**: How recently a customer was active
* **Frequency**: How often the customer engages
* **Monetary**: How much revenue the customer generates

Segments were analyzed to identify:

 	              **count** **perc**
**Segment** 		
Hibernating 	      441 	28.053435
Loyal Customers 	  326 	20.737913
Champions 	          236 	15.012723
Potential Loyalists   177 	11.259542
At Risk 	          162 	10.305344
About to Sleep 	       97 	6.170483
Need Attention 	       84 	5.343511
Promising 	           21 	1.335878
Can't Loose 	       21 	1.335878
New Customers 	       7 	0.445293

### 4.5 Predictive Modeling

A supervised learning model was developed to predict **future CLTV**, using:

* Behavioral features
* Historical revenue patterns

> The model enables proactive CVM actions rather than reactive analysis.

Develop **SHAP** values to know how each attribute used in the model affects the model outcome

Then develop **PCA** and **K-Means** to cluster each customer based on their CLTV value

---

## 5. Key Insights

* A small percentage of customers contributes a disproportionately large share of total CLTV.
* RFM segmentation clearly distinguishes **high-potential** vs **churn-risk** customers.
* Predictive CLTV enables prioritization of retention efforts toward customers with the highest expected future value.

---

## 6. Business Impact & CVM Use Cases

This project supports multiple CVM initiatives:

* 🎯 Targeted retention campaigns for high-CLTV
* 💰 Personalized offers for high-value segments
* 📉 Reduced churn through early identification of declining engagement
* 📈 Revenue optimization via value-based customer prioritization

---

## 7. Tools & Technologies

* **Python** (Pandas, NumPy, Scikit-learn,Shap)
* **Data Visualization** (Matplotlib / Seaborn)
* **flask and Ngrok** for deploying ML model.

---

## 8. Limitations & Future Improvements

* Incorporate churn probability explicitly into CLTV calculation
* Extend modelling with survival analysis or probabilistic CLTV models
* Integrate campaign response data to measure uplift

---

## 9. Conclusion

This CLTV project demonstrates an **end-to-end CLTV prediction**, from raw data to business-ready insights.

It highlights how data science can directly support **customer-centric decision-making**, revenue growth, and long-term value optimisation.

---


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



