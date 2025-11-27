# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
Program to develop to implement univariate Linear Regression to fit a straight line using least squares.

Developed by : Abinesh A
Register no : 25017255
```
```
import numpy as np
import matplotlib.pyplot as plt
X= np.array([0,1,2,3,4,5,6,7,8,9])
Y= np.array([1,3,2,5,7,8,8,9,10,12])
plt.scatter(X,Y)
plt.show()
X_Mean=np.mean(X)
Y_Mean=np.mean(Y)
num=0
den=0
for i in range(len(X)):
    num+=(X[i]-X_Mean)*(Y[i]-Y_Mean)
    den+=(X[i]-X_Mean)**2

m=num/den
b=Y_Mean-(m*X_Mean)
print(f"Slope : {m}\nIntercept : {b}")
Y_Pred=(m*X)+b
print(f"Predicted values are : \n{Y_Pred}")
plt.scatter(X,Y,color='Red')
plt.plot(X,Y_Pred,color='Blue')
plt.show()

```
## Output
<img width="712" height="532" alt="image" src="https://github.com/user-attachments/assets/64c7ba8f-69ff-4985-93bc-3807a4959d51" />
<img width="757" height="625" alt="image" src="https://github.com/user-attachments/assets/55bdf8f3-46c1-45d1-a07b-ff1d6a09d139" />



## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

