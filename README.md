# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Get the input matrix from user
2. write a program to find the L and U matri
3. using the L and U matrix slove the matrix
4. display the output

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: yuva krishna k
RegisterNumber: 212222110056
'''

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: yuva krishna k 
RegisterNumber: 212222110056
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array(eval(input()))
B=np.array(eval(input()))
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:
i)
![Screenshot (58)](https://github.com/Yuvakrishna0/LU-Decomposition/assets/117915037/b27ed0a5-b495-4172-b320-f420bbbbcd80)
ii)
![Screenshot (59)](https://github.com/Yuvakrishna0/LU-Decomposition/assets/117915037/cc148611-a937-4a90-9002-aa144bfd481d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

