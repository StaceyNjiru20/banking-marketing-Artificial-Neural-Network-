
Bank Marketing Campaign Prediction Using Deep Learning

Project Overview

This project analyzes a banking marketing campaign dataset to predict customer subscription to term deposits, using a deep learning model. By identifying patterns in customer data, we aim to improve marketing strategies for increasing term deposit subscriptions.

Dataset

The dataset contains customer and campaign-related information, with the target variable being whether a customer subscribed to a term deposit (deposit - Yes or No).


Project Steps

Data Import and Exploration: Load and perform an initial analysis of the data.

Data Cleaning: Handle missing values, encode categorical variables, and scale numerical features.  

Model Building: Construct a deep learning model using a neural network to classify subscription outcomes.

Evaluation: Assess model performance using accuracy, precision, recall, and ROC-AUC metrics.

Deep Learning Model Overview

The model is a neural network built with the following configuration:

Architecture: Dense layers with dropout for regularization.

Activation Functions: ReLU for hidden layers and sigmoid for the output layer.

Optimizer: Adam.

Loss Function: Binary Cross-Entropy.

Metrics: Accuracy and AUC.


