# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### (i) To Find the L and U Matrices

1.Start

2.Import necessary libraries: numpy as np, and lu from scipy.linalg.

3.Prompt the user to enter a matrix A.

4.Convert the user input into a NumPy array.

5.Perform LU decomposition using lu(A) and store the result in P, L, and U.

6.Display the lower triangular matrix L.

7.Display the upper triangular matrix U.


### (ii) To Find the LU Decomposition and Solve a System

1.Start

2.Import necessary libraries: numpy as np, and lu_factor, lu_solve from scipy.linalg.

3.Prompt the user to enter a matrix A and a vector b.

4.Convert the inputs into NumPy arrays.

5.Use lu_factor(A) to compute the LU decomposition of matrix A, resulting in lu and piv.

6.Solve the system Ax = b using lu_solve((lu, piv), b) and store the result in X.

7.Display the solution vector X.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Shri Raama Krishanan J
RegisterNumber: 212224220100
*/
```
```python
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Shri Raama Krishanan J
RegisterNumber: 212224220100
*/
```
```python
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![Screenshot 2025-04-28 122457](https://github.com/user-attachments/assets/cef3bd5b-293a-4fc4-8dc5-9ba7006645b9)
(ii) To find the LU Decomposition of a matrix
![Screenshot 2025-04-28 122513](https://github.com/user-attachments/assets/9cdc923e-522b-4177-95d0-59db50c60bfd)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

