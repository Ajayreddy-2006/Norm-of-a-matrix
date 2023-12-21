![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742508/d2d3822d-a063-4cdf-9a1e-a7fc8c216e45)# Norm of a matrix
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
```
```
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

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
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742508/2c8b5fca-f412-4dca-92c9-531d35e63801)

### 2-Norm of a Matrix
![Screenshot 2023-12-21 215731](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742508/cbe1fefd-48d8-4e41-bc32-46029df221fc)

### Infinity Norm of a Matrix
![Screenshot 2023-12-21 215841](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742508/84841dcf-d8fc-4ae2-bfb9-eea167a3a643)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
