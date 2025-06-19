# Binary Classification for Cardiovascular Risk Prediction


## 🩺 Project Description
This project leverages a dataset from an ongoing cardiovascular study in Framingham, Massachusetts. The goal is to predict whether a patient has a 10-year risk of developing coronary heart disease (CHD).

The dataset consists of 4,000+ records and 15 features, representing a combination of demographic, behavioral, and medical risk factors. Each attribute potentially contributes to cardiovascular risk.

---

## 🔍 Steps Followed

1. **Define the Problem**
   - Understanding the objective: Predict 10-year CHD risk.

2. **Data Collection**
   - Framingham Heart Study dataset used.

3. **Exploratory Data Analysis (EDA)**
   - Analyzing distributions, correlations, and identifying patterns.

4. **Data Preprocessing / Feature Engineering**
   - Handling missing values and outliers.
   - Encoding categorical variables.
   - Feature selection.
   - Data scaling and splitting.

5. **Build the Model**
   - Multiple classification models were trained.

6. **Model Evaluation**
   - Evaluation using Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
![Flowchart](https://github.com/Harsh-Singh24/CHD-Binary-classification/blob/main/Flow%20Chart.png)
---

## 🤖 Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boost
- Adaboost
- XGBoost
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes

---

## ✅ Conclusion
When selecting the best model, the bias-variance trade-off was considered. A model with high scores and minimal overfitting was ideal.

> **KNN emerged as the best model**:
> - Training Accuracy: 86%
> - Test Accuracy: 81%
> - Training Precision: 78%
> - Test Precision: 74.8%
> - Training Recall: 99%
> - Test Recall: 98.2%

In this problem, minimizing **false negatives** is critical — thus **recall** is prioritized over accuracy. Hence, **KNN** is best suited for this binary classification task.

---

## 📁 Repository Link
[GitHub Repository](https://github.com/Harsh-Singh24/CHD-Binary-classification)

Feel free to fork, clone, and contribute!

