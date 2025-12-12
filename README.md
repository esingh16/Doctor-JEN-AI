# 🩺🤖 DOCTOR JEN-AI  
**Heart Disease Prediction System**  
*DATA 602 – Final Project Tutorial*

🔗 **Live Tutorial:** https://esingh16.github.io/Doctor-JEN-AI/

---

## 👥 Team Members
- **Eshan Singh** (UID: 122115569)  
- **Nicole Miranda** (UID: 116014687)  
- **Jamiya Kirkland** (UID: 122328396)

---

## 🎯 Problem Statement
Heart disease is one of the leading causes of death worldwide.  
This project builds a data-driven system that predicts the presence of heart disease using patient medical attributes.

The goal is to demonstrate a complete **end-to-end data science workflow**, from raw clinical data to interpretable machine-learning predictions.

---

## 📂 Dataset
- Real-world heart disease dataset
- Combination of numerical and categorical clinical features
- Binary target variable indicating heart disease presence

---

## 🔧 Data Preparation
- Column renaming for clarity  
- Handling missing values  
- Correcting data types  
- Removing duplicate records  
- Feature scaling where required  

All preprocessing steps are shown directly in code.

---

## 📊 Exploratory Data Analysis (EDA)
EDA focuses on visual understanding of the data.

Includes:
- Class distribution plots  
- Feature-wise histograms and boxplots  
- Correlation heatmap  
- Clinical interpretation of:
  - Maximum heart rate  
  - ST depression  
  - Age and gender patterns  

---

## 📐 Statistical Analysis
Statistical tests are used to support visual findings:

- Correlation analysis  
- Independent t-tests for numerical features  
- Chi-square tests for categorical features  

These tests help distinguish statistical association from predictive importance.

---

## 🤖 Machine Learning Models
The following models are trained, evaluated, and compared:

- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest**  
- **Support Vector Machine (SVM)**  

Each model is evaluated using consistent metrics and visualizations.

---

## 📈 Model Evaluation & Visualization
- Accuracy, precision, recall, and F1-score  
- ROC curves and AUC comparisons  
- Decision boundary visualizations  
- Feature importance plots for tree-based models  
- Overfitting analysis across different tree depths  

---

## 🧠 Key Insights & Conclusions
- Maximum heart rate and ST depression are consistently strong predictors of heart disease.
- Some features show statistical association but limited predictive power when combined with others.
- Logistic Regression provides stable performance with strong interpretability.
- Decision Trees capture non-linear patterns but may overfit at higher depths.
- Combining EDA, statistical testing, and machine learning leads to more reliable medical insights.

This tutorial allows:
- A non-technical reader to understand the medical significance of features.
- A technical reader to understand model behavior and trade-offs.

---

## 🛠️ Tools & Libraries
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

