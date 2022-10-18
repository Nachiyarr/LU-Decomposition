# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import the lu funtion.

3.Get inputs from the user and assign the values in np.array().

4.Using the lu() function,we can find the L and U matrix.

5.Print the obtained values.

6.End the program.

## Program:

(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Alagu nachiyar k
RegisterNumber: 22002084


import numpy as np
from scipy.linalg import lu
a=eval(input()) 
P,L,U=lu(a) 
print(L)
print(U)
```


(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Alagu nachiyar k
RegisterNumber: 22002084


import numpy as np
from scipy. linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```


##  OUTPUT1:
![5](https://user-images.githubusercontent.com/113497340/192204151-63e761e3-b5b4-4786-ab67-a56168f16660.png)

## Output2:
![Screenshot from 2022-09-26 11-30-01](https://user-images.githubusercontent.com/113497340/192203912-7fa77742-6e9e-4254-88b0-3d5a24bfcd20.png)


## Result:
Thus the program to solve the matrix using LU Decomposition is written and verified using python programming.



