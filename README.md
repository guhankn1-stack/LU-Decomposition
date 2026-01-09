# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program
    

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,lmatrix,Umatrix=lu(InputMatrix)
print(lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
A=np.array(eval(input()),dtype=float)
B=np.array(eval(input()),dtype=float)
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![lu decomposition]()
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c49a4d31-e2cc-42e8-a9af-d9e94282e098" />

![Uploading image.png…]()

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

