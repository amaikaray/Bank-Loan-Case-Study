# 🏦 Bank Loan Case Study Analysis

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a bank loan application dataset to identify patterns associated with customer repayment difficulties and loan default risk. The analysis helps financial institutions understand how customer demographics, financial background, and loan-related attributes influence the likelihood of default.

The project uses Microsoft Excel for data cleaning, statistical analysis, visualization, and correlation analysis to support better lending decisions and improve credit risk assessment.

---

## 🎯 Problem Statement

Financial institutions face two major risks during loan approval:

* Approving loans for customers who may default
* Rejecting customers who are capable of repayment

The objective of this project is to analyze customer and loan data to identify patterns that indicate repayment difficulties so that banks can make smarter lending decisions.

---

## 🧹 Data Cleaning & Preprocessing

The dataset underwent several preprocessing steps to improve data quality and analysis accuracy:

* Handling missing values
* Removing irrelevant columns
* Dropping columns with high null percentages
* Replacing missing values using median/mode methods
* Identifying numerical and categorical variables
* Converting date-related columns into usable formats
* Standardizing and preparing the dataset for analysis

The project utilized:

* application_data.csv
* previous_application.csv
* columns_description.csv

---

## 📊 Data Analysis Tasks

### A. Missing Value Analysis

* Identified missing values using Excel functions
* Calculated null percentages for variables
* Applied appropriate imputation techniques

### B. Outlier Detection

Used Quartile, IQR, Lower Bound, and Upper Bound methods to detect outliers in numerical variables such as:

* Income
* Credit Amount
* Loan Annuity
* Goods Price
* Repayment Period

### C. Data Imbalance Analysis

Analyzed the TARGET variable distribution to identify imbalance between:

* Customers with payment difficulties
* Customers making payments on time

### D. Univariate, Segmented Univariate & Bivariate Analysis

Performed:

* Univariate analysis to study individual variable distributions
* Segmented analysis to compare repayment behaviors
* Bivariate analysis to explore relationships between variables and default risk

Key variables analyzed:

* Income
* Loan Amount
* Education
* Age
* Family Status
* Credit Amount
* Previous Loan Status

### E. Correlation Analysis

Used Excel CORREL function to identify the strongest relationships between variables for different customer scenarios.

Strong correlations were observed between:

* AMT_CREDIT
* AMT_GOODS_PRICE
* AMT_ANNUITY

The analysis showed that loan default depends on a combination of financial and customer-related factors rather than a single variable.

---

## 📈 Tools & Techniques Used

* Microsoft Excel (2019)
* Pivot Tables & Pivot Charts
* Data Cleaning & Transformation
* Descriptive Statistics
* Correlation Analysis
* Outlier Detection using IQR
* Scatter Plots & Heatmaps
* Data Visualization

---

## 📖 Key Insights

* Lower-income applicants showed higher default risk
* Younger applicants faced more repayment difficulties
* Higher education was associated with lower default probability
* Most applicants belonged to middle-income groups
* Consumer loans had the highest approval rates
* Financial variables such as credit amount and annuity showed strong relationships

---

## 🚀 Conclusion

This project demonstrates how Exploratory Data Analysis can be applied in banking and financial services to improve credit risk management and lending decisions.

By identifying patterns related to repayment difficulties and customer risk profiles, financial institutions can reduce default risk, improve loan approval strategies, and make more informed business decisions.

