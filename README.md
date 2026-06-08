# CodeAlpha Tasks — Machine Learning Projects
## 📁 Task 1 — Credit Scoring Model
### Credit Worthiness Prediction using Machine Learning
![Python](https://img.shields.io/badge/Python-3.x-blue)
![sklearn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-98.00%25-brightgreen)

### 📌 Objective
Predict whether an individual has **Good Credit** or **Bad Credit**
based on 10 financial features.

### 📊 Dataset
- Source: Custom Realistic Financial Dataset
- Samples: 1000 individuals
- Features: 10 financial measurements
- Classes: Good Credit (1) | Bad Credit (0)

### 🤖 Models Used
| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---|---|---|---|---|
| Logistic Regression | 76.00% | 80.00% | 88.89% | 84.21% | 0.8549 |
| Decision Tree | 98.50% | 97.96% | 100% | 98.97% | 0.9732 |
| Random Forest | **98.00% 🏆** | **97.30%** | **100%** | **98.63%** | **0.9987** |

### 🏆 Best Model — Random Forest
- Accuracy : 98.00%
- ROC-AUC  : 0.9987 ⭐
- Recall   : 100% (No Good Credit case missed!)

### 🔝 Top Features
1. income
2. savings
3. late_payments
