# 🚗 Insurance Customer Conversion Analysis

### 📊 Exploratory Data Analysis of Insurance Customer Behavior

An exploratory data analysis project focused on understanding **insurance customer characteristics, engagement patterns, claims-related attributes, and conversion behavior** using Python.

The project analyzes a synthetic insurance dataset containing **10,000 customer records and 27 attributes**.

---

## 🔎 Project Overview

Insurance companies collect large amounts of customer and policy-related data. Understanding this data can help uncover patterns in customer behavior and provide a stronger foundation for business decision-making.

This project explores customer characteristics and investigates relationships between variables such as:

* 👤 Age and senior-customer status
* 💳 Credit score
* 🌐 Website visits
* 💬 Customer inquiries
* 📝 Quotes requested
* 🧾 Claims frequency and severity
* 🏠 Region
* 📄 Policy type
* 🔄 Conversion status
* ⏱️ Time to conversion

The dataset contains several customer, claims, policy, engagement, and conversion-related attributes.

---

## 🎯 Objectives

The main objectives of this project are to:

* Understand the structure and distribution of insurance customer data
* Explore customer demographic and behavioral patterns
* Analyze insurance claims characteristics
* Investigate factors associated with customer conversion
* Identify relationships between numerical variables
* Visualize patterns using statistical graphics
* Generate insights that can support further predictive analysis

---

## 🗂️ Dataset

**Dataset Size**

| Property        |                    Value |
| --------------- | -----------------------: |
| Records         |                   10,000 |
| Features        |                       27 |
| Data Type       | Synthetic Insurance Data |
| Target Variable |      `Conversion_Status` |

The dataset contains variables related to customer demographics, insurance history, claims, policy characteristics, digital engagement, credit profile, region, and conversion behavior.

### Example Features

`Age` • `Marital_Status` • `Prior_Insurance` • `Claims_Frequency` • `Claims_Severity` • `Policy_Type` • `Website_Visits` • `Inquiries` • `Quotes_Requested` • `Credit_Score` • `Region` • `Conversion_Status`

---

## 🧪 Analysis Performed

### 1️⃣ Data Understanding

The project begins with basic data inspection and descriptive analysis using:

* `head()`
* `tail()`
* `describe()`
* `info()`

This provides an overview of the dataset structure, distributions, and statistical characteristics.

### 2️⃣ Univariate Analysis

Individual variables were analyzed using histograms, count plots, and pie charts.

Examples include:

* Age distribution
* Credit score distribution
* Time since first contact
* Senior-customer distribution
* Conversion status distribution
* Claims severity distribution

### 3️⃣ Bivariate Analysis

Relationships between pairs of variables were explored using:

* Box plots
* Scatter plots
* Count plots

Examples include:

* Credit Score vs Conversion Status
* Website Visits vs Conversion Status
* Marital Status vs Senior Status
* Credit Score vs Time Since First Contact

### 4️⃣ Multivariate Analysis

Multiple variables were analyzed simultaneously using:

* Pair plots
* Multivariate scatter plots
* Feature-based visual comparisons

This helps identify more complex patterns between customer engagement, credit profile, demographics, and conversion.

### 5️⃣ Correlation Analysis

A correlation matrix and heatmap were used to examine relationships between numerical variables and identify potentially related features.

---

## 📈 Key Areas of Investigation

The analysis focuses particularly on understanding:

### 👥 Customer Profile

How customer demographics and senior status vary across the dataset.

### 💳 Financial Profile

How credit score varies across customer groups.

### 🌐 Digital Engagement

How website visits and inquiries relate to customer behavior.

### 🧾 Claims Behavior

How claims frequency and severity are distributed among customers.

### 🔄 Conversion Behavior

How customer characteristics and engagement variables differ according to conversion status.

---

## 🛠️ Technologies Used

| Technology          | Purpose                   |
| ------------------- | ------------------------- |
| 🐍 Python           | Data analysis             |
| 🐼 Pandas           | Data manipulation         |
| 🔢 NumPy            | Numerical analysis        |
| 📊 Matplotlib       | Data visualization        |
| 📈 Seaborn          | Statistical visualization |
| 📓 Jupyter Notebook | Development environment   |

---

## 📂 Project Structure

```text
insurance-customer-conversion-analysis/
│
├── 📓 insurance_customer_conversion_analysis.ipynb
├── 📄 Insurance_Customer_Conversion_Report.pdf
├── 📊 data/
│   └── synthetic_insurance_data.csv
├── 🖼️ images/
│   └── analysis_visualizations/
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/insurance-customer-conversion-analysis.git
```

### 2. Navigate to the project

```bash
cd insurance-customer-conversion-analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
insurance_customer_conversion_analysis.ipynb
```

---

## 📊 Project Preview

### Customer & Conversion Analysis

*Add your strongest visualization screenshots here.*

### Correlation Analysis

*Add your correlation heatmap here.*

### Multivariate Analysis

*Add your best multivariate visualization here.*

---

## 💡 What This Project Demonstrates

This project demonstrates practical experience with:

**Data Cleaning → Data Exploration → Statistical Description → Visualization → Relationship Analysis → Business-Oriented Interpretation**

It also provides a foundation for extending the project into predictive customer-conversion modeling.

---

## 🔮 Future Improvements

The current project is primarily focused on exploratory data analysis. Possible future extensions include:

* 🤖 Customer conversion prediction using Machine Learning
* 📊 Interactive Power BI dashboard
* 🎯 Customer segmentation
* 🔍 Feature importance analysis
* 📈 Conversion-rate KPI analysis
* ⚡ Automated prediction pipeline

---

## 👨‍💻 Author

### Sathvik B R

**BCA Student | Aspiring Data Analyst**

Interested in:

`Data Analytics` • `Python` • `SQL` • `Power BI` • `Machine Learning`

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐

---

### 📌 Project Status

**Status:** ✅ Exploratory Data Analysis Completed

**Focus:** Insurance Customer Behavior & Conversion Analysis
