# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### (i) To find the L and U matrix using LU decomposition:

### Algorithm Steps:

1. Import the necessary libraries (scipy.linalg and numpy).

2. Accept a matrix as input from the user.

3. Convert the input matrix into a NumPy array.

4. Use the LU decomposition function (lu) from scipy.linalg to decompose the matrix into the product of a permutation matrix P, a lower triangular matrix L, and an upper triangular matrix U.

5. Print the lower triangular matrix L.

6. Print the upper triangular matrix U.


### (ii) To find the LU Decomposition of a matrix:

### Algorithm Steps:

1. Import the necessary libraries (scipy.linalg and numpy).
   
2. Accept a matrix as input from the user.

3. Convert the input matrix into a NumPy array.

4. Accept a constant matrix (right-hand side of the equations) as input from the user.

5. Convert the constant matrix into a NumPy array.

6. Use the LU factorization function (lu_factor) from scipy.linalg to compute the LU decomposition of the coefficient matrix.

7. Use the LU solve function (lu_solve) to find the solution to the system of linear equations.

8. Print the solution matrix.
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: T.Ajay
RegisterNumber: 23007325
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: T.Ajay
RegisterNumber: 23007325
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
(i)

![Screenshot 2023-12-21 212854](https://github.com/Ajayreddy-2006/LU-Decomposition/assets/145742508/44172335-3d4e-4ed8-914b-5c3120ca9692)


(ii)

![Screenshot 2023-12-21 212908](https://github.com/Ajayreddy-2006/LU-Decomposition/assets/145742508/ef7f5fd2-065b-4264-857d-063733ae37d9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

