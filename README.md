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
import numpy as np

# Coefficient matrix A
A = np.array([[1, -3],
              [3, 1]])

# Right-hand side matrix B
B = np.array([0, 10])

# Solve the system of equations
solution = np.linalg.solve(A, B)

# Ensure that the result matches exactly the expected output
solution = np.round(solution, decimals=1)

# Output the solution
print(f"{solution}")
```

## Output:
![Screenshot 2024-12-05 183235](https://github.com/user-attachments/assets/6b12bcfc-fe32-4859-a85f-eb981bc5f03f)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

