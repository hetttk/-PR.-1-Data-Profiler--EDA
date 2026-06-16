# -PR.-1-Data-Profiler--EDA
 # Customer Churn Analysis and Data Profiling Project

## Project Overview

This project focuses on customer churn analysis using data science techniques. The objective is to acquire customer data from multiple sources, clean and preprocess the dataset, perform exploratory data analysis (EDA), and generate a comprehensive profiling report to understand customer behavior and churn patterns.

---

## Objectives

* Understand the data analysis workflow.
* Collect data from different sources.
* Perform data cleaning and preprocessing.
* Conduct exploratory data analysis using Seaborn.
* Generate a data profiling report using YData Profiling.
* Identify factors that influence customer churn.

---

## Dataset Description

The dataset contains customer information including:

| Feature          | Description                               |
| ---------------- | ----------------------------------------- |
| CustomerID       | Unique customer identifier                |
| Age              | Customer age                              |
| Gender           | Customer gender                           |
| Income           | Annual income                             |
| Purchases        | Number of purchases                       |
| MembershipYears  | Years of membership                       |
| LastPurchaseDays | Days since last purchase                  |
| Category         | Product category                          |
| Churn            | Target variable (0 = No Churn, 1 = Churn) |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* SQLite
* Requests
* YData Profiling
* Jupyter Notebook

---

## Project Workflow

### Part A: Fundamentals

* Introduction to Data Analysis
* Data Science Project Lifecycle
* Machine Learning Problem Statement
* Tensor Concepts and Examples

### Part B: Data Acquisition
<img width="1522" height="797" alt="image" src="https://github.com/user-attachments/assets/b69a8c11-f97f-4509-8998-4c3ca7d6c3bc" />

Data was collected from:

* CSV Files
* JSON Files
* SQLite Database
* API Sources
<img width="1541" height="886" alt="image" src="https://github.com/user-attachments/assets/5c91425e-afb7-4e72-afb8-6e7f9f3ab9c1" />

The collected datasets were merged and prepared for analysis.

### Part C: Data Understanding and Cleaning

The following preprocessing tasks were performed:

* Dataset inspection
* Missing value detection
* Duplicate record detection
* Data type verification
* Feature selection
* Data quality validation

### Part D: Exploratory Data Analysis (EDA)

EDA was performed using Seaborn visualizations.

#### Univariate Analysis
<img width="1541" height="886" alt="image" src="https://github.com/user-attachments/assets/5c91425e-afb7-4e72-afb8-6e7f9f3ab9c1" />

* Age Distribution
* Income Distribution
* Purchases Distribution
* Gender Distribution
* Category Distribution

#### Bivariate Analysis

<img width="1508" height="682" alt="image" src="https://github.com/user-attachments/assets/e0356be6-8b25-4c54-8304-dd62f646df47" />

* Gender vs Purchases
* Income vs Churn
* Category vs Churn
* Gender vs Churn
* Age vs Churn

#### Multivariate Analysis
<img width="1337" height="743" alt="image" src="https://github.com/user-attachments/assets/9237ae81-301c-4476-97ef-8f55985ac32b" />

* Correlation Heatmap
* Pair Plot
* Income vs Purchases
* Membership Years vs Purchases
* Last Purchase Days vs Purchases
<img width="1304" height="1228" alt="5e221448-1871-4424-b5cb-0f050968d208" src="https://github.com/user-attachments/assets/459a1922-df29-4664-97ef-0cb4b5a08940" />


### Part E: Data Profiling

YData Profiling was used to generate an automated profiling report containing:
<img width="1919" height="859" alt="image" src="https://github.com/user-attachments/assets/76e7c18b-5a51-4155-a456-69cdf7f336f5" />

* Dataset Overview
* Variable Statistics
* Missing Value Analysis
* Correlation Analysis
* Duplicate Detection
* Data Quality Assessment

---

## Key Findings

* The dataset contained 1000 customer records.
* No missing values were detected.
* No duplicate records were found.
* Customer demographics and purchasing behavior were successfully analyzed.
* Correlation analysis revealed relationships among numerical features.
* The dataset is suitable for machine learning applications such as customer churn prediction.

---

## Generated Files

* cleaned_customer_data.csv
* customer_churn_profile_report.html
* Jupyter Notebook (.ipynb)

---

## Conclusion

This project successfully demonstrated the complete data science workflow from data acquisition to profiling and exploratory analysis. The generated insights can help businesses better understand customer behavior and develop strategies to reduce customer churn.


