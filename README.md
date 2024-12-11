## Data-3010:Customer Satisfaction Classification Project

This repository contains code for a Data 4010 project focused on using machine learning and deep learning to classify customer satisfaction levels based on demographic and flight information. We explored various binary classifier models, ultimately building a custom neural network for this classification task.

#Project Description

The goal of this project is to accurately predict customer satisfaction levels using a dataset of demographic and flight-related information. Several classification models were evaluated, and a neural network was implemented to optimize predictive performance.

# Usage

Data Preparation and Preprocessing

The data required for this project includes demographic details and flight information, which has been preprocessed to optimize for model input.

# Generate and Preprocess Data:

Run data_preprocessing.py to load and preprocess the dataset, handling any missing values and encoding categorical variables as necessary.

# Model Training and Evaluation

The main Jupyter Notebook (Project_Notebook.ipynb) covers model training and evaluation:
- Tests and compares various binary classification models, including logistic regression, decision trees, and support vector machines, to determine which algorithms best fit the data.
- Contains the code for our custom neural network model, designed to improve accuracy in classifying customer satisfaction. The model is evaluated using performance metrics like accuracy, precision, recall, and F1 score.

# Requirements

Ensure you have the following dependencies installed to run the code:

- Python 3.10.4
- Jupyter Notebook
- keras
- matplotlib
- numpy
- pandas
- scikit-learn
- tensorflow
