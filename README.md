# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Write a python program for the given matrix.

Step 2: Using numpy library.

Step 3: Using linalg.inv(), we can get the inverse of the matrix.

Step 4: Run the program and get the output.
## Program:
```

#Program to find the inverse of a matrix.
#Developed by: VIJAYASHANKAR N
#RegisterNumber:212225230301

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)

```
## Output:
<img width="877" height="201" alt="brave_screenshot_lms2 ai saveetha in (2)" src="https://github.com/user-attachments/assets/4955879a-7aed-46a5-8f82-85bbb16a6150" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

