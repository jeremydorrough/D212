# Customer Segmentation with K-Means Clustering

This repository contains the code and documentation for a k-means clustering project that segments telecom customers based on their tenure and other behavioral and demographic characteristics. This project was submitted as part of the D212 - Data Mining II course at Western Governors University.

## 🔍 Project Overview

**Objective:**  
To identify distinct customer segments using k-means clustering based on tenure and related features, with the aim of informing business decisions and improving customer retention.

## 📁 Files

- `Jeremy_Dorrough_D212_Task_1_Python_Jupyter_Notebook.ipynb`: Full Jupyter Notebook with data preprocessing, visualization, clustering, and evaluation steps.
- `preprocessed_data.csv`: Cleaned dataset used for clustering.
- `Jeremy_Dorrough_D212_Task_1_Performance_Assessment.docx`: Full performance assessment with detailed methodology, evaluation, and reflections.

## 📊 Features Used for Clustering

- `Tenure`
- `Income`
- `Age`
- `Children`
- `MonthlyCharge`
- `Bandwidth_GB_Year`

## 🛠️ Technologies Used

- Python
- pandas, numpy, scipy
- scikit-learn (KMeans, silhouette_score)
- matplotlib, seaborn
- Jupyter Notebook

## 🧹 Data Preprocessing Steps

1. Removed duplicates and missing values
2. Removed outliers using z-score filtering
3. Standardized features using `StandardScaler`
4. Exported cleaned dataset to `preprocessed_data.csv`

## 📈 Clustering Process

- Used the **Elbow Method** to determine optimal `k = 2`
- Applied **KMeans** clustering
- Visualized clusters across all features with centroids
- Evaluated clustering with a **Silhouette Score** of `0.30`

## 📌 Key Insights

- Two clear customer segments were found.
- A tenure gap at 25–40 months emerged, suggesting possible churn or behavior changes.
- Recommendations include segment-specific marketing, pricing, and retention strategies.

## 🎓 Author

Jeremy Dorrough  
Western Governors University  

## 📚 References

- [scikit-learn documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [Real Python - K-Means Clustering](https://realpython.com/k-means-clustering-python/)
- [Machine Learning Plus - Scatter Plots](https://www.machinelearningplus.com/plots/python-scatter-plot/)
