"C:\Users\PRADEEP V\Desktop\WEB_LOGO-01.png"
# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.User Input and Array Initialization 
2.LU Decomposition
3.Printing L and U Matrices
4.Explanation 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: PRADEEP V
RegisterNumber: 23013543
'''
import numpy as nu
from scipy.linalg import lu
a=nu.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:PRADEEP V 
RegisterNumber: 212223240119
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
A=np.array(a)
B=np.array(b)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)

```

## Output:
1.![maths 1 5](https://github.com/velupradeep/LU-Decomposition/assets/150329341/154b7bf9-4fb2-49e7-abd3-783055c754a6)
2.![maths 1 5 1](https://github.com/velupradeep/LU-Decomposition/assets/150329341/1bd705a9-f601-4120-98e6-aba603461398)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

