# CP_1-Sonar_rock_mine_prediction-
Its a copy project
Rock vs Mine Prediction 🎯
📌 Project Overview
This project predicts whether a sonar signal is reflected from a Mine (M) or a Rock (R) using Machine Learning techniques. The dataset contains 60 frequency-based features extracted from sonar signals.
The goal is to build and evaluate classification models that can distinguish between the two classes with high accuracy.
📂 Dataset
Source: https://www.kaggle.com/datasets/ranasabrii/sonar-data
Shape: 208 samples × 61 columns
Columns 0–59 → numeric features (energy of sonar signals at different frequencies)
Column 60 → Target label (M = Mine, R = Rock)
🛠️ Tech Stack
Language: Python 3
Libraries:
1)Data Processing → Pandas, NumPy
2)Machine Learning → Scikit-learn
📊 Project Workflow
##Data Preprocessing
Handled features and labels
Train-test split
Standardized data
Exploratory Data Analysis (EDA)
Grouped by class (M vs R
Compared average frequency responses
##Model Training & Evaluation
Logistic Regression
##Model Evaluation
Accuracy Score
🚀 Results
Logistic Regression → ~76% accuracy
