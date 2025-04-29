# Exp.No:2e  
## SEB - Count and Display the Number of Digits in a Given Number

---

### AIM  
To create a Python program to count and display the number of digits in a given number.


---

### ALGORITHM

1.	Begin the program.
2.	Use input() to read the number from the user.
3.	Convert the input to an integer.
4.	Initialize a counter variable to 0.
5.	Use a while loop to divide the number by 10 in each iteration.
6.	Increment the counter in each loop iteration.
7.	Stop when the number becomes 0.
8.	Display the counter value as the number of digits.
9.	Terminate the program.


---

### PROGRAM
```
#Reg.NO:212222040120
#Name:PRASANNA R
#Write your Code here
a=int(input())
count=0
while(a>0):
    a=a//10
    count=count+1
print("The number of digits in the number are:",count)
```
### OUTPUT

![LAB2 SEBEXAM](https://github.com/user-attachments/assets/4de1a79d-53ac-4540-a06b-307543527349)


### RESULT
Thus, the Python program to count the number of digits in a number has been implemented and executed successfully.
