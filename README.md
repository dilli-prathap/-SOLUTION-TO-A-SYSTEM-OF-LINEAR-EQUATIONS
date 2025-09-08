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
Prepare the lists from each linear equations and assign in sp.array()
### Step 3: 
Using the sp.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Dilli prathap
#RegisterNumber: 212224110014
import numpy as sp
s=[[1,-3],[3,1]]
d=sp.array([0,10])
sd=sp.linalg.solve(s,d)
print(sd)
```
## Output:
<img width="1641" height="969" alt="Screenshot 2025-09-08 091741" src="https://github.com/user-attachments/assets/b1b7e5d2-d855-4bf3-8896-8c736990014f" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

