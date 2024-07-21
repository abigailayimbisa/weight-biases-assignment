# Author : Ayimbisa Abigail 

This repository contains an assignment that explores the concepts of weights and biases in machine learning models,
specifically focusing on logistic regression and decision trees.
The assignment uses the URLset dataset to classify URLs into phishing or non-phishing categories.

# Weights and Biases
Weights and biases are fundamental parameters in machine learning models.

Weights: Weights are coefficients for each input feature in the model. They determine the importance of each feature in predicting the output.
In the context of logistic regression, weights are adjusted during the training process to minimize the error between the predicted and actual outputs.

Biases: Biases are additional parameters in the model that allow the model to fit the data better by shifting the activation function. 
They provide the model with the ability to represent patterns that do not pass through the origin.

In essence, weights and biases work together to define the output of a model given a set of inputs. 
The optimization of these parameters during training is crucial for the model's performance.

# Dataset
The URLset dataset is used to train and evaluate the models. This dataset consists of various features extracted from URLs,
which help in determining whether a URL is legitimate or malicious (phishing).

# Models
Logistic regression is used to classify the URLs into phishing or non-phishing categories. 
It is a statistical model that uses a logistic function to model a binary dependent variable.
The primary goal is to find the best-fitting model to describe the relationship between the 
dependent binary variable and one or more independent variables.

Decision trees are also used to classify the URLs into phishing or non-phishing categories. 
A decision tree is a non-parametric supervised learning method used for classification and regression. 
It splits the data into subsets based on the value of input features, creating a tree-like model of decisions.
Each internal node represents a feature, each branch represents a decision rule, and each leaf node represents an outcome.
