# 📊 Customer Churn Analysis

<p align="center">
  <b>Exploratory Data Analysis of Customer Churn using Python</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-Visualization-76B900" alt="Seaborn">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter" alt="Jupyter">
</p>

---

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses because losing existing customers can directly impact revenue and long-term growth.

This project performs an **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset to understand customer behavior and identify the factors associated with customer churn.

The analysis focuses on customer demographics, services, contracts, payment methods, and other customer attributes to discover meaningful churn patterns.

---

## 🎯 Business Objective

The main objective is to answer:

> **Why are customers leaving, and which customer segments show higher churn?**

### Key Questions

* What is the overall customer churn distribution?
* Which contract type has more churned customers?
* Which internet service has more churned customers?
* Does technical support relate to customer churn?
* Does online security relate to churn?
* Which payment methods are associated with higher churn?
* Which customer segments should receive more retention attention?

---

## 📂 Dataset

The project uses the **Telco Customer Churn** dataset.

### Dataset Summary

| Attribute       | Details                   |
| --------------- | ------------------------- |
| Dataset         | Telco Customer Churn      |
| Records         | 7,043 customers           |
| Features        | 21 columns                |
| Target Variable | `Churn`                   |
| Analysis Type   | Exploratory Data Analysis |

### Major Feature Categories

**Customer Information**

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure

**Services**

* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies

**Subscription & Billing**

* Contract
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges

**Target**

* Churn

---

## 🛠️ Tech Stack

| Technology          | Usage                        |
| ------------------- | ---------------------------- |
| 🐍 Python           | Data analysis                |
| 🐼 Pandas           | Data cleaning & manipulation |
| 🔢 NumPy            | Numerical operations         |
| 📊 Matplotlib       | Data visualization           |
| 📈 Seaborn          | Statistical visualization    |
| 📓 Jupyter Notebook | Analysis environment         |
| 🔧 Git              | Version control              |
| 🌐 GitHub           | Project hosting              |

---

## 🔍 Analysis Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Exploration
     ↓
Exploratory Data Analysis
     ↓
Visualization
     ↓
Churn Pattern Analysis
     ↓
Business Insights
     ↓
Retention Recommendations
```

---

## 🧹 Data Preparation

The dataset was inspected and prepared before performing the analysis.

### Steps Performed

* Checked dataset dimensions
* Inspected column names and data types
* Checked missing values
* Checked duplicate records
* Examined unique values
* Reviewed numerical statistics
* Prepared categorical variables for analysis
* Created visualizations for important customer attributes

---

## 📊 Exploratory Data Analysis

The project analyzes churn across multiple dimensions.

### 👥 Customer Demographics

Customer churn was explored across demographic characteristics such as gender and other customer attributes.

### 📄 Contract Type

Churned customers were analyzed across:

* Month-to-month
* One year
* Two year

This helps identify whether customer commitment through longer contracts is associated with better retention.

### 🌐 Internet Service

Churned customers were compared across different internet service categories.

This helps identify internet service segments that require further investigation.

### 🛠️ Technical Support

Customers were analyzed based on their technical support status.

This helps understand whether support availability is associated with customer churn.

### 🔐 Online Security

The analysis compares churned customers based on online security service availability.

### 💳 Payment Method

Customer churn was also analyzed across different payment methods to identify potential billing or payment-related patterns.

---

## 📈 Key Visualizations

The project includes visualizations such as:

* Customer churn distribution
* Churn by gender
* Customer count by contract type
* Churn by internet service
* Churn by technical support
* Churn by online security
* Churn by payment method
* Service-level churn comparisons

---

## 💡 Key Business Insights

The exploratory analysis helps identify several important areas for customer retention.

### 1. Contract Type

Month-to-month customers represent an important churn segment compared with customers on longer-term contracts.

**Business Action:**
Consider targeted incentives for month-to-month customers to encourage longer-term contracts.

---

### 2. Internet Service

Churn behavior varies across internet service categories.

**Business Action:**
Investigate service quality, pricing, customer experience, and technical issues within high-churn internet segments.

---

### 3. Technical Support

Technical support availability provides an additional dimension for understanding churn behavior.

**Business Action:**
Improve support accessibility and proactively assist customers experiencing service issues.

---

### 4. Online Security

Customer churn patterns differ based on online security service availability.

**Business Action:**
Consider bundled security offerings and educate customers about the value of additional services.

---

### 5. Payment Method

Different payment methods show different levels of churn.

**Business Action:**
Investigate billing friction and encourage convenient payment methods where appropriate.

---

## 🎯 Customer Retention Recommendations

Based on the analysis, businesses can consider:

### 🔹 1. Target High-Risk Customers

Create customer segments based on contract, services, tenure, and billing characteristics.

### 🔹 2. Encourage Long-Term Contracts

Offer discounts, loyalty benefits, or additional services to month-to-month customers.

### 🔹 3. Improve Customer Support

Provide faster technical assistance and proactive issue resolution.

### 🔹 4. Monitor High-Churn Service Segments

Regularly track churn rates across internet and additional service categories.

### 🔹 5. Improve Billing Experience

Identify customers experiencing payment or billing friction and provide simpler payment options.

---

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── 📄 .gitignore
├── 📄 README.md
├── 📄 requirements.txt
├── 📊 Telco-Customer-Churn.csv
└── 📓 customer_churn_analysis.ipynb
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/aryansingh186/customer-churn-analysis.git
```

### 2. Navigate to the Project

```bash
cd customer-churn-analysis
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

```text
customer_churn_analysis.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

---

## 📦 Requirements

The project uses the following Python libraries:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

This project can be extended beyond exploratory analysis.

### Machine Learning

Build a predictive model to identify customers who are likely to churn.

Potential algorithms:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

### Customer Segmentation

Use clustering techniques to identify different customer groups based on:

* Tenure
* Monthly Charges
* Services
* Contract
* Customer behavior

### Dashboard

Create an interactive **Power BI Customer Churn Dashboard** containing:

* Total Customers
* Churn Rate
* Churned Customers
* Monthly Revenue at Risk
* Churn by Contract
* Churn by Internet Service
* Churn by Payment Method
* Customer Segments

---

## 📌 Project Outcome

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* NumPy
* Data Visualization
* Seaborn
* Matplotlib
* Business Insight Generation
* Customer Retention Analysis

The project focuses not only on creating charts, but also on **translating customer data into actionable business recommendations**.

---

## 👨‍💻 Author

### Aryan Singh

**Aspiring Data Analyst**

**Skills:** Python • SQL • Power BI • Excel • Data Analysis

---

## ⭐ Project

If you find this project useful, feel free to ⭐ the repository.

**GitHub:**
https://github.com/aryansingh186
