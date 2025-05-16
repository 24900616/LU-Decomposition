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
8.End

### (ii) To Find the LU Decomposition and Solve a System

1.Start

2.Import necessary libraries: numpy as np, and lu_factor, lu_solve from scipy.linalg.

3.Prompt the user to enter a matrix A and a vector b.

4.Convert the inputs into NumPy arrays.

5.Use lu_factor(A) to compute the LU decomposition of matrix A, resulting in lu and piv.

6.Solve the system Ax = b using lu_solve((lu, piv), b) and store the result in X.

7.Display the solution vector X.
8.End
## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Swetha K
RegisterNumber: 212224230284
```
```

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Swetha K
RegisterNumber: 212224230284
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:

![Screenshot 2025-04-16 103921](https://github.com/user-attachments/assets/06768555-bb3f-47da-95a1-44a5bb51b018)
![Screenshot 2025-04-16 103932](https://github.com/user-attachments/assets/19f4476b-8f27-4afd-ab6f-df6f2bd9bdf8)
![Screenshot 2025-04-16 103943](https://github.com/user-attachments/assets/fcc0eb15-1c65-4051-92d8-fc5b8fb43aec)
![Screenshot 2025-04-16 103952](https://github.com/user-attachments/assets/63a01443-1b54-4c24-8283-28abba137c0c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

