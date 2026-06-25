# Iris Classification using KNN, SVM, and Decision Tree

## Project Overview

This project demonstrates the implementation and comparison of three popular Machine Learning classification algorithms: Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree using the Iris Dataset.

The objective is to classify iris flowers into different species based on their sepal and petal measurements and evaluate the performance of each algorithm.

---

## Dataset Information

The Iris dataset is one of the most widely used datasets in Machine Learning.

### Dataset Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Classes

* Setosa
* Versicolor
* Virginica

### Dataset Size

* 150 Samples
* 3 Classes
* 4 Features

---

## Algorithms Implemented

### 1. Support Vector Machine (SVM)

Support Vector Machine is a supervised learning algorithm used for classification tasks.

#### Kernels Used

* Linear Kernel
* RBF Kernel
* Polynomial Kernel
* Sigmoid Kernel

#### Advantages

* Effective in high-dimensional spaces
* Works well with clear margin separation

#### Limitations

* Computationally expensive for large datasets
* Requires proper kernel selection

---

### 2. K-Nearest Neighbors (KNN)

KNN classifies data points based on the majority class among the nearest neighbors.

#### Working Process

1. Select value of K
2. Calculate distances
3. Identify nearest neighbors
4. Assign majority class

#### Advantages

* Easy to understand
* No training phase required

#### Limitations

* Slow on large datasets
* Sensitive to K value

---

### 3. Decision Tree

Decision Tree is a supervised learning algorithm that splits data into branches based on feature values.

#### Advantages

* Easy to interpret
* Works with numerical and categorical data
* No feature scaling required

#### Limitations

* Can overfit data
* Sensitive to data variations

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix

### Observations

* SVM with RBF Kernel achieved the highest accuracy.
* KNN performance depended on the selected K value.
* Decision Tree provided interpretable results with good accuracy.

---

## Results

| Algorithm     | Performance |
| ------------- | ----------- |
| SVM (RBF)     | Best        |
| KNN           | Moderate    |
| Decision Tree | Good        |

---

## Key Learnings

* Different algorithms perform differently on the same dataset.
* Kernel selection significantly affects SVM performance.
* Choosing the correct K value is important in KNN.
* Decision Trees are easy to understand but may overfit.
* Model comparison helps identify the most suitable algorithm.

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature engineering
* Testing on larger datasets
* Ensemble learning methods

---

## Author

Bijil Biju





