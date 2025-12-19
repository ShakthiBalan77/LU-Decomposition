# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program
   
## Program:
(i) To find the L and U matrix
```
Developed by: SHAKTHI BALAN V
RegisterNumber: 25016098

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

Developed by: Shakthi Balan V
RegisterNumber: 25016098

```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

```

## Output:

<img width="1490" height="841" alt="Screenshot 2025-12-19 160906" src="https://github.com/user-attachments/assets/e9f774cd-e9e7-4643-b012-1545e8cda0f8" />

<img width="835" height="651" alt="Screenshot 2025-12-19 160921" src="https://github.com/user-attachments/assets/f9e2cd01-ea82-4907-a588-f5d5053cac2c" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

