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
# Register No:23000827
# Developed By:Naveen kumar V
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
![image](https://github.com/Naveenkumarvedarajan/Norm-of-a-matrix/assets/147140428/17102e78-f8b0-4774-b640-5d423a2447a2)


### 2-Norm of a Matrix
![image](https://github.com/Naveenkumarvedarajan/Norm-of-a-matrix/assets/147140428/b6753511-f43e-45c0-b16f-66ded259cb24)


### Infinity Norm of a Matrix
![image](https://github.com/Naveenkumarvedarajan/Norm-of-a-matrix/assets/147140428/9718a03d-8f0d-4a39-a288-be9d02dcc689)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
