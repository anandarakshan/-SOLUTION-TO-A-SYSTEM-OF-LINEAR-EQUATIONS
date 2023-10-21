# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Ananda Rakshan K V
#RegisterNumber:23001531
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```
## Output:
![output1](https://github.com/anandarakshan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139217934/b3ef0e2e-d384-4925-ad7c-2c20c110dcae)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

