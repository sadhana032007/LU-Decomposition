# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Write a python program for the given matrix. 
2. Using numpy library.
3. Using the np.linalg.matrix_rank(),we can find the rank of the matrix.
4. Run the program and get the output.

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input())
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input())
B=np.array(eval(input())
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
(i)
![maths1](https://github.com/user-attachments/assets/266bdbbd-fb6e-4b43-8dfd-d4995b2c053e)

(ii)
![maths2](https://github.com/user-attachments/assets/e49ba7cc-4ed5-4254-b0ab-a96de83a5a45)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

