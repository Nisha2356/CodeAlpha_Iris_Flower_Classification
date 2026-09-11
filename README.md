# CodeAlpha_Iris_Flower_Classification
Machine learning project for Iris flower species classification using Scikit-learn.
# 🌸 Iris Flower Classification — CodeAlpha Task 1

## 📌 Project Overview

This project focuses on classifying Iris flowers into three species — **Iris Setosa, Iris Versicolor, and Iris Virginica** — using machine learning.

The model uses four flower measurements as input:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

A **Logistic Regression** classification model is trained using **Scikit-learn**.

## 🎯 Objectives

* Understand basic classification concepts in Machine Learning.
* Explore and preprocess the Iris dataset.
* Train a classification model using Scikit-learn.
* Evaluate model performance using test data.
* Use accuracy, classification report, and confusion matrix for evaluation.
* Predict the species of a new Iris flower.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📊 Dataset

The project uses the Iris dataset containing **150 observations** belonging to three species:

| Species         | Samples |
| --------------- | ------: |
| Iris Setosa     |      50 |
| Iris Versicolor |      50 |
| Iris Virginica  |      50 |

## 🤖 Machine Learning Model

**Algorithm:** Logistic Regression

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

Feature scaling was performed using `StandardScaler`.

## 📈 Model Performance

The model achieved:

**Accuracy: 93.33%**

The project also includes:

* Classification Report
* Confusion Matrix
* Iris species visualization
* New flower prediction

## 📂 Project Structure

```text
CodeAlpha_Iris_Flower_Classification/
│
├── Task_1_Iris_Flower_Classification.ipynb
├── Iris.csv
├── confusion_matrix.png
├── iris_species_distribution.png
└── README.md
```

## 🔍 Example Prediction

The trained model can predict the species of a new flower using measurements such as:

```text
Sepal Length = 5.1 cm
Sepal Width  = 3.5 cm
Petal Length = 1.4 cm
Petal Width  = 0.2 cm
```

The model predicts:

**Iris-setosa**

## ✅ Conclusion

This project demonstrates the complete basic workflow of supervised machine learning, from dataset exploration and preprocessing to model training, prediction, and evaluation.

It provides practical understanding of how classification algorithms can be used to identify flower species from numerical measurements.

---

### 👩‍💻 Author

**Nisha Nayak**

BCA Student | Aspiring Data Analyst & Web Developer

### 📌 CodeAlpha Internship

**Task 1 — Iris Flower Classification**
