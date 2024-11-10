# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

## DATE: 13-8-24

## REGISTER NUMBER : 212222040037

### AIM:  

To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:

1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.

### Program:
 
```
1) do while:

start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
   start=int(start)
   end=int(end)
   while start<end:
       print(start)
       start+=1
else:
   print("Enter a valid positive number.")

2) while do:

start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
       print(start)
       start+=1
else:
    print("Enter a valid positive number.")

3) switch :

def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    } 
    
    n = input('Enter a value for N: ') 
    
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.") 

switch()


4) if else :

def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    
    try: 
        a = int(a) 
        b = int(b) 
        
        if a > b: 
            print("A is greater than B")  # Added "B" to complete the comparison message
        elif a < b: 
            print("B is greater than A")  # Added "A" to complete the comparison message
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")  # Fixed quotes to standard double quotes

compare()

5) for :

def iterate(): 
    string = input("Enter a string: ") 
    
    for i in string:  # The 'for' statement should be on a single line
        print(ord(i), end=" ")  # Correct indentation

iterate()

```

### Output:

### 1) do while:
![1 1](https://github.com/user-attachments/assets/19927084-b472-4a79-b26d-950eac871d3a)

### 2) while do:
![1 2](https://github.com/user-attachments/assets/73180bc6-3096-47f1-9bf9-9ee965fe6d1d)

### 3) switch :
![1 3](https://github.com/user-attachments/assets/602c6a4f-dbae-4d05-a221-efe21170bafd)

### 4) if else :
![1 4](https://github.com/user-attachments/assets/d358c0bb-e3c6-4f15-84e4-6bc342066556)

### 5) for :
![1 5](https://github.com/user-attachments/assets/07743f2f-545d-449d-827d-3a36568d670a)


### Result:

Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


