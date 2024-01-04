# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 Step1: upload csv file of contents

 Step2: now open the file using open(cars.csv)

 Step3: to show give linear.linearRegression()

 Step4: the weight and volume columns contents have been read

 Step5: the read content have been gien has a output 

## Program:
```
# developed by: FRANKLIN RAJ G
# register no: 23001518

import pandas as pd
from sklearn import linear_model

df=pd.read_csv('cars.csv')
a=df[["Weight","Volume"]]
b=df[["CO2"]]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))





```
## Output:
![py ex 10](https://github.com/franklinraj/Multivariate-Linear-Regression/assets/148993740/763646db-4f88-48d5-8435-7b12788ef7de)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
