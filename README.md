# EX:1.SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
# Date:14.4.2024

## Aim:
To write a python program to find a solution to a system of linear equations.

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
	
## Algorithm:
# Step 1: 
Import the numpy module to use the built-in functions for calculation

# Step 2: 
Prepare the lists from each linear equations and assign in np.array()

# Step 3: 
Using the np.linalg.solve(), we can find the solutions.

# Step 4: 
End the program


## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: A DIVYA
#RegisterNumber: 2305002007
```
```
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
solution=np.linalg.solve(A,B)
print ('The solution for the given matrix is',solution)
```
## Output:
![Screenshot 2024-04-04 184954](https://github.com/divyaanbu-143/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155506447/a5a445fd-5a8b-4719-93bc-8f7406f5cebd)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

