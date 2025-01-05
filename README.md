# Diabetes Prediction Using KNN Classifier

## Project Overview
This project implements a machine learning model that predicts the likelihood of diabetes in patients using the **Pima Indians Diabetes Dataset**. The model leverages the **KNeighborsClassifier** algorithm to classify whether a patient has diabetes or not based on medical measurements and personal health data. The goal of this project is to demonstrate the application of KNN for classification tasks and showcase the ability to predict diabetes based on diagnostic data.

---

## Dataset Description

The dataset used in this project is from the **National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)**. It contains medical data and diagnostic results for female patients of Pima Indian heritage, aged 21 years or older. The dataset is designed to help predict whether a patient has diabetes based on several medical predictor variables.

The dataset consists of 8 predictor variables and 1 target variable (`Outcome`), which indicates whether the patient has diabetes (1) or not (0).

---

## Features

| **Feature**                  | **Description**                                                                 |
|------------------------------|---------------------------------------------------------------------------------|
| **Pregnancies**               | The number of times a patient has been pregnant.                                |
| **Glucose**                   | Plasma glucose concentration measured 2 hours after an oral glucose tolerance test. |
| **BloodPressure**             | Diastolic blood pressure (measured in mm Hg).                                   |
| **SkinThickness**             | Triceps skin fold thickness (measured in mm).                                  |
| **Insulin**                   | 2-hour serum insulin concentration (measured in µU/ml).                        |
| **BMI**                       | Body Mass Index (calculated as weight in kg divided by height in meters squared). |
| **DiabetesPedigreeFunction**  | A function representing the family history of diabetes (genetic risk).          |
| **Age**                       | Age of the patient in years.                                                   |
| **Outcome**                   | Target variable (0 or 1). Classifies whether the patient has diabetes (1) or not (0). |

---

### Additional Notes:
- **BMI (Body Mass Index)**: A key indicator of body fat, calculated using the formula:  
  `BMI = weight(kg) / height(m)²`
  
- **DiabetesPedigreeFunction**: This value represents the genetic predisposition to diabetes, where a higher value indicates a stronger family history of diabetes.

---

This layout helps in clearly distinguishing the features and their descriptions, making the information easier to digest and more visually appealing.


## Installation
Follow these steps to set up the project locally:

### Prerequisites:
- Python 3.x
- pip (Python package installer)

### Required Libraries:
You can install the required Python libraries using pip:



## Features

| **Feature**                  | **Description**                                                                 |
|:-----------------------------|:-------------------------------------------------------------------------------|
| **Pregnancies**               | The number of times a patient has been pregnant.                                |
| **Glucose**                   | Plasma glucose concentration measured 2 hours after an oral glucose tolerance test. |
| **BloodPressure**             | Diastolic blood pressure (measured in mm Hg).                                   |
| **SkinThickness**             | Triceps skin fold thickness (measured in mm).                                  |
| **Insulin**                   | 2-hour serum insulin concentration (measured in µU/ml).                        |
| **BMI**                       | Body Mass Index (calculated as weight in kg divided by height in meters squared). |
| **DiabetesPedigreeFunction**  | A function representing the family history of diabetes (genetic risk).          |
| **Age**                       | Age of the patient in years.                                                   |
| **Outcome**                   | Target variable (0 or 1). Classifies whether the patient has diabetes (1) or not (0). |
