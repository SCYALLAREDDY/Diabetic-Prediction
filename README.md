# Diabetes Prediction Project

## Overview

This project aims to predict the likelihood of diabetes in patients using various machine learning models. The dataset used is the Pima Indians Diabetes dataset, which contains various health metrics and indicators.

## Dataset

The dataset used for this project is the [Pima Indians Diabetes Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv). It includes the following columns:
- `Pregnancies`: Number of pregnancies
- `Glucose`: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: Class variable (0 or 1) where 1 indicates the presence of diabetes

## Project Description

The project includes the following key components:
1. **Data Preprocessing**: Handling missing values, scaling features, and splitting the dataset.
2. **Model Implementation**:
   - **K-Nearest Neighbors (KNN)**: Used for classification with hyperparameter tuning.
   - **Decision Tree**: Implemented to classify diabetes risk and evaluate feature importance.
   - **Random Forest**: An ensemble method used for classification and assessing feature importance.
   - **Support Vector Machine (SVM)**: Used for classification with ROC curve analysis.
3. **Evaluation**: Models are evaluated based on accuracy, confusion matrices, and ROC curves.

## Results

- **K-Nearest Neighbors (KNN)**: Achieved an accuracy of [insert accuracy].
- **Decision Tree**: Achieved an accuracy of [insert accuracy]. Feature importance was analyzed.
- **Random Forest**: Achieved an accuracy of [insert accuracy]. Feature importance was analyzed.
- **Support Vector Machine (SVM)**: Achieved an accuracy of [insert accuracy]. ROC curve analysis was performed.

## Visualizations

- **Feature Correlation Heatmap**: Shows the correlation between different features.
- **Histograms**: Displays the distribution of individual features.
- **Pair Plot**: Illustrates the relationships between features.
- **Box Plots**: Shows feature distributions by outcome.
- **ROC Curves**: Plots for KNN, SVM models to assess classification performance.
- **Confusion Matrices**: Visual representations of model performance for KNN, Decision Tree, Random Forest, and SVM.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/username/repository.git
