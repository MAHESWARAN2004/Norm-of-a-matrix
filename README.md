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

##  1-Norm of a Matrix
```
Program to find the 1-Norm of a matrix 
Developed by:Maheswaran.K
Register Number: 212222110023
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


## 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by:Maheswaran.K
Register Number: 212222110023
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
Program to find infinity of a matrix.
Developed by:Maheswaran.K
Register Number: 212222110023
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

<img width="879" alt="Screenshot 2023-06-04 at 9 38 32 PM" src="https://github.com/MAHESWARAN2004/Norm-of-a-matrix/assets/119478181/bb96a864-aa19-4158-b4c3-ef4b9602d9de">

### 2-Norm of a Matrix
<img width="874" alt="Screenshot 2023-06-04 at 9 38 52 PM" src="https://github.com/MAHESWARAN2004/Norm-of-a-matrix/assets/119478181/7e0eacbb-4b42-46d1-a142-6ee3b2c0d156">

### Infinity Norm of a Matrix
<img width="859" alt="Screenshot 2023-06-04 at 9 39 07 PM" src="https://github.com/MAHESWARAN2004/Norm-of-a-matrix/assets/119478181/37748c08-2b3f-466c-a3ca-4be4efe42e4f">

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
