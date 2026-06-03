# Customer Segmentation using RFM Analysis

## Overview

This project analyzes customer purchasing behavior using the RFM (Recency, Frequency, Monetary) model and groups customers into meaningful business segments.

The goal is to identify high-value customers, loyal customers, and customers at risk of churn, helping businesses make data-driven marketing and retention decisions.

---

## Problem Statement

Businesses often treat all customers equally without understanding differences in purchasing behavior. This can lead to ineffective marketing strategies and reduced customer retention.

This project aims to segment customers based on their transaction history using RFM analysis.

---

## Question

Can customer transaction behavior be used to identify meaningful customer segments for targeted marketing and customer retention?

---

## Hypothesis

Customers with similar Recency, Frequency, and Monetary characteristics exhibit similar purchasing behavior and can be grouped into actionable business segments.

---

## Experiment

### Data Preprocessing
- Removed missing Customer IDs
- Removed cancelled transactions
- Removed invalid quantity values
- Converted date fields into datetime format

### Feature Engineering
Created:

```python
TotalPrice = Quantity × UnitPrice
```

### RFM Calculation

- Recency → How recently a customer purchased
- Frequency → How often a customer purchased
- Monetary → Total spending amount

### Customer Segmentation

Customers were grouped into segments such as:

- Champions
- Loyal Customers
- At Risk Customers
- Others

### Machine Learning Enhancement

K-Means clustering was applied on RFM metrics to explore automated customer grouping.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Results

The analysis successfully identified different customer segments and provided actionable business insights for:

- Customer retention
- Marketing campaigns
- Revenue optimization
- Customer relationship management

---

## Business Applications

- Personalized marketing
- Customer retention strategies
- Customer lifetime value analysis
- Revenue optimization

---

## Author

Abishikth Ebenezer

Bachelor of Engineering (Artificial Intelligence and Machine Learning)

AMC Engineering College
