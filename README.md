# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P,L,U matric using lu().
5. Print L and U matrix.

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

