# Police_Force_US

+ The goal of this project was to examine the factors that play into the horrible event of a fatal shooting by the police in the US.

+ A dataset from the Washington Post was used, which had over 5700 data points. Cleaned the data by using pandas. As far as feature engineering, 9 out of the total 17 variables type had to be transformed into different types.

+ In relation to predicting the status of mental illness, I worked with sklearn. Implemented a Logistic Regression, SVC, SGD, Decision Tree and Random Forest. Used RandomizedSearchCV to fine tune the final model (Random Forest) and improved the accuracy score by 7%.

## To run the jupyter notebook you would need the following libraries (or at least the most up to date versions):

+ import pandas as pd
+ import numpy as np
+ import re
+ import seaborn as sns
+ import matplotlib
+ import matplotlib.pyplot as plt
+ import copy
+ import geopandas
+ import folium
+ import geopy
+ from geopy.geocoders import Nominatim
+ from branca.element import Template, MacroElement
+ from matplotlib import pyplot
+ from sklearn import preprocessing
+ from sklearn.linear_model import LogisticRegression
+ from sklearn.preprocessing import StandardScaler
+ from sklearn.metrics import accuracy_score
+ from sklearn.svm import SVC
+ from sklearn.tree import DecisionTreeClassifier
+ from sklearn.ensemble import RandomForestClassifier
+ from prettytable import PrettyTable
+ from sklearn.model_selection import cross_val_score
+ from sklearn.model_selection import RandomizedSearchCV
