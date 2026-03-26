#  Customer Segmentation using RFM & K-Means

##  Description

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis combined with K-Means clustering to identify distinct customer groups and support data-driven business decisions.

---

##  Objectives

* Analyze customer purchasing behavior
* Segment customers into meaningful groups
* Provide actionable business insights

---

## Tools & Technologies

* Python
* Pandas
* Scikit-learn
* Matplotlib / Seaborn

---

##  Methodology

### 1. Data Cleaning

* Removed missing CustomerID values
* Converted date column to datetime format
* Created TotalPrice feature

---

### 2. RFM Analysis

* Recency → Days since last purchase
* Frequency → Number of purchases
* Monetary → Total spending

---

### 3. Data Scaling

* Standardized RFM values to ensure equal importance

---

### 4. Clustering (K-Means)

* Applied K-Means clustering
* Used Elbow Method to determine optimal clusters

---

### 5. Customer Segmentation

Customers were grouped into:

*  VIP Customers → High value, frequent buyers
*  Loyal Customers → Frequent purchases
*  At Risk Customers → No recent activity
* New Customers → Recently acquired

---

##  Key Insights

* VIP customers contribute significantly to revenue
* At-risk customers require retention strategies
* New customers need engagement campaigns
* Customer behavior varies significantly across segments

---

##  Business Recommendations

* Offer loyalty rewards for VIP customers
* Provide discounts to re-engage at-risk customers
* Design onboarding strategies for new customers

---

##  Conclusion

The segmentation provides valuable insights into customer behavior and enables targeted marketing strategies to improve customer retention and revenue growth.

---
