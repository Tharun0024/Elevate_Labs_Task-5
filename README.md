# Elevate_Labs_Task-5

# ❤️ Heart Disease Prediction using Decision Trees & Random Forests

This project explores the use of tree-based machine learning algorithms—**Decision Trees** and **Random Forests**—to predict the presence of heart disease. It was developed as part of the **AI & ML Internship by Elevate Labs** in collaboration with the **Ministry of MSME, Govt. of India**.

---

## 📊 Dataset

- **Source**: [Heart Disease Dataset – Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Format**: CSV (`heart.csv`)
- **Target Variable**: `target` (1 = heart disease present, 0 = not present)
- **Attributes**: Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, maximum heart rate, and others.

---

## 🛠️ Tools & Technologies

- **Platform**: Google Colab
- **Programming Language**: Python 3
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` (for model training and evaluation)
  - `Graphviz` (for tree visualization)

---

## 🎯 Objectives

- Build a **Decision Tree Classifier** and visualize the model structure.
- Control **overfitting** by tuning hyperparameters such as tree depth.
- Train and evaluate a **Random Forest Classifier** and compare performance.
- Analyze **feature importance** to understand key drivers of prediction.
- Evaluate models using **accuracy**, **confusion matrix**, **classification report**, and **cross-validation**.

---

## 🧠 Model Overview

### 🔹 Decision Tree Classifier
- Trained with a controlled depth to prevent overfitting.
- Visualized using `plot_tree()` for interpretability.

### 🔹 Random Forest Classifier
- Ensemble model with 100 decision trees.
- Improved accuracy and robustness by reducing variance.

---

## 📈 Evaluation Metrics

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-Score)
- **Cross-Validation Score** (5-fold)

---

## 🔍 Feature Importance Insights

The most influential features identified by the Random Forest model include:

- **Chest Pain Type (`cp`)**
- **Maximum Heart Rate Achieved (`thalach`)**
- **ST Depression (`oldpeak`)**
- **Number of Major Vessels (`ca`)**

These features showed strong correlations with the target variable and played key roles in classification.

---

## ✅ Results Summary

| Model            | Accuracy |
|------------------|----------|
| Decision Tree    | ~84%     |
| Random Forest    | ~88–90%  |

Random Forest outperformed the Decision Tree due to its ensemble approach, offering better generalization and robustness against overfitting.

---

## 📚 Key Learnings

- Hands-on experience with **tree-based classification models**.
- Understanding of **ensemble learning** through Random Forests.
- Importance of **feature selection and importance analysis**.
- Practical application of **evaluation techniques** for model validation.

---

## 📌 Internship Task Reference

This project addresses **Task 5: Decision Trees and Random Forests** as part of the AI & ML Internship organized by **Elevate Labs** under the guidance of the **Ministry of MSME, Government of India**.

