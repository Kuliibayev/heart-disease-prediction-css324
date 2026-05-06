# Heart Disease Prediction using Machine Learning
**CSS 324 – Introduction to Machine Learning | Final Project**

## Team Members
| Name | Role |
|------|------|
| Nazerke Kenges | EDA, Report Writing, Interactive Demo |
| Alikhan Kulibayev | Model Training & Hyperparameter Tuning |
| Zhuldyz Leken | Data Preprocessing & Feature Engineering |
| Aruzhan Anarbek | Error Analysis & Report Writing |
| Aidana Alibek | Model Training & Evaluation |

## Project Overview
Binary classification task to predict heart stroke risk from
demographic and clinical features using Logistic Regression,
Decision Tree, and Random Forest.

## Best Model: Logistic Regression
- Accuracy: 0.665 | Recall: 0.574 | F1-Score: 0.343

## Repository Structure
heart-disease-prediction-css324/
├── finalprojectML.ipynb       # Main notebook with all code + interactive demo
├── heart_disease.csv          # Raw dataset (Kaggle)
└── Report.pdf                 # Final project report

## How to Run
1. Clone this repo
2. Install dependencies: pip install pandas scikit-learn matplotlib seaborn ipywidgets joblib missingno
3. Open finalprojectML.ipynb in Jupyter Notebook
4. Run all cells — the last cell launches the interactive prediction widget
