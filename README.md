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
1-form
```
'''
Program to find 2-norm of a matrix.
Developed by:Dinesh Karthik R
RegisterNumber: 212224230068
'''


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
l2-norm
```
'''
Program to find 2-norm of a matrix.
Developed by:Dinesh Karthik R
RegisterNumber: 212224230068
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
infinity
```
'''
Program to find 2-norm of a matrix.
Developed by:Dinesh Karthik R
RegisterNumber: 212224230068
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```



## Output:
<img width="1490" height="980" alt="image" src="https://github.com/user-attachments/assets/a2c5342f-7f7b-4cb7-8013-ac003a73ecae" />
<img width="1612" height="1042" alt="image" src="https://github.com/user-attachments/assets/ffa35601-1b4b-4bed-b3ff-95260c22e4bb" />
<img width="1547" height="1028" alt="image" src="https://github.com/user-attachments/assets/ce93cfca-9d25-4f37-b691-7eefbf6bdb30" />





## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
