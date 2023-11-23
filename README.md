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
Program to find the gcd of two number using function.
Developed by: NATARAJ  KUMARAN S
RegisterNumber:23003973
def gcd():
    a=int(input())
    b=int(input())
    for i in range(1,min(a,b)):
        if a%i==0 and b%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)
```

## Output:
![image](https://github.com/nataraj26/GCD-of-two-numbers/assets/147514615/a47aade1-09d1-48d8-b8cf-584074515351)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
