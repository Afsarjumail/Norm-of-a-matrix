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
# Developed By: Afsar jumail S 
# Register No: 212222240004
# Developed By: Kavinraja D
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
![2023-06-03 (4)](https://github.com/Afsarjumail/Norm-of-a-matrix/assets/118343395/afaa06f6-448f-461a-bf7f-7d23908ed5d0)
<br>

### 2-Norm of a Matrix
![2023-06-03 (5)](https://github.com/Afsarjumail/Norm-of-a-matrix/assets/118343395/713060a1-7745-411c-b4cc-5e4044c303ba)

<br>

### Infinity Norm of a Matrix
![2023-06-03 (6)](https://github.com/Afsarjumail/Norm-of-a-matrix/assets/118343395/0b98c0f0-3366-45f5-90ca-f8ca7b8b5bb7)


<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
