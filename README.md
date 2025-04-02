# 💪 Relative Lean Body Mass (LBM) Prediction

This project focuses on predicting **Relative Lean Body Mass (LBM)** using biometric and physiological data through regression-based machine learning models. It aims to provide accurate and interpretable insights into an individual's body composition.

## 📌 What is Relative LBM?

**Relative Lean Body Mass** is the ratio of lean mass (muscle, bone, organs, etc.) to total body weight. It’s an important indicator for physical fitness, health monitoring, and personalized training programs.

---

## 📊 Project Overview

- ✅ **Objective**: Predict relative LBM using input features such as age, height, weight, BMI, and more  
- 🧪 **Approach**: Regression modeling with proper preprocessing, feature selection, and model tuning  
- 📉 **Evaluation**: Used metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score  
- 🔍 **Analysis**: Included exploratory data analysis (EDA) and feature importance visualizations for interpretability  

---

## 🛠️ Tech Stack

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📁 Repository Structure

```
project-root/
├── data/
│   └── lbm_dataset.csv          # Cleaned dataset for training/testing
├── notebooks/
│   └── relative_lbm_model.ipynb # Main notebook with code, EDA, modeling, and results
├── results/
│   └── plots/                   # Visualizations of feature importances, residuals, etc.
└── README.md
```

---

## 🚀 Results Summary

- **Best-performing model**: Linear Regression
- **R² Score**: ~_Insert value here_  
- **MAE**: ~_Insert value here_  

---

## 🔮 Future Work

- Incorporate additional physiological data (e.g., body fat %, muscle circumference)  
- Evaluate on gender-specific or age-grouped subsets  
- Explore model generalization on external datasets
