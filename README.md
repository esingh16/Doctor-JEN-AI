# 🩺🤖 DOCTOR JEN-AI 🤖🩺
**(Heart Disease Prediction System)**  

## 📌 Project Topic
This project predicts Heart Disease using data science tools and machine learning models. The system uses algorithms including Decision Trees, Logistic Regression, Random Forest, and Support Vector Machines (SVM) to provide accurate predictions based on medical data.

## 👥 Group Members
- Eshan Singh (UID: 122115569)
- Nicole Miranda (UID: 116014687)
- Jamiya Kirkland (UID: 122328396)
# Doctor-JEN-AI 🫀  
*A Data Science Tutorial on Heart Disease Prediction (DATA 602 Final Project)*

Welcome to **Doctor-JEN-AI**, my DATA 602 final project hosted on GitHub Pages.  
This project walks through an end-to-end data science workflow to predict **heart disease** using real clinical data.

You can view the full interactive tutorial here:

👉 **Live Project:** https://esingh16.github.io/

---

## 📌 Project Overview

This tutorial is designed to be accessible to readers with **no data science background**, while still offering depth for those familiar with analytics and machine learning.

It covers:

- **Problem framing:** Why heart disease prediction matters.
- **Data understanding & cleaning:** Renaming columns, handling missing values, fixing types, and removing duplicates.
- **Exploratory Data Analysis (EDA):**
  - Pie charts for class and feature distributions  
  - Histograms, boxplots, and correlation heatmaps  
  - Interpretation of key clinical features like **max heart rate** and **ST depression**
- **Statistical analysis:**
  - Correlation analysis  
  - T-tests  
  - Chi-Square tests for categorical associations  

---

## 🤖 Machine Learning Models

The project implements and compares:

- **Logistic Regression**
  - Baseline, interpretable model  
  - Train/test split with scaling  
  - Accuracy, classification report, ROC curve, and AUC

- **Decision Tree Classifier**
  - Non-linear decision rules  
  - Hyperparameter exploration over different `max_depth` values  
  - Feature importance visualization  
  - ROC curves for multiple depths

Additional elements:

- **Decision boundary plots** using `max_heart_rate` and `ST_depression`
- **ROC curve analysis** comparing models and depths
- A **“current day” prediction** scenario using the model trained on previous days’ data

---

## 📊 Key Insights

- **Max heart rate** and **ST depression** consistently emerge as strong predictors of heart disease.
- Some features show statistical association (e.g., gender), but limited predictive power once all variables are modeled together.
- Logistic Regression provides **strong, stable performance** and high AUC.
- Decision Trees help visualize **non-linear interactions** and feature importance, but may overfit at high depth.
- The project demonstrates how combining **EDA, statistics, and ML** leads to a more complete understanding of heart disease risk.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Google Colab**
- **GitHub Pages** for hosting

---

## 📁 Files in This Repository

- `index.html` – Rendered HTML version of the full tutorial (served at https://esingh16.github.io/)
- `Heart_Disease_Project.ipynb` – Original Jupyter/Colab notebook

---

