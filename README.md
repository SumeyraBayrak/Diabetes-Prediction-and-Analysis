# Diabetes Prediction Using KNN Classifier

## Project Overview
This project implements a machine learning model that predicts the likelihood of diabetes in patients using the **Pima Indians Diabetes Dataset** on Kaggle . The model leverages the **KNeighborsClassifier** algorithm to classify whether a patient has diabetes or not based on medical measurements and personal health data. The goal of this project is to demonstrate the application of KNN for classification tasks and showcase the ability to predict diabetes based on diagnostic data.

---

## Dataset Description

The dataset used in this project is from the **National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)**. It contains medical data and diagnostic results for female patients of Pima Indian heritage, aged 21 years or older. The dataset is designed to help predict whether a patient has diabetes based on several medical predictor variables.

The dataset consists of 8 predictor variables and 1 target variable (`Outcome`), which indicates whether the patient has diabetes (1) or not (0).

---

## Features

| **Index** | **Feature**                  | **Description**                                                                 |
|:---------:|:-----------------------------|:-------------------------------------------------------------------------------|
| 1         | **Pregnancies**               | The number of times a patient has been pregnant.                                |
| 2         | **Glucose**                   | Plasma glucose concentration measured 2 hours after an oral glucose tolerance test. |
| 3         | **BloodPressure**             | Diastolic blood pressure (measured in mm Hg).                                   |
| 4         | **SkinThickness**             | Triceps skin fold thickness (measured in mm).                                  |
| 5         | **Insulin**                   | Hour serum insulin concentration (measured in µU/ml).                        |
| 6         | **BMI**                       | Body Mass Index (calculated as weight in kg divided by height in meters squared). |
| 7         | **DiabetesPedigreeFunction**  | A function representing the family history of diabetes (genetic risk).          |
| 8         | **Age**                       | Age of the patient in years.                                                   |
| 9         | **Outcome**                   | Target variable (0 or 1). Classifies whether the patient has diabetes (1) or not (0). |

---
**[Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)**
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
## Acknowledgements

Thanks to **[GeeksforGeeks](https://www.geeksforgeeks.org/videos/diabetes-prediction-in-machine-learning/)** for the helpful tutorial on diabetes prediction using machine learning. It played a key role in the development of this project.
