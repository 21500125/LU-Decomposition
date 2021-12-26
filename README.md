# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement
2. From scipy package import lu()
3. Get input from user and pass it as an array
4. Get P,LU matrix using lu()
5. Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Sithi Hajara
RegisterNumber: 21500125

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Sithi Hajara
RegisterNumber: 21500125

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![lu decomposition](./ss1.PNG)
![lu decomposition](./ss2.PNG)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

