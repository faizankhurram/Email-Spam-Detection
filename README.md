# Email Spam Detection Project (Binary Classification)

This project demonstrates the complete machine learning pipeline for a binary classification task using a high-quality dataset. We train and evaluate multiple models to determine the best performer using both base and tuned configurations.

---

## 📊 Project Overview

- **Objective:** Predict the 'Prediction' class using a range of engineered and original features.
- **Type of Problem:** Supervised Binary Classification
- **Tools & Libraries:**
  - Python
  - pandas, NumPy
  - scikit-learn
  - seaborn, matplotlib

---

## 🧹 Data Processing

- Handled missing values
- Performed feature analysis:
  - **Barplots**
  - **Correlation matrices**

---

## 🧠 Models Trained

- Random Forest Classifier
- Support Vector Classifier
- Logistic Regression

Logistic Regression showed best result in base performance. Random Forest Classifier and Logistic Regression were then evaluated in:
- **Base form**
- **Tuned using RandomizedSearchCV**
- **Tuned using GridSearchCV**

---

## 🔍 Evaluation Strategy

### 📦 Data Splits:
- **Training Set**
- **Testing Set**  

### 📈 Metrics Used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross-validation (5-fold)

---

## 🏆 Best Model

### ✅ **Logistic Regression (Tuned using GSCV)**

This model outperformed tuned versions and others with consistent and robust performance.

---

## 📌 Key Takeaways

- **Data quality was crucial** — strogn and large amount of features led to high model confidence.
- **Cross-validation** ensured generalization and ruled out overfitting.
