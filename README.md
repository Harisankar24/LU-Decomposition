# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1.Input the coefficient matrix A and the constant matrix B.
2.Convert the input into a NumPy array.
3.Perform LU decomposition on A to obtain L (lower triangular matrix) and U (upper triangular matrix).
4.Output the solution x.
5.end


## Program:
(i) To find the L and U matrix
```

'''Program to find L and U matrix using LU decomposition.
Developed by:Harisankar.S 
RegisterNumber:212224240051 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```

'''Program to solve a matrix using LU decomposition.
Developed by:Harisankar.S
RegisterNumber:212224240051
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:
![Screenshot 2025-03-21 144221](https://github.com/user-attachments/assets/eb6f0859-71f0-4b60-8089-4fdf5c72a108)
![Screenshot 2025-03-21 144237](https://github.com/user-attachments/assets/baad9624-fa28-4598-b567-c2a9aeb984d8)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

