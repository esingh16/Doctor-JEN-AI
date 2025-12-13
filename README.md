<div align="center">

<h1 style="font-size:48px;">
🩺🤖 <span style="color:#58a6ff;">DOCTOR</span> <span style="color:#7ee787;">JEN-AI</span>
</h1>

<h3 style="color:#c9d1d9;">
Heart Disease Prediction System <br>
DATA 602 – Final Project Tutorial
</h3>

<br/>

<img src="./images/beat.gif" width="420" alt="Heartbeat Animation"/>

<br/>

<span style="background:#238636; color:white; padding:6px 12px; border-radius:12px;">Python</span>
<span style="background:#1f6feb; color:white; padding:6px 12px; border-radius:12px;">Data Science</span>
<span style="background:#8957e5; color:white; padding:6px 12px; border-radius:12px;">Machine Learning</span>
<span style="background:#da3633; color:white; padding:6px 12px; border-radius:12px;">DATA 602</span>

</div>

---

## 👥 Team
- **Eshan Singh** *(UID: 122115569)*  
- **Nicole Miranda** *(UID: 116014687)*  
- **Jamiya Kirkland** *(UID: 122328396)*  

---

## 🎯 Problem Definition
> **Heart disease is one of the leading causes of mortality worldwide.**

This project presents an **end-to-end machine learning pipeline** that predicts the **presence of heart disease** using real patient clinical data.

✨ Focus areas:
- Clear **data exploration**
- **Statistical validation**
- Multiple **ML model comparisons**
- **Interpretability over black-box predictions**

---

## 📂 Dataset
🧬 **Clinical Heart Disease Dataset**
- Real-world medical attributes  
- Numerical + categorical features  
- Binary outcome:  
  - `0` → No heart disease  
  - `1` → Presence of heart disease  

---

## 🧠 Model Architecture
<p align="center">
  <img src="images/heartfinal.png" width="650" alt="Pipeline Diagram">
</p>

This diagram visually represents the **full workflow** from raw data to final inference.

---

## 🔧 Data Preparation
✔ Renamed columns for readability  
✔ Missing value handling  
✔ Data type correction  
✔ Duplicate removal  
✔ Feature scaling  

> Every transformation is shown explicitly in code for transparency.

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

EDA provides **visual intuition** into:
- Feature distributions  
- Class imbalance  
- Correlation patterns  
- Clinically meaningful variables

---

## 📐 Statistical Analysis
<p align="center">
  <img src="images/chisquare.png" width="650">
</p>

<p align="center">
  <img src="images/pairwise.png" width="750">
</p>

🔍 Techniques used:
- Correlation analysis  
- Independent **t-tests**
- **Chi-square tests**

These ensure results are **statistically grounded**, not just model-driven.

---

## 🤖 Machine Learning Models
Implemented models include:

🟢 Logistic Regression  
🟡 Decision Tree  
🔵 Random Forest  
🟣 Support Vector Machine (SVM)

All models follow a **consistent evaluation framework**.

---

## 📈 Model Performance & Visualization

### 🌈 ROC Curve Comparison
<p align="center">
  <img src="images/roc.png" width="750">
</p>

### 🌳 Decision Tree Feature Importance
<p align="center">
  <img src="images/dt.png" width="650">
</p>

### 📐 Decision Boundary Visualization
<p align="center">
  <img src="images/boundary.png" width="650">
</p>

Metrics analyzed:
- Accuracy  
- Precision / Recall  
- F1-Score  
- ROC-AUC  
- Overfitting behavior  

---

## 🧠 Insights & Conclusions
⭐ **Maximum heart rate** and **ST depression** are the strongest predictors  
⭐ Statistical significance ≠ predictive dominance  
⭐ Logistic Regression balances performance and interpretability  
⭐ Tree models capture non-linear patterns but risk overfitting  

✔ Clear for non-technical readers  
✔ Insightful for technical reviewers  

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
Kumar, A., & Patel, D.(2022): https://www.researchgate.net/publication/368848738_Heart_Disease_Prediction_Using_Logistic_Regression  
Zhang, Y., et al. (2025): https://www.nature.com/articles/s41598-025-93675-1  

