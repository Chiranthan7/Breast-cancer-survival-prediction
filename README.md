# Breast Cancer Survival Prediction using Machine Learning

## Overview

This project builds a machine learning system to predict breast cancer patient survival outcomes based on clinical and demographic features. It compares multiple models and uses explainable AI techniques to interpret predictions.

## Problem Statement

Breast cancer survival prediction is crucial for early decision-making and treatment planning. This project aims to develop a predictive model that can assist healthcare professionals in identifying high-risk patients.

## Dataset

* **Dataset**: Breast Cancer Survival Dataset
* **Records**: 4024 patients
* **Features**: 16 clinical attributes

### Key Features:

* Age
* Tumor Size
* Regional Node Examined
* Survival Months
* Estrogen Status
* Progesterone Status
* Cancer Stage

## Machine Learning Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost

## Best Model

**Random Forest Classifier**

* Accuracy: **~90%**
* Robust performance across cross-validation

## Model Evaluation

* Accuracy Score
* Confusion Matrix
* ROC Curve
* Cross Validation


## Visualizations

* Correlation Heatmap
* Feature Importance
* ROC Curve
* Model Comparison


## Explainability

* SHAP (SHapley Additive Explanations) used to interpret model predictions
* Helps understand feature impact on survival prediction


## Project Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Model Comparison
7. Explainability using SHAP


## Sample Output

* Predicts survival outcome based on patient data
* Provides probability-based predictions

(Add screenshots here: ROC_Curve.png, Model_comparison.png)


## Tech Stack

* Python
* Scikit-learn
* XGBoost
* Pandas
* Matplotlib
* Seaborn
* SHAP


## Project Structure

```
Breast-cancer-survival-prediction/
│── Breast_Cancer.csv
│── Brest_Cancer_Survival_prediction.ipynb
│── Model_comparison.png
│── ROC_Curve.png
│── requirements.txt
│── README.md
```


## Real-World Impact

* Assists doctors in identifying high-risk patients
* Supports data-driven treatment planning
* Enables early intervention strategies


## Future Improvements

* Deploy as a web app (Streamlit / Flask)
* Add real-time patient input system
* Improve model performance with deep learning
* Integrate with healthcare datasets
