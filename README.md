# 📊 Customer Lifetime Value (CLTV) Analytics Project

##  Project Overview

Customer Lifetime Value (CLTV) is a core pillar of **Customer Value Management (CVM)**. This project demonstrates how data-driven CLTV analysis can be used to **identify high-value customer segments**, **predict future value**, and **support retention & monetization decisions**.

**What is customer lifetime value (CLV)?**

Customer lifetime value (CLV) is the total revenue a business can expect from a customer throughout the entire relationship. It’s a forward-looking metric that helps you understand not just how much a customer has spent, but also how much they’re likely to spend in the future.(salesforce)

Objective: Build an end-to-end analytics workflow to calculate, analyze, and predict CLTV, and translate insights into actionable CVM recommendations.

---

##  Business Problem

Customer bases are heterogeneous: not all customers contribute equally to revenue or profitability, and tailoring effective Value-based marketing strategies leads to retaining your loyal customers for as long as possible.


**Key business questions addressed:**

* Which customers generate the highest value?
* How can we segment customers based on behavioural and monetary patterns?
* Can we predict future customer value to support targeted retention strategies?
* How can CLTV insights be translated into actionable CVM decisions?

---

##  Dataset Description

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


## 🔄 Project Pipeline

1. Data Preparation  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. RFM Segmentation  
5. CLTV Prediction (XGBoost)  
6. Model Explainability (SHAP)  
7. Customer Clustering (PCA + K-Means)  
8. Business Recommendations  

---
      


## 🔗 Customer Clustering

Using **PCA + K-Means**, customers were grouped into:

**Cluster 0:** (Mid-Value Customers)

    This segment has a medium average CLTV.
    They purchase many unique products.
    This segment has the highest quantity.
    This segment includes the Can’t Lose, Need Attention, and Loyal Customers.

**Cluster 1:** (Low-Value / At-Risk)

    This segment has the lowest average CLTV.
    This segment has a high recency.
    This segment includes the hibernating, at-risk, and about-to-sleep Customers.

**Cluster 2:** (High-Value Customers)

    This segment has the highest average CLTV and the highest average cancellation rate.
    They repeated the purchase of the same products
    This segment has a low recency.
    This segment includes promising new customers, potential Loyalists, and champions.

**Recommendations**

    For the lowest average CLTV customers, this segment presents an opportunity for reengagement. It is recommended that we employ email marketing strategies that incorporate discounts, promotions, and personalised recommendations for new products.
    For the average CLTV customers, applying upselling and cross-selling tactics can increase our revenue.
    For the highest average CLTV customers, implement a loyalty program that includes loyalty points, discounts, product bundles, and regularly ask for feedback. We can not ignore that retaining loyal customers is cheaper than acquiring new ones.
    By analysing the overlap between segment features and our cluster predictions, the marketing team can effectively move customers from one cluster to another by tailoring their marketing strategy.



---

##  Key Insights

* A small percentage of customers contributes a disproportionately large share of total CLTV.
* RFM segmentation clearly distinguishes **high-potential** vs **churn-risk** customers.
* Predictive CLTV enables prioritization of retention efforts toward customers with the highest expected future value.

---

##  Business Impact & CVM Use Cases

This project supports multiple CVM initiatives:

* 🎯 Targeted retention campaigns for high-CLTV
* 💰 Personalized offers for high-value segments
* 📉 Reduced churn through early identification of declining engagement
* 📈 Revenue optimization via value-based customer prioritization

---

##  Tools & Technologies

* **Python** (Pandas, NumPy, Scikit-learn,Shap)
* **Data Visualization** (Matplotlib / Seaborn)
* **flask and Ngrok** for deploying ML model.

---

##  Limitations & Future Improvements

* Incorporate churn probability explicitly into CLTV calculation
* Extend modelling with survival analysis or probabilistic CLTV models
* Integrate campaign response data to measure uplift

---

##  Conclusion

This CLTV project demonstrates an **end-to-end CLTV prediction**, from raw data to business-ready insights.

It highlights how data science can directly support **customer-centric decision-making**, revenue growth, and long-term value optimisation.

---

## Final Application


![alt text](https://github.com/doaa450/Customer-lifetime-value/blob/main/App.PNG)


## Render this result
![alt text](https://github.com/doaa450/Customer-lifetime-value/blob/main/Prediction.PNG)


[App Link](https://f71dd6122a60.ngrok-free.app/)

⚠️ Note: The deployed app uses ngrok and may not always be active.



[Medium Article](https://medium.com/@DoaaA/end-to-end-machine-learning-project-customer-lifetime-value-prediction-and-segmentation-80fea7730cb1).

**References**

    https://medium.com/data-science/data-driven-growth-with-python-part-3-customer-lifetime-value-prediction-6017802f2e0f
    https://youtu.be/s-32u6XdY7c?si=mhOti9SFF-VSNZWJ
    https://youtu.be/8vOMNRqiaDw?si=550TCLShtPzYJbFq
    https://github.com/FarzadNekouee/Retail_Customer_Segmentation_Recommendation_System
    https://www.putler.com/rfm-analysis/#How_to_Calculate_the_RFM_Score_on_a_Scale_of_1-5
    https://github.com/joaolcorreia/RFM-analysis?tab=readme-ov-file
    https://www.kaggle.com/code/marcinrutecki/outlier-detection-methods
    https://medium.com/data-science/customer-segmentation-with-python-31dca5d5bdad
    https://www.sagacitysolutions.co.uk/about/news-and-blog/customer-value-management-strategies-tips-best-practices/

