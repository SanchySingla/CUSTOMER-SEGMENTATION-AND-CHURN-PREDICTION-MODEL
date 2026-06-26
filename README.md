# CUSTOMER-SEGMENTATION-AND-CHURN-PREDICTION-MODEL
Through this project, customer analysis of ibm telecom dataset has been performed and then according to graph and chart views, model is designed to calculate churn score and recall predictions

(GONNA UPDATE THE STRUCTURE AND EFFICIENCY SOON)

# Telco Customer Churn Analysis

This repository contains an exploratory data analysis (EDA) notebook investigating telecommunications customer churn.Exploring customer demographics, account information, and service configurations to identify patterns linked to customer attrition.

---

# Dataset Overview

The analysis uses the Telco_customer_churn.xlsx IBM dataset, which consists of 7,043 rows and 33 columns**. 

# Class Distribution
The target variable 'Churn Label' shows a noticeable class imbalance:

Churn Label--Customer Count--Approximate Percentage
No--(Retained)--5,174--73.5%|||
Yes--(Churned)--1,869--26.5%

# Key Features Analyzed
* Demographics: Gender, Senior Citizen, Partner, Dependents, and Geographic locations (City, Zip Code).
* Services: Phone Service, Multiple Lines, Internet Service, Online Security, Device Protection, and Tech Support.
* Account Info: Tenure Months, Contract Type, Paperless Billing, Payment Method, Monthly Charges, and Total Charges.

---

# Tech Stack & Dependencies

The analysis is performed in Python 3 using a standard data science environment. The primary libraries utilized are:

* Data Manipulation: `pandas`, `numpy`
* Data Visualization:`matplotlib`, `seaborn`
* Machine Learning Preparation: `scikit-learn`
* Excel Engine:`openpyxl` (required for parsing `.xlsx` files in Pandas)

---

# Key Insights from Notebook

* Data Structure: The dataset includes 24 object/text columns, 6 integer columns, and 3 float columns.
* Missing Values: High-level validation shows clean data across baseline attributes, while specific situational tracking columns like `Churn Reason` contain targeted entries (1,869 non-null values matching the churn count).
* Tenure Distribution: Initial visualizations highlight customer volume trends plotted across various tenure frequencies to pinpoint critical timeframes where churn is most volatile.

---

# How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
   cd YOUR-REPO-NAME
