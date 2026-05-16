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
# Register No: 212225040094
# Developed By: Girishva.K
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print(normal)


# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print(f"{norm2:.2f}")

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
norminf=np.linalg.norm(mat,np.inf)
print(f"{norminf:.2f}")
```
## Output:
### 1-Norm of a Matrix

<img width="890" height="839" alt="image" src="https://github.com/user-attachments/assets/d77de68d-eb11-4d7a-8a22-f53e48b13ba4" />


### 2-Norm of a Matrix

<img width="827" height="847" alt="image" src="https://github.com/user-attachments/assets/242104a4-400a-4f28-8cd9-4aadcb0d9598" />


### Infinity Norm of a Matrix

<img width="1081" height="877" alt="image" src="https://github.com/user-attachments/assets/45413d7f-af6b-4568-9b81-ba20621136c3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
