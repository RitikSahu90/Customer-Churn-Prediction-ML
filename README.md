# Customer Churn Prediction using PSO-Based Feature Selection

## Project Overview

This project focuses on predicting telecom customer churn using Machine Learning and Particle Swarm Optimization (PSO) based feature selection techniques.

The system performs end-to-end ML workflow including:
- Data preprocessing
- Feature engineering
- Data balancing using SMOTE
- PSO-based feature optimization
- Multi-model training and evaluation
- Performance visualization

The objective is to identify customers likely to leave telecom services and improve prediction performance through optimized feature selection.

---

## Dataset

Dataset: Telco Customer Churn Dataset

Features include:
- Customer demographics
- Billing information
- Subscription details
- Internet services
- Payment methods
- Contract types

Target Variable:
- Churn (Yes/No)

---

## Workflow Pipeline

1. Data Cleaning
2. Feature Engineering
3. Target Encoding
4. One Hot Encoding
5. Feature Scaling
6. Train-Test Split
7. SMOTE Oversampling
8. PSO Feature Selection
9. Model Training
10. Cross Validation
11. Performance Evaluation
12. Visualization and Result Saving

---

## Feature Engineering

Custom engineered features include:
- Average Monthly Spend
- Remaining Customer Value
- Service Count
- Support Services Count
- Fiber Optic Usage
- Paperless Billing Indicator

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- PySwarms
- Imbalanced-learn

---

## Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost
- Multi-Layer Perceptron (MLP)

---

## Feature Selection using PSO

Particle Swarm Optimization (PSO) was used to select the most relevant features by minimizing classification error and improving F1-score.

Benefits:
- Reduced feature dimensionality
- Improved model efficiency
- Better generalization performance

---

## Evaluation Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Cross Validation F1 Mean

---

## Best Model Performance

| Model | Accuracy | F1-Score | ROC-AUC |
|------|------|------|------|
| PSO + Gradient Boosting | 77.14% | 0.6139 | 0.8269 |

---

## Visualizations

The project generates:
- Confusion Matrices
- ROC Curves
- Feature Importance Graphs
- Correlation Heatmaps
- Model Comparison Charts

---

## Project Structure

```text
Customer-Churn-Prediction-ML/
│
├── data/
├── notebooks/
├── results/
├── src/
├── requirements.txt
├── README.md
└── .gitignore
