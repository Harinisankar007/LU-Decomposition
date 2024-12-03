# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu
2.Get the input from user and print L and U matrix by 'print'
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the 
4.Print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

Program to find the L and U matrix.
Developed by: HARINI S
RegisterNumber:24901178 
```
(ii) To find the LU Decomposition of a matrix
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)

Program to find the LU Decomposition of a matrix.
Developed by: HARINI S
RegisterNumber:24901178

```

## Output:
![lu decomposition]
![image](https://github.com/user-attachments/assets/24d0fcbb-c4d5-433f-89cb-90ff4bbeb530)
![image](https://github.com/user-attachments/assets/1426553b-5150-4771-9c75-b7ec1521c71e)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

