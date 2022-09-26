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

##  OUTPUT:
![5](https://user-images.githubusercontent.com/113497340/192204151-63e761e3-b5b4-4786-ab67-a56168f16660.png)


## Result:
Thus the program to find the LU decomposition of a matrix is written and verfied using python programming.

## AIM:
To write a program to solve a matrix using LU Decomposition.

## Equipments Required:
1.Hardware-PCs
2.Anaconda-Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import lu_factor and lu_solve functions for calculations.

3.Get inputs from the user and assign the values in A and B in np.array().

4.Using the lu_factor(),we can find the LU and pivot.

5.Substitue the value in a variable obtained from lu_solve().

6.Print the variable.

7.End the program.

## Program:

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

## Output:
![Screenshot from 2022-09-26 11-30-01](https://user-images.githubusercontent.com/113497340/192203912-7fa77742-6e9e-4254-88b0-3d5a24bfcd20.png)


## Result:
Thus the program to solve the matrix using LU Decomposition is written and verified using python programming.



