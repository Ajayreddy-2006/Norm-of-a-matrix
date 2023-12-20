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
```Python
# Register No: 212223240065
# Developed By: K Santhan Kumar
# 1-Norm of a Matrix

import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/SANTHAN-2006/Norm-of-a-matrix/assets/80164014/52469767-94fe-4b4f-9155-d5e6c470c336)

### 2-Norm of a Matrix
![image](https://github.com/SANTHAN-2006/Norm-of-a-matrix/assets/80164014/c3c12628-d13d-4996-8e14-855f23717c8e)

### Infinity Norm of a Matrix
![image](https://github.com/SANTHAN-2006/Norm-of-a-matrix/assets/80164014/97f30b0e-847c-4b50-b891-dc3019252bc1)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
