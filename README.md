# Used-cars-Price-Prediction
by **Anmol Jindal**.

### Introduction
Predicting the price of second-hand cars is not an easy task.
In recent times, there has been an increase in the demand
for used cars, making it essential to predict the price more
accurately due to consumer exploitation, which can happen
due to high demand. <br>
Predicting the price of a car includes various factors like
mileage, version, location, engine capacity, power steering,
and many more. Collating this information and buying the
perfect fit can take some time and even might not produce
fruitful results.


### Description and Implementation Details
For this project, we have implemented various machine learning aglorithms on the dataset extracted from kaggle. We have used the following steps to reach to our conclusion - <br>

1. Data Cleaning and Preprocessing - In this we first did feature selection, then we encoded the categorical features. Then we handled the null values by either dropping the rows containing the null values or by replacing null values by method of imputation. 
3. Methodology - For this we used various machine learning techniques that best suited our model. These include Linear Regression, Ridge regression, Lasso regression, KNN, Random Forest, AdaBoost, XGBoost. 

### How to Run ? 
The model is deployed on Azure cloud. Just click the link provided in the 'About' section.</br>
**NOTE: This websites works only on desktop/laptop screens.


### Installed dependencies

  import pandas as pd </br>
  import numpy as np </br>
  import matplotlib.pyplot as plt </br>
  import missingno as ms </br>
  from sklearn.preprocessing import LabelEncoder </br>
  from tqdm import tqdm </br>
  from sklearn.experimental import enable_iterative_imputer </br>
  from sklearn.impute import IterativeImputer </br>
  from sklearn.impute import SimpleImputer </br>
  from sklearn.ensemble import RandomForestRegressor </br>
  from sklearn.linear_model import BayesianRidge </br>
  from sklearn.tree import DecisionTreeRegressor </br>
  from sklearn.neighbors import KNeighborsRegressor </br>
  from sklearn.preprocessing import OrdinalEncoder </br>
  from sklearn.model_selection import cross_val_score </br>
  from sklearn.model_selection import RepeatedStratifiedKFold </br>
  from sklearn.ensemble import AdaBoostRegressor </br>
  from sklearn.pipeline import Pipeline </br>
  from sklearn.metrics import mean_squared_log_error,r2_score,mean_squared_error </br>
  from sklearn.linear_model import Ridge </br>
  from sklearn.linear_model import LassoCV,RidgeCV </br>
  from yellowbrick.regressor import AlphaSelection </br>
  import xgboost as xgb </br>
  from sklearn.linear_model import Lasso </br>
  from sklearn.neighbors import KNeighborsRegressor </br>
  import warnings </br>
  warnings.filterwarnings('ignore') </br>

### Contact 
For any further queries feel free to reach out to me. 

Anmol Jindal (anmol19296@iiitd.ac.in) </br>
