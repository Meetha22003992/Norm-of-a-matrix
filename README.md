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
# Register No:212222240065
# Developed By:Meetha Prabhu
# 1-Norm of a Matrix
import numpy as np

a=np.array(eval(input()))

sol=np.linalg.norm(a,1)

norm="{:.2f}".format(sol)

print(norm)

# 2-Norm of a Matrix
mport numpy as np

a=np.array(eval(input()))

sol=np.linalg.norm(a,2)

norm="{:.2f}".format(sol)

print(norm)

# Infinity Norm of a Matrix
import numpy as np

a=np.array(eval(input()))

sol=np.linalg.norm(a,np.inf)

norm="{:.2f}".format(sol)

print(norm)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Meetha22003992/Norm-of-a-matrix/assets/119401038/0100121e-800f-48cd-b64c-dc3092add4d7)

### 2-Norm of a Matrix
![image](https://github.com/Meetha22003992/Norm-of-a-matrix/assets/119401038/e8e5afb7-b9f4-4ed0-9ac3-927d01e56051)

### Infinity Norm of a Matrix
![image](https://github.com/Meetha22003992/Norm-of-a-matrix/assets/119401038/6c2c4165-92e0-48ce-92e8-bc8f74b64b5f)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
