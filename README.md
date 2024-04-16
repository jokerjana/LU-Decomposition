# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
We have to initialise program using import numpy to perform mathematical calculation

### Step 2:
The input from the user is stored in the variable A.

### Step 3:
from scipy.linalg import lu_factor,lu_solve and lu.

### Step 4:
Execute the program.

## Program:
(i) To find the L and U matrix
 '''Program to find L and U matrix using LU decomposition.
    Developed by: JANARTHANAN B
    RegisterNumber: 212223100014
'''
     import numpy as np
     from scipy.linalg import lu
     matrix=np.array(eval(input()))
     pivot,l_matrix,u_matrix=lu(matrix)
     print(l_matrix)
     print(u_matrix)
     
(ii) To find the LU Decomposition of a matrix
  '''Program to solve a matrix using LU decomposition.
     Developed by: JANARTHANAN B
     RegisterNumber: 212223100014
  '''
     import numpy as np
     from scipy.linalg import lu_factor,lu_solve
     a=eval(input())
     b=eval(input())
     lu,piv=lu_factor(a)
     x=lu_solve((lu,piv),b)
     print(x)


## Output:
(i) To find the L and U matrix
![image](https://github.com/jokerjana/LU-Decomposition/assets/147173630/60f43260-5fdb-45e2-b6cc-4d1e7ef8c713)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/jokerjana/LU-Decomposition/assets/147173630/342e964f-7723-48e0-a875-5f65fbc7c116)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

