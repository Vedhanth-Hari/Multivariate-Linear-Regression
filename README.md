# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd

### Step2
Read the csv file

### Step3
Get the value of X and Y variables

### Step4
Create the linear regression model and fit

### Step5
Predict the CO2 emission of a car where the weight is 2300kg and the volume is 1300cm^3

### Step 6:
Print the predicted output.

## Program:
```
Developed by: VEDHANTH H
Reg.No: 212224240181

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient",regr.coef_)
print("Intercept",regr.intercept_)
print("Co2 required is",regr.predict([[3300,1300]]))


```
## Output:
### Insert your output
<img width="1359" height="250" alt="Screenshot 2025-10-16 091136" src="https://github.com/user-attachments/assets/9ad1b81b-bae9-46a7-a24c-8d13e3b0516c" />

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
