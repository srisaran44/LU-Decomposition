# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. DEVELOPE THE CONSUMING NUMPY TO INPUT
3. ENSURE THE SCIPY(USING LINALG)
4. GET INPUT ASUME THREE VAR().
5. RETURN THE FOLLOWING ASSUMED VARIABLES

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SRI SARAN J.
RegisterNumber: 212225240159
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SRI SARAN .J
RegisterNumber: 212225240159
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
*/
```

## Output:
<img width="985" height="559" alt="image" src="https://github.com/user-attachments/assets/aa51926e-b50a-43a4-a61c-02099a408978" />
<img width="1141" height="224" alt="image" src="https://github.com/user-attachments/assets/94dfedf5-e858-4b90-8b7f-43d9db9fd748" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

