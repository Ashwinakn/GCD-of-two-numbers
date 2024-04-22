# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:

To write a python Program to find the gcd of a number using function.
Developed By: ASHWINA K N
Register Number: 212223230025

```
def gcd():
    num1,num2 = int(input()),int(input())
    if num1>num2:
        small=num2
    else:
        small=num1
    for i in range(1,small+1):
        if (num1%i==0) and (num2%i==0):
            gcdd=i
    print("GCD of two numbers is:",gcdd)
gcd()
```
## Output:

![EXP-4](https://github.com/Ashwinakn/GCD-of-two-numbers/assets/152128332/a50253b2-da7a-4bdc-8936-bd0476553071)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
