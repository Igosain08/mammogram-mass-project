
# Mammogram Mass Prediction: Benign or Malignant

## Overview
This project uses various supervised machine learning techniques to predict whether a mammogram mass is benign or malignant based on patient attributes such as age, mass shape, margin, and density. The dataset comes from the UCI Machine Learning Repository.

## Dataset
- **Source**: [Mammographic Masses Data Set - UCI](https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass)
- **Attributes**:
  - **Age**: Patient's age in years (integer).
  - **Shape**: Mass shape (round=1, oval=2, lobular=3, irregular=4).
  - **Margin**: Mass margin (circumscribed=1, microlobulated=2, obscured=3, ill-defined=4, spiculated=5).
  - **Density**: Mass density (high=1, iso=2, low=3, fat-containing=4).
  - **Severity**: Target variable (benign=0, malignant=1).

## Project Goal
The goal is to apply several supervised machine learning techniques to predict the severity of mammogram masses, and identify which model provides the highest accuracy.

## Techniques Implemented
The following algorithms were applied to the dataset:
1. Decision Tree
2. Random Forest
3. K-Nearest Neighbors (KNN)
4. Naive Bayes
5. Support Vector Machine (SVM)
6. Logistic Regression
7. Neural Network (using Keras)

### Evaluation
Each model was evaluated using **10-Fold Cross Validation** to obtain reliable accuracy scores.

## Requirements
To run this project, you need the following libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `tensorflow` (for the neural network model)
- `matplotlib` (optional for visualizations)

Install the dependencies using:
```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
