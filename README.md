Project Overview

This project focuses on analyzing mall customer data to identify distinct customer segments based on their demographics and purchasing behavior. The goal is to help businesses understand their customers better and make data-driven decisions for targeted marketing and improved customer engagement.

Using Python, data analysis, and machine learning techniques, this project performs end-to-end analysis including data preprocessing, exploratory data analysis (EDA), and customer segmentation using clustering.

🎯 Problem Statement

Businesses often struggle to understand customer behavior and target the right audience. This project aims to:

> Identify different types of customers

> Analyze spending patterns

> Segment customers for targeted marketing strategies

📂 Dataset Information

The dataset contains the following features:

> CustomerID → Unique identifier for each customer

> Gender → Male/Female

> Age → Age of the customer

> Annual Income (k$) → Customer income

> Spending Score (1-100) → Score assigned based on customer behavior

⚙️ Project Workflow

1️⃣ Data Cleaning

> Checked for missing values

> Removed duplicates

> Ensured proper data types

2️⃣ Exploratory Data Analysis (EDA)

> Analyzed distribution of Age, Income, and Spending Score

> Performed gender-based analysis

> Identified relationships using correlation

3️⃣ Data Visualization

> Histograms and distribution plots

> Scatter plots (Income vs Spending Score)

> Pair plots for feature relationships

4️⃣ Customer Segmentation (Core Part 🔥)

> Applied K-Means Clustering

> Identified optimal number of clusters using Elbow Method

> Segmented customers into meaningful groups
🤖 Machine Learning Model

> Algorithm Used: K-Means Clustering

> Type: Unsupervised Learning
📊 Key Insights

> Identified high-value customers with high spending scores

> Found that income does not always correlate with spending

> Discovered distinct customer groups such as:

> High Income – High Spending (VIP Customers)

> High Income – Low Spending (Potential Customers)

> Low Income – High Spending (Impulse Buyers)

> Low Income – Low Spending (Low Engagement Customers)
