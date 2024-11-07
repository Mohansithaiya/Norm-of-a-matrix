# DATE:
# EXP.NO.07 Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```
Program to find 1-norm of a matrix.
Developed by: MOHAN S 
Register Number: 212223240094

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:2f}".format(a)
print(n)
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: MOHAN S
RegisterNumber: 212223240094

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
print("{:.2f}".format(a))

```

# Infinity Norm of a Matrix
```
Program to find infinity- norm of a matrix.
Developed by: MOHAN S
RegisterNumber: 212223240094

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
print("{:.2f}".format(a))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/9f8bf0b7-0eb4-4631-86e3-2e97e6f58ad6)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/5464857c-3a8f-460f-b29a-c3e0c9fb2a34)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/460c0928-d7fe-494b-bae4-35f8f552eb84)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
