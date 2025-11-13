# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: LOGESH B
RegisterNumber: 212224110034
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: LOGESH B
RegisterNumber: 212224110034
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
<img width="1876" height="1021" alt="image" src="https://github.com/user-attachments/assets/aacc7299-5f86-4e11-8795-f05e94730b13" />
<img width="1887" height="682" alt="image" src="https://github.com/user-attachments/assets/b358072e-2302-4616-a666-06e27652bd8a" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

