 Customer Segmentation using K-Means

 Project Overview
This project is part of my **AI & ML Internship**.  
The objective was to segment customers based on their **Annual Income** and **Spending Score** using the **K-Means Clustering algorithm**.

 Objectives
- Understand and apply **Unsupervised Learning**.
- Use **K-Means** to cluster customers with similar purchasing behavior.
- Visualize the customer segments and analyze their characteristics.

 Tools & Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Steps Followed
1. Imported the dataset (`Mall_Customers.csv`).
2. Explored the dataset (checked rows, columns, and info).
3. Selected features: `AnnualIncome` and `SpendingScore`.
4. Visualized data distribution using scatter plot.
5. Applied **Elbow Method** to find the best `K`.
6. Trained **K-Means** model with chosen clusters.
7. Visualized clusters with different colors and centroids.
8. Analyzed cluster characteristics.

 Results
- The **Elbow Method** suggested **K = 5** as the optimal number of clusters.
- Customers were segmented into 5 groups:
  - High income, high spending (premium customers)
  - High income, low spending (savers)
  - Low income, high spending (potential impulse buyers)
  - Low income, low spending (budget customers)
  - Middle income, average spending

Learning Outcomes
- Learned how **unsupervised learning** groups data without labels.
- Understood the concept of **inertia**, **Elbow Method**, and **Silhouette Score**.
- Gained hands-on practice in **data preprocessing, visualization, and clustering**.

 Visualizations
- Elbow Curve
- Customer Segmentation Scatter Plot with Centroids

---

✅ This task helped me strengthen my understanding of **Clustering & Unsupervised ML** in real-world datasets.
