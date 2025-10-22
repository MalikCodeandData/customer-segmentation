# Customer Segmentation Using KMeans Clustering

## Overview

This project focuses on segmenting customers from a marketing campaign dataset to better understand different customer groups based on their demographics and purchasing behavior. By grouping customers with similar characteristics, businesses can tailor their marketing strategies to target the right audience more effectively.

Customer segmentation is a fundamental step in modern marketing and data-driven business decisions. This analysis applies **KMeans clustering**, an unsupervised machine learning technique, to discover meaningful customer groups without any prior labels.

---

## What I Did

- **Data Cleaning & Preprocessing:** Handled missing values, converted dates to datetime objects, and engineered new features such as customer tenure and total spending.
- **Feature Engineering:** Created meaningful variables like total amount spent across product categories, customer age, number of children in the household, and the total number of marketing campaigns accepted by each customer.
- **Exploratory Data Analysis (EDA):** Explored data distributions and relationships between key features to better understand the customer base.
- **Clustering with KMeans:** Applied the elbow method to determine the optimal number of clusters, then segmented customers into distinct groups based on selected features.
- **Cluster Profiling:** Analyzed the characteristics of each cluster to understand differences in demographics and spending behavior.

---

## Key Insights

- Customers naturally group into distinct segments based on their age, income, spending habits, and responsiveness to marketing campaigns.
- Some clusters represent high-spending, loyal customers, while others include budget-conscious or newer customers.
- Understanding these segments enables businesses to design targeted marketing campaigns, improve customer retention, and allocate resources efficiently.

---

## Why It Matters for Business

Customer segmentation helps companies move beyond a “one size fits all” marketing approach. By identifying and understanding different customer groups, businesses can:

- Personalize offers and communication to increase engagement and sales.
- Allocate marketing budget more effectively by focusing on high-potential segments.
- Enhance customer satisfaction through relevant products and services.
- Improve customer lifetime value and loyalty.

This project demonstrates how data science techniques can turn raw customer data into actionable business insights, providing a foundation for smarter, data-driven marketing strategies.

---

## How to Use This Repo

- **`customer_culstering_project.ipynb`**: Contains the complete step-by-step analysis, from data loading to clustering and visualization.
- **`Marketing_Campaign.csv`**: Cleaned dataset used for the analysis.
- Feel free to explore the notebook, rerun the analysis, or adapt the code for similar customer datasets.

---

## Technologies & Libraries Used

- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Scikit-learn for machine learning (KMeans clustering)
- Jupyter Notebook for interactive analysis

---

## Author

Mehwish Malik  
Data enthusiast passionate about turning data into impactful insights.

---

Thank you for checking out this project!  
If you have any questions or want to collaborate, feel free to reach out.
