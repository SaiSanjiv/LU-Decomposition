# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'

## Program:
(i) To find the L and U matrix
```

#Program to find the L and U matrix.
#Developed by: SAI SANJIV R
#RegisterNumber: 212223230179
import numpy as np
from scipy.linalg import lu
A =np.array(eval(input()))
p,L,U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: SAI SANJIV R
#RegisterNumber: 212223230179


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor , lu_solve 
A = np.array(eval(input()))
b = np.array(eval(input()))
lu , piv = lu_factor(A)
x = lu_solve((lu , piv) , b)
print(x)

```

## Output:
(i) To find the L and U matrix

![image](https://github.com/SaiSanjiv/LU-Decomposition/assets/151772975/d8c2f88e-630e-494f-b178-3ab9bfea3cf6)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/SaiSanjiv/LU-Decomposition/assets/151772975/2e5c7455-c871-4877-9bb6-68e9a5d6440a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

