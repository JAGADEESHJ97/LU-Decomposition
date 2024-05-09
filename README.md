# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1.Define the package as scipy.linalg import lu.    
stap 2.Get input from user and print L and U matrix by 'print' .   
step 3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.  
stap 4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```python
Program to find L and U matrix using LU decomposition.
Developed by: JAGADEESH J
RegisterNumber: 212223110015
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition.
Developed by: JAGADEESH J
RegisterNumber: 212223110015
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
X=lu_solve((lu,piv),b)
print(X)

```
## Output:
![alt text](<Screenshot 2024-05-09 194525.png>)
![alt text](<Screenshot 2024-05-09 194547.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

