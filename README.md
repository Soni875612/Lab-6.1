## Lab Activity 6.1 — Predicting Diabetes in Indian Patients Using Logistic Regression
Objective
To build a Logistic Regression machine learning model to predict whether a patient has diabetes based on medical predictor variables from the Pima Indians Diabetes dataset.
Dataset
🔗 Pima Indians Diabetes Database — Kaggle
Requirements

Python (Jupyter Notebook / Google Colab)
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Prerequisites

Basic Python knowledge
Understanding of Logistic Regression (binary classification)
Familiarity with Pandas, NumPy, Matplotlib, and Scikit-Learn

Problem Statement
Diabetes is a growing health concern in India and early detection is critical. This task predicts whether a patient is diabetic or non-diabetic using health attributes such as glucose level, BMI, age, and blood pressure. The model is trained using Logistic Regression and evaluated with appropriate metrics.
Steps
StepTask1Import required libraries2Load the dataset3Data preprocessing — handle missing/inconsistent values4Train the Logistic Regression model5Evaluate model performance (accuracy, confusion matrix, classification report)6Interpret results and suggest improvements
Tech Stack
LibraryUsagepandasData loading and manipulationnumpyNumerical operationsscikit-learnLogistic Regression, train-test split, evaluation metricsmatplotlib / seabornVisualizations
File Structure
Lab6_1/
├── Lab6_1.ipynb          # Main notebook
├── diabetes.csv          # Dataset
└── README.md             # This file
Conclusion
The Logistic Regression model classifies patients as diabetic or non-diabetic. Model accuracy and metrics (precision, recall, F1-score) are analyzed to evaluate reliability. Improvements such as hyperparameter tuning or alternative models (e.g., Random Forest) can be explored for better performance.
