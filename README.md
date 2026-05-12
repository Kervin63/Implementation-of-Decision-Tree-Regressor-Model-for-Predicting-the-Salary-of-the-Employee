# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import required libraries such as Pandas and sklearn.

2.Load dataset and split into features (X) and target (y).

3.Divide dataset into training and testing sets.

4.Create Decision Tree Regressor model.

5.Train model and predict salary values.

6.Evaluate model using MSE, MAE, and R² score and visualize tree.

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: Kervin.S
RegisterNumber:212225220051
import numpy as np
from sklearn.tree import DecisionTreeRegressor
from sklearn.model_selection import train_test_split

X = np.array([
    [1],
    [2],
    [3],
    [4],
    [5],
    [6],
    [7],
    [8]
])

Y = np.array([20000, 30000, 40000, 50000, 60000, 70000, 80000, 90000])

X_train, X_test, Y_train, Y_test = train_test_split(X, Y, test_size=0.2, random_state=0)

model = DecisionTreeRegressor()
model.fit(X_train, Y_train)

Y_pred = model.predict(X_test)

print("Predicted Salaries:", Y_pred)

sample = np.array([[5]])
prediction = model.predict(sample)

print("Predicted Salary for 5 years experience:", prediction[0])
*/
```

## Output:
<img width="524" height="55" alt="image" src="https://github.com/user-attachments/assets/8f1debca-40d6-40cb-8850-1ad464668150" />



## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
