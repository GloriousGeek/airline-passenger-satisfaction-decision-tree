# ✈Airline Passenger Satisfaction Prediction using Decision Trees

This project applies a Decision Tree classifier to predict whether an airline passenger is satisfied or dissatisfied based on various service and personal attributes. The objective is to help airlines understand key drivers of customer satisfaction using a model that is both accurate and interpretable.

---

## Problem Statement

Customer satisfaction is essential for building brand loyalty and improving services in the airline industry. This project uses machine learning to predict passenger satisfaction levels using data collected from customer surveys. The focus is on building a decision-support tool that identifies key service attributes contributing to satisfaction, such as inflight Wi-Fi, seat comfort, and check-in service.

---

## Dataset

- **Source**: [Kaggle – Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
- **Type**: Binary classification
- **Target**: `satisfaction` (Satisfied / Neutral or Dissatisfied)
- **Split**: Predefined `train.csv` and `test.csv`

---

## Tools & Libraries

- Python (Pandas, NumPy)
- Scikit-learn (DecisionTreeClassifier, GridSearchCV)
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Project Workflow

1. **Data Cleaning**: Removed missing values and filtered adults (age > 18)
2. **Encoding**: Applied dummy encoding to categorical features
3. **Modeling**: Built a base Decision Tree and fine-tuned it using GridSearchCV
4. **Evaluation**: Assessed model performance using Accuracy, F1 Score, ROC AUC, and visual tools

---

## Results

| Model        | Accuracy | F1 Score | ROC AUC |
|--------------|----------|----------|---------|
| Fine-Tuned   | 95.2%    | 0.95     | 0.97    |

The model showed strong generalisation and interpretability, making it suitable for stakeholder-facing use in customer experience analysis.

---

## 🚀 How to Run

1. Clone this repo
2. Install dependencies  
