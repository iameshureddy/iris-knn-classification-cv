# Iris KNN Classification with Cross-Validation and Decision Boundary Visualization

This repository contains a Python project implementing a K-Nearest Neighbors (KNN) classifier on the famous Iris dataset. The project includes:

- Hyperparameter tuning of the number of neighbors (`K`) using stratified 5-fold cross-validation.
- Selection of the best K value based on mean accuracy.
- Training the final model and evaluation on a hold-out test set.
- Visualization of the confusion matrix.
- Visualization of the decision boundary using the first two features.

## Project Overview

The Iris dataset is a classic dataset in machine learning, containing 150 samples of iris flowers classified into three species: Setosa, Versicolor, and Virginica. The goal is to classify the species based on four features: sepal length, sepal width, petal length, and petal width.

This project demonstrates:
- Data preprocessing with feature scaling.
- Model selection with cross-validation.
- Visualization techniques to interpret model performance and decision boundaries.

## Requirements

- Python 3.7+
- NumPy
- Pandas
- scikit-learn
- matplotlib

You can install the required packages using:

```bash
pip install numpy pandas scikit-learn matplotlib
