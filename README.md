# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm 
```
Step 1: Start the program.
Step 2: Read the size n of the square matrix.
Step 3: Input the matrix A.
Step 4: Create two matrices:(Lower triangular matrix) and (Upper triangular matrix)
Step 5: Initialize:
Set all diagonal elements of L to 1
Set all elements of U to 0
Step 6: For each row, do the following:
Find values for the upper triangular matrix U
Then find values for the lower triangular matrix L
Step 7: Repeat the process for all rows until both L and U are completely filled.
Step 8: Display matrices L and U.
Step 9: Stop the program.
```

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
Developed by: Akshaya Sree G
RegisterNumber: 212225230011
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

Developed by: Akshaya Sree G
RegisterNumber:212225230011 
*/
```
## Output:
<img width="1205" height="555" alt="image" src="https://github.com/user-attachments/assets/26baf515-2044-45d8-8402-62e111725447" />
<img width="988" height="351" alt="image" src="https://github.com/user-attachments/assets/b756c468-8aeb-4709-9d49-2df7015f7fed" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

