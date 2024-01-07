# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. write a program
2. to the given input
4. read the file
5.and find the LU Decomposition of the matrix 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: NAINA MOHAMED Z
RegisterNumber: 23010605
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```

'''Program to solve a matrix using LU decomposition.
Developed by: NAINA MOHAMED Z
RegisterNumber: 23010605
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![Screenshot 2023-12-29 112253](https://github.com/nainamohamed09642/LU-Decomposition/assets/151916360/26a79878-d349-40e2-a33e-964df086f385)
![Screenshot 2023-12-29 112636](https://github.com/nainamohamed09642/LU-Decomposition/assets/151916360/b7315835-c4eb-43fa-9664-5c043774ebb7)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

