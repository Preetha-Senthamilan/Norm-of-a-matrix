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

![Screenshot 2023-10-04 134617](https://github.com/Preetha-Senthamilan/Norm-of-a-matrix/assets/119390282/0c57bad9-fe41-46a8-9166-b2f4cfbeb745)


### 2-Norm of a Matrix

![Screenshot 2023-10-04 134756](https://github.com/Preetha-Senthamilan/Norm-of-a-matrix/assets/119390282/22619f50-79f2-4b04-ba5d-d11f4a487e08)


### Infinity Norm of a Matrix

![Screenshot 2023-10-04 134916](https://github.com/Preetha-Senthamilan/Norm-of-a-matrix/assets/119390282/97b1a365-d939-4c15-aa17-7bb56a129ee7)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
