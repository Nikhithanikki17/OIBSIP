# 💳 Credit Card Fraud Detection using Machine Learning

A Machine Learning project that detects fraudulent credit card transactions using classification algorithms and addresses the challenge of class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**. The project compares multiple models and evaluates them using appropriate metrics such as Precision, Recall, F1-Score, and ROC-AUC instead of relying only on accuracy.

---

## 📌 Project Objectives

- Analyze the credit card fraud dataset.
- Identify and visualize class imbalance.
- Perform Exploratory Data Analysis (EDA).
- Handle class imbalance using SMOTE.
- Train multiple Machine Learning models.
- Compare model performance.
- Evaluate models using Precision, Recall, F1-Score, and ROC-AUC.
- Analyze feature importance.
- Discuss real-world deployment and scalability.

---

## 📂 Dataset Information

**Dataset Name:** balanced_dataset.csv

This project uses a balanced version of the Credit Card Fraud Detection dataset created after applying SMOTE to address the severe class imbalance in the original dataset.

### Dataset Statistics

| Attribute | Value |
|-----------|------:|
| Total Transactions | 984 |
| Total Features | 32 |
| Target Variable | Class |
| Class Labels | 0 (Legitimate), 1 (Fraud) |


### Features

- **Time** – Seconds elapsed between transactions.
- **Amount** – Transaction amount.
- **V1–V28** – PCA-transformed anonymous numerical features.
- **Class**
  - 0 → Legitimate Transaction
  - 1 → Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Joblib
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value analysis
- Duplicate record removal
- Class imbalance visualization
- Fraud percentage calculation
- Transaction amount distribution
- Fraud vs Non-Fraud comparison
- Time-of-day fraud analysis

---

Therefore, this project evaluates models using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score

These metrics provide a much more reliable assessment for fraud detection.

---

## ⚙️ Data Preprocessing

- Loaded the dataset
- Checked missing values
- Removed duplicate records
- Standardized **Time** and **Amount**
- Performed Stratified Train-Test Split
- Applied **SMOTE** to balance the training dataset

---

## 🤖 Machine Learning Models

The following classification models were trained:

- Logistic Regression
- Random Forest Classifier

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

---

## 📊 Feature Importance

Random Forest feature importance was used to identify the most influential features contributing to fraud detection.

---

## 📈 Results

The Random Forest model outperformed Logistic Regression by achieving higher Recall and ROC-AUC while maintaining strong Precision, making it more suitable for fraud detection.

---

## ⚖️ Precision vs Recall

In fraud detection, **Recall** is more important than Accuracy because missing fraudulent transactions can result in significant financial losses.

Precision is also important because excessive false positives increase investigation costs.

An ideal fraud detection system maintains a balance between Precision and Recall.

---

## 🚀 Scalability

To handle millions of transactions per hour, the model can be deployed using:

- REST API
- Apache Kafka
- Apache Spark Streaming
- AWS / Azure / Google Cloud
- Load Balancer
- Docker
- Kubernetes

These technologies enable real-time fraud detection with high throughput and low latency.

---

## 📁 Project Structure

```
Fraud_Detection/
│
├── balenced_dataset.csv
├── credit_card_Fraud_Detection.ipynb
├── fraud_detection_model.pkl
└── README.md
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Fraud_Detection.git
```

Move into the project folder:

```bash
cd Fraud_Detection
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Fraud_Detection.ipynb
```

Run all cells.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
joblib
```

---

## 📚 Learning Outcomes

Through this project, I learned how to:

- Handle highly imbalanced datasets
- Perform Exploratory Data Analysis
- Apply SMOTE for class balancing
- Train multiple Machine Learning models
- Compare model performance
- Interpret Precision, Recall, F1-Score, and ROC-AUC
- Analyze feature importance
- Build scalable fraud detection systems

---

## 🎯 Conclusion

This project demonstrates an end-to-end Machine Learning pipeline for detecting fraudulent credit card transactions. By applying SMOTE to address class imbalance and evaluating models using Recall, Precision, F1-Score, and ROC-AUC, the solution provides a reliable approach for real-world fraud detection systems.

---

## 👩‍💻 Author

**Niharika Gokinapalli**

B.Tech – Computer Science and Engineering

---

⭐ If you found this project useful, feel free to star this repository.