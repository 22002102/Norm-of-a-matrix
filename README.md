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
1-Norm of a Matrix:

#Register Number:212222230132
#NAME:  SANJAY S
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
print("%.2f"%soln)



2-Norm of a Matrix:

Developed by: SANJAY S
RegisterNumber: 212222230132
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
print("%.2f"%soln)



3.Infinity Norm of a Matrix:

Developed by: SANJAY S
RegisterNumber: 212222230132
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
print("%.2f"%soln)

```
## Output:
1.
![image](https://github.com/22002102/Norm-of-a-matrix/assets/119091638/c215395c-2651-434b-a7e7-7b564dbbd86b)



2.
![image](https://github.com/22002102/Norm-of-a-matrix/assets/119091638/7d6a98ff-bbbb-484d-acd1-95104ccf4cfa)



3.
![image](https://github.com/22002102/Norm-of-a-matrix/assets/119091638/d3649371-6490-46f1-b984-e195a28ccb3f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
