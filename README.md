# Predicting Rain in Australia
Predicting whether it will rain "tomorrow" in Australia: Machine Learning Project.

## Objective
Train two classical machine learning and two neural models to predict whether it will rain "tomorrow" using an Australian weather-based dataset.

## Data Exploration 
The first step when tackling any new dataset is data exploration, so we can get a better idea of what our data looks like. Our dataset includes 145460 rows, of which only 56420 remain after dropping missing values. 

Our data is quite imbalanced, with only 22% of our rows being days where it rains the next day (after dropping missing values).

The dataset includes 23 columns pertaining to the weather of a given day, its location, date and the variable we want to predict: whether it rained the next day. 

## Models
### Classical Models
1. Logistic Regression 
2. Ranfom Forest Classifier

### Neural Models
1. Simple Recurrent Neural Network (RNN)
2. Binary Classification Model

## Dependencies
imbalanced-learn
python 3.8.12
