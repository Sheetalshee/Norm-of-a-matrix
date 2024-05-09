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
# Register No: 212223230206
# Developed By: SHEETAL.R
# 1-Norm of a Matrix
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SHEETAL.R
RegisterNumber: 212223230206
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Sheetalshee/Norm-of-a-matrix/assets/144979107/7c303a15-a0e7-47b8-a593-9d58a743e6f3)


### 2-Norm of a Matrix
![image](https://github.com/Sheetalshee/Norm-of-a-matrix/assets/144979107/1d2442d0-5424-4f3c-9764-6bb905613d35)


### Infinity Norm of a Matrix
![image](https://github.com/Sheetalshee/Norm-of-a-matrix/assets/144979107/976ac6fb-ab4f-4137-88e7-aefb35bceb0d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
