# 📊 Telecom Customer Intelligence System

An end-to-end Machine Learning project that integrates **Clustering, Classification, and Regression** to analyze telecom customer data and extract actionable business insights.  
The project is implemented using **scikit-learn Pipelines** to ensure clean preprocessing, prevent data leakage, and support production-ready workflows.

---

## 🚀 Project Overview

Telecom companies face challenges such as customer churn, lack of customer segmentation, and difficulty in forecasting revenue.  
This project addresses these challenges by building a unified Machine Learning system that:

- Segments customers using clustering
- Predicts customer churn using classification
- Estimates monthly charges using regression

---

## 🎯 Objectives

- Perform customer segmentation using unsupervised learning
- Predict customer churn using supervised classification
- Estimate customer monthly charges using regression
- Build all models using pipeline-based architecture
- Compare model performance using appropriate evaluation metrics

---

## 📁 Dataset

- **Source:** Telco Customer Churn Dataset (Kaggle)
- **Downloaded using:** `kagglehub`
- **Dataset Link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Dataset Download Code

```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("blastchar/telco-customer-churn")

print("Path to dataset files:", path)
```
---

# 🧹 Data Preprocessing

- Handled missing values and data type inconsistencies

- Removed irrelevant features such as customer ID

- Scaled numerical features using StandardScaler

- Encoded categorical features using One-Hot Encoding

- Used ColumnTransformer and Pipelines for clean preprocessing

---

# 🧠 Machine Learning Models

**1️⃣ Clustering – Customer Segmentation**

- Algorithm: KMeans

- Evaluation Metric: Silhouette Score

- Goal: Identify distinct customer segments based on behavior

**2️⃣ Classification – Churn Prediction**

- Algorithm: Random Forest Classifier

- Evaluation Metrics: Accuracy, Precision, Recall, F1-score

- Goal: Predict whether a customer will churn

**3️⃣ Regression – Monthly Charges Prediction**

- Algorithm: Linear Regression

- Evaluation Metrics: RMSE, R² Score

- Goal: Estimate customer monthly revenue

---

# 📊 Model Performance Evaluation

- Classification performance evaluated using accuracy and classification report

- Regression performance evaluated using RMSE and R² score

- Clustering performance evaluated using silhouette score

- Bar charts used for visual comparison of model performance

---

# 🛠️ Tools & Technologies

- Programming Language: Python

- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib

- Techniques: Machine Learning Pipelines, Feature Engineering, Model Evaluation

---

# 💼 Business Impact

- Helps telecom companies identify high-risk churn customers

- Supports targeted retention and marketing strategies

- Improves revenue forecasting and planning

- Enables data-driven decision-making

---

# 🔮 Future Enhancements

- Hyperparameter tuning using GridSearchCV

- Interactive dashboard using Streamlit

- Model deployment using REST APIs

- Automated insight generation using LLMs

---

# ⭐ Acknowledgements

- Kaggle for providing the dataset

- Scikit-learn documentation and community

---

# 👤 Author

**Mohammed Hayath RK** |
Data Science & Analytics Enthusiast
