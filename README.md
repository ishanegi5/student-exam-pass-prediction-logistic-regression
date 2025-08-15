Student Exam Pass Prediction — Logistic Regression (Small Project)
📌 Overview

This project applies Logistic Regression to predict whether a student will pass or fail based on given features.
The dataset contains 709 rows with multiple features like study hours, previous scores, etc.

📂 Dataset

Source: Kaggle (Student Exam Pass Prediction)

Target Variable: Pass (1 = Pass, 0 = Fail)

Type: Balanced binary classification problem

⚙️ Steps Performed

Data Loading

EDA (Exploratory Data Analysis) – Checked distributions, correlations, and missing values

Data Preprocessing

Handled missing values

Encoded categorical variables

Feature scaling using StandardScaler

Model Training

Used LogisticRegression from scikit-learn

Model Evaluation

Measured Accuracy, Precision, Recall, and F1-score
📊 Model Performance
| Metric       | Class 0 | Class 1 | Macro Avg | Weighted Avg |
| ------------ | ------- | ------- | --------- | ------------ |
| Precision    | 0.99    | 0.99    | 0.99      | 0.99         |
| Recall       | 0.99    | 0.99    | 0.99      | 0.99         |
| F1-Score     | 0.99    | 0.99    | 0.99      | 0.99         |
| **Accuracy** | **--**  | **--**  | **0.99**  | **0.99**     |
Confusion Matrix:
[[70,  1],
 [ 1, 70]]
🛠 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

scikit-learn

📈 Results

The model achieved 98.59% accuracy with balanced precision and recall for both classes, indicating strong predictive performance for this dataset.
