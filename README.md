# Amazon Sales Analytics

A Python-based analysis of 100,000 synthetic Amazon-style e-commerce transactions using machine learning and data analytics techniques to explore customer behavior, sales patterns, and purchasing trends.

## Project Overview

This project applies four analytical approaches to Amazon-style sales data:

* **Classification — Logistic Regression:** Used supervised learning to predict categorical outcomes.
* **Regression — Random Forest:** Predicted total order amounts based on sales and customer-related features.
* **Clustering — K-Means:** Identified distinct customer groups based on purchasing behavior.
* **Association Rules — Apriori:** Examined products and categories purchased together to identify potential purchasing patterns.

## Key Findings

* **Random Forest Regression:** Achieved an $R^2$ of 0.9992, with an RMSE of approximately \$21 and MAE of approximately \$15.
* **K-Means Clustering:** Identified four customer segments: Premium Shoppers, Budget Shoppers, Bulk Shoppers, and Mid-Range Shoppers.
* **Association Rules:** Found limited meaningful product associations. One weak multi-category relationship was identified, with a lift of 1.01, indicating the relationship was close to random.
* **Logistic Regression:** Classification was less accurate than the regression and clustering approaches.

## Dataset

The dataset contains 100,000 synthetic Amazon-style e-commerce transactions with information about customers, products, pricing, payments, logistics, and order outcomes.

## Technologies

* **Python**
* **Pandas**
* **Scikit-learn**
* **MLxtend**
* **Jupyter Notebook**

## Files

* **DataMiningAmazon.ipynb** — Python analysis, data processing, modeling, and results
* **Amazon Sales Analytics.pdf** — Project presentation and findings
* **Data Mining Project Report.pdf** — Project write up

## Project Focus

The analysis combines supervised and unsupervised machine learning to examine customer spending, segment purchasing behavior, and identify patterns within e-commerce transactions.
