# EX1 Implementation of Univariate Linear Regression to fit a straight line using Least Squares
## DATE:
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
/*
Program to implement univariate Linear Regression to fit a straight line using least squares.
Developed by:Poovarasu V 
RegisterNumber:2305002017 
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
df=pd.read_csv('/content/ex1.csv')
df.head()
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
*/
```

## Output:

![Screenshot (21)](https://github.com/user-attachments/assets/3a3a5cb5-5f06-479d-8f42-db05fe80174d)


## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
