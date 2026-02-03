# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: pranav kirthik s s
RegisterNumber:  25011678
*/
import numpy as np
from sklearn.linear_model import LinearRegression
import matplotlib.pyplot as plt

x=np.array([5,6,8,10,12]).reshape(-1,1)
y=np.array([40,50,60,65,95])

model=LinearRegression()
model.fit(x,y)
y_pred=model.predict(x)
print("Slope:",model.coef_[0])
print("Intercept:",model.intercept_)

plt.scatter(x,y,color='blue',label='actual data')
plt.plot(x,y_pred,color='red',label='Regression Line')
plt.xlabel("Total number of hours studied")
plt.ylabel("Marks obtained")
plt.legend()
plt.show()
*/
```

## Output:
![simple linear regression model for predicting the marks scored](sam.png)
![exp 2 ML](https://github.com/user-attachments/assets/df89206f-abad-4cd1-a7cf-b78b623030c2)


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
