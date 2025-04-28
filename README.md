# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X'

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

