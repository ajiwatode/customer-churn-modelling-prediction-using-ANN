# Customer-churn-modelling-prediction-using-ANN
Churn prediction aims to detect customers intended to leave a service provider.Here the prediction is done on bank customers.This modelling enables the companies or organisations to identify the areas where they lag behind, thereby enabling them to rectify those issues and also aid in increasing the retention rate.he machine learning technique used in this project is Artificial Neural Network without momentum.

# Overview

This project involves building an Artificial Neural Network (ANN) for predicting customer churn. The dataset used contains various customer attributes, and the ANN is trained to predict whether a customer is likely to leave the bank.

![Customer_Churn_Prediction_Models_in_Machine_Learning](https://github.com/ajiwatode/customer-churn-modelling-prediction-using-ANN/assets/139065906/c65746d1-0e56-4a65-9f6b-b2101673c689)

# Files

1.artificial_neural_network(Customer Churn Prediction).ipynb: Jupyter Notebook containing the code for data preprocessing, model building, training, and evaluation.

2.Churn_Modelling.csv: Dataset used for training and testing the ANN.


# Workflow

a.Importing Libraries: Necessary libraries such as NumPy, Pandas, TensorFlow, and Keras are imported.

b.Data Preprocessing: The dataset is loaded, and data preprocessing steps include handling categorical data, label encoding, one-hot encoding, splitting the dataset, and feature scaling.

c.Building the ANN: A Sequential model is created using TensorFlow and Keras. The model architecture consists of an input layer, two hidden layers with ReLU activation, and an output layer with sigmoid activation.

d.Training the ANN: The model is compiled using the Adam optimizer and binary crossentropy loss. It is then trained on the training set for 100 epochs.

e.Making Predictions and Evaluating the Model: Predictions are made on the test set, and the model's performance is evaluated using a confusion matrix and accuracy score.


# Dataset

The considered data set contains details of a bank's customers and the target variable is a binary variable reflecting the fact whether the customer leave the bank (closed his account) or he continues to be a customer. Dataset can be found in the repository or download the dataset from https://www.kaggle.com/shrutimechlearn/churnmodelling?select=Churn_Modelling.csv 

# Result

Model that is built gives the training accuracy of 90% and a testing accuracy of 84%.





