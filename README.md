# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required :

1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

## Program:

### 1-Norm of a Matrix :-

```
# program to find the 1-norm of a matrix
# Developed by : Rajalakshmi R
# reg no : 212223110037

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```

### 2-Norm of a Matrix :-

```
# Program to find 2-norm of a matrix.
# Developed by: Rajalakshmi R
# RegisterNumber: 212223110037

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```

### Infinity Norm of a Matrix :-

```
# Program to find infinity norm of a matrix.
# Developed by: Rajalakshmi R
# RegisterNumber: 212223110037

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```

## Output:

### 1-Norm of a Matrix
![output](https://github.com/dhandeeswaran2005/Norm-of-a-matrix/assets/147139188/0f797a31-921e-469f-b53e-6fd423a4132d)


### 2-Norm of a Matrix
![output 1](https://github.com/dhandeeswaran2005/Norm-of-a-matrix/assets/147139188/54d120df-a3ca-4b6c-90ef-51b15c4cd8a7)


### Infinity Norm of a Matrix
![output 3](https://github.com/dhandeeswaran2005/Norm-of-a-matrix/assets/147139188/0b9405ed-e219-4d2c-b691-9098652ec388)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
