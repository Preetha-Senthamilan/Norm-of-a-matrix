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
# Register No:PREETHA.S
# Developed By:212222230110
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)



```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-10-04 134051](https://github.com/Preetha-Senthamilan/Norm-of-a-matrix/assets/119390282/7db2cbb7-20bb-4679-8c22-ab68ca906564)

### 2-Norm of a Matrix

![image](https://github.com/Preetha-Senthamilan/Norm-of-a-matrix/assets/119390282/1658e04c-6ea7-4296-899e-57812cfe64a8)


### Infinity Norm of a Matrix
![Screenshot 2023-10-04 134347](https://github.com/Preetha-Senthamilan/Norm-of-a-matrix/assets/119390282/6f05d4fb-911d-4871-ab26-db9f7f644bb9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
