# 🩺🤖 DOCTOR JEN-AI  
**Heart Disease Prediction System**  
*DATA 602 – Final Project Tutorial*

🔗 **Live Tutorial:** https://esingh16.github.io/Doctor-JEN-AI/

---

## 👥 Team
- **Eshan Singh** (UID: 122115569)  
- **Nicole Miranda** (UID: 116014687)  
- **Jamiya Kirkland** (UID: 122328396)

---

## 🎯 Problem Definition
Heart disease is a major global health concern.  
This project develops a **machine-learning–based prediction system** to identify the presence of heart disease using patient clinical data.

**Objective:**  
Demonstrate a complete **end-to-end data science pipeline** with emphasis on **code, visualizations, and interpretable insights**.

---

## 📂 Dataset
- Real clinical heart disease dataset  
- Mixed numerical and categorical medical features  
- Binary target: **Heart Disease (0 = No, 1 = Yes)**  

---

## 🔧 Data Preparation
- Renamed columns for interpretability  
- Handled missing values  
- Corrected data types  
- Removed duplicates  
- Applied feature scaling where required  

> All preprocessing steps are shown explicitly in code.

---

## 📊 Exploratory Data Analysis (EDA)

<p align="center">
  <img src="images/heatmap.png" width="750">
</p>

EDA focuses on **visual understanding** of feature distributions and relationships.

Includes:
- Target class distribution  
- Feature histograms and boxplots  
- Correlation heatmap  
- Clinical interpretation of **max heart rate** and **ST depression**

---

## 📐 Statistical Analysis

<p align="center">
  <img src="images/chisquare.png" width="650">
</p>

To support EDA findings:
- Correlation analysis  
- Independent **t-tests** for numerical variables  
- **Chi-square tests** for categorical variables  

These tests distinguish **statistical association** from **predictive importance**.

---

## 🤖 Machine Learning Models
The following models are implemented and compared:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest**
- **Support Vector Machine (SVM)**

Each model follows the same:
- Train/test split  
- Evaluation metrics  
- Visualization strategy  

---

## 📈 Model Performance & Visualization

### ROC Curve Comparison
<p align="center">
  <img src="images/roc_curves.png" width="750">
</p>

### Decision Tree Feature Importance
<p align="center">
  <img src="images/feature_importance.png" width="650">
</p>

### Decision Boundary Visualization
<p align="center">
  <img src="images/decision_boundary.png" width="650">
</p>

Evaluation includes:
- Accuracy, Precision, Recall, F1-score  
- ROC curves and AUC  
- Feature importance (tree-based models)  
- Overfitting analysis across tree depths  

---

## 🧠 Insights & Conclusions
- **Maximum heart rate** and **ST depression** consistently emerge as the strongest predictors.
- Some variables show statistical significance but limited contribution in multivariate models.
- **Logistic Regression** offers stable performance and high interpretability.
- **Decision Trees** capture non-linear patterns but overfit at higher depths.
- Integrating **EDA, statistics, and ML** produces more reliable and explainable predictions.

✔ A non-technical reader gains medical insight.  
✔ A technical reader gains modeling insight.

---

## 🛠️ Tools & Libraries
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

