# Weight Category Prediction 

This machine learning model uses various features to predict the weight category of an individual, such as their height, age, gender, and body measurements.And based on that we can analyze that the individual is Extremely obese,Obesity,Overweight,Normal,weak,Extreme weak.

# Getting Started

To get started with this model, you will need to have the following libraries installed:

#for manupulations
import pandas as pd
import numpy as np

#for data visualizations
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

#for ignore warning messages
import warnings
warnings.filterwarnings("ignore")

Programming Language:
#Python -3.9.7

Jupyter Notebook version- v6.5.3

# Dataset

The dataset has 500 rows and 4 columns which includes records of individuals' height, age, gender, and body measurements, along with their weight category.By using it we can analyze various things such as stats for men and women, checking the value counts, descriptive statistics etc...


# Training the Model

For model training, we use RandomForestClassifier Algorithm is used and get the accuracy as 87.3333.

# Conclusion

The Dataset has 500 rows and 4 columns.In this dataset we perform EDA, descriptive statistics and data visualization by using various libraries and using RandomForestClassifier model in various applications where weight category prediction is important, such as in the health and fitness industry. 

The accuracy of the model is 87.3333
