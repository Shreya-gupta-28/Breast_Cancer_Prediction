# Breast_Cancer_Prediction
This project applies Logistic Regression on the Breast Cancer dataset to evaluate how well the model can classify tumors.  The notebook focuses on model training and performance evaluation using accuracy score and a confusion matrix.  It demonstrates a simple binary classification workflow using logistic regression.


Project Overview:
Uses Logistic Regression for binary classification
Dataset: Breast Cancer Wisconsin dataset from scikit-learn
Includes:
-Data loading & preprocessing
-Splitting into train/test sets
-Model training
-Evaluating performance
-Accuracy score
-Confusion matrix

Model Performance:
Accuracy Score: 97.37%
Confusion Matrix:
Shows how many samples were correctly and incorrectly classified into the two output classes.

Tech Stack:
-Python
-NumPy
-Pandas
-Scikit-learn
-Google colab 

Project Structure:
📂 Breast-Cancer-Logistic-Regression
│── logistic_regression(breast_cancer).ipynb  # Main notebook
│── README.md                                 # Project documentation

How to Run:
Clone the repository:
git clone <your-repo-link>

Install required packages:
pip install -r requirements.txt

Open the notebook:
jupyter notebook logistic_regression(breast_cancer).ipynb

Future Improvements:
-Display predicted labels (benign / malignant)
-Add ROC curve & AUC score
-Add hyperparameter tuning
-Try models like SVM, Random Forest, KNN
