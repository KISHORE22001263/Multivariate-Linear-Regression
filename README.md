# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd.

### Step2
Read the csv file.

### Step3
Get the value of X and y variables.



### Step4
Create the linear regression model and fit.



### Step5
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm3.   
### Step6  
Print the predicted output.

## Program:
```
program to find Multivariate Linear Regression  
NAME:KISHORE.B
REG.NO:212222110020
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("amount:",regr.predict([[3300,1300]]))
```
## Output:
![Screenshot from 2023-06-10 13-17-22](https://github.com/KISHORE22001263/Multivariate-Linear-Regression/assets/121484538/9d1fd197-8a86-4ffd-9c67-d93bf660f9df)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
