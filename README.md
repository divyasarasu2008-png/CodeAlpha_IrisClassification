# Iris Flower Classification

## Project Overview

This project is developed as part of the CodeAlpha Data Science Internship.
It focuses on building a machine learning model to classify iris flowers into different species based on their measurements.

---

## Objective

To classify iris flowers into:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

using supervised machine learning techniques.

---

## Dataset

The dataset used is **Iris.csv**, which contains:

* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm
* Species (Target)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Models Implemented

* Logistic Regression
* Random Forest Classifier

---

## Workflow

1. Load dataset from CSV file
2. Data preprocessing (remove Id column, encode labels)
3. Data visualization using pairplot
4. Feature scaling using StandardScaler
5. Train-test split
6. Train multiple models
7. Evaluate models using:

   * Accuracy
   * Classification Report
   * Confusion Matrix
8. Perform sample prediction

---

## Results

* Achieved **100% accuracy** on test data
* Both models performed perfectly on classification
* Random Forest used for final prediction

---

## How to Run

1. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn

2. Run the program:
   python iris_classification_pro.py

---

## Project Structure

CodeAlpha_IrisClassification/
│
├── iris_classification_pro.py
├── Iris.csv
└── README.md

---

## Author

DIVYA.M

---

## Note

This project is created for educational purposes as part of the internship program.
