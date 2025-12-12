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
- https://archive.ics.uci.edu/dataset/45/heart+disease
- Real clinical heart disease dataset  
- Mixed numerical and categorical medical features  
- Binary target: **Heart Disease (0 = No, 1 = Yes)**  

---

## 🧠 Model Architecture Diagram
<p align="center">
  <img src="images/heartfinal.png" width="650" height="550>
</p>

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
  <img src="images/histogram.png" width="750">
</p>

<p align="center">
  <img src="images/piechart.png" width="750">
</p>

<p align="center">
  <img src="images/heatmap.png" width="750">
</p>

<p align="center">
  <img src="images/boxplot.png" width="750">
</p>

EDA focuses on **visual understanding** of feature distributions and relationships.

Includes:
- Target class distribution  
- Feature histograms and boxplots  
- Correlation heatmap  
- Clinical interpretation of **maximum heart rate** and **ST depression**

---

## 📐 Statistical Analysis

<p align="center">
  <img src="images/chisquare.png" width="650">
</p>

<p align="center">
  <img src="images/pairwise.png" width="750">
</p>

To support EDA findings:
- Correlation analysis  
- Independent **t-tests** for numerical variables  
- **Chi-square tests** for categorical variables  

These tests help distinguish **statistical association** from **predictive importance**.

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
  <img src="images/roc.png" width="750">
</p>

### Decision Tree Feature Importance
<p align="center">
  <img src="images/dt.png" width="650">
</p>

### Decision Boundary Visualization
<p align="center">
  <img src="images/boundary.png" width="650">
</p>

Evaluation includes:
- Accuracy, Precision, Recall, and F1-score  
- ROC curves and AUC  
- Feature importance for tree-based models  
- Overfitting analysis across different tree depths  

---

## 🔍 Inference
The trained models can be used to **infer heart disease risk for new patient records** by passing clinical attributes through the final trained pipeline.

This demonstrates how machine learning models can support **clinical decision-making**, while emphasizing that such systems are **assistive tools** and not replacements for professional medical diagnosis.

---

## 🧠 Insights & Conclusions
- **Maximum heart rate** and **ST depression** consistently emerge as the strongest predictors.
- Some variables show statistical significance but limited contribution in multivariate models.
- **Logistic Regression** offers stable performance and high interpretability.
- **Decision Trees** capture non-linear patterns but may overfit at higher depths.
- Integrating **EDA, statistics, and machine learning** produces more reliable and explainable predictions.

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
```
---

## 📚 Bibliography

Scikit-learn. (n.d.): https://scikit-learn.org/stable/modules/model_evaluation.html#roc-metrics  
Scikit-learn. (n.d.): https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression  
James, G., Witten, D., Hastie, T., & Tibshirani, R. (2021): https://www.statlearning.com/  
World Health Organization: https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)  
Alotaibi, F. S. (2023): https://pmc.ncbi.nlm.nih.gov/articles/PMC10378171/  
Sharma, R., & Kumar, S. (2024): https://pmc.ncbi.nlm.nih.gov/articles/PMC12614364/  
Kumar, A., & Patel, D. (2022): https://www.researchgate.net/publication/368848738_Heart_Disease_Prediction_Using_Logistic_Regression  
Zhang, Y., et al. (2025): https://www.nature.com/articles/s41598-025-93675-1  

