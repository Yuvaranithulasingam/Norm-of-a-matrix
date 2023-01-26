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
# Register No:22009033
# Developed By:Yuvarani T

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![Screenshot_20230117_213344](https://user-images.githubusercontent.com/121418522/212949918-b6ed9091-7880-42e2-9231-ec8bb7a5b507.png)

### 2-Norm of a Matrix

![2 norm](https://user-images.githubusercontent.com/121418522/212950755-4d26eb0f-0977-4213-87b6-b4b20fa78748.png)
### Infinity Norm of a Matrix

![infinity norm](https://user-images.githubusercontent.com/121418522/212950841-ddf0089a-bee1-4426-a979-79829f2e47cc.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
