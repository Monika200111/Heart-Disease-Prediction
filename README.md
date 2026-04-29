# Heart Disease Prediction – ML Project

Predicting presence of heart disease in patients using machine learning on UCI Heart Disease Dataset.

## 📊 Day 1: Exploratory Data Analysis | 29-Apr-2026

**Dataset**: UCI Heart Disease Dataset  
**Size**: 1025 patients × 14 features  
**Target**: 0 = No Disease, 1 = Disease  
**Null Values**: 0 – Clean dataset  

### Key Insights from EDA
1. **Class Distribution**: 526 Disease | 499 No Disease
2. **High Risk Age Groups**: 40-45 and 50-55 years show highest disease density  
3. **Top Correlated Features with Target**:
   - `cp` (Chest Pain Type): +0.43
   - `thalach` (Max Heart Rate): +0.42  
   - `exang` (Exercise Induced Angina): -0.44
   - `oldpeak` (ST Depression): -0.44
4. **Surprising**: Age (-0.23) and Cholesterol (-0.10) have weak correlation

### Visualizations
1. Age distribution by disease status – Histogram + KDE
2. Feature correlation heatmap – Found key predictors

## 🛠️ Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## 🚀 Next Steps – Day 2
1. Data preprocessing: Feature scaling, Train-test split
2. Baseline model: Logistic Regression  
3. Target accuracy: >85%
4. Model evaluation: Confusion matrix, ROC-AUC

## 📈 Project Goal
Build end-to-end ML pipeline and deploy as web app for placement portfolio.

---
**Author**: Monika200111 | B.Tech CSE 2025 | Placement Prep

