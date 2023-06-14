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

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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
![image](https://github.com/22002102/Norm-of-a-matrix/assets/119091638/d3533775-d45f-4e76-ba2e-6bab654d2efc)


### 2-Norm of a Matrix
![image](https://github.com/22002102/Norm-of-a-matrix/assets/119091638/a5fc245a-e2f7-428e-b37b-5ed92f0abc5a)

### Infinity Norm of a Matrix
![image](https://github.com/22002102/Norm-of-a-matrix/assets/119091638/09d127b8-0996-4b08-a646-5383a1c0b509)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
