# SALES-PERFORMANCE-DASHBOARD-WITH-ANALYSIS-AND-PREDICTION

## Project Overview

This project focuses on analyzing retail sales performance and using machine learning techniques for prediction. The analysis explores **sales, profit, quantity, discounts, customer segments, product categories, regions, and shipping modes** to identify important business trends and performance patterns.

Machine learning models are also applied to predict profit and classify profitable and non-profitable transactions.

## Objectives

* Analyze overall sales and profit performance.
* Identify top-performing product categories and regions.
* Analyze customer segment and shipping mode performance.
* Study the relationship between discounts, sales, and profit.
* Predict profit using machine learning models.
* Classify transactions based on positive and non-positive profit.
* Evaluate model performance using appropriate metrics.
* Generate insights to support data-driven business decisions.

## Dataset

The project uses the **Sample Superstore** dataset containing retail transaction information.

### Important Features

* Order Date
* Ship Date
* Ship Mode
* Customer Name
* Segment
* Region
* Category
* Sub-Category
* Sales
* Quantity
* Discount
* Profit

## Product Categories

The dataset contains three major product categories:

### Furniture

* Chairs
* Tables
* Bookcases
* Furnishings

### Office Supplies

* Binders
* Paper
* Storage
* Labels
* Envelopes
* Art
* Fasteners
* Appliances

### Technology

* Phones
* Accessories
* Copiers
* Machines

## Data Preprocessing

The dataset was cleaned and prepared for analysis and machine learning. Unnecessary columns were removed, categorical variables were encoded, numerical features were scaled using **Min-Max Scaling**, and the processed numerical and categorical data were combined into a final dataset.

## Exploratory Data Analysis

The analysis examines:

* Sales and profit by region.
* Sales and profit by customer segment.
* Performance of product categories and sub-categories.
* Quantity and discount patterns.
* Sales trends over time.
* Relationship between discounts and profitability.
* Top-performing products and business segments.

## Machine Learning Models

### Linear Regression

Linear Regression is used to analyze the relationship between selected sales-related features and profit and to predict continuous profit values.

### K-Nearest Neighbors (KNN)

KNN is used for classification by predicting the class of a transaction based on its nearest observations. Different values of **K** are evaluated to identify a suitable number of neighbors.

### Support Vector Regression (SVR)

SVR is applied to predict continuous profit values by identifying a suitable relationship between the input features and the target variable.

### Logistic Regression

Logistic Regression is used to classify transactions into:

* **1 — Positive Profit**
* **0 — Non-positive Profit**

## Model Evaluation

The models are evaluated using appropriate performance metrics, including:

* R² Score
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

## Key Findings

The analysis provides insights into sales and profitability across different regions, customer segments, product categories, and discounts. The machine learning models demonstrate how sales-related features can be used for **profit prediction and profit classification**.

Overall, the project combines **business analysis and machine learning** to understand sales performance, identify important trends, evaluate profitability, and support data-driven decision-making.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering & Scaling
      ↓
Data Splitting
      ↓
Machine Learning Models
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Business Insights
```

## Conclusion

The Sales Performance Dashboard with Analysis and Prediction demonstrates how **data analysis, visualization, and machine learning** can be combined to evaluate retail business performance. The project provides useful insights into sales, profit, discounts, products, regions, and customer segments while applying multiple machine learning models for prediction and classification.
