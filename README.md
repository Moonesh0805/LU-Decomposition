# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu
2. Get input from user and print L and U matrix bu 'print'
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in that       variable.
4. Print the variable 'X'


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Moonesh P
RegisterNumber: 23001144
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Moonesh P
RegisterNumber: 23001144
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```
## Output:
![OUTPUT](/5%20a.png)
![OUTPUT](/5%20b.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

