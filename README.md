# 🛍️ Ecommerce Return Analysis

This end-to-end data science project focuses on analyzing return behavior in an e-commerce business and building predictive intelligence to reduce return-related losses. It combines data cleaning, feature engineering, exploratory analysis, machine learning, and visualization to create business-ready insights.

---

## 🚀 Overview

Returns can significantly impact customer satisfaction, logistics, and revenue. This project analyzes real-world Brazilian e-commerce data to:

- Identify key return drivers across customer, product, seller, and logistic dimensions.
- Engineer meaningful features such as delivery status, review sentiment, and price sensitivity.
- Build machine learning models to **predict whether an order will be returned**.
- Segment customers using clustering to **identify loyal buyers, risky returners, and one-time shoppers**.
- Create a **Power BI dashboard** to communicate actionable insights visually.

---

## 🔍 Key Highlights

- **Extensive EDA** covering return rate by product category, state, delivery status, seller, price buckets, and review scores.
- **Feature Engineering**: Created columns like `delivery_delay`, `review_score_sentiment`, `payment_per_installment`, `customer_type`, and more.
- **ML Models Used**: Logistic Regression, Random Forest, XGBoost, LightGBM with performance comparisons using metrics like ROC-AUC, precision, recall, and F1-score.
- **Customer Segmentation** via KMeans clustering with custom labels:
  - 💎 Loyal Premium Customers
  - ⚠️ Risky Returners
  - 🛍️ One-Time Buyers
  - 🎯 Discount Shoppers
- **Power BI Dashboard** built using a cleaned, merged dataset with geolocation, cancellations, and full return logic.

---

## 🤖 Machine Learning Insights

- Models trained on features like delivery performance, payment behavior, and review sentiment.
- Achieved high accuracy with **XGBoost** and **LightGBM**, identifying patterns in return likelihood.
- ROC-AUC Scores exceeded **0.94**, indicating strong model discrimination.

---

## 📈 Visualization (Power BI)

Interactive Power BI dashboard includes:

- Top categories by return rate
- Delivery performance vs review scores
- Lost revenue due to returns
- Cancellations heatmap by time
- Return trends over time and price segments

---

## 📦 What's Included

- Cleaned dataset ready for Power BI
- All trained ML models saved as `.pkl`
- Visualizations for EDA and clustering
- Notebook with complete workflow from preprocessing to prediction

---

## 📄 License

This project is licensed under the MIT License.

---
> 📍 Author: Rachit Patwa 🔗 LinkedIn: www.linkedin.com/in/rachitpatwa1076

