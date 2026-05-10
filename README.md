# Customer Segmentation Using Machine Learning

## Overview
This project focuses on customer segmentation using Machine Learning techniques.  
The goal is to divide customers into different groups based on their purchasing behavior, income, and spending patterns.

Customer segmentation helps businesses:
- Understand customer behavior
- Improve marketing strategies
- Increase customer retention
- Target the right audience

---

# Problem Statement
Businesses often have thousands of customers with different purchasing habits.  
It becomes difficult to target every customer using the same marketing strategy.

This project uses clustering algorithms to group customers into meaningful segments based on:
- Annual Income
- Spending Score
- Age
- Purchasing Behavior

---

# Dataset
The project uses the **Mall Customer Segmentation Dataset**.

Dataset Features:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

Dataset Source:
- Kaggle Mall Customer Dataset

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Machine Learning Algorithm

## K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to group similar data points into clusters.

The algorithm:
1. Selects cluster centroids
2. Assigns data points to nearest centroid
3. Updates centroids iteratively
4. Creates optimized customer groups

---

# Project Workflow

1. Import Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Find Optimal Number of Clusters
6. Train K-Means Model
7. Visualize Customer Segments
8. Analyze Business Insights

---

# Data Visualization

The project includes:
- Scatter Plots
- Cluster Visualization
- Elbow Method Graph
- Customer Distribution Analysis

---

# Model Performance

## Optimal Number of Clusters
Using the Elbow Method:
- Optimal Clusters = 5

The model successfully groups customers into different segments such as:
- High Income & High Spending
- Low Income & Low Spending
- High Income & Low Spending
- Budget Customers
- Premium Customers

---

# Business Insights

The segmentation helps businesses:
- Identify premium customers
- Create personalized marketing campaigns
- Improve sales strategies
- Increase customer satisfaction

---

# Project Structure

```text
customer-segmentation/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── screenshots/
│   └── clusters.png
│
├── src/
│   └── segmentation.py
│
├── requirements.txt
├── README.md
└── .gitignore
