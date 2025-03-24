# Customer Segmentation using KMeans Clustering

This project uses machine learning to segment customers based on their age, annual income, and spending score. It helps businesses understand different customer types and tailor their marketing strategies accordingly.

# Files Included

- `data/Customer_Segments_KMeans.csv`: Final dataset with cluster labels and segment names.
- `models/kmeans_model.pkl`: Trained KMeans model (k=6).
- `models/scaler.pkl`: Scaler used to preprocess data before clustering.
- `notebooks/customer_segmentation_analysis.ipynb`: Full code for preprocessing, clustering, evaluation, and visualization.

# Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn (KMeans, PCA, DBSCAN, StandardScaler)
- Matplotlib
- Joblib

# Business Use Case
Customer segmentation helps marketing teams:
- Target the right customer group
- Optimize campaigns based on behavior
- Personalize offers for high-value or under-engaged customers

# How to Use

1. Clone the repo:
```bash
git clone https://github.com/yourusername/customer-segmentation-project.git
cd customer-segmentation-project
