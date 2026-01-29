# Clustering_Creditcard
## Project Overview

This project presents an analysis and segmentation of customer credit card usage behavior by applying **clustering techniques** to the **CC GENERAL Dataset** from Kaggle. The objective is to uncover hidden behavioral patterns in customer transaction data, including balance levels, credit utilization, payment behavior, installment purchases, and cash advance usage.

The analytical pipeline covers **data preparation**, **missing value imputation**, **feature space construction**, and **dimensionality reduction** using **PCA** and **UMAP**. Multiple clustering algorithms are evaluated, including **K-Means**, **Agglomerative Clustering**, **Gaussian Mixture Models (GMM)**, and **DBSCAN**.

Model performance is assessed using standard clustering evaluation metrics: **Silhouette Score**, **Calinski–Harabasz Index**, and **Davies–Bouldin Index**, along with a **composite score** to summarize overall effectiveness across configurations. The selected optimal model is then used for **cluster profiling**, revealing distinct customer segments such as high credit utilization with consistent repayment, heavy cash advance users, low-activity customers, and full-payment users.

The results provide behavioral insights and strategic recommendations to support **marketing strategies** and **risk management** in financial institutions.
