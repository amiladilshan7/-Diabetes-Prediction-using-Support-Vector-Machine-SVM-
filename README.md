# -Diabetes-Prediction-using-Support-Vector-Machine-SVM-


This project is a machine learning model that predicts whether a person has diabetes based on the PIMA Diabetes Dataset. The model is built using a Support Vector Machine (SVM) classifier and is trained on standardized data to improve accuracy.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Prediction](#prediction)
- [License](#license)

## Project Overview

The goal of this project is to predict diabetes using the PIMA Diabetes Dataset. The dataset contains various medical predictor variables and one target variable, `Outcome`, which indicates whether the patient has diabetes (1) or not (0). The project involves data preprocessing, standardization, model training, and evaluation using an SVM classifier.

## Dataset

The dataset used in this project is the **PIMA Diabetes Dataset**, which contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target Variable)

The dataset is loaded from a CSV file (`diabetes.csv`).

## Dependencies

To run this project, you need the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`

You can install these dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn
