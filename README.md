# Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview

This project focuses on customer segmentation using Machine Learning (K-Means Clustering) to identify distinct groups of customers based on their income and spending behavior.

The objective is to help businesses understand their customers better and enable targeted marketing strategies.

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Dataset

Source: Kaggle - Mall Customer Segmentation Dataset

### Features Used:

* CustomerID → Unique identifier (removed during analysis)
* Gender → Customer gender
* Age → Customer age
* Annual Income (k$) → Income in thousand dollars
* Spending Score (1–100) → Score based on purchasing behavior

---

## 🔧 Project Workflow

### 1. Data Cleaning

* Renamed columns for better readability
* Removed unnecessary column (CustomerID)
* Verified no missing values and duplicates
* Ensured correct data types

---

### 2. Exploratory Data Analysis (EDA)

Performed analysis to understand customer patterns:

* Age distribution
* Income distribution
* Spending behavior
* Gender distribution
* Correlation analysis
* Income vs Spending scatter plot

---

### 3. Feature Selection

Selected key features for clustering:

* Annual Income
* Spending Score

These features best represent customer purchasing behavior.

---

### 4. K-Means Clustering

* Used Elbow Method to determine optimal clusters (K = 5)
* Applied K-Means algorithm
* Assigned cluster labels to each customer

---

### 5. Cluster Visualization

* Created scatter plots to visualize customer segments
* Identified clear separation between different customer groups

---

## 📈 Customer Segments Identified

| Cluster | Segment Type      |
| ------- | ----------------- |
| 0       | Average Customers |
| 1       | Premium Customers |
| 2       | Impulsive Buyers  |
| 3       | Target Customers  |
| 4       | Budget Customers  |

---

## 💡 Key Insights

* Customers are segmented into 5 distinct groups based on income and spending behavior.
* Premium customers (high income, high spending) contribute the most to revenue.
* High-income but low-spending customers represent strong growth potential.
* Impulsive buyers (low income, high spending) show unique purchasing behavior.
* Budget customers contribute the least to revenue.
* Average customers form a stable customer base.
* Targeted marketing strategies can significantly improve business outcomes.
* Customer segmentation helps in personalized marketing and better decision-making.

---

## 🎯 Business Impact

This project demonstrates how customer segmentation can:

* Improve targeted marketing strategies
* Increase customer retention
* Identify high-value customers
* Optimize resource allocation

---

## 👤 Author

Mariya Kapadia
Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning
