# IRIS FLOWER CLASSIFICATION USING MACHINE LEARNING
================================================

## PROJECT OVERVIEW
----------------
This project implements supervised machine learning models to classify Iris flower species based on their physical characteristics. The goal is to predict the species of an Iris flower using sepal length, sepal width, petal length, and petal width.

Two classification algorithms are used:
- Logistic Regression
- K-Nearest Neighbors (KNN)

The project also evaluates model performance using accuracy score, confusion matrix, and classification reports.

------------------------------------------------

DATASET
-------
Dataset: Iris Dataset  
Samples: 150  
Features: 4 numerical features  
Target: Flower species (variety)

Features used:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

------------------------------------------------

DATA PREPROCESSING
-----------------
- Dataset loaded using Pandas
- Target labels encoded using LabelEncoder
- Data split into training and testing sets (80% train, 20% test)
- Stratified sampling applied to preserve class balance

------------------------------------------------

MODELS USED
-----------
1. Logistic Regression
   - Trained on the training dataset
   - Used for baseline classification

2. K-Nearest Neighbors (KNN)
   - Number of neighbors: 3
   - Used to compare performance with Logistic Regression

------------------------------------------------

MODEL EVALUATION
----------------
The models are evaluated using:
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

Both models are tested on unseen data to measure generalization performance.

------------------------------------------------

TECHNOLOGIES USED
-----------------
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

------------------------------------------------

HOW TO RUN
----------
1. Clone the repository
2. Install dependencies from requirements.txt
3. Run the Python script:

   python iris_ml.py

------------------------------------------------

AUTHOR
------
Ahmed Sobowale

------------------------------------------------

LICENSE
-------
This project is open-source and available for educational purposes.
