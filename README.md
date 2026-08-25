# Regression and Classification Error Analysis of LEGO Sets

## Student Information

* **Student:** Yuval Kravchik
* **Course:** Data Science
* **Assignment:** Homework 2 – Regression and Classification: Error Analysis

## Project Description

This project presents a regression and classification analysis of a LEGO sets dataset, with a focus on model performance and systematic error analysis.

The analysis uses k-fold cross-validation and investigates not only overall predictive performance, but also where and why the models fail.

The project includes:

* Data preprocessing and feature preparation
* 5-fold cross-validation
* Regression residual analysis
* Error analysis as a function of features
* Analysis of extreme regression errors
* Statistical analysis of residuals
* Comparison of Linear Regression, Decision Tree Regressor, and Random Forest Regressor
* Confusion matrix analysis
* False Positive and False Negative analysis
* Probability-based classification error analysis
* Feature-based classification error analysis
* Threshold sensitivity analysis
* Precision, Recall, F1-score, F-beta, MCC, and ROC-AUC evaluation
* Comparison of Logistic Regression, Decision Tree, and Random Forest classifiers
* Final discussion of model limitations, failure modes, and possible improvements

## Dataset

The original dataset contains **18,457 LEGO sets**.

After preprocessing and filtering:

* **Regression dataset:** 6,982 observations
* **Classification dataset:** 18,457 observations

## Cross-Validation

A **5-fold cross-validation** procedure is used throughout the analysis.

The data are shuffled before splitting and a fixed random state is used for reproducibility.

The choice of k=5 provides a balance between computational cost and the bias-variance trade-off, while also providing sufficiently large validation subsets and allowing each model to train on approximately 80% of the available observations in each fold.

## Files

* `Yuval_Kravchik_Lego_Task2.ipynb` – Complete Jupyter Notebook
* `lego_sets.csv` – Source dataset
