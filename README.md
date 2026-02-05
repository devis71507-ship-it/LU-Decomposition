# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Start the program and import the required library (numpy).

2.Initialize the matrix for which the LU decomposition needs to be found.

3.Apply LU Decomposition

4.Display the results

## Program:

(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: s.devi
RegisterNumber: 212225100008/25004804
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
'''Program to solve a matrix using LU decomposition.
Developed by: s.devi
RegisterNumber: 212225100008/25004804

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

```

## Output:
5i)
<img width="1191" height="445" alt="Screenshot 2026-02-05 202212" src="https://github.com/user-attachments/assets/fdd5e129-11a8-4ebb-8fc9-e6b8969bfd2c" />

5ii)
<img width="1050" height="199" alt="Screenshot 2026-02-05 202232" src="https://github.com/user-attachments/assets/2f8930f4-f5ff-46dd-9969-2b022458a74c" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

