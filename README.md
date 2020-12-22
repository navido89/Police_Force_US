<img src="images/police.jpg">

<!-- Add buttons here -->
![Follow me at Twitter](https://img.shields.io/twitter/follow/NMashinchi?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/navido89/Time-Series-Analysis-ARIMA-Model-Covid19-Predictions)

# Police_Force_US
**Project Status: Completed**
<br>
<a href="https://nbviewer.jupyter.org/github/navido89/Police_Force_US/blob/main/Police%20Force%20Project.ipynb" target="_blank">Jupyter Notebook Viewer</a>
<br>
<a href="https://towardsdatascience.com/an-examination-of-fatal-force-by-police-in-the-us-db897d97085c" target="_blank">Read Article</a>

## Table of contents
- [Project Objective](#project-objective)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Project Description](#project-description)
- [Project Results](#project-results)
- [Installation](#installation)

## Project Objective
[(Back to top)](#table-of-contents)
<br>
The purpose of this project is to examine the factors that play into the horrible event of a fatal shooting by the police in the US. Which ones carry more weight that lead to fatal shootings and are perhaps predictive in nature? Are they race? State location? Mental Illness? Based on our findings from the dataset of the available variables, we are looking to predict the deceased’s race or mental illness status.


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
