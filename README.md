# DS605 Lab Assignment 8: Decision Trees and Support Vector Machines

**Course:** DS605 – Fundamentals of Machine Learning

## Overview
This project implements Decision Tree and Linear SVM classifiers from scratch and compares them with Scikit-learn models using the UCI Banknote Authentication dataset.

## Parts
- **Part A:** Manual Decision Tree using Gini impurity and entropy, with tree visualization and decision-boundary comparisons.
- **Part B:** Manual linear soft-margin SVM using hinge loss and gradient/subgradient descent, including margin visualization.
- **Part C:** Comparison of linear, polynomial, and RBF SVM kernels on nonlinear data.
- **Part D:** Final model evaluation using all four Banknote features, with accuracy, precision, recall, F1-score, training time, and prediction time.

## Dataset
UCI Banknote Authentication dataset: 1,372 samples, four input features, and two classes.

## How to Run
Open `DS605_Lab08_Decision_Trees_SVM.ipynb` in Google Colab or Jupyter Notebook and run the cells in order.

## Key Observations
The experiments compare model performance, interpretability, feature scaling, overfitting, and computational cost. On the evaluated test split, the RBF SVM achieved the highest reported accuracy.

## Files
- `DS605_Lab08_Decision_Trees_SVM.ipynb` — implementations, experiments, visualizations, and results.
