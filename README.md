<div align="center">

<h1 style="font-size:48px;">
🩺🤖 <span style="color:#58a6ff;">DOCTOR</span> <span style="color:#7ee787;">JEN-AI</span>
</h1>

<h3 style="color:#c9d1d9;">
Heart Disease Prediction System <br/>
DATA 602 – Final Project Tutorial
</h3>

<br/>

<img src="./images/doctorji.png" width="420" alt="Heartbeat Animation"/>

<br/><br/>

<a href="https://esingh16.github.io/Doctor-JEN-AI/"><b>🌐 Live Tutorial</b></a> •
<a href="#-model-performance--visualization"><b>📊 Results</b></a> •
- [⚙️ How to Run](#-how-to-run)


<br/><br/>

<img src="https://img.shields.io/badge/Python-3.x-blue"/>
<img src="https://img.shields.io/badge/scikit--learn-ML-orange"/>
<img src="https://img.shields.io/badge/status-complete-brightgreen"/>
<img src="https://img.shields.io/badge/course-DATA%20602-purple"/>

</div>

---

## 📌 Table of Contents
- [👥 Team](#-team)
- [🎯 Problem Definition](#-problem-definition)
- [📂 Dataset](#-dataset)
- [🧠 Model Architecture](#-model-architecture)
- [🔧 Data Preparation](#-data-preparation)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis-eda)
- [📐 Statistical Analysis](#-statistical-analysis)
- [🤖 Machine Learning Models](#-machine-learning-models)
- [📈 Model Performance](#-model-performance--visualization)
- [🧠 Insights & Conclusions](#-insights--conclusions)
- [📚 Bibliography](#-bibliography)
- [❓ Key Questions Answered](#-key-questions-answered)
- [✅ Reproducibility Checklist](#-reproducibility-checklist)
- [⚙️ How to Run](#️-how-to-run)
  
---

## 👥 Team
- **Eshan Singh** *(UID: 122115569)*  
- **Nicole Miranda** *(UID: 116014687)*  
- **Jamiya Kirkland** *(UID: 122328396)*  

---

## 🎯 Problem Definition
**Heart disease is one of the leading causes of mortality worldwide.**

This project presents an **end-to-end machine learning pipeline** to predict the **presence of heart disease** using real patient clinical data.

✨ **Focus Areas**
- Structured **data exploration**
- **Statistical hypothesis testing**
- Multiple **ML model comparisons**
- Emphasis on **interpretability over black-box prediction**

---

## 📂 Dataset
🧬 **Clinical Heart Disease Dataset**
- **Source:** UCI Machine Learning Repository (Cleveland subset)
- **Observations:** 303 patients
- **Features:** 13 clinical attributes
- Mixed numerical & categorical features  
- Binary outcome:
  - `0` → No heart disease  
  - `1` → Presence of heart disease  


---

## 🧠 Model Architecture
<div align="center">
  <img src="images/newheart.png" width="700" alt="Pipeline Diagram"/>
  <br/>
  <i>End-to-end workflow from raw data to insights</i>
</div>

---

## 🔧 Data Preparation
✔ Column renaming for clarity  
✔ Missing value handling  
✔ Data type correction  
✔ Duplicate removal  
✔ Feature scaling  

> All transformations are explicitly shown in code to ensure **full transparency and reproducibility**.

---

## 📊 Exploratory Data Analysis (EDA)

<details>
<summary><b>📈 Click to view EDA visualizations</b></summary>

<br/>

<p align="center"><img src="images/histogram.png" width="750"></p>
<p align="center"><img src="images/piechart.png" width="750"></p>
<p align="center"><img src="images/heatmap.png" width="750"></p>
<p align="center"><img src="images/boxplot.png" width="750"></p>

EDA provides intuition into:
- Feature distributions  
- Class imbalance  
- Correlation structure  
- Clinically meaningful variables  

</details>

---

## 📐 Statistical Analysis

<details>
<summary><b>📐 Click to view statistical tests</b></summary>

<br/>

<p align="center"><img src="images/chisquare.png" width="650"></p>
<p align="center"><img src="images/pairwise.png" width="750"></p>

🔍 Techniques applied:
- Correlation analysis  
- Independent **t-tests**
- **Chi-square tests**

These ensure insights are **statistically validated**, not just model-driven.

</details>

---

## 🤖 Machine Learning Models
Implemented models include:

🟢 Logistic Regression  
🟡 Decision Tree  
🔵 Random Forest  
🟣 Support Vector Machine (SVM)  

All models follow a **consistent training, tuning, and evaluation pipeline**.

---

## 📈 Model Performance & Visualization

### 🌈 ROC Curve Comparison
<p align="center"><img src="images/roc.png" width="750"></p>

### 🌳 Decision Tree Feature Importance
<p align="center"><img src="images/dt.png" width="650"></p>

### 📐 Decision Boundary Visualization
<p align="center"><img src="images/boundary.png" width="650"></p>

## Logistic Regression was selected as the final model due to its strong generalization, stability, and interpretability—critical requirements in healthcare applications.


📊 Metrics evaluated:
- Accuracy  
- Precision / Recall  
- F1-Score  
- ROC-AUC  
- Overfitting behavior  

---

## 🧠 Insights & Conclusions
⭐ **Maximum heart rate** and **ST depression** are the strongest predictors  
⭐ Statistical significance does **not always imply** predictive dominance  
⭐ Logistic Regression offers the best balance of **performance + interpretability**  
⭐ Tree-based models capture non-linear patterns but may **overfit without tuning**

✔ Accessible to non-technical readers  
✔ Informative for technical evaluators  


---

## 🛠️ Tools & Libraries
python
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

--- 
## 📚 Bibliography

1. Scikit-learn Documentation – Model Evaluation (ROC Metrics):  
   https://scikit-learn.org/stable/modules/model_evaluation.html#roc-metrics

2. Scikit-learn Documentation – Logistic Regression:  
   https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression

3. James, G., Witten, D., Hastie, T., Tibshirani, R.  
   *An Introduction to Statistical Learning*:  
   https://www.statlearning.com/

4. World Health Organization.  
   Cardiovascular Diseases (CVDs):  
   https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)

5. ResearchGate.  
   Heart Disease Prediction Using Logistic Regression:  
   https://www.researchgate.net/publication/368848738_Heart_Disease_Prediction_Using_Logistic_Regression


---

## ❓ Key Questions Answered

- **Key features:** Maximum heart rate, ST depression  
- **Best interpretable model:** Logistic Regression  
- **Stats vs models:** Largely consistent, not always equal importance  
- **Tradeoff:** Trees fit complex patterns; LR generalizes better

--- 

## ✅ Reproducibility Checklist
- [x] Clear preprocessing steps
- [x] EDA visualizations included
- [x] Statistical testing included
- [x] Multiple models compared
- [x] Interpretable results & insights

---

## ⚙️ How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy

