# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import the lu funtion.

3.Get inputs from the user and assign the values in np.array().

4.Using the lu() function,we can find the L and U matrix.

5.Print the obtained values.

6.End the program.
```
## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
import numpy as np 
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: SRINIDHI SENTHIL
RegisterNumber: 22001408
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:

(i) To find the L and U matrix

![image](https://user-images.githubusercontent.com/121373170/214666613-f9b99ef6-6990-4941-9ef8-04a3219388f2.png)



(ii) To find the LU Decomposition of a matrix

![image](https://user-images.githubusercontent.com/121373170/214666285-0855a201-721d-47bc-bfda-c8b876a0d8f2.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

