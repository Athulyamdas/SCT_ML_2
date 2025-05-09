# Mall Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers of a retail store based on their purchasing behavior. The objective is to group similar customers together to help the business understand their customer base and plan targeted marketing strategies.

---

## 📊 Dataset

The dataset used is the [Mall Customers dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial), which contains information about 200 customers, including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## 🧠 Problem Statement

**Goal:**  
Group customers into segments based on their **Annual Income** and **Spending Score**, using K-Means Clustering.

---
## Explanation

In this project, we applied K-Means Clustering, an unsupervised machine learning algorithm, to segment mall customers based on their purchasing behavior. We began by preprocessing the dataset, where we dropped the irrelevant CustomerID column and selected two key features: Annual Income (k$) and Spending Score (1-100) for clustering. We then used data visualization to understand the distribution of these features and applied the Elbow Method to determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS). After identifying the best value for k, we built a K-Means model to group customers into clusters. Finally, we visualized the customer segments in a scatter plot, clearly showing distinct clusters along with their centroids, which helps businesses understand different customer groups for targeted marketing.
