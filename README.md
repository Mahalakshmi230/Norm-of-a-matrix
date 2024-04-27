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
# 1-Norm of a Matrix
Program to find 1-Norm of a matrix.
Developed by: Mahalakshmi R
Register Number: 212223230116
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: Mahalakshmi R
RegisterNumber: 212223230116
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
Program to find Infinity of a matrix.
Developed by: Mahalakshmi R
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Mahalakshmi230/Norm-of-a-matrix/assets/149365324/358ecd43-28d9-4ac2-94c9-137f0556826e)


### 2-Norm of a Matrix
![image](https://github.com/Mahalakshmi230/Norm-of-a-matrix/assets/149365324/86827eb8-e1f7-4892-b51f-3485d767a938)


### Infinity Norm of a Matrix
![Screenshot 2024-04-27 103510](https://github.com/Mahalakshmi230/Norm-of-a-matrix/assets/149365324/2511a35f-0689-4239-bdfb-310bf10e7c06)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
