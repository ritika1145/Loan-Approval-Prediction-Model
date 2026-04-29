# Loan Approval Prediction Model

This is an end-to-end machine learning project that predicts loan approval using applicant financial and demographic data. It project explores multiple classification models, evaluates performance using key metrics, and analyzes the impact of class imbalance on predictions and actively works to solve it. 

---

## Project Overview

The goal of this project is to build and compare machine learning models that determine whether a loan application should be approved or rejected.

The workflow includes:

* Data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis (EDA)
* Training and Testing multiple classification model
* Model evaluation and comparison

---

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Naive Bayes

---

## Model Performance

| Model               | Accuracy | Notes                                    |
| ------------------- | -------- | ---------------------------------------- |
| Logistic Regression | 0.84     | Strong baseline, biased toward approvals |
| Decision Tree       | 0.80     | Lower performance                        |
| Random Forest       | **0.85** | Best overall performance                 |
| KNN                 | 0.84     | More balanced predictions                |
| SVM                 | 0.84     | Similar to Logistic Regression           |
| Naive Bayes         | 0.80     | Weaker performance                       |

---

## Key Insights

* The dataset is **imbalanced**, with more approved loans than rejected ones
* Most models are **biased toward predicting approvals**
* Random Forest achieved the best balance between accuracy and overall performance
* Recall for rejected applications remains lower across models, indicating difficulty in identifying risky loans

## Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
