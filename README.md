# 🛒 E-Commerce Product Price Prediction Using Machine Learning

## 📘 Project Overview

This project aims to predict the prices of products in an e-commerce platform using machine learning. By analyzing features like category, brand, rating, and specifications, the model estimates a suitable price for each product. The goal is to support better pricing strategies for sellers and improve price transparency for consumers.

---

## 📌 Table of Contents
- 🌍 Societal and Industrial Impact
- 🎯 Objectives
- 🔍 Research Questions
- 🧠 Contributions
- 📦 Dataset
- 🛠️ Methodology
- 🤖 ML Models Used
- ❓ Why These Models?
- 📏 Evaluation Metrics
- ⚙️ Hyperparameter Tuning
- 🧪 Results & Insights
- 📂 Folder Structure
- 🚀 How to Run
- 📝 Report & Presentation

---

## 🌍 Societal and Industrial Impact

- Enables fair and competitive product pricing
- Builds consumer trust in e-commerce platforms
- Helps sellers optimize pricing to maximize profits
- Supports data-driven pricing strategies

---

## 🎯 Objectives

- Analyze how product features affect pricing
- Train ML models to predict product prices
- Evaluate model performance using regression metrics
- Provide pricing suggestions based on data insights

---

## 🔍 Research Questions

- **What** features influence product prices in e-commerce?
- **Why** is accurate price prediction important for platforms and users?
- **How** can ML models estimate realistic prices using available data?

---

## 🧠 Contributions

- Built a regression-based ML pipeline for price prediction
- Engineered features like category, brand, rating, etc.
- Compared multiple ML models for performance
- Generated actionable insights for pricing decisions

---

## 📦 Dataset

- **Type:** Secondary Dataset  
- **Source:** [Kaggle / Flipkart Product Data / Amazon](#)  
- **Key Columns:**  
  - Product Name  
  - Brand  
  - Category  
  - Rating  
  - Number of Reviews  
  - Product Specs  
  - Selling Price (Target)

---

## 🛠️ Methodology

1. Data Cleaning and Preprocessing
2. Feature Encoding
3. Train-Test Split
4. Model Training (Regression)
5. Evaluation & Tuning
6. Visualization and Insights

---

## 🤖 ML Models Used

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor (optional)

---

## ❓ Why These Models?

- Effective for tabular regression tasks  
- Easy to interpret  
- Handle numerical and categorical features  
- Tree-based models capture non-linear patterns

---

## 📏 Evaluation Metrics

- R² Score (Accuracy of prediction)  
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)

---

## ⚙️ Hyperparameter Tuning

- Random Forest: `n_estimators`, `max_depth`  
- Decision Tree: `max_depth`, `min_samples_split`  
- XGBoost: `learning_rate`, `n_estimators`, `max_depth`  

Tuned using GridSearchCV and manual testing.

---

## 🧪 Results & Insights

- Random Forest achieved the highest R² Score
- Top 3 price-influencing features: Brand, Category, Rating
- Price outliers were filtered to improve model accuracy

---

## 📂 Folder Structure

