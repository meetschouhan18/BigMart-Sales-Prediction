# BigMart-Sales-Prediction
Predicting future sales based on previous years data

Dataset of BigMart Sales was taken from Kaggle..
The dataset consists null values, thus data cleaning was necessary. So the data is cleaned using functions of pandas and numpy libraries.

After cleaning the data, Basic data visualization is performed using Matplotlib library.
Since the data is cleaned, Label and One hot encoding is perfomed on the dataset to convert categorical data into numerical.

After encoding, data is feed to Linear Regression model of Polynomial Degree 3 with the help of Polynomial Features.

After training is done, an accuracy of 79% is obtained.
