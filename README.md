# 🧠 Credit Card Customer Segmentation using K-Means Clustering

Segmenting customers is at the heart of personalized finance. In this project, I used **K-Means Clustering** to identify distinct customer groups based on their **credit card usage behavior**.

This analysis provides actionable insights for businesses — such as **targeted marketing**, **risk management**, and **customer retention** — by transforming raw credit card data into well-defined customer segments.

---

## 🚀 Project Highlights

- 📊 **Data:** Real-world credit card usage data with features like purchases, payments, credit limit, cash advances, etc.
- 🤖 **Model:** Unsupervised machine learning using **K-Means Clustering**
- 🔍 **Techniques:** Feature scaling, Elbow method, Silhouette score, PCA visualization
- 🎯 **Goal:** Understand spending behavior and payment patterns to help credit card companies make better business decisions

---

## 📌 Key Results

After applying K-Means with `k=4`, we identified **4 distinct customer segments**:

| Cluster | Profile |
|--------|---------|
| 🔵 **Cluster 0** | High balance, high cash advances, low full payments – likely high-risk users |
| 🟢 **Cluster 1** | Low balance, low purchases – inactive or low-usage customers |
| 🟡 **Cluster 2** | High purchases, good payment behavior – ideal loyal customers |
| 🟠 **Cluster 3** | Low spending, high cash advances – possibly financially stressed |

These insights can be directly applied to:
- ✅ Tailored credit offers
- ✅ Loyalty rewards
- ✅ Fraud and risk flagging
- ✅ Optimizing customer experience

---

## 🛠 Tech Stack

- `Python`
- `pandas`, `numpy` – Data manipulation
- `scikit-learn` – Clustering, PCA, metrics
- `matplotlib`, `seaborn` – Visualization

---



