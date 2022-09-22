# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:alagu nachiyar 
RegisterNumber: 22002084
'''

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:alagu nachiyar 
RegisterNumber: 22002084
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu, piv=lu_factor(A)
x=lu_solve((lu, piv),B)
print(x)
```

## Output for finding  L and U matrix
![Screenshot from 2022-09-22 14-24-31](https://user-images.githubusercontent.com/113497340/191705156-9f253fa2-18e4-4d9f-a017-2756f4ebec98.png)
Output for finding LU decomposition of a matrix
![Screenshot from 2022-09-22 14-30-51](https://user-images.githubusercontent.com/113497340/191705296-6f00dfba-2874-41bd-9a55-9f7fd75b328a.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

