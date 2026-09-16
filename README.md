# Olist Customer Satisfaction Analysis

## 📌 Project Overview

This project analyses approximately 100K orders from the Olist Brazilian E-Commerce Marketplace to identify key factors influencing customer satisfaction.

The project covers data cleaning, exploratory data analysis, feature engineering, machine learning model development, model comparison, explainability, and business-oriented visualization.

## 🎯 Business Objective

The main objectives of this project are to:

- Understand factors associated with customer satisfaction.
- Analyse delivery performance and its relationship with customer experience.
- Identify patterns related to sellers, products, payments and orders.
- Build machine learning models to analyse customer satisfaction.
- Compare different classification models.
- Explain model predictions using SHAP and LIME.
- Communicate findings through a Power BI dashboard.

## 📊 Dataset

The analysis uses the Olist Brazilian E-Commerce dataset containing approximately 100K e-commerce orders and multiple related datasets.

The dataset includes information related to:

- Orders
- Customers
- Sellers
- Products
- Payments
- Reviews
- Order items
- Geolocation

**Dataset:** [Olist Order Reviews Dataset](https://www.kaggle.com/datasets/gayatribehera5474/olist-order-reviews-dataset)

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- XGBoost
- SHAP
- LIME
- Power BI
- Jupyter Notebook

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Cleaning & Preparation
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Baseline Model
      ↓
Model Comparison
      ↓
Model Optimization
      ↓
Model Explainability
      ↓
Power BI Dashboard
      ↓
Business Insights
```

🔍 Analysis Performed

1. Data Cleaning

Integrated multiple Olist datasets.
Cleaned and prepared data for analysis.
Handled missing values and data inconsistencies.
Prepared datasets for exploratory analysis and machine learning.

2. Exploratory Data Analysis
Analysed customer reviews and order-related factors to understand patterns in customer satisfaction.
Key areas included:

Delivery performance
Order characteristics
Seller-related factors
Product-related factors
Customer review patterns

3. Feature Engineering

Created analytical features from the available order, delivery and customer-related information to support machine learning and business analysis.

4. Machine Learning
Built and compared multiple classification models:

Logistic Regression
Random Forest
LightGBM
XGBoost

The models were evaluated and compared to identify the most suitable approach for the analysis.

5. Model Optimization
The selected XGBoost model was further improved using:

Hyperparameter tuning
Feature selection

6. Model Explainability
Used:

1. SHAP to understand feature contributions to model predictions.
2. LIME to explain individual predictions.

📈 Power BI Dashboard

A Power BI dashboard was developed to communicate important findings from the analysis in an interactive and business-friendly format.
The dashboard focuses on customer satisfaction and factors related to the e-commerce order experience.

💡 Key Business Insights

The analysis was used to identify relationships between customer satisfaction and factors such as:

Delivery performance
Seller quality
Order characteristics
Product-related factors

These insights can help e-commerce businesses identify areas for improving customer experience and operational performance.

▶️ How to Run
Clone or download this repository.
Install the required Python libraries.
Open the notebooks using Jupyter Notebook or JupyterLab.
Run the notebooks in the intended sequence:
data-cleaning_Gayatri Behera
eda-and-baseline-model_Gayatri Behera
model-comparison-and-optimisation_Gayatri Behera

Ensure the required Olist dataset files are available in the expected location.
Run the notebook cells sequentially.

📁 Project Structure
Olist-Customer-Satisfaction-Analysis/
│
├── data-cleaning_Gayatri Behera.ipynb
├── eda-and-baseline-model_Gayatri Behera.ipynb
├── model-comparison-and-optimisation_Gayatri Behera.ipynb
└── README.md

📌 Project Outcome
This project demonstrates an end-to-end data analytics and machine learning workflow, from data preparation and exploratory analysis through model development, explainability and business visualization.
It combines Python-based analytics with machine learning and Power BI to translate e-commerce data into actionable business insights.

👩‍💻 Author
Gayatri Behera
Data Analytics | Python | SQL | Power BI | Machine Learning | Engineering Analytics
