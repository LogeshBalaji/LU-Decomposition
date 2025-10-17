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
Developed by: V RISHON ANAND
RegisterNumber: 212224240135
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
![lu decomposition]()
<img width="1236" height="949" alt="image" src="https://github.com/user-attachments/assets/3b357a81-d364-49ac-93c5-88eb11b5efae" />
<img width="1243" height="639" alt="image" src="https://github.com/user-attachments/assets/ef2a827a-c4fa-44d1-8fc4-54a0cbf5c09d" />
<img width="1218" height="900" alt="image" src="https://github.com/user-attachments/assets/3979d9ed-b777-4f52-ab10-727555b2544b" />
<img width="1239" height="341" alt="image" src="https://github.com/user-attachments/assets/88a4bc59-415a-46a7-bae4-67076e13663d" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

