# Customer Segmentation System

A comprehensive data analysis and customer segmentation project using machine learning techniques to identify distinct customer groups based on shopping mall behavior.

## 📋 Project Overview

This project analyzes customer data from a shopping mall to segment customers into meaningful groups using K-means clustering. The segmentation helps businesses understand different customer types and tailor marketing strategies accordingly.

## 🎯 Objectives

- Perform exploratory data analysis on customer demographics and spending behavior
- Implement data preprocessing and feature engineering
- Apply K-means clustering algorithm for customer segmentation
- Analyze and interpret customer segments for business insights

## 📊 Dataset

The project uses the `Mall_Customers.csv` dataset containing:
- **CustomerID**: Unique identifier for each customer
- **Gender**: Customer's gender (Male/Female)
- **Age**: Customer's age
- **Annual Income (k$)**: Customer's annual income in thousands of dollars
- **Spending Score (1-100)**: Mall's assessment of customer spending behavior

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms
  - StandardScaler for feature scaling
  - LabelEncoder for categorical variables
  - KMeans for clustering
  - Silhouette Score for cluster evaluation

## 📁 Project Structure
Customer Segmentation System/
├── Customer Segmentation System.ipynb # Main Jupyter notebook
├── Mall_Customers.csv # Dataset
├── README.md # Project documentation
└── requirements.txt # Python dependencies

## Methodology
1. Data Loading & Exploration
- Load and inspect the dataset
- Understand data structure and basic statistics

2. Data Preprocessing
- Handle missing values and duplicates
- Encode categorical variables (Gender)
- Scale numerical features (Age, Annual Income, Spending Score)

3. Exploratory Data Analysis (EDA)
- Statistical summaries
- Data visualization and distribution analysis
- Correlation analysis between features

4. Clustering Implementation
- Determine optimal number of clusters using silhouette analysis
- Apply K-means clustering algorithm
- Evaluate cluster quality and interpret results

5. Segment Analysis
- Profile each customer segment
- Identify characteristics and behaviors of different segments
- Provide business recommendations based on segments

📊 Key Findings
The analysis reveals distinct customer segments including:
- High-income, Low-spending customers
- Moderate-income, Moderate-spending customers
- Low-income, High-spending customers
- High-income, High-spending premium customers
- Low-income, Low-spending budget-conscious customers

💡 Business Applications
- Targeted Marketing: Customize promotions for different segments
- Product Placement: Optimize product offerings based on segment preferences
- Customer Retention: Develop loyalty programs for high-value segments
- Resource Allocation: Focus resources on most profitable customer groups
