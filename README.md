CSCI-164-FINAL-PROJECT

######USE StudentGradePrediction.ipynb with student-mat.csv
For regression task, predict G3
For classification task, predict pass/fail

USE WineQualityPrediction.ipynb with winequality-red.csv##########









CSCI-164 project using Linear Regression, KNN, Naive Bayes, MLP
I developed machine learning models to analyze two datasets from the UCI Machine Learning Repository: the Wine Quality dataset and the Student Performance dataset. These datasets represent two subjects wine quality and education - demonstrating how machine learning can be applied across different fields to solve real-world problems.

Overview:

Wine Quality: A dataset used to predict wine quality scores based on laboratory measurements, understanding chemical factors that influence wine ratings and how automated ratings could be right or wrong.
Student Performance: An educational dataset used to predict student academic outcomes based on demographic, social, and school-related features.
Tools: Python's scikit-learn library.

K-Nearest Neighbors and Neural Networks for wine quality classification/regression
Linear Regression and Naive Bayes for student performance prediction
Preprocessing pipelines using StandardScaler and OneHotEncoder
Hyperparameter optimization using GridSearchCV
Results:

Wine Quality: MLP classifier achieved good accuracy in binary classification, effectively identifying key chemical properties that influence wine quality including alcohol content and volatile acidity.
Student Performance: Naive Bayes classifier demonstrated good accuracy in pass/fail prediction, with strong predictive power from features like previous grades and study time.
