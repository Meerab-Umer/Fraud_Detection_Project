# Credit Card Fraud Detection

## Project Overview

This project detects fraudulent credit card transactions using machine learning techniques.

## Dataset

The project uses the `creditcard.csv` dataset, which contains credit card transaction information and a `Class` column indicating whether a transaction is legitimate or fraudulent.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn
* Jupyter Notebook

## Project Steps

1. Load and explore the dataset.
2. Check missing values and duplicate records.
3. Analyze the transaction classes.
4. Scale the required features.
5. Handle class imbalance using SMOTE.
6. Train machine learning models.
7. Tune the Random Forest model using GridSearchCV.
8. Evaluate model performance.
9. Generate confusion matrices and ROC curves.
10. Compare the model results.

## Machine Learning Models

* Logistic Regression
* Random Forest Classifier

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC

## How to Run

1. Install Python.
2. Install the required libraries using the `requirements.txt` file.
3. Place `creditcard.csv` in the project folder.
4. Open the Jupyter Notebook.
5. Run the notebook cells from top to bottom.

## Project Files

* `creditcard.csv` — Dataset
* `Fraud_Detection.ipynb` — Main Jupyter Notebook
* `requirements.txt` — Required Python libraries
* `README.md` — Project documentation

## Objective

The main objective of this project is to build a machine learning-based system that can identify potentially fraudulent credit card transactions and evaluate different classification techniques.
