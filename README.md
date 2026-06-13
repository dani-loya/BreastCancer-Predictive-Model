------------------------------------------------------------------------

# **Breast Cancer Predictive Modeling**

<div align="center">
  <img src="images/WBC.png" width="600">
</div>

## Installation

1.  To reproduce this analysis, install the required packagesin R: "tidyverse", caret", "e1071, "randomForest", "pROC" and "rprojroot"

- Use this R code:

  install.packages(c( "tidyverse", "caret", "e1071", "randomForest", "pROC", "rprojroot" ))

2.  Clone the repository:

- Go to your terminal and type:

  git clone <https://github.com/dani-loya/BreastCancer-Predictive-Model.git>

3.  Open the project:

- Open BreastCancer-Predictive-Model.Rproj

- Open scripts/WBC_analysis.Rmd

- Run all chunks to reproduce this analysis

------------------------------------------------------------------------

## Abstract

This project applies machine learning to the Wisconsin Diagnostic Breast Cancer dataset to classify tumors as 'benign' or 'malignant'. After pre-processing and feature scaling, multiple models were trained and evaluated: Logistic Regression, KNN, SVM, and Random Forest. The models achieved high accuracy, with SVM and Random Forest which show the strongest performance and clear separation between diagnostic classes.

------------------------------------------------------------------------

## Problem Statement

Breast cancer diagnosis often relies on manual interpretation of cell features, which can be prone to human errors and time consuming. This project evaluates some machine learning algorithms to determine which model most accurately and reliably predicts tumor malignancy using measurable features extracted from digitized breast tissue images, which are the microscope images of breast tissue that were converted to numerical measurements.

------------------------------------------------------------------------

## Goals

- Build a reproducible machine‑learning workflow for breast cancer classification
- Explore and visualize key predictors that differentiate benign and malignant tumors
- Train multiple classification models and compare their performance
- Identify the most important features contributing to diagnostic accuracy
- Produce a clear, well‑documented analysis suitable for academic or professional review

## Non‑Goals

- Developing a clinical‑grade diagnostic tool
- Deploying a real‑time prediction system or web application
- Performing deep learning or neural network modeling
- Collecting new medical data or conducting clinical trials
- Providing medical advice or treatment recommendations

------------------------------------------------------------------------

## Video Presentation

link for final video presentation will be added here

------------------------------------------------------------------------

## References

- UCI Machine Learning Repository: Wisconsin Diagnostic Breast Cancer Dataset\
  Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993). Breast Cancer Wisconsin (Diagnostic) [Dataset]. UCI Machine Learning Repository.<https://doi.org/10.24432/C5DW2B/>
- Classification methods: logistic regression, K‑nearest neighbors, support vector machines, and ensemble models.\
  Hastie, Tibshirani, & Friedman — The Elements of Statistical Learning: Data Mining, Inference, and Prediction. Springer.<https://hastie.su.domains/ElemStatLearn/>
