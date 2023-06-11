# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1:start
step 2:get an input from user
step 3: display the value 4.
step 4:stop

## Program:
Program to find the LU Decomposition of a matrix.
Developed by: NAVEEN S
RegisterNumber: 212222240070
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![ex5(mfa)a(1)](https://github.com/Naveensrinivasan07/LU-Decomposition/assets/119475891/f29aafbf-9447-4e6e-86c7-b80b1770857b)
![ex5(mfa)b](https://github.com/Naveensrinivasan07/LU-Decomposition/assets/119475891/efcd8744-00e7-4213-9aa3-a7b5f5528990)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
