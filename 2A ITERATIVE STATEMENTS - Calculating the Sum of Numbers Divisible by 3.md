# Exp. No: 2a  
## ITERATIVE STATEMENTS – Calculating the Sum of Numbers Divisible by 3

###  Aim
To write a Python program that determines whether a given number is a palindrome.

###  Algorithm
1.	Begin the program.
2.	Use input() to read the number from the user.
3.	Convert the input to an integer.
4.	Store the original number in a temporary variable.
5.	Initialize a variable to store the reverse of the number.
6.	Use a while loop to extract the digits of the number and construct its reverse.
7.	Compare the reverse of the number with the original number.
8.	If they are equal, print that the number is a palindrome.
9.	Otherwise, print that the number is not a palindrome.
10.	Terminate the program
    
### 🧾 Program

```python
#Reg.NO:212222040120
#Name:PRASANNA R
#Write your Code here

n=int(input())
temp=n
rev=0
while n!=0:
    d=n%10
    rev=rev*10+d
    n=n//10
if (temp==rev):
    print(f"The given number {temp} is a Palindrome")
else:
    print(f"The given number {temp} is not a palindrome")
```
### OUTPUT
```
![LAB2 DAY1](https://github.com/user-attachments/assets/c8db4b28-963c-4853-8160-237dea882ef1)
```
### RESULT
```
Thus, the implementation of the Python program for calculating the sum of natural numbers up to N that are divisible by 3 was verified successfully.
```

