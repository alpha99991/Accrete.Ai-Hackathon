# Accrete.Ai-Hackathon

The Problem Statement was to build a model to predict the top 100 M&A Rumors based on the features provided by the company.
The details of what each feature means was provided in the VariableKey.pdf file

SOLUTION Summary: 

Original solution is provided in the notebook

# 1.) I formulated the problem as a binary classification problem by creating labels based on ordering of the feature engineered column 'STRENGTH' ( by taking product of RELIABILITY AND CREDIBILITY). Thus the top 100 rumors grouped by a month was labelled as 1 and the rest for the month was labelled as 0.

# 2.) Almost all traditional classification models were applied like KNN, Random Forest, Logistic Regression, SVM, A deep neural network.

# 3.) I shuffled the data and chose the best splitting of train and test for which the validation score was highest.
