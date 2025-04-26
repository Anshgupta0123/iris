# IRIS Flower Prediction

A machine learning project for classifying iris flowers into their species based on sepal and petal measurements. Implemented in a Jupyter Notebook using the classic Iris dataset.

---

## 🌸 Project Overview

This repository demonstrates supervised machine learning for multi-class classification using the Iris dataset. The notebook guides you through data analysis, visualization, model building, and prediction of iris species (*Iris-setosa*, *Iris-versicolor*, *Iris-virginica*).

---

## 📂 Dataset Description

The Iris dataset contains 150 samples with the following features:

| Feature        | Description                   | Range      |
|----------------|------------------------------|------------|
| sepal_length   | Sepal length in centimeters  | 4.3–7.9    |
| sepal_width    | Sepal width in centimeters   | 2.0–4.4    |
| petal_length   | Petal length in centimeters  | 1.0–6.9    |
| petal_width    | Petal width in centimeters   | 0.1–2.5    |
| species        | Target class (flower species)| 3 classes  |

**Sample Data:**

| sepal_length | sepal_width | petal_length | petal_width | species         |
|--------------|-------------|--------------|-------------|----------------|
| 5.1          | 3.5         | 1.4          | 0.2         | Iris-setosa    |
| 4.9          | 3.0         | 1.4          | 0.2         | Iris-setosa    |
| 4.7          | 3.2         | 1.3          | 0.2         | Iris-setosa    |
| ...          | ...         | ...          | ...         | ...            |
| 6.7          | 3.0         | 5.2          | 2.3         | Iris-virginica |
| 6.3          | 2.5         | 5.0          | 1.9         | Iris-virginica |
| 6.5          | 3.0         | 5.2          | 2.0         | Iris-virginica |

**Statistical Summary:**

| Statistic | sepal_length | sepal_width | petal_length | petal_width |
|-----------|--------------|-------------|--------------|-------------|
| count     | 150.000      | 150.000     | 150.000      | 150.000     |
| mean      | 5.843        | 3.054       | 3.759        | 1.199       |
| std       | 0.828        | 0.434       | 1.764        | 0.763       |
| min       | 4.300        | 2.000       | 1.000        | 0.100       |
| 25%       | 5.100        | 2.800       | 1.600        | 0.300       |
| 50%       | 5.800        | 3.000       | 4.350        | 1.300       |
| 75%       | 6.400        | 3.300       | 5.100        | 1.800       |
| max       | 7.900        | 4.400       | 6.900        | 2.500       |

---

## ✨ Features

- **Data Exploration:** Statistical summary and visualization of feature distributions.
- **Preprocessing:** Handling missing values, encoding categorical variables, and scaling.
- **Model Building:** Training classifiers (e.g., Logistic Regression, Decision Tree, SVM).
- **Evaluation:** Accuracy, confusion matrix, and classification report.
- **Prediction:** Predicting species from new measurements.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Install dependencies:

## ⚡ Quickstart

### 1. Install Requirements

pip install numpy pandas scikit-learn matplotlib seaborn



### 2. Run the Notebook

- Download `IRIS_FLOWER_PREDICTION.ipynb`.
- Open a terminal and start Jupyter Notebook
- Open the notebook file in your browser.

### 3. Execute

- Run all cells in order.
- To predict a new flower, change the input values in the prediction cell and run it.

---
