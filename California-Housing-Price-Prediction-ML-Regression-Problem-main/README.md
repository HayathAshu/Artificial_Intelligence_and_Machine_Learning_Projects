# 🏡 California Housing Price Prediction  
Predicting median house values using Machine Learning (Regression Project)

---

## 🔶 Tech Stack  
![Python](https://img.shields.io/badge/Python-3.8+-orange?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Library-orange?logo=scikitlearn)

---

## 📌 Problem Statement  
The objective of this project is to build a machine learning regression model capable of predicting the **median house value** for districts in California based on various demographic, geographic, and housing-related features.  
Using the California Housing Dataset, the model must analyze factors such as **median income, housing age, number of rooms, population density, longitude, and latitude** to understand how each variable influences housing prices.  
The goal is to develop an accurate, data-driven predictive system that can assist in **real estate valuation, investment analysis, and understanding housing market trends** across California.

---

## 📌 Project Overview  
This project focuses on predicting **California house prices** using multiple features such as:

- Median Income  
- Housing Median Age  
- Total Rooms / Total Bedrooms  
- Population & Households  
- Latitude & Longitude  

The dataset is sourced from Kaggle and is widely used for regression problems.

🎯 **Goal:** Build, train, and evaluate ML models to predict *median_house_value*.

---


## 🎯 Objectives  

1. Load and explore the dataset  
2. Clean and preprocess the data  
3. Perform exploratory data analysis (EDA)  
4. Train and compare multiple regression models  
5. Evaluate model performance  
6. Identify the best model for accurate predictions  

---

## 📂 Dataset  
**Source:** Kaggle – *California Housing Prices Dataset*  
- https://www.kaggle.com/datasets/camnugent/california-housing-prices  

You can download it automatically using:

```python
import kagglehub

path = kagglehub.dataset_download("camnugent/california-housing-prices")
print("Path to dataset files:", path)
