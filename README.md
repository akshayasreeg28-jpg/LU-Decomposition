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
Developed by: Akshaya Sree G
RegisterNumber: 212225230011
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Akshaya Sree G
RegisterNumber:212225230011 
*/
```

## Output:
![lu decomposition]()
L and U matrix
<img width="1152" height="843" alt="image" src="https://github.com/user-attachments/assets/c1803c9e-a138-44a5-9106-bb664dc16596" />
LU Decomposition of a matrix
<img width="978" height="645" alt="Screenshot 2026-02-13 104641" src="https://github.com/user-attachments/assets/9ef1927b-cb23-440b-8f0d-1b3af17775e4" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

