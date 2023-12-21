
# Norm of a matrix
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
#Program to find 1-Norm of a matrix
#Developed by :T.Ajay
#Register number :212223230007

import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''

import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```

# Infinity Norm of a Matrix
```
#Program to find 3-Norm of a matrix
#Developed by :T.Ajay
#Register number :212223230007
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-21 221625](https://github.com/Ajayreddy-2006/Norm-of-a-matrix/assets/145742508/5afe1a5b-163b-44b5-b3ed-aa5d0fc505b5)

### 2-Norm of a Matrix
![image](https://github.com/Ajayreddy-2006/Norm-of-a-matrix/assets/145742508/12283b4b-a3bf-4dca-a969-7dea08779450)

### Infinity Norm of a Matrix
![Screenshot 2023-12-21 221843](https://github.com/Ajayreddy-2006/Norm-of-a-matrix/assets/145742508/c49a56ac-cffd-4475-b692-d665f746e434)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
