*Dependencies are :
import numpy as numpy
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
import sklearn.datasets

from xgboost import XGBRegressor
from sklearn import metrics


/*-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------/*
model is 
model=XGBRegressor()


ERROR ON train data is
R squared error:  0.9999980039471451
Mean Absolute error  0.0091330346494618

ERROR ON test data is
R squared error:  0.9051721149855378
Mean Absolute error  2.0748727686264927

