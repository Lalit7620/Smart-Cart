# 🛒 SmartCart Customer Segmentation using Unsupervised Machine Learning

## 📌 Overview

SmartCart is an e-commerce customer segmentation project built using **Unsupervised Machine Learning**. The objective is to group customers based on their purchasing behavior, demographics, and engagement patterns to help businesses create personalized marketing strategies and improve customer retention.

This project applies data preprocessing, feature engineering, clustering algorithms, dimensionality reduction, and cluster characterization to discover meaningful customer segments.

---

## 🎯 Problem Statement

Businesses often have large amounts of customer data but lack insights into different customer behaviors. Treating every customer the same leads to ineffective marketing and missed opportunities.

The goal of this project is to segment customers into meaningful groups based on their purchasing habits and demographic information using clustering algorithms.

---

## 📂 Dataset

- **Total Customers:** 2240
- **Original Features:** 22
- **Type:** Customer Demographics & Purchase History

The dataset includes:

- Customer demographics
- Income
- Education
- Marital status
- Purchase history
- Website activity
- Campaign responses
- Customer complaints

---

# 🚀 Project Workflow

### 1. Data Cleaning
- Handled missing values
- Removed unnecessary columns
- Treated outliers

### 2. Feature Engineering
Created new features including:

- Age
- Customer Tenure
- Total Spending
- Total Children
- Living_With

### 3. Data Preprocessing
- One-Hot Encoding
- Feature Scaling using StandardScaler

### 4. Dimensionality Reduction
Applied **Principal Component Analysis (PCA)** for visualization.

### 5. Clustering
Implemented and compared:

- K-Means Clustering
- Agglomerative Clustering

### 6. Cluster Evaluation
Used:

- Elbow Method (WCSS)
- Silhouette Score

to determine the optimal number of clusters.

### 7. Cluster Characterization
Analyzed each customer segment using business metrics such as:

- Income
- Total Spending
- Web Purchases
- Store Purchases
- Catalog Purchases
- Website Visits
- Recency
- Campaign Response
- Customer Complaints

Provided business recommendations for every customer segment.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kneed
- Jupyter Notebook

---

# 📚 Machine Learning Concepts Used

- Data Cleaning
- Feature Engineering
- One-Hot Encoding
- Standard Scaling
- Principal Component Analysis (PCA)
- K-Means Clustering
- Agglomerative Clustering
- Elbow Method
- Silhouette Score
- Cluster Profiling

---

# 📁 Project Structure

```
SmartCart/
│
├── SmartCart.ipynb
├── smartcart_customers.csv
├── requirements.txt
└── README.md
```

---

# 📊 Results

- Successfully segmented customers into **5 meaningful customer groups**
- Compared K-Means and Agglomerative Clustering
- Evaluated cluster quality using Silhouette Score
- Characterized each cluster using customer behavior and demographic information
- Suggested business strategies for targeted marketing

---

# 📈 Cluster Summary

| Cluster | Customer Type | Description |
|----------|---------------|-------------|
| Cluster 0 | Regular Customers | Medium-income customers with moderate spending and frequent use of discounts. |
| Cluster 1 | Premium Customers | High-income, high-spending customers who purchase frequently across all channels. |
| Cluster 2 | Loyal Customers | High-value customers with consistent purchasing behavior and strong engagement. |
| Cluster 3 | Low-Value Customers | Low-income customers with minimal spending and fewer purchases. |
| Cluster 4 | Budget Customers | Price-sensitive customers with lower spending but regular website activity. |

---

# 💡 Business Recommendations

- Reward premium customers with loyalty programs.
- Provide personalized product recommendations to loyal customers.
- Offer discounts and promotional campaigns to budget customers.
- Target inactive customers with re-engagement campaigns.
- Use customer segmentation for personalized marketing and improved retention.

---

# 📷 Project Visualizations

The notebook includes:

- Correlation Heatmap
- PCA 3D Visualization
- Elbow Curve
- Silhouette Score Analysis
- K-Means Cluster Visualization
- Agglomerative Cluster Visualization

---

# ⚙️ Requirements

Install the required libraries:

```bash
pip install -r requirements.txt
```

or

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kneed jupyter
```

---

# 🔮 Future Improvements

- Deploy the model using Streamlit
- Build a FastAPI backend for real-time predictions
- Create an interactive dashboard using Plotly
- Automate customer segmentation for new customer data
- Experiment with DBSCAN and Gaussian Mixture Models

---

# 👨‍💻 Author

**Lalit Kumar Sahoo**

Aspiring AI/ML Engineer

GitHub: https://github.com/Lalit7620

---

⭐ If you found this project helpful, feel free to star the repository.
