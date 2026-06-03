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
'''
Program to find 1-norm of a matrix.
Developed by: THENAMUDHEN S
RegisterNumber: 212225040471
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: THENAMUDHEN S
RegisterNumber: 212225040471
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix
'''
Program to find infinity-norm of a matrix.
Developed by: THENAMUDHEN S
RegisterNumber: 212225040471
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="606" height="780" alt="image" src="https://github.com/user-attachments/assets/33cb3706-3581-4c3e-b18f-0ddf094e34e8" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="562" height="816" alt="image" src="https://github.com/user-attachments/assets/5f9cbf21-ce79-4ba3-abff-96c2fd06e166" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="650" height="763" alt="image" src="https://github.com/user-attachments/assets/25f2672e-3fbe-4477-aecf-bfed5c483481" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
