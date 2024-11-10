# Ex.No: 2   Matrix Multiplication 

### DATE: 20-8-24                                                                          
### REGISTER NUMBER : 212222040037

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
7. 
### Program:
```
#5 Input the dimensions of the matrices
r1, c1 = input("Enter row and column count in matrix 1: ").split()
r2, c2 = input("Enter row and column count in matrix 2: ").split()

# Convert the input to integers
if r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric():
    r1, c1, r2, c2 = int(r1), int(c1), int(r2), int(c2)
    
    # Check if matrix multiplication is possible
    if c1 != r2:
        print("Matrix multiplication not possible: Columns of matrix 1 must equal rows of matrix 2.")
    elif max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) == 0:
        print("Matrix multiplication not possible: Matrix dimensions must be within the range 1-20.")
    else:
        # Input the elements of matrix 1
        matrix1 = []
        print("Enter the elements of matrix 1:")
        for i in range(r1):
            a = []
            for j in range(c1):
                a.append(int(input(f"Element [{i+1}][{j+1}]: ")))
            matrix1.append(a)
        
        # Input the elements of matrix 2
        matrix2 = []
        print("Enter the elements of matrix 2:")
        for i in range(r2):
            a = []
            for j in range(c2):
                a.append(int(input(f"Element [{i+1}][{j+1}]: ")))
            matrix2.append(a)
        
        # Perform matrix multiplication
        result = []
        for i in range(r1):
            inter = []
            for j in range(c2):
                sum = 0
                for k in range(c1):
                    sum += matrix1[i][k] * matrix2[k][j]
                inter.append(sum)
            result.append(inter)
        
        # Print the result matrix
        print("Resultant Matrix:")
        for i in range(r1):
            for j in range(c2):
                print(result[i][j], end=" ")
            print()

else:
    print("Enter a valid number.")
```
### Output:
![2 1](https://github.com/user-attachments/assets/6551e74e-8598-47b3-a22b-ef7208025f54)
![2 2](https://github.com/user-attachments/assets/587ce726-c059-4aa0-9c81-8bfc61e04dec)

### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

