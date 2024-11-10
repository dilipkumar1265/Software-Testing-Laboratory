# EX.05 - BINARY SEARCH
### DATE : 10-9-24
### REG.NO : 212222040037

### AIM: 
Write a Python program to perform a binary search on a sorted list and identify the position of a target element.

### Algorithm:
1.Start the program.

2.Initialize low as 0 and high as the length of the array minus 1.

3.Repeat until low is less than or equal to high:

4.Calculate mid as the average of low and high.

5.If the element at index mid is equal to the target, return mid.

6.If the element at index mid is less than the target, set low to mid + 1.

7.If the element at index mid is greater than the target, set high to mid - 1.

8.If the target element is not found, return -1.

9.Stop the program.


### Program:
```
def binary_search(arr, x):
    low = 0
    high = len(arr) - 1

    while low <= high:
        mid = (high + low) // 2

        # Check if x is present at mid
        if arr[mid] < x:
            low = mid + 1
        elif arr[mid] > x:
            high = mid - 1
        else:
            return mid

    return -1  # If element is not present in array

arr = [2, 3, 4, 10, 40]
x = input("Enter the element to be searched: ")

try:
    x = int(x)
    result = binary_search(arr, x)
    if result != -1:
        print("Element is present at index", str(result))
    else:
        print("Element is not present in array")
except ValueError:
    print("Enter a valid input!")

```
### Output:
![05](https://github.com/user-attachments/assets/9348582e-6d98-4784-b1b2-9e1a03d92f4a)

### Result:
Thus, the Python program for binary search was implemented successfully, and the output was verified.

