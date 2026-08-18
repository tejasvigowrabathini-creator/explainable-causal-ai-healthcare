# Explainable AI for Healthcare Risk Prediction

## Overview
This repository contains a machine learning study using clinical healthcare data (Pima Indians Diabetes Dataset) to predict early disease risk. The project focuses on data quality analysis, missing value handling, exploratory data analysis (EDA), and baseline predictive modeling while emphasizing model interpretability.

## Dataset
- **Source:** Pima Indians Diabetes Dataset (768 patient records, 9 clinical features)
- **Features:** Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
- **Target:** Diabetes Outcome (0 = No Diabetes, 1 = Diabetes)

## Project Workflow
1. **Exploratory Data Analysis (EDA):** Feature distributions, outcome balance analysis, and data quality checks (identifying zero values in clinical variables).
2. **Preprocessing:** Handling missing/implausible zero values in biological indicators (Glucose, BMI, BP).
3. **Model Development:** Baseline classification models evaluated using ROC-AUC and Recall.
4. **Interpretability:** Evaluating feature importance (e.g., Glucose and BMI) to understand model decisions.

## How to Run
1. Open `NOTEBOOKS/01_EDA.ipynb` in Google Colab or Jupyter Notebook.
2. Run all cells sequentially to reproduce the visualizations and summary statistics.

## Tech Stack
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
