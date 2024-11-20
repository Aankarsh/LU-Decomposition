# EXP - 5 LU Decomposition 
# DATE:
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

Step 1
Import the numpy module to use the built-in functions for calculation

Step 2
Prepare the lists from each linear equations and assign in np.array()

Step 3
Using the np.linalg.solve(), we can find the solutions.

Step 4
End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: AANKARSH .j 
RegisterNumber: 22304386
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu (A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: AANKARSH
RegisterNumber: 22304386
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```
## Output:
(i) 
![Screenshot 2024-11-20 151549](https://github.com/user-attachments/assets/8132edce-e1d3-44d0-80c8-db22997d66a6)
(ii)
![Screenshot 2024-11-20 151607](https://github.com/user-attachments/assets/d4b40193-12ad-4c02-a66d-c7277f0d80c7)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

