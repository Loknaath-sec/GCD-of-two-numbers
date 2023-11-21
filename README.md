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
```
#Program to find gcd of anumber using functions
#Developed By: P.LOKNAATH
#RegisterNumber: 23004546

def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:
![Exp 2a Op](https://github.com/Loknaath-sec/GCD-of-two-numbers/assets/145742558/d5846bf5-88ae-4610-a5c0-8228148afb40)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
