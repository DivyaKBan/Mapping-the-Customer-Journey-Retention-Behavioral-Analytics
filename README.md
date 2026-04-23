# 🧠Mapping-the-Customer-Journey-Retention-Behavioral-Analytics


<div align="center">
  <img src="https://github.com/DivyaKBan/Mapping-the-Customer-Journey-Retention-Behavioral-Analytics/blob/main/img/customer%20segmentation.jpg" alt="Customer Segmentation Banner" width="80%">
</div>

---

## 📌 Problem Overview

- In the **retail industry**, understanding customer value is essential for business growth.
- Businesses must identify:
  - High-value customers
  - Loyal customers
  - At-risk customers

---

### 💡 What is RFM?

- **RFM (Recency, Frequency, Monetary)** is a widely used technique to evaluate customer value based on:
  - **Recency** → How recently a customer made a purchase
  - **Frequency** → How often they purchase
  - **Monetary** → How much they spend

---

### 🎯 Objective

- Perform **customer segmentation** using:
  - Cohort Analysis
  - RFM Modeling

- Final goal:
  - Categorize customers from:
    - 🟢 Most valuable → High R, F, M
    - 🔴 Least valuable → Low R, F, M

---

## 📂 Dataset Description

- **Type:** Transnational transactional dataset  
- **Duration:** 01 Dec 2010 → 09 Dec 2011  
- **Business:** UK-based online retail store  
- **Domain:** Unique and all-occasion gift items  

---

### 📊 Features Description

| Variable | Description | Details |
|:---|:---|:---|
| **InvoiceNo** | Invoice Number | Unique 6-digit transaction ID (prefix 'C' = cancellation) |
| **StockCode** | Product Code | Unique identifier for each product |
| **Description** | Product Name | Item description |
| **Quantity** | Quantity Purchased | Number of items per transaction |
| **InvoiceDate** | Transaction Timestamp | Date and time of purchase |
| **UnitPrice** | Price per Unit | Product price (in GBP) |
| **CustomerID** | Customer ID | Unique customer identifier |
| **Country** | Customer Location | Country of residence |

---

## 🛠️ Project Workflow

### 🗂️ Data Cleaning & Cohort Analysis

- Perform initial data inspection
- Handle missing values:
  - Identify nulls
  - Apply suitable imputation strategy
- Remove duplicate records
- Conduct descriptive analysis

#### 📅 Cohort Analysis
- Define cohorts based on monthly activity
- Analyze:
  - Customer retention over time
  - Behavior comparison across cohorts

---

### 📊  RFM Modeling

- Build RFM framework:
  - Calculate Recency, Frequency, Monetary values

- Create RFM Segments:
  - Divide metrics into quartiles
  - Assign scores individually

- Generate:
  - Combined RFM segment (string format)
  - Overall RFM score (numeric sum)

- Analyze:
  - Segment behavior
  - Business insights from segmentation

---

### 🤖  K-Means Clustering

- Prepare dataset:
  - Handle skewness using transformations
  - Standardize features

- Apply K-Means algorithm:
  - Determine optimal clusters (Elbow Method)

- Evaluate clusters:
  - Interpret patterns
  - Compare with RFM segmentation

---

### 📈 Data Visualization & Dashboard

- Develop Tableau dashboard with key insights:

#### 📌 Dashboard Components

- 🌍 Country-wise average spending (monthly bar chart)
- 📦 Top 15 most purchased products
- ⏰ Orders distribution by hour of the day
- 📊 RFM value distributions (histograms)
- 📉 Cost vs number of clusters (Elbow curve)
- 🔥 Heatmap comparing cluster RFM values


---

## 🧾 Dataset Snapshot

<div align="center">
  <img src="https://github.com/DivyaKBan/Mapping-the-Customer-Journey-Retention-Behavioral-Analytics/blob/main/img/dataframe.jpg" alt="Dataset Overview" width="80%">
</div>

---

## 🔥 Cohort Analysis Visualizations

### 1️⃣ Retention Rate Heatmap

<div align="center">
  <img src="https://github.com/DivyaKBan/Mapping-the-Customer-Journey-Retention-Behavioral-Analytics/blob/main/img/monthly_retention_rates.jpg" width="80%">
</div>

---

### 2️⃣ Average Quantity Analysis

<div align="center">
  <img src="https://github.com/DivyaKBan/Mapping-the-Customer-Journey-Retention-Behavioral-Analytics/blob/main/img/avg_quantity_monthly.jpg" width="80%">
</div>

---

### 3️⃣ Average Spending Trends

<div align="center">
  <img src="https://github.com/DivyaKBan/Mapping-the-Customer-Journey-Retention-Behavioral-Analytics/blob/main/img/avg_spend_monthly.jpg" width="80%">
</div>

---

## 📊 RFM Dashboard

<div align="center">
  <img src="https://github.com/DivyaKBan/Mapping-the-Customer-Journey-Retention-Behavioral-Analytics/blob/main/img/Dashboard.jpg" alt="RFM Dashboard" width="85%">
</div>

---

## 🚀 Key Takeaways

- RFM modeling effectively segments customers based on behavior
- Cohort analysis helps track customer retention trends over time
- K-Means clustering provides additional grouping insights
- Combining these techniques leads to **data-driven business decisions**

---
