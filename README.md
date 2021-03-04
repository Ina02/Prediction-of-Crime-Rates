## Objective
The goal of this project is to analyze the Chicago Crimes Dataset, classify the crimes and
build a model that predicts the crime for 2017-2020.

## Proposed Approach
The proposed approach for predicting occurrence of crime is by Linear Regression Model and Linear Ridge Regression model .

Linear Regression is a good supervised learning algorithm which is used for predictions problems, it finds the target variable by finding a best suitable fit line between the independent and dependent variables.

## High Level System Architecture
● Numpy - fundamental package for scientific computing with Python.
● Pandas - software library written for the Python programming language for data manipulation and analysis.
● Matplotlib - visualization library in Python for 2D plots of arrays.
● Seaborn- Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
● Math- The math module is a standard module in Python. It provides access to the mathematical functions defined by the C standard.

## Data Requirements
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to 2017. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.
We downloaded this dataset from the kaggle website where it was available in the form of four csvs (crime rates in chicago 2001-04, 2005-07, 2008-11 and 2012-17 respectively).
https://www.kaggle.com/currie32/crimes-in-chicago

## Conclusions
On Analyzing the Chicago Crimes Data, it was observed that maximum crimes occur on Streets and Residence areas, and the types of crimes that occur most frequently are Theft and Battery. Moreover maximum crimes have occured in 2008. It’s alarming that the number of arrests are very less compared to the number of crimes.We were successfully able to implement linear regression and linear ridge regression model having an accuracy of 95.801% and 95.815% respectively.
