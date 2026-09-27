# Heart Disease Prediction using Machine Learning

## Project Overview

This project focuses on predicting heart disease using machine learning classification algorithms. The `heart.csv` dataset is used to train and evaluate different machine learning models.

The project explores:

* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Logistic Regression

The models are evaluated using common classification metrics such as Accuracy, Precision, Recall, and F1 Score.

## Dataset

The dataset used in this project is:

`heart.csv`

It contains the following features:

* `age` – Age
* `sex` – Sex
* `cp` – Chest pain type
* `trestbps` – Resting blood pressure
* `chol` – Cholesterol
* `fbs` – Fasting blood sugar
* `thalach` – Maximum heart rate achieved
* `exang` – Exercise-induced angina
* `oldpeak` – ST depression
* `ca` – Number of major vessels
* `target` – Target variable for heart disease prediction

## Machine Learning Models

### 1. K-Nearest Neighbors (KNN)

A KNN classifier is implemented with `k = 5`.

Different values of `k` are also tested:

* k = 1
* k = 3
* k = 5
* k = 7
* k = 9

### 2. Decision Tree

A Decision Tree classifier is trained using the training data.

Different maximum depths are tested:

* Depth = 2
* Depth = 3
* Depth = 4
* Depth = 5
* Depth = None

### 3. Random Forest

A Random Forest classifier is implemented using 100 estimators.

Different combinations of:

* Number of estimators: 50, 100, 200
* Maximum depth: 3, 5, None

are tested.

### 4. Logistic Regression

Logistic Regression

