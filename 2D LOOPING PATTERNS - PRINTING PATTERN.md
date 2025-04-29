# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN


### AIM  
To write a Python program to print a triangular star pattern using loops.


### ALGORITHM
Start

Input the number of rows (size)

Initialize m = (2 × size) - 2 (controls spacing)

Repeat for i = 0 to size - 1:

Print m spaces

Decrease m by 1

Print i + 1 stars followed by a space

Move to the next line

End

### PROGRAM
size = int(input())

m = (2 * size) - 2

for i in range(0, size):

    for j in range(0, m):
    
        print(end=" ")
    
    m = m - 1
    
    for j in range(0, i + 1):
    
        print("* ", end=' ')
        
    print(" ")

### OUTPUT
![image](https://github.com/user-attachments/assets/94e5015c-72f8-44ce-bc26-aab77b83e8e4)


### RESULT
Thus, Python program to print a triangular star pattern using loops was implemented successfully.
