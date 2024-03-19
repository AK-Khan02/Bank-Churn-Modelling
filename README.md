# Bank Customer Churn Prediction

## Overview

This repository hosts a series of machine learning models aimed at predicting churn among bank customers. Churn prediction is critical for banks to identify at-risk customers and to develop strategies for improving customer retention. The models included span a range of complexity and approaches, from simple linear models to sophisticated ensemble and neural network models.

## Models Included

### Logistic Regression Model (Baseline)
This model serves as the baseline for our predictions. Logistic regression is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). In this case, it is used to model the probability of a customer churning. It is simple, fast, and provides a useful reference point for the performance of more complex models.

### Decision Tree Model
A decision tree is a flowchart-like tree structure where an internal node represents a feature(or attribute), the branch represents a decision rule, and each leaf node represents the outcome. The decision tree model is intuitive and easy to interpret, as it mirrors human decision-making more closely than other models.

### Random Forest Model
This is an ensemble learning method that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification) of the individual trees. Random forests correct for decision trees' habit of overfitting to their training set.

### Neural Network
A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. In this context, it can identify complex patterns and relationships that other algorithms might miss, which might be crucial for churn prediction.

### Shallow Neural Network Model
The shallow neural network consists of fewer hidden layers and neurons, which makes it less complex and quicker to train than its deep counterparts. This model can be effective if the relationships in the data are comparatively straightforward and do not require the deeper learning that more layers offer.

### Deep Neural Network
This is a more sophisticated version of a neural network with multiple hidden layers. These layers enable the model to learn deep non-linear relationships within the data. It is a powerful model that can capture a high level of complexity in the dataset, but it also requires more data and longer training times.

### XGBoost Model
XGBoost stands for eXtreme Gradient Boosting and is an implementation of gradient boosted decision trees designed for speed and performance. It is a highly sophisticated algorithm renowned for its performance on structured and tabular data.

## Data

Contained within this repository is a dataset detailing various customer characteristics and their churn status. This data is fundamental to training the predictive models. Prior to model training, this data undergoes several preprocessing steps to ensure it is in a suitable format for the algorithms.

## Preprocessing

The preprocessing phase is crucial for transforming raw data into a format that can be fed into machine learning algorithms. This includes handling missing values, encoding categorical variables, normalizing numerical features, and partitioning the data into training and test sets to ensure the robustness of our models.
