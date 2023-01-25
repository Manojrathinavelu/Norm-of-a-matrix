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
# 1-Norm of a Matrix

# Register No: Manoj karthik R
# Developed By: 22003728
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Manoj Karthik R
RegisterNumber: 22003728
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![norm1](https://user-images.githubusercontent.com/119560395/214602668-0b0c16a7-a120-4baf-8be2-4ec27cd504cc.png)


### 2-Norm of a Matrix
![norm2](https://user-images.githubusercontent.com/119560395/214602724-6b54310d-9608-492b-aad2-d944581ac7e7.png)


### Infinity Norm of a Matrix
![norm3](https://user-images.githubusercontent.com/119560395/214602764-edd22408-e4db-4f06-8e96-76b9d61f96b2.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
