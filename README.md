# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
(i) 1-Norm of a Matrix
```
'''
Program to find the 1-Norm of a matrix
Developed by : Vikaash K S
Register number : 23013426
'''
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print("{:.2f}".format(b))
```
(ii) 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print("{:.2f}".format(b))
```
(iii) Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print("{:.2f}".format(b))
```
## Output:
### 1-Norm of a Matrix
![Norm 1 mat](https://github.com/Vikaash19/Norm-of-a-matrix/assets/148514589/e74641e5-571f-4bd5-844a-066514f33ec7)

### 2-Norm of a Matrix
![Norm 2 mat](https://github.com/Vikaash19/Norm-of-a-matrix/assets/148514589/cde11ac2-9c36-4b4d-96e4-0a8072cebb98)

### Infinity Norm of a Matrix
![Norm inf mat](https://github.com/Vikaash19/Norm-of-a-matrix/assets/148514589/20f85a4c-c5ef-40b7-ba27-060a68afb457)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
