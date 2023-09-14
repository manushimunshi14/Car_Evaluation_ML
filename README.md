# Car_Evaluation_ML
This repository contains the code and documentation for a machine learning project focused on car evaluation. The goal of this project is to perform EDA on a car evaluation dataset and  build a predictive model that can classify cars into different evaluation categories based on their features.

# Data
The dataset used for this project is the Car Evaluation Dataset from the UCI Machine Learning Repository. This dataset contains various features of cars, including their price, maintenance cost, number of doors, number of passengers, luggage capacity, safety rating, and more. The target variable is the car's evaluation category, which can be one of "unacceptable," "acceptable," "good," or "very good."
Dataset link - https://archive.ics.uci.edu/ml/datasets/Car+Evaluation

# Installation
To run this project, you need to have Python 3.x and the following libraries installed:

1. numpy
2. pandas
3. scikit-learn
4. matplotlib
5. seaborn

# Machine Learning Models 
1. Logistic Regression
2. K-Nearest Neighbours Classifier
3. Support Vector Machine (SVM) Classifier
4. Decision Tree
5. Random Forest Classifier
We have performed grid search to find best parameters for all the models. Further, we have also implemented a voting classifier to create an ensemble model of all the machine learning models implemented. The best accuracy achieved is 98.92% with SVM classifier. 

#

