# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
## Program:
```
Developed by: S.Krishna Prasad
RegisterNumber: 212223230108
```
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: SANJAI L
RegisterNumber:212223230184

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
## i)
![image](https://github.com/KrishnaPrasad148/LU-Decomposition/assets/147332763/f47dd6f3-679b-47ad-bd18-48021a1fe638)
![image](https://github.com/KrishnaPrasad148/LU-Decomposition/assets/147332763/5d60d259-f9fc-4ef5-9722-efcd0557a1e9)

## ii)
![Web_Photo_Editor](https://github.com/KrishnaPrasad148/LU-Decomposition/assets/147332763/c31bb54d-3841-4039-afe1-0d81047495ba)
![320253112-17ded43a-a6c9-464e-b192-3c3e066205e3](https://github.com/KrishnaPrasad148/LU-Decomposition/assets/147332763/52db64e9-d701-4a67-8271-3dc96f97890b)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

