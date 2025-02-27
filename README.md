# 🛒 eCommerce Transactions Analysis

## 📌 Project Overview
This project focuses on analyzing eCommerce transactions using data science techniques. The dataset includes customer profiles, product details, and transaction records. The analysis covers **Exploratory Data Analysis (EDA)**, **Lookalike Modeling**, and **Customer Segmentation using Clustering**.

## 📂 Files Included
- 📊 **Aayush_Shah_EDA.pdf** – EDA insights and business analysis.
- 📄 **Aayush_Shah_EDA.ipynb** – Jupyter Notebook with EDA code.
- 📈 **Aayush_Shah_Lookalike.csv** – Top 3 lookalike customers for the first 20 customers.
- 🔍 **Aayush_Shah_Lookalike.ipynb** – Lookalike model implementation.
- 🔢 **Aayush_Shah_Clustering.pdf** – Report on customer segmentation and clustering results.
- 📂 **Aayush_Shah_Clustering.ipynb** – Jupyter Notebook with clustering code.
- 📊 **customer_similarity.xlsx** – Customer similarity calculations for the lookalike model.

## 🔍 Tasks Performed
### 1️⃣ Exploratory Data Analysis (EDA)
- **Dataset Overview**: Customers (200 entries), Products (100 entries), Transactions (1000 entries).
- **Key Insights**:
  - South America has the highest number of customers (29%).
  - Books generate the highest sales (~$200,000), followed by Electronics, Clothing, and Home Decor.
  - South America also leads in spending (~$200,000), suggesting business expansion strategies.
  - High-value customers (top 10%) contribute 20% of revenue; retention strategies needed.
  - Customers are **not highly price-sensitive**, as all price ranges see significant purchases.

### 2️⃣ Lookalike Model
- Built a **Lookalike Model** to recommend similar customers based on profiles and purchase history.
- Used **customer and product features** to compute similarity scores.
- Generated a **Lookalike.csv** file with top 3 lookalike customers for the first 20 customers.

### 3️⃣ Customer Segmentation (Clustering)
- Applied **K-Means Clustering** with **4 clusters**.
- **Evaluation Metrics**:
  - **Davies-Bouldin Index (DBI):** 0.315 (indicating strong separation between clusters).
  - **Silhouette Score:** 0.784 (indicating well-defined clusters).
- **Cluster Insights**:
  - **Cluster 0 (Europe):** Moderate spending & quantity purchased.
  - **Cluster 1 (South America):** Highest spending & quantity purchased.
  - **Cluster 2 (North America):** Lowest spending & quantity purchased.
  - **Cluster 3 (Asia):** Moderate spending & quantity purchased.

## 🚀 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning** (KMeans, DBSCAN, Cosine Similarity, Clustering Metrics)
- **Jupyter Notebook** for implementation and visualization

