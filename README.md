# Disease Prediction using Machine Learning

> Completed as part of the CodeAlpha Machine Learning Internship - Task 4: Disease Prediction from Medical Data

## Project Overview

This project predicts whether a patient is likely to have diabetes using Machine Learning techniques. The model analyzes medical attributes such as glucose level, BMI, blood pressure, insulin level, and age to support early disease detection.

## Objective

To build a classification model that predicts diabetes based on patient medical data.

## Dataset

Pima Indians Diabetes Dataset

### Features Used

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target Variable

* Outcome

  * 0 = Non-Diabetic
  * 1 = Diabetic

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Feature Engineering

A new feature named BMI_Age was created:

BMI_Age = BMI × Age

This feature combines body mass index and age information to improve predictive capability.

## Machine Learning Models

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

## Results

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 75.32%   | 64.91%    | 67.27% | 66.07%   |
| Decision Tree       | 71.43%   | 58.46%    | 69.09% | 63.33%   |
| Random Forest       | 75.32%   | 64.91%    | 67.27% | 66.07%   |

## Hyperparameter Tuning

Best Parameters:

* max_depth = 5
* n_estimators = 200

Best Cross Validation Score:

* 77.37%

## Visualizations

* Disease Distribution
* Confusion Matrix
* ROC Curve
* Feature Importance Analysis

## Conclusion

Machine Learning techniques successfully predicted diabetes risk using patient health information. Logistic Regression and Random Forest achieved the best performance. Feature engineering and hyperparameter tuning improved the overall reliability of the model.
