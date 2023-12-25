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
# Register No:23002806
# Developed By: T MOUNISH
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-25 171125](https://github.com/MounishT/Norm-of-a-matrix/assets/138955798/bbaee67d-c11f-4078-bc08-bb9d2fed93b7)


### 2-Norm of a Matrix
![Screenshot 2023-12-25 171137](https://github.com/MounishT/Norm-of-a-matrix/assets/138955798/a39d6955-3868-49c4-9141-ae9731ae11e6)


### Infinity Norm of a Matrix

![Screenshot 2023-12-25 171149](https://github.com/MounishT/Norm-of-a-matrix/assets/138955798/4332b4c1-895b-4468-b981-dd32ae0d9174)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
