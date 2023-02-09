# Logistic-Regression-on-Titanic-Dataset
This code work on titanic.csv file,where we apply logistic regression and find out the accuracy of the data with X=("Age","Farw")and Y=("survived").
to apply this we need to do the following:

#import libraries
import pands as pd

import matplotib.pyplot as plt

#import dataset

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression

from sklearn.metrics import accuracy_score
Y_predict= model.predict(X_test)

print(accuracy_score(Y_predict,Y_test))
