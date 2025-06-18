# Heart-Disease-Risk-Prediction-Model
Predictive machine learning model for early heart disease detection using clinical features, optimized for accuracy and interpretability.

# Heart Disease Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-9D96C8?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Overview

This project builds a predictive model using machine learning techniques to detect the presence of heart disease based on clinical features. The goal is to support early detection and intervention by identifying high-risk patients using real-world health data.

---

## Dataset

The dataset includes features such as:
- Age, Sex, Chest Pain Type
- Resting Blood Pressure, Serum Cholesterol
- Fasting Blood Sugar, Resting ECG Results
- Maximum Heart Rate Achieved, Exercise-Induced Angina
- ST Depression, Slope of ST Segment
- Number of Major Vessels, Thalassemia, Target (Diagnosis)

---

## Methodology

### Data Preprocessing
- Handled missing values by removing incomplete records
- Encoded categorical features using one-hot encoding
- Standardized numerical features to improve model performance

### Exploratory Data Analysis
- Used Matplotlib and Seaborn to visualize relationships between risk factors
- Identified high-correlation features such as age, cholesterol, and blood pressure

###  Model Building
- Trained a Decision Tree Classifier
- Optimized hyperparameters using `GridSearchCV`
- Evaluated using accuracy, confusion matrix, precision, and recall

---

##  Results

- **Model:** Decision Tree Classifier
- **Performance:** High accuracy and recall for binary heart disease classification
- **Key Insights:** Age, cholesterol levels, and chest pain type were strong predictors of heart disease

---

##  Key Learnings

- Effective data preprocessing significantly boosts model performance
- Medical datasets often require careful feature engineering for meaningful results
- Interpretable models like Decision Trees are valuable in clinical decision support

---


