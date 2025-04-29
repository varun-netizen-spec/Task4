Task 4: Classification with Logistic Regression
Objective:
Build a binary classifier using Logistic Regression to predict cancer diagnosis (Malignant or Benign).

Dataset:
Breast Cancer Wisconsin Dataset

Target column: diagnosis (M = Malignant, B = Benign)

Tools Used:
Python
Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Steps:
Import and Load Data

Load the dataset using pandas.

Drop the id column.

Convert diagnosis column to binary (M = 1, B = 0).

Preprocessing

Standardize features using StandardScaler.
Train/Test Split

Split data into training and testing sets (80/20).

Model Training

Train a Logistic Regression model using LogisticRegression from sklearn.linear_model.

Model Evaluation

Evaluate using:

Confusion Matrix

Precision and Recall

Accuracy Score

ROC-AUC Score
Plot:

Confusion Matrix using seaborn.heatmap

ROC Curve using matplotlib
