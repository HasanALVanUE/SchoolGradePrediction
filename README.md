# Student Grade Prediction & Machine Learning Model Comparisons

This repository contains a comparative machine learning project that evaluates and compares **2 Simple Models** and **3 Ensemble Learners** using the Student Performance dataset from Kaggle.

## 📌 Project Overview
The objective of this project is to predict whether a student will pass or fail their final mathematics exam (`G3`) based on various demographic, social, and academic features. 

- **Target Variable:** Binary classification (`Passed`: 1 if final grade $\ge 10$, otherwise 0).
- **Evaluation Metric:** Accuracy, Precision, Recall, and F1-Score.

---

## 🤖 Models Implemented

### Simple Models (2)
1. **Logistic Regression:** A linear baseline model for binary classification.
2. **Decision Tree Classifier:** A rule-based non-linear model.

### Ensemble Models (3)
1. **Random Forest Classifier (Bagging):** Combines multiple decision trees in parallel to reduce overfitting.
2. **Gradient Boosting Classifier (Boosting):** Sequentially builds trees to minimize prediction errors.
3. **AdaBoost Classifier (Adaptive Boosting):** Focuses subsequent models on previously misclassified instances.

---

## 📊 Experimental Results

| Model | Type | Accuracy |
| :--- | :--- | :--- |
| **Random Forest** | Ensemble (Bagging) | **91.14%** |
| **AdaBoost** | Ensemble (Boosting) | **91.14%** |
| **Logistic Regression** | Simple | 89.87% |
| **Decision Tree** | Simple | 88.61% |
| **Gradient Boosting** | Ensemble (Boosting) | 86.08% |

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/HasanALVanUE/SchoolGradePrediction.git](https://github.com/HasanALVanUE/SchoolGradePrediction.git)