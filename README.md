# Clustering with K-Means and Agglomerative Hierarchical Clustering

This project demonstrates unsupervised machine learning techniques using **K-Means Clustering** and **Agglomerative Hierarchical Clustering**. The notebook includes data preprocessing, clustering, visualization, and evaluation using the **Elbow Method** (based on **Sum of Squared Errors**) for K-Means.

## 📁 File

- `Unsupervised.ipynb`: Jupyter Notebook that performs clustering analysis on a dataset using K-Means and Agglomerative Clustering.

## 🗂 Dataset Used

**Mall Customers Dataset**  
This dataset contains demographic and behavioral information about mall customers and includes the following features:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

### 📌 Features Used for Clustering:
- **Age**
- **Annual Income (k$)**

The notebook performs clustering based on the relationship between **Age** and **Annual Income**, helping to identify customer segments like young high earners, older low earners, etc.

## 🧠 Algorithms Used

### 1. K-Means Clustering
- Divides data into `k` clusters by minimizing the **Sum of Squared Errors (SSE)**.
- Uses the **Elbow Method** to find the optimal number of clusters.
- Visualizes the results with scatter plots and shows cluster centroids.

### 2. Agglomerative Hierarchical Clustering
- A bottom-up hierarchical clustering technique.
- Uses a **dendrogram** to visualize the merging of clusters and help select the number of clusters.
- Supports different linkage criteria (default used: `ward`).

## 🧪 Features

- Data preprocessing and scaling
- Clustering using both K-Means and Hierarchical Clustering
- Optimal cluster selection using SSE (Elbow Method)
- Visualization of clusters and dendrogram
- Comparison between clustering methods

## 📦 Requirements

Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
