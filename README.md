# Wine Quality Prediction Project

## Overview
This repository contains a Jupyter notebook that uses machine learning to predict wine quality based on its chemical properties. The purpose of this project is to help winemakers understand the factors that make wine good or bad, ultimately improving their products.

## Contents
- `Wine Quality Prediction Project.ipynb`: The notebook containing the code for data analysis, preprocessing, model building, and evaluation.
- `winequality.csv`: The dataset used for training and testing the machine learning models (not included in the repo).

## Problem Statement
The goal of this project is to create a predictive model to classify the quality of wine based on chemical properties such as:
- Acidity
- Alcohol content
- Residual sugar
- Chlorides
- pH level
- Sulfates, and more.

## Libraries Used
- **Numpy**: For numerical computations.
- **Pandas**: For data manipulation and loading the dataset.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Matplotlib** & **Seaborn**: For data visualization and exploration.

## Key Analysis and Steps
1. **Data Loading**: Loading the wine quality dataset and performing initial exploration.
2. **Data Preprocessing**: Handling missing values, scaling the data, and applying label encoding to categorical variables.
3. **Model Building**: Building various machine learning models (e.g., Logistic Regression, Random Forest) to predict wine quality.
4. **Model Evaluation**: Evaluating model performance using metrics such as accuracy, precision, recall, and confusion matrices.

## How to Run
1. Clone this repository.
2. Install the necessary Python libraries (listed in `requirements.txt`).
3. Open `Wine Quality Prediction Project.ipynb` using Jupyter Notebook or JupyterLab and run the cells.

## Conclusion
By analyzing the chemical properties of wine, the project successfully creates a predictive model to classify wine quality. This model could assist winemakers in improving their product quality by focusing on key chemical factors.

