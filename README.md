# 📊 Project 3 - Exploratory Data Analysis (EDA) on Industry Dataset

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an Industry Dataset containing company-level information such as employee count, annual revenue, profit margin, customer count, market rating, industry, country, and region.

The objective of this analysis is to understand business performance patterns, identify relationships between variables, detect outliers, and generate actionable business insights using statistical analysis and data visualization techniques.

---

## 🎯 Objectives

* Understand the structure and quality of the dataset.
* Perform data cleaning and preprocessing.
* Analyze distributions of numerical and categorical variables.
* Detect potential outliers using statistical methods.
* Explore relationships between business metrics.
* Identify industry and country-wise performance trends.
* Generate meaningful business insights and recommendations.

---

## 📂 Dataset Information

The dataset contains information related to companies operating across multiple industries and countries.

### Features Included

| Column Name            | Description                  |
| ---------------------- | ---------------------------- |
| company_name           | Company Name                 |
| industry               | Industry Category            |
| country                | Country of Operation         |
| employee_count         | Number of Employees          |
| annual_revenue_million | Annual Revenue (Million USD) |
| profit_margin_percent  | Profit Margin (%)            |
| founded_year           | Company Foundation Year      |
| customer_count         | Number of Customers          |
| market_rating          | Market Rating                |
| created_date           | Record Creation Date         |
| region                 | Geographic Region            |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked dataset shape and structure
* Data type validation
* Missing value analysis
* Duplicate record detection
* Unique value analysis
* Date conversion for created_date column
* Audit table creation

### Audit Checks

* Missing Values: 0
* Duplicate Records: 0
* Data Quality: Good
* Dataset Status: Analysis Ready

---

## 📈 Univariate Analysis

### Numerical Variables

Analysis performed on:

* Employee Count
* Annual Revenue
* Profit Margin
* Founded Year
* Customer Count
* Market Rating

### Techniques Used

* Descriptive Statistics
* Histograms
* Distribution Analysis
* Skewness
* Kurtosis
* Boxplots

### Categorical Variables

Analysis performed on:

* Industry
* Country
* Region

### Visualizations

* Pie Charts
* Count Plots
* Frequency Analysis

---

## 🚨 Outlier Detection

Outliers were examined using:

### Methods

* Boxplot Analysis
* Interquartile Range (IQR)

### Observation

No significant outliers were detected across the major business variables, indicating a balanced and well-distributed dataset.

---

## 🔗 Bivariate Analysis

Relationships between variables were analyzed using:

### Numerical vs Numerical

* Employee Count vs Annual Revenue
* Customer Count vs Annual Revenue
* Market Rating vs Profit Margin
* Founded Year vs Revenue

### Categorical vs Numerical

* Industry vs Revenue
* Industry vs Market Rating
* Country vs Revenue
* Region vs Revenue

### Visualizations

* Scatter Plots
* Bar Charts
* Boxplots
* Correlation Heatmap

---

## 📊 Multivariate Analysis

Advanced analysis was performed using:

### Pairplot Analysis

* Numerical variables grouped by Industry

### Trend Analysis

* Revenue Trend by Industry over Founded Years
* Customer Count Trend by Region over Created Years

### Heatmap Analysis

* Industry vs Country Revenue Performance

### Pivot Tables

* Industry-Country Revenue Matrix
* Comparative Business Performance Analysis

---

## 🔑 Key Findings

* The dataset contains 15,000 clean records with no missing values.
* Employee count and customer count show positive business significance.
* Revenue distribution is relatively balanced across industries.
* Retail industry records the highest average revenue.
* Market ratings remain moderate across most segments.
* Industry and country combinations influence revenue performance.
* Regional customer trends remain stable over time.
* No significant outliers were observed in the dataset.

---

## 💼 Business Implications

* The dataset is suitable for benchmarking because quality checks passed and segment coverage is even.
* Management should not assume revenue is driven only by employee count or customer count.
* Retail has the highest average revenue, but performance gaps remain relatively small.
* Market rating improvements should focus on overall customer satisfaction rather than only top-performing firms.
* Feature engineering such as company age, revenue per employee, and revenue per customer can improve future predictive models.

---

## ✅ Conclusion

This Exploratory Data Analysis successfully examined company performance across industries, countries, and regions.

The dataset demonstrated strong data quality with no missing values and no major outliers. Through univariate, bivariate, and multivariate analysis, meaningful patterns were identified regarding revenue generation, customer behavior, industry performance, and market ratings.

The insights generated from this analysis can support strategic decision-making, benchmarking, market evaluation, and future predictive analytics initiatives.

---

## 👩‍💻 Author

**Shivangini**

Project: Exploratory Data Analysis (EDA) – Industry Dataset
