# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To create a Python program to print a square pattern of numbers based on the number of rows using nested for loops.

### ALGORITHM

1. Begin the program.  
2.  Use input() to read the number of rows from the user.
3. Convert the input to an integer.
4.Use a nested for loop:
   -The outer loop runs from 1 to n (inclusive) for each row.
   - The inner loop runs from 1 to n (inclusive) for each column.
5.In each iteration of the inner loop:
   - If the column index is less than the current row index, print the row index.
   - Otherwise, print the column index.
6. Print a newline after each row.
7. Terminate the program.

---

### PROGRAM
```
#Reg.No:
#Name:
#Add Your Code Here
n=int(input())
c=1
for i in range(n):
    for j in range(1,c):
        print(c,end=" ")
    for j in range(c,n+1):
        print(j,end=" ")
    
    c+=1
    print()
```

### OUTPUT

![LAB2 DAY4](https://github.com/user-attachments/assets/5790f2b3-cf86-47bb-b81f-e5a59d7a6423)


### RESULT
Thus, the Python program to print a square pattern of numbers has been implemented and executed successfully.
