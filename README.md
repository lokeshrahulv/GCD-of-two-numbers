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
Developed by: Lokesh Rahul V V
RegisterNumber: 22004702 
def gcd():
    a,b=int(input()),int(input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)            

```

## Output:
![Screenshot (82)](https://user-images.githubusercontent.com/118423842/210346814-7ff6d945-f68e-493f-9462-05e65cba2e98.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
