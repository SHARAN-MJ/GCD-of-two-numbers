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
Developed by: SHARAN MJ
RegisterNumber: 22009349 
def gcd():
    a,b=int(input()),int(input())
    if a>b:
       min=a
    else:
        min=b
    for i in range(1,min+1):
        if a%i==0 and b%i==0:
            gcd=i
    print('GCD of two numbers is:',gcd)        

```

## Output:
![2023-01-14 (5)](https://user-images.githubusercontent.com/119560305/212466082-20b45f48-f7a5-4dd2-bec1-0deeca4ca43e.png)
)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
