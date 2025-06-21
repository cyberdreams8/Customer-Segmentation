# Customer-Segmentation
# 🧠 Customer Segmentation using K-Means Clustering

This project performs customer segmentation using unsupervised machine learning. It helps businesses identify distinct customer groups based on their annual income and spending score, enabling data-driven marketing strategies.

## 📁 Project Overview

- **File**: `Customer_Segmentation.ipynb`  
- **Goal**: Segment customers into meaningful groups using **K-Means Clustering**
- **Dataset Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## 📊 What the Notebook Covers

- ✅ Exploratory Data Analysis (EDA)
- ✅ Data cleaning and preprocessing
- ✅ K-Means clustering
- ✅ Elbow method to determine optimal number of clusters
- ✅ Cluster visualization (2D)


## 🛠️ Requirements

To run the notebook, install the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


🔍 Clustering Technique
Algorithm: K-Means

Optimal k: Determined using the Elbow Method

Visualization: Scatter plots of Annual Income vs Spending Score, colored by cluster

📈 Output
Visualized customer clusters

Business-friendly interpretation of each segment

💡 Use Cases
Targeted advertising

Product personalization

Customer loyalty analysis

📌 Sample Insight
For example:

One cluster may represent young high-income high-spenders

Another may represent low-income budget-conscious customers

These insights can drive business decisions.
