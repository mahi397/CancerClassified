# Breast Cancer Classification model

Predicting breast cancer using a machine learning model

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not somebody has breast cancer.

## 1. Dataset

[Wisconsin Diagnostic Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)): This dataset has 569 samples with 32 attributes.

## 2. Features

Attribute information:

* ID number
* Diagnosis (M = malignant, B = benign)
* 3-32: Ten real-valued features are computed for each cell nucleus:
  * a) radius (mean of distances from center to points on the perimeter)
  * b) texture (standard deviation of gray-scale values)
  * c) perimeter
  * d) area
  * e) smootness (local variation in radius lengths)
  * f) compactness (perimeter^2 / area - 1.0)
  * g) concavity (severity of concave portions of the contour)
  * h) concave points (number of concave portions of the contour)
  * i) symmetry
  * j) fractal dimension ("coastline approximation" -1)


## 3. Evaluation

The project will be considered successful if we reach accuracy score higher than 95.8% at predicting whether the patient has a malignant or benign tumor.
