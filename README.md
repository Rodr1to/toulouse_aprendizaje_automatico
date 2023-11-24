# Machine Learning Analysis of Penguin Data
## Introduction
#### This document presents an analysis of a penguin dataset as part of the ‘Machine Learning’ module at the Peruvian institution, Instituto Superior Tecnológico Toulouse Lautrec. The objective of this analysis is to predict the species of a penguin based on various physical characteristics.

## Data Collection
#### The Palmer Penguins dataset was loaded from a URL in CSV format using Python’s pandas library.

## Data Preparation
#### The data was cleaned by removing rows with null values. Categorical variables were encoded using pandas’ get_dummies method. Numerical variables were normalized using StandardScaler from the sklearn library.

## Model Selection
#### For this dataset, the K-Nearest Neighbors algorithm was chosen. It is a simple but powerful algorithm that can handle both categorical and numerical variables.

## Model Training
#### Once the data was prepared and the model was chosen, the model was trained. This involved splitting the dataset into a training set and a test set. Then, the KNN model was created and fitted using the training set.

## Model Evaluation
#### After training the model, its performance was evaluated by making predictions on the test set and calculating the model’s accuracy.

## Inference Prediction
### Finally, the trained model was used to make predictions on new data. A new penguin was defined with certain characteristics, these characteristics were normalized using the same scaler that was used for the training data, and then a prediction was made using the model.
