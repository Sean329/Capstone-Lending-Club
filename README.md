# Capstone-Lending-Club

## Motivation for choosing this project:
On May 5, 2020 LendingClub announced their Q1 2020 earnings. Lenders in the US are being hit hard by the COVID-19 and we are now getting a sense of how significant the impact may be. Revenues dropped 31% to $120.2 million from the prior year period; further more, LendingClub expects originations to fall 90% in Q2 as they have further tightened credit criteria. Investors are also pulling back on funding personal loans.

All the related news above, having happened just in the most recent a couple of days, motivated me to pick this project as my final Capstone Project for the Udacity Data Science NanoDegree.

## Model Achievement:
We are able to build a Neural Network Model on top of the LendingClub loan data to predict the Good/Bad loans at the level of 79% accuracy rate f1-score. Moreover, we refined the model to further reduce overfitting; and customized the model to play more conservative on the Type 2 error side.

Read my blog about it: https://medium.com/@xiangyuxu329/predict-bad-loans-with-deep-learning-3eec489594d5

## Files in this repository:
1. Capstone Project _ Predict Bad Loans with Deep Learning.ipynb -- The detailed logic of everysteps in data extracting, processing, deep learning modeling and discussions.

2. scaler.pkl -- Saved copy of the Data Normalization scaler

3. my_model_lending_club.h5 -- Saved copy of the Neural Networks Model

4. LCDataDictionary.xlsx -- Data Dictionary

## Libaries used in this project:
1. import pandas as pd
2. import numpy as np
3. import matplotlib.pyplot as plt
4. import seaborn as sns
5. from sklearn.model_selection import train_test_split
6. from sklearn.preprocessing import MinMaxScaler
7. from tensorflow.keras.models import Sequential
8. from tensorflow.keras.layers import Dense,Dropout
9. from tensorflow.keras.callbacks import EarlyStopping
10. from tensorflow.keras.models import load_model
11. from sklearn.metrics import confusion_matrix, classification_report
12. from pickle import dump, load
