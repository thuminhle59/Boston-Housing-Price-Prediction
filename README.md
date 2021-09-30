# BOSTON HOUSING PRICE PREDICTION

The goal of this project is to build and train a classical Machine Learning model using Scikit-learn to predict the housing price of housings in Boston, Massachussets and give an evaluation on the overall performance of the model as well as providing insights about the Boston housing.

## DATASET
The dataset can be accessed here: https://raw.githubusercontent.com/anhquan0412/boston_housing/master/housing.csv.

The Boston housing data was collected in 1978 and consists of 506 entries, each of which represents information about 14 features for homes from suburbs areas in Boston. Data preprocessing has been applied to this dataset, which includes:
  - 16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.
  - 1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.
  - The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.
  - The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation.

## OUTLINE
1. Data Exploration (EDA)
2. Training a Machine learning model
3. Evaluation 
4. Prediction on a new data
5. Applicability
