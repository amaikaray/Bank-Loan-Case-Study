# 🏦 Bank Loan Case Study Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a bank loan application dataset to identify the key factors that influence customer repayment behavior and loan default risk. The analysis compares customers facing payment difficulties with those successfully repaying loans to uncover meaningful patterns that support better credit risk assessment.

The project applies data cleaning, statistical analysis, visualization techniques, and business storytelling to generate actionable insights for banks and financial institutions.

The objective is to help lenders make smarter loan approval decisions while minimizing financial losses caused by defaults.

---

## 🎯 Problem Statement

How can banks identify customers who are likely to face repayment difficulties?

Financial institutions face two major risks during loan approval:

* Approving loans for customers who may default
* Rejecting customers who are actually capable of repayment

This project aims to identify patterns associated with payment difficulties so that banks can improve lending strategies and reduce credit risk.

---

## 🧹 Data Cleaning & Preprocessing

The datasets underwent multiple preprocessing steps to ensure accurate and reliable analysis:

* Handling missing and null values
* Removing irrelevant columns
* Dropping columns with more than 30% missing values
* Replacing missing values using median/mode methods
* Removing negative signs from date-related columns
* Converting DAYS_BIRTH into age in years
* Identifying numerical and categorical variables
* Standardizing and preparing data for analysis

The project used three datasets:

* `application_data.csv`
* `previous_application.csv`
* `columns_description.csv`

---

## 📊 Data Analysis Tasks

### A. Missing Value Analysis

* Calculated null value percentages for all columns
* Identified highly missing variables
* Treated remaining missing values appropriately using statistical methods

---

### B. Outlier Detection Analysis

Used Quartiles, IQR, Lower Bound, and Upper Bound techniques to identify outliers.

#### Key Variables Analyzed:

* AMT_INCOME_TOTAL
* AMT_CREDIT
* AMT_ANNUITY
* AMT_GOODS_PRICE
* CNT_CHILDREN
* CNT_PAYMENT
* YEARS_BIRTH

#### Key Findings:

* A few applicants had extremely high incomes and loan amounts
* Some loans contained unusually large repayment periods
* Age distribution showed no major outliers

---

### C. Data Imbalance Analysis

Analyzed the distribution of loan repayment difficulty using the TARGET variable.

#### Findings:

* Approximately 92% customers were non-defaulters
* Only around 8% customers faced payment difficulties

This indicates a highly imbalanced dataset where successful repayments significantly outnumber defaults.

---

### D. Univariate Analysis

Performed analysis on individual variables to understand customer distribution patterns.

#### Variables Analyzed:

* Income
* Credit Amount
* Loan Annuity
* Goods Price
* Number of Children
* Age
* Gender
* Education Type
* Income Type
* Family Status

#### Key Insights:

* Most applicants belong to middle-income groups
* Moderate loan amounts are most common
* Majority of applicants are working professionals
* Married individuals form the largest applicant group
* Female applicants are higher in number compared to males

---

### E. Segmented Univariate Analysis

Compared variable distributions across customers with and without payment difficulties.

#### Key Findings:

* Lower-income applicants showed higher default rates
* Younger applicants were more likely to face repayment difficulties
* Higher education levels were associated with lower default risk
* Applicants with children showed slightly higher default rates

---

### F. Previous Loan Application Analysis

Analyzed customer previous loan application behavior.

#### Key Findings:

* Most previous applications were approved
* Consumer loans had the highest approval rates
* Repeat customers formed the largest applicant segment
* Higher loan amounts and longer repayment terms carried more risk

---

### G. Bivariate Analysis

Studied relationships between multiple variables to identify repayment risk indicators.

#### Analysis Included:

* Income vs Credit Amount
* Loan Amount vs Default Risk
* Credit Amount across Income Bins

#### Key Findings:

* Higher-income applicants generally qualified for larger loans
* Loan defaults occurred across all loan ranges
* Financial variables showed strong interrelationships

---

### H. Correlation Analysis

Performed correlation analysis using Excel’s `CORREL` function for different customer segments.

#### Findings:

Strong positive relationships were observed between:

* AMT_CREDIT
* AMT_GOODS_PRICE
* AMT_ANNUITY

The correlation patterns were similar for both defaulters and non-defaulters, indicating that loan default depends on a combination of customer characteristics and financial behavior rather than a single factor.

---

## 📈 Tools & Techniques Used

* Microsoft Excel (2019)
* Data Cleaning & Transformation
* Pivot Tables & Pivot Charts
* Descriptive Statistics
* Correlation Analysis
* Outlier Detection using IQR
* Data Visualization
* Scatter Charts & Trend Analysis
* Business Storytelling

---

## 📖 Key Insights

This project provides insights into:

* Customer characteristics associated with loan default
* Relationship between income and loan eligibility
* Impact of education and family status on repayment behavior
* Loan approval trends in previous applications
* Risk patterns among younger and lower-income applicants
* Financial variables strongly connected to repayment capacity

---

## 🚀 Conclusion

This analysis demonstrates how Exploratory Data Analysis can be applied in the banking and financial sector to improve credit risk assessment and lending decisions.

By identifying repayment behavior patterns and customer risk profiles, financial institutions can reduce default risk while ensuring eligible customers are not unnecessarily rejected.

The project also highlights the importance of combining statistical analysis, visualization, and business storytelling to transform raw financial data into meaningful business insights.

