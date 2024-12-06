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
# Register No: 24900503
# Developed By: AGILAN J
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
		inform="{:.2f}".format(ans)
		print(inform)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-06 133311](https://github.com/user-attachments/assets/b24130c4-060b-435a-8f21-b3d4f6b7df75)


### 2-Norm of a Matrix
![Screenshot 2024-12-06 133338](https://github.com/user-attachments/assets/c36720ea-477b-4d2b-ad21-36493f509f7f)


### Infinity Norm of a Matrix
![Screenshot 2024-12-06 133354](https://github.com/user-attachments/assets/e33df8fa-0036-4b9d-934d-6a6372752827)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
