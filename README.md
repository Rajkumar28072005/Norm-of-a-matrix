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
# Developed by : Rajkumar G
# reg no : 23003498

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```

### 2-Norm of a Matrix :-

```
# Program to find 2-norm of a matrix.
# Developed by:Rajkumar G
# RegisterNumber: 23003498

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```

### Infinity Norm of a Matrix :-

```
# Program to find infinity norm of a matrix.
# Developed by: Rajkumar G
# RegisterNumber: 23003498

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```

## Output:

### 1-Norm of a Matrix
![Screenshot 2023-12-29 110734](https://github.com/Rajkumar28072005/Norm-of-a-matrix/assets/144980101/62c99524-f1ce-4380-b154-f307889bc00f)



### 2-Norm of a Matrix
![Screenshot 2023-12-29 110745](https://github.com/Rajkumar28072005/Norm-of-a-matrix/assets/144980101/31176628-9f19-4c6c-aec4-494c1a84f022)



### Infinity Norm of a Matrix
![Screenshot 2023-12-29 110753](https://github.com/Rajkumar28072005/Norm-of-a-matrix/assets/144980101/9fac05a1-ef31-45e8-8cd3-022a17e127ed)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
