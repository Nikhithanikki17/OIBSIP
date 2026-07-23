# Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview

This project applies **K-Means Clustering** to segment an e-commerce company's customers based on their purchasing behavior. Customer segmentation helps businesses identify different customer groups and create personalized marketing strategies to improve customer satisfaction, retention, and sales.

---

## 🎯 Objective

- Analyze customer purchasing behavior.
- Perform data preprocessing and feature selection.
- Apply K-Means clustering to group similar customers.
- Visualize customer segments.
- Generate business insights and marketing recommendations.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains customer information such as:

- Customer ID
- Age
- Gender
- Annual Income
- Spending Score
- Purchase Frequency
- Average Order Value
- Customer Lifetime Value
- Total Purchases
- Last Purchase Days
- Product Preferences
- Loyalty Tier
- Customer Satisfaction Score
- And other customer behavioral features.

---

## 📊 Project Workflow

1. Load the dataset.
2. Inspect the dataset structure.
3. Handle missing values.
4. Perform descriptive statistical analysis.
5. Select key behavioral features (Recency, Frequency, Monetary).
6. Standardize selected features using StandardScaler.
7. Determine the optimal number of clusters using the Elbow Method.
8. Apply K-Means Clustering.
9. Visualize customer clusters using scatter plots.
10. Profile each customer segment.
11. Visualize the number of customers in each cluster.
12. Generate business insights and marketing recommendations.

---

## 📈 Features Used

- Last Purchase Days (Recency)
- Purchase Frequency
- Customer Lifetime Value (Monetary)

These features represent the RFM (Recency, Frequency, Monetary) model for customer segmentation.

---

## 📉 Visualizations

- Elbow Method
- Customer Cluster Scatter Plot
- Recency vs Purchase Frequency Plot
- Customers per Cluster Bar Chart

---

## 💡 Business Insights

The clustering model identifies different customer groups such as:

- High-value loyal customers
- Frequent shoppers
- Occasional customers
- At-risk or inactive customers

These segments help businesses:

- Design personalized marketing campaigns.
- Improve customer retention.
- Increase customer lifetime value.
- Offer targeted promotions.
- Enhance customer engagement.

---

## 🚀 Results

The K-Means clustering algorithm successfully segmented customers into distinct groups based on purchasing behavior. These customer segments provide valuable insights for targeted marketing and strategic business decision-making.

---

## 📁 Project Structure

```
Customer-Segmentation/
│
├── Customer_Segmentation.ipynb
├── customer_segmentation.csv
├── README.md
└
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/customer-segmentation.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all notebook cells.

---

## 📚 Future Improvements

- Apply Hierarchical Clustering.
- Compare with DBSCAN clustering.
- Use PCA for dimensionality reduction.
- Build an interactive dashboard using Streamlit or Power BI.

---

## 👩‍💻 Author

**Niharika Gokinapalli**

B.Tech CSE Student

Interested in Data Analytics, Machine Learning, and Artificial Intelligence.

---

## ⭐ Acknowledgements

- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib & Seaborn
- Kaggle Datasets