# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start with a square matrix A of order 𝑛×𝑛
Initialize:𝐿=𝐼
L=I (Identity matrix)
𝑈=0 (Zero matrix)

2. For each row 
𝑖=1 to n:Compute elements of U using
𝑈𝑖𝑗=𝐴𝑖𝑗−∑𝑘=1𝑖−1 𝐿𝑖𝑘 𝑈𝑘𝑗,for 𝑗≥𝑖

3. For each column 𝑗=1
j=1 to 𝑛
Compute elements of L using
𝐿𝑗𝑖=𝑈𝑖𝑖(𝐴𝑗𝑖−∑𝑘=1 𝑖−1 𝐿𝑗𝑘𝑈𝑘𝑖),for 𝑗>i

4. epeat Steps 2 and 3 until all elements are calculated.
Finally, obtain 𝐴=𝐿𝑈


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

