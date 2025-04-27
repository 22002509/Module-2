# Exp. No: 2a  
## ITERATIVE STATEMENTS – Calculating the Sum of Numbers Divisible by 3

###  Aim

  To create a Python program that calculates and prints the sum of all natural numbers up to a given number 'N' that are divisible by 3.

---

###  Algorithm

1.	Begin the program. 
2.	Use the input() function to read the upper limit 'N' from the user. 
3.	Convert the input to an integer using the int() function. 
4.	Initialize a variable, say sum_of_multiples, to 0. This variable will store the sum. 
5.	Use a for loop to iterate through the natural numbers from 1 up to 'N' (inclusive). 
6.	Inside the loop, for each number i, check if it is divisible by 3 using the modulo operator (%). If i % 3 == 0, it means the number is divisible by 3. 
7.	If the number is divisible by 3, add it to the sum_of_multiples variable. 
8.	After the loop finishes, print the final value of sum_of_multiples with an appropriate message. 
9.	Terminate the program.

---

### 🧾 Program

```python
#Reg.NO:212222040120
#Name:PRASANNA R
#Write your Code here

n=int(input())
sum=0
for i in range(1,n+1):
    if i%3==0:
        sum=sum+i
print("Sum is:",sum)

```
### OUTPUT
```
![LAB2 DAY1](https://github.com/user-attachments/assets/21e77d2a-4f68-46f6-8d43-6bad41b6a75c)

```
### RESULT
```

```

